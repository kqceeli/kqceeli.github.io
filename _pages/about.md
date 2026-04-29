---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* =========================================================
   Homepage Style
   Minimal Premium Academic
   Palette: ivory / charcoal / warm grey / deep wine / muted brass
   ========================================================= */

:root {
  --kq-ink: #171615;
  --kq-text: #3f3c38;
  --kq-muted: #7a746c;

  --kq-bg: #faf9f6;
  --kq-paper: #ffffff;
  --kq-soft: #f3f1ec;

  --kq-line: #e4dfd7;
  --kq-line-soft: #eee9e2;

  --kq-accent: #7a2636;
  --kq-accent-dark: #4f1722;
  --kq-brass: #9b8465;
  --kq-brass-soft: #eee6da;

  --kq-shadow: rgba(23, 22, 21, 0.055);
  --kq-shadow-soft: rgba(23, 22, 21, 0.032);
}

.kq-home {
  max-width: 940px;
  margin: 0 auto;
  color: var(--kq-text);
  font-size: 0.92rem;
  line-height: 1.72;
}

.kq-home * {
  box-sizing: border-box;
}

.kq-home a {
  color: var(--kq-accent-dark);
  text-decoration: none;
  border-bottom: 1px solid rgba(122, 38, 54, 0.22);
  transition: color 0.18s ease, border-color 0.18s ease;
}

.kq-home a:hover {
  color: var(--kq-ink);
  border-bottom-color: var(--kq-ink);
}


/* =========================================================
   Hero
   ========================================================= */

.kq-hero {
  position: relative;
  margin: 0.2rem 0 1.55rem;
  padding: 2.35rem 0 1.55rem;
  border-bottom: 1px solid var(--kq-line);
}

.kq-hero::before {
  content: "";
  position: absolute;
  left: 0;
  top: 1.28rem;
  width: 54px;
  height: 2px;
  background: linear-gradient(90deg, var(--kq-accent), var(--kq-brass));
}

.kq-hero::after {
  content: "";
  position: absolute;
  right: 0;
  top: 1.7rem;
  width: 170px;
  height: 170px;
  border-radius: 50%;
  background:
    radial-gradient(circle, rgba(155, 132, 101, 0.13), rgba(155, 132, 101, 0.03) 58%, transparent 72%);
  pointer-events: none;
  z-index: -1;
}

.kq-hero h1 {
  margin: 0;
  padding-top: 0.72rem;
  color: var(--kq-ink);
  font-size: clamp(2.12rem, 3.35vw, 2.9rem);
  line-height: 1.06;
  font-weight: 860;
  letter-spacing: -0.045em;
}

.kq-position {
  max-width: 830px;
  margin: 0.72rem 0 0;
  color: var(--kq-muted);
  font-size: 0.95rem;
  line-height: 1.58;
}

.kq-hero-desc {
  max-width: 820px;
  margin: 1.08rem 0 0;
  color: var(--kq-text);
  font-size: 0.96rem;
  line-height: 1.82;
}

.kq-hero-desc strong {
  color: var(--kq-ink);
  font-weight: 760;
}


/* =========================================================
   Metrics
   ========================================================= */

.kq-metrics {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  margin: 1.35rem 0 2.45rem;
  border-top: 1px solid var(--kq-line);
  border-bottom: 1px solid var(--kq-line);
  background: linear-gradient(180deg, rgba(255,255,255,0.92), rgba(250,249,246,0.88));
}

.kq-metric {
  padding: 0.96rem 0.95rem 0.85rem;
  border-right: 1px solid var(--kq-line-soft);
}

.kq-metric:last-child {
  border-right: none;
}

.kq-metric-number {
  display: block;
  color: var(--kq-accent-dark);
  font-size: 1.1rem;
  line-height: 1.2;
  font-weight: 860;
  letter-spacing: -0.025em;
}

.kq-metric-label {
  display: block;
  margin-top: 0.24rem;
  color: var(--kq-muted);
  font-size: 0.7rem;
  line-height: 1.35;
  font-weight: 660;
  letter-spacing: 0.025em;
}


/* =========================================================
   Common Section
   ========================================================= */

.kq-section,
.home-section {
  margin: 2.55rem 0;
}

.kq-section-header,
.home-section-header {
  margin-bottom: 1.05rem;
}

.kq-section-title,
.home-section-title {
  position: relative;
  margin: 0;
  padding-left: 0.82rem;
  color: var(--kq-ink);
  font-size: clamp(1.26rem, 2vw, 1.55rem) !important;
  line-height: 1.3;
  font-weight: 840;
  letter-spacing: -0.03em;
}

.kq-section-title::before,
.home-section-title::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.24em;
  bottom: 0.22em;
  width: 3px;
  border-radius: 99px;
  background: var(--kq-accent);
}

.kq-section-subtitle,
.home-section-subtitle {
  max-width: 780px;
  margin: 0.42rem 0 0 0.82rem;
  color: var(--kq-muted);
  font-size: 0.83rem;
  line-height: 1.65;
}


/* =========================================================
   About
   ========================================================= */

.kq-about {
  position: relative;
  padding: 1.34rem 1.42rem;
  border: 1px solid var(--kq-line);
  border-radius: 14px;
  background: linear-gradient(180deg, #ffffff 0%, #fbfaf7 100%);
  box-shadow: 0 12px 26px var(--kq-shadow-soft);
}

.kq-about::before {
  content: "";
  position: absolute;
  left: 0;
  top: 1.25rem;
  bottom: 1.25rem;
  width: 3px;
  border-radius: 0 99px 99px 0;
  background: linear-gradient(180deg, var(--kq-accent), var(--kq-brass));
}

.kq-about p {
  margin: 0.62rem 0;
  color: var(--kq-text);
  font-size: 0.875rem;
  line-height: 1.78;
}

.kq-about p:first-child {
  margin-top: 0;
}

.kq-about p:last-child {
  margin-bottom: 0;
}

.kq-about strong {
  color: var(--kq-ink);
  font-weight: 760;
}

.kq-about-divider {
  height: 1px;
  margin: 1.02rem 0;
  background: var(--kq-line-soft);
}

.kq-education {
  display: grid;
  grid-template-columns: 118px minmax(0, 1fr);
  gap: 0.72rem 1.05rem;
  margin-top: 0.88rem;
}

.kq-edu-label {
  color: var(--kq-brass);
  font-size: 0.7rem;
  line-height: 1.45;
  font-weight: 790;
  letter-spacing: 0.095em;
  text-transform: uppercase;
}

.kq-edu-text {
  color: var(--kq-text);
  font-size: 0.835rem;
  line-height: 1.64;
}


/* =========================================================
   Research Agenda
   ========================================================= */

.agenda-list {
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.82rem;
}

.agenda-item {
  display: grid;
  grid-template-columns: 96px minmax(0, 1fr);
  gap: 1.05rem;
  padding: 1.06rem 1.2rem;
  border: 1px solid var(--kq-line);
  border-radius: 14px;
  background: linear-gradient(180deg, #ffffff 0%, #fbfaf7 100%);
  box-shadow: 0 8px 22px var(--kq-shadow-soft);
  transition: border-color 0.18s ease, transform 0.18s ease, box-shadow 0.18s ease;
}

.agenda-item:hover {
  transform: translateY(-1px);
  border-color: rgba(122, 38, 54, 0.28);
  box-shadow: 0 12px 26px rgba(23, 22, 21, 0.052);
}

.agenda-no {
  padding-top: 0.1rem;
  color: var(--kq-accent);
  font-size: 0.68rem;
  line-height: 1.4;
  font-weight: 860;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.agenda-content h3 {
  margin: 0;
  color: var(--kq-ink);
  font-size: 0.98rem !important;
  line-height: 1.4;
  font-weight: 820;
  letter-spacing: -0.018em;
}

.agenda-content p {
  margin: 0.42rem 0 0.72rem;
  color: #5b5650;
  font-size: 0.79rem;
  line-height: 1.62;
}

.agenda-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.34rem;
}

.agenda-tags span {
  display: inline-flex;
  align-items: center;
  padding: 0.16rem 0.5rem;
  border: 1px solid #e6ded3;
  border-radius: 999px;
  background: rgba(243, 241, 236, 0.82);
  color: #6a625a;
  font-size: 0.6rem;
  line-height: 1.35;
  font-weight: 660;
}


/* =========================================================
   Selected News
   ========================================================= */

.kq-news-panel {
  border: 1px solid var(--kq-line);
  border-radius: 14px;
  background: #ffffff;
  box-shadow: 0 12px 26px var(--kq-shadow-soft);
  overflow: hidden;
}

.kq-news-group {
  display: grid;
  grid-template-columns: 165px minmax(0, 1fr);
  gap: 1.05rem;
  padding: 1.08rem 1.18rem;
  border-bottom: 1px solid var(--kq-line-soft);
}

.kq-news-group:last-child {
  border-bottom: none;
}

.kq-news-heading {
  margin: 0;
  color: var(--kq-accent-dark);
  font-size: 0.78rem !important;
  line-height: 1.45;
  font-weight: 830;
  letter-spacing: 0.025em;
}

.kq-news-heading span {
  display: inline-block;
  padding-bottom: 0.26rem;
  border-bottom: 2px solid rgba(155, 132, 101, 0.35);
}

.kq-news-list {
  margin: 0;
  padding-left: 1rem;
}

.kq-news-list li {
  margin: 0.29rem 0;
  color: #514c46;
  font-size: 0.765rem;
  line-height: 1.62;
}

.kq-news-list li::marker {
  color: var(--kq-brass);
}

.kq-news-list strong {
  color: var(--kq-ink);
  font-weight: 745;
}

.kq-news-list em {
  color: #332f2c;
}


/* =========================================================
   Visitors
   ========================================================= */

.kq-visitors {
  margin: 2rem 0 0;
  padding-top: 1rem;
  border-top: 1px solid var(--kq-line);
}

.kq-visitors-title {
  margin: 0 0 0.65rem;
  color: var(--kq-muted);
  font-size: 0.69rem;
  line-height: 1.3;
  font-weight: 770;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}


/* =========================================================
   Responsive
   ========================================================= */

@media (max-width: 900px) {
  .kq-metrics {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .kq-metric:nth-child(2) {
    border-right: none;
  }

  .kq-metric:nth-child(1),
  .kq-metric:nth-child(2) {
    border-bottom: 1px solid var(--kq-line-soft);
  }

  .kq-news-group {
    grid-template-columns: 1fr;
    gap: 0.55rem;
  }
}

@media (max-width: 650px) {
  .kq-home {
    max-width: 100%;
  }

  .kq-hero {
    padding-top: 1.75rem;
  }

  .kq-hero::after {
    width: 120px;
    height: 120px;
    opacity: 0.65;
  }

  .kq-metrics {
    grid-template-columns: 1fr;
  }

  .kq-metric {
    border-right: none !important;
    border-bottom: 1px solid var(--kq-line-soft);
  }

  .kq-metric:last-child {
    border-bottom: none;
  }

  .kq-education {
    grid-template-columns: 1fr;
    gap: 0.22rem;
  }

  .agenda-item {
    grid-template-columns: 1fr;
    gap: 0.42rem;
    padding: 1rem;
  }

  .agenda-no {
    color: var(--kq-brass);
  }

  .kq-section-title,
  .home-section-title {
    font-size: 1.22rem !important;
  }

  .kq-section-subtitle,
  .home-section-subtitle {
    font-size: 0.8rem;
  }

  .kq-about p,
  .agenda-content p {
    font-size: 0.78rem;
  }

  .kq-news-list li {
    font-size: 0.74rem;
  }
}
</style>


<div class="kq-home">

  <!-- ================= Hero ================= -->
  <section class="kq-hero">

    <h1>Kai-Qi Li, Ph.D.</h1>

    <p class="kq-position">
      Incoming Professor, School of Water Resources and Hydropower Engineering, Wuhan University
    </p>

    <p class="kq-hero-desc">
      I develop <strong>mechanics-grounded</strong>, <strong>data-enabled</strong>, and
      <strong>uncertainty-aware</strong> methods to reveal, predict, and manage complex
      geotechnical systems under evolving environmental and engineering conditions.
    </p>

  </section>


  <!-- ================= Metrics ================= -->
  <section class="kq-metrics" aria-label="Research metrics">

    <div class="kq-metric">
      <span class="kq-metric-number">40+</span>
      <span class="kq-metric-label">Journal papers</span>
    </div>

    <div class="kq-metric">
      <span class="kq-metric-number">1,500+</span>
      <span class="kq-metric-label">Citations</span>
    </div>

    <div class="kq-metric">
      <span class="kq-metric-number">23</span>
      <span class="kq-metric-label">h-index</span>
    </div>

    <div class="kq-metric">
      <span class="kq-metric-number">5</span>
      <span class="kq-metric-label">ESI Highly Cited Papers</span>
    </div>

  </section>


  <!-- ================= About ================= -->
  <section class="kq-section" id="about-me">

    <div class="kq-section-header">
      <h2 class="kq-section-title">About Me</h2>
    </div>

    <div class="kq-about">

      <p>
        I am an <strong>NSFC Excellent Young Scientists Fund Overseas Awardee</strong> and will join the
        <strong>School of Water Resources and Hydropower Engineering, Wuhan University</strong> as an
        Incoming Professor.
      </p>

      <p>
        I am currently a Postdoctoral Fellow in the Department of Civil and Environmental Engineering at
        <a href="https://www.polyu.edu.hk/" target="_blank" rel="noopener">The Hong Kong Polytechnic University</a>,
        working with Prof.
        <a href="https://www.polyu.edu.hk/cee/people/academic-staff/prof-yin-zhenyu/" target="_blank" rel="noopener">Zhen-Yu Yin</a>.
      </p>

      <div class="kq-about-divider"></div>

      <div class="kq-education">

        <div class="kq-edu-label">Education</div>
        <div class="kq-edu-text">
          Ph.D. in Geotechnical Engineering, Wuhan University, supervised by Prof. Yong Liu and Prof. Dian-Qing Li.
        </div>

        <div class="kq-edu-label">Visiting</div>
        <div class="kq-edu-text">
          Visiting Ph.D. student at the
          <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>,
          hosted by Prof.
          <a href="https://cde.nus.edu.sg/cee/staff/fook-hou-lee/" target="_blank" rel="noopener">Fook-Hou Lee</a>.
        </div>

        <div class="kq-edu-label">Research</div>
        <div class="kq-edu-text">
          Geotechnical engineering, mechanics, computational modelling, stochastic analysis, and artificial intelligence.
        </div>

      </div>

    </div>

  </section>


  <!-- ================= Research Agenda ================= -->
  <section class="home-section" id="research-agenda">

    <div class="home-section-header">
      <h2 class="home-section-title">Research Agenda</h2>
      <p class="home-section-subtitle">
        Shaping future geotechnics through mechanics-informed intelligence, uncertainty-aware modelling,
        and resilient infrastructure systems.
      </p>
    </div>

    <div class="agenda-list">

      <div class="agenda-item">
        <div class="agenda-no">Agenda 01</div>

        <div class="agenda-content">
          <h3>Mechanics of ground in extreme and evolving environments</h3>
          <p>
            Coupled thermal, hydraulic, mechanical, chemical, and phase-change processes in frozen soils,
            artificial ground freezing, and hydrate-bearing sediments.
          </p>

          <div class="agenda-tags">
            <span>Frozen soils</span>
            <span>Artificial ground freezing</span>
            <span>THM/THMC coupling</span>
            <span>Phase change</span>
            <span>Energy geotechnics</span>
          </div>
        </div>
      </div>


      <div class="agenda-item">
        <div class="agenda-no">Agenda 02</div>

        <div class="agenda-content">
          <h3>AI that understands mechanics, not merely fits data</h3>
          <p>
            Physics-informed and mechanics-guided models combining constitutive modelling, numerical simulation,
            machine learning, neural operators, and graph-based learning.
          </p>

          <div class="agenda-tags">
            <span>Physics-informed ML</span>
            <span>Constitutive modelling</span>
            <span>Graph neural networks</span>
            <span>Neural operators</span>
            <span>Computational geomechanics</span>
          </div>
        </div>
      </div>


      <div class="agenda-item">
        <div class="agenda-no">Agenda 03</div>

        <div class="agenda-content">
          <h3>Turning uncertainty into actionable engineering knowledge</h3>
          <p>
            Uncertainty quantification, stochastic analysis, reliability assessment, Bayesian updating,
            and risk-informed design for geotechnical systems.
          </p>

          <div class="agenda-tags">
            <span>Uncertainty quantification</span>
            <span>Reliability and risk</span>
            <span>Bayesian updating</span>
            <span>Digital twins</span>
            <span>Resilient infrastructure</span>
          </div>
        </div>
      </div>


      <div class="agenda-item">
        <div class="agenda-no">Agenda 04</div>

        <div class="agenda-content">
          <h3>From advanced models to safer infrastructure decisions</h3>
          <p>
            Translating frontier geomechanics and AI into practical tools for underground construction,
            cold-region infrastructure, marine geotechnics, and climate-resilient engineering.
          </p>

          <div class="agenda-tags">
            <span>Underground construction</span>
            <span>Cold-region infrastructure</span>
            <span>Marine geotechnics</span>
            <span>Risk-informed design</span>
            <span>Engineering resilience</span>
          </div>
        </div>
      </div>

    </div>

  </section>


  <!-- ================= Selected News ================= -->
  <section class="kq-section" id="selected-news">

    <div class="kq-section-header">
      <h2 class="kq-section-title">Selected News</h2>
      <p class="kq-section-subtitle">
        Recent highlights in research, funding, awards, and academic service.
      </p>
    </div>

    <div class="kq-news-panel">

      <div class="kq-news-group">
        <h3 class="kq-news-heading"><span>Awards &amp; Honors</span></h3>
        <ul class="kq-news-list">
          <li>[2026] Awarded the <strong>NSFC Excellent Young Scientists Fund Overseas</strong> and will join <strong>Wuhan University</strong> as an incoming professor.</li>
          <li>[2025] Shortlisted for the <strong>JC STEM Early Career Research Fellowship</strong>.</li>
          <li>[2024] Awarded the <strong>PolyU Distinguished Postdoctoral Fellowship</strong> in October 2024.</li>
          <li>[2024] Received the <strong>2023 Hubei Province Science &amp; Technology Progress Award</strong> for the project <em>Risk Prevention and Control of Artificial Ground Freezing Technique in Water-Rich Stratum</em>.</li>
          <li>[2023] Received the <strong>2023 Academic Innovation Award</strong> from Wuhan University.</li>
          <li>[2021] Received the <strong>Excellence in Teaching Award</strong> from Wuhan University.</li>
          <li>[2020] Named one of <strong>Wuhan University’s Top 10 Academic Stars</strong>.</li>
          <li>[2016] Awarded the <strong>Top 10 Future Star Undergraduate</strong> by the China Water Resources Education Association.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading"><span>Research &amp; Publications</span></h3>
        <ul class="kq-news-list">
          <li>[2026] Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.</li>
          <li>[2026] Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em> in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em>.</li>
          <li>[2025] Published <em>Physics-informed neural networks for solving steady-state temperature field in artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>State of the art of mechanical behaviors of frozen soils through experimental investigation</em> in <em>Cold Regions Science and Technology</em>.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading"><span>Funding</span></h3>
        <ul class="kq-news-list">
          <li>[2025–2026] Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical coupling in hydrate-bearing sediments using physics-informed neural networks.</li>
          <li>[2025–2029] Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project on digital twins for coastal resilience under extreme storm surges in Hong Kong.</li>
          <li>[2024–2026] Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed multi-fidelity neural networks for intelligent rectification of shield machine attitude in layered soils.</li>
          <li>[2022] Received the <strong>Centrally Funded Postdoctoral Fellowship HK$763,555</strong> for thermo-hydro-mechanical modelling of artificial ground freezing.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading"><span>Academic Service</span></h3>
        <ul class="kq-news-list">
          <li>[2025] Serving as Co-chair of Mini-Symposium 9: <em>Multiphysics Modeling of Geo-engineering and Geohazards</em> at <strong>IACMAG 2025</strong>, Hong Kong.</li>
          <li>[2024] Joined the <strong>Early-career Editorial Panel</strong> for the <em>European Journal of Soil Science</em>.</li>
          <li>[2024] Served as Session Chair at the <strong>12th National Conference on Engineering Geology</strong>, Shenzhen.</li>
          <li>[2023] Served as Secretary of the <strong>International Symposium on Innovations in Geotechnical Engineering towards Sustainability</strong>, IGES 2023.</li>
        </ul>
      </div>

    </div>

  </section>


  <!-- ================= Visitors ================= -->
  <section class="kq-visitors">
    <div class="kq-visitors-title">Visitors</div>
    <script type="text/javascript" id="clustrmaps"
      src="//clustrmaps.com/map_v2.js?d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=faf9f6&cmo=9b8465&cmn=7a2636&ct=3f3c38">
    </script>
  </section>

</div>
