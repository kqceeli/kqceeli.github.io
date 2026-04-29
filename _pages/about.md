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
   Homepage Global Style
   Nature / Science Inspired Academic Design
   Palette: editorial white / graphite / Nature red / Science navy
   ========================================================= */

:root {
  /* Neutral system */
  --kq-ink: #1f2328;
  --kq-graphite: #2f343a;
  --kq-text: #424850;
  --kq-muted: #747b84;

  --kq-paper: #ffffff;
  --kq-bg-soft: #f7f7f5;
  --kq-bg-warm: #faf8f3;

  --kq-border: #dedbd5;
  --kq-border-soft: #ebe8e2;

  /* Refined academic accents */
  --kq-nature-red: #b6424b;
  --kq-nature-red-dark: #8f3038;
  --kq-nature-red-soft: #fbf1f2;

  --kq-science-blue: #465f7a;
  --kq-science-blue-dark: #31465d;
  --kq-science-blue-soft: #f0f4f7;

  /* Secondary accents */
  --kq-gold: #a58a64;
  --kq-green-muted: #6f7f78;

  --kq-shadow: rgba(31, 35, 40, 0.055);
  --kq-shadow-soft: rgba(31, 35, 40, 0.035);
}

.kq-home {
  max-width: 980px;
  margin: 0 auto;
  color: var(--kq-text);
  line-height: 1.65;
  font-feature-settings: "kern";
}

.kq-home * {
  box-sizing: border-box;
}

.kq-home a {
  color: var(--kq-science-blue-dark);
  text-decoration: none;
  border-bottom: 1px solid rgba(23, 74, 124, 0.25);
  transition: color 0.18s ease, border-color 0.18s ease;
}

.kq-home a:hover {
  color: var(--kq-nature-red-dark);
  border-bottom-color: rgba(165, 28, 48, 0.55);
}


/* =========================================================
   Hero
   ========================================================= */

.kq-hero {
  position: relative;
  margin: 0.45rem 0 1.55rem;
  padding: 1.95rem 2.15rem 1.85rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background:
    radial-gradient(circle at 95% 12%, rgba(165, 28, 48, 0.055), transparent 30%),
    radial-gradient(circle at 88% 88%, rgba(23, 74, 124, 0.045), transparent 34%),
    linear-gradient(180deg, #ffffff 0%, #fbfbfb 100%);
  box-shadow: 0 10px 26px var(--kq-shadow-soft);
  overflow: hidden;
}

.kq-hero::before {
  content: "";
  position: absolute;
  left: 0;
  top: 1.25rem;
  bottom: 1.25rem;
  width: 4px;
  border-radius: 0 99px 99px 0;
  background: linear-gradient(180deg, var(--kq-nature-red), var(--kq-science-blue));
}

.kq-hero h1 {
  margin: 0;
  color: var(--kq-ink);
  font-size: clamp(1.95rem, 3vw, 2.62rem);
  line-height: 1.1;
  font-weight: 860;
  letter-spacing: -0.04em;
}

.kq-position {
  max-width: 860px;
  margin: 0.5rem 0 0;
  color: #4d4d4d;
  font-size: 0.98rem;
  line-height: 1.55;
}

.kq-hero-desc {
  max-width: 850px;
  margin: 1.08rem 0 0;
  color: #424242;
  font-size: 0.96rem;
  line-height: 1.78;
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
  margin: 1.25rem 0 2.15rem;
  border: 1px solid var(--kq-border);
  border-radius: 16px;
  background: var(--kq-paper);
  box-shadow: 0 6px 18px var(--kq-shadow-soft);
  overflow: hidden;
}

.kq-metric {
  position: relative;
  padding: 0.88rem 0.9rem 0.82rem;
  border-right: 1px solid var(--kq-border-soft);
  background: linear-gradient(180deg, #ffffff 0%, #fcfcfc 100%);
}

.kq-metric::before {
  content: "";
  position: absolute;
  left: 0.9rem;
  right: 0.9rem;
  top: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--kq-nature-red), var(--kq-science-blue));
  opacity: 0.78;
}

.kq-metric:last-child {
  border-right: none;
}

.kq-metric-number {
  display: block;
  color: var(--kq-ink);
  font-size: 1.08rem;
  line-height: 1.25;
  font-weight: 860;
  letter-spacing: -0.018em;
}

.kq-metric-label {
  display: block;
  margin-top: 0.22rem;
  color: var(--kq-muted);
  font-size: 0.71rem;
  line-height: 1.42;
  font-weight: 650;
}


/* =========================================================
   Common Section
   ========================================================= */

.kq-section,
.home-section {
  margin: 2.35rem 0;
}

.kq-section-header,
.home-section-header {
  margin-bottom: 1.05rem;
  padding-bottom: 0.72rem;
  border-bottom: 1px solid var(--kq-border-soft);
}

.kq-section-title,
.home-section-title {
  position: relative;
  margin: 0;
  padding-left: 0.82rem;
  color: var(--kq-ink);
  font-size: clamp(1.35rem, 2.1vw, 1.72rem) !important;
  line-height: 1.28;
  font-weight: 860;
  letter-spacing: -0.028em;
}

.kq-section-title::before,
.home-section-title::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.2em;
  bottom: 0.16em;
  width: 3px;
  border-radius: 99px;
  background: var(--kq-nature-red);
}

.kq-section-subtitle,
.home-section-subtitle {
  max-width: 820px;
  margin: 0.45rem 0 0 0.82rem;
  color: var(--kq-muted);
  font-size: 0.875rem;
  line-height: 1.68;
}


/* =========================================================
   About
   ========================================================= */

.kq-card {
  position: relative;
  padding: 1.22rem 1.35rem;
  border: 1px solid var(--kq-border);
  border-radius: 17px;
  background:
    linear-gradient(180deg, #ffffff 0%, #fcfcfc 100%);
  box-shadow: 0 7px 20px var(--kq-shadow-soft);
}

.kq-card::before {
  content: "";
  position: absolute;
  left: 1.35rem;
  right: 1.35rem;
  top: 0;
  height: 2px;
  background: linear-gradient(90deg, var(--kq-nature-red), var(--kq-science-blue));
  opacity: 0.75;
}

.kq-card p {
  margin: 0.65rem 0;
  color: #424242;
  font-size: 0.9rem;
  line-height: 1.78;
}

.kq-card p:first-child {
  margin-top: 0;
}

.kq-card p:last-child {
  margin-bottom: 0;
}

.kq-card strong {
  color: var(--kq-ink);
  font-weight: 760;
}


/* =========================================================
   Research Agenda
   ========================================================= */

.agenda-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.92rem;
}

.agenda-card {
  display: grid;
  grid-template-columns: 185px minmax(0, 1fr);
  gap: 1rem;
  padding: 1.05rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 22px var(--kq-shadow-soft);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.agenda-card:hover {
  transform: translateY(-1px);
  border-color: #cfcfcf;
  box-shadow: 0 12px 26px rgba(17, 17, 17, 0.05);
}

.agenda-index {
  min-height: 130px;
  padding: 0.9rem 0.92rem;
  border-radius: 14px;
  border: 1px solid #dedede;
  background:
    linear-gradient(180deg, #fbfaf7 0%, #f4f2ee 100%);
}

.agenda-number {
  color: var(--kq-nature-red-dark);
  font-size: 0.76rem;
  line-height: 1.35;
  font-weight: 850;
  letter-spacing: 0.115em;
  text-transform: uppercase;
}

.agenda-theme {
  margin-top: 0.5rem;
  color: var(--kq-ink);
  font-size: 0.98rem;
  line-height: 1.35;
  font-weight: 830;
  letter-spacing: -0.018em;
}

.agenda-content h3 {
  margin: 0 0 0.42rem;
  color: var(--kq-ink);
  font-size: 1rem !important;
  line-height: 1.4;
  font-weight: 830;
  letter-spacing: -0.016em;
}

.agenda-content p {
  margin: 0 0 0.72rem;
  color: #4f4f4f;
  font-size: 0.82rem;
  line-height: 1.66;
}

.agenda-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.34rem;
}

.agenda-tags span {
  display: inline-flex;
  align-items: center;
  padding: 0.18rem 0.5rem;
  border: 1px solid #e4e4e4;
  border-radius: 999px;
  background: #f7f7f7;
  color: #555555;
  font-size: 0.62rem;
  line-height: 1.35;
  font-weight: 670;
}

.agenda-tags span:nth-child(1) {
  border-color: rgba(165, 28, 48, 0.18);
  background: rgba(165, 28, 48, 0.045);
}

.agenda-tags span:nth-child(2) {
  border-color: rgba(23, 74, 124, 0.16);
  background: rgba(23, 74, 124, 0.045);
}


/* =========================================================
   Selected News
   ========================================================= */

.kq-news-panel {
  padding: 1.12rem 1.36rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 22px var(--kq-shadow-soft);
}

.kq-news-group {
  margin-top: 1.08rem;
  padding-top: 0.96rem;
  border-top: 1px solid var(--kq-border-soft);
}

.kq-news-group:first-child {
  margin-top: 0;
  padding-top: 0;
  border-top: none;
}

.kq-news-heading {
  position: relative;
  margin: 0 0 0.54rem;
  padding-left: 1rem;
  font-size: 0.92rem !important;
  line-height: 1.35;
  font-weight: 830;
  letter-spacing: -0.01em;
}

.kq-news-heading::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.47em;
  width: 0.42rem;
  height: 0.42rem;
  border-radius: 999px;
}

.kq-news-awards {
  color: var(--kq-nature-red-dark);
}

.kq-news-awards::before {
  background: var(--kq-nature-red);
}

.kq-news-research {
  color: var(--kq-science-blue-dark);
}

.kq-news-research::before {
  background: var(--kq-science-blue);
}

.kq-news-funding {
  color: #5f4b22;
}

.kq-news-funding::before {
  background: var(--kq-gold);
}

.kq-news-service {
  color: #303030;
}

.kq-news-service::before {
  background: #303030;
}

.kq-news-list {
  margin: 0;
  padding-left: 1rem;
}

.kq-news-list li {
  margin: 0.34rem 0;
  color: #4c4c4c;
  font-size: 0.79rem;
  line-height: 1.62;
}

.kq-news-list li::marker {
  color: #9a9a9a;
}

.kq-news-list strong {
  color: var(--kq-ink);
  font-weight: 750;
}

.kq-news-list em {
  color: #333333;
}


/* =========================================================
   Visitors
   ========================================================= */

.kq-visitors {
  margin: 1.85rem 0 0;
  padding-top: 1rem;
  border-top: 1px solid var(--kq-border-soft);
}

.kq-visitors-title {
  margin: 0 0 0.55rem;
  color: var(--kq-muted);
  font-size: 0.72rem;
  line-height: 1.3;
  font-weight: 760;
  letter-spacing: 0.12em;
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
    border-bottom: 1px solid var(--kq-border-soft);
  }

  .agenda-card {
    grid-template-columns: 1fr;
  }

  .agenda-index {
    min-height: auto;
  }

  .kq-hero {
    padding: 1.65rem 1.45rem;
  }
}

@media (max-width: 600px) {
  .kq-home {
    max-width: 100%;
  }

  .kq-hero {
    border-radius: 18px;
  }

  .kq-metrics {
    grid-template-columns: 1fr;
  }

  .kq-metric {
    border-right: none !important;
    border-bottom: 1px solid var(--kq-border-soft);
  }

  .kq-metric:last-child {
    border-bottom: none;
  }

  .kq-section-title,
  .home-section-title {
    font-size: 1.28rem !important;
  }

  .kq-section-subtitle,
  .home-section-subtitle {
    font-size: 0.84rem;
  }

  .kq-news-panel,
  .kq-card {
    padding: 1rem;
  }

  .kq-card::before {
    left: 1rem;
    right: 1rem;
  }

  .agenda-card {
    padding: 0.95rem;
  }

  .agenda-content h3,
  .kq-news-heading {
    font-size: 0.9rem !important;
  }

  .agenda-content p,
  .kq-news-list li {
    font-size: 0.76rem;
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
      <span class="kq-metric-number">24</span>
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

    <div class="kq-card">

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
        I received my Ph.D. in Geotechnical Engineering from Wuhan University under the supervision of
        Prof. <a href="https://scholar.google.com/citations?user=O6MLOGQAAAAJ&amp;hl=zh-CN" target="_blank" rel="noopener">Yong Liu</a>
        and Prof. <a href="https://scholar.google.com/citations?user=8mV4Gy4AAAAJ&amp;hl=en" target="_blank" rel="noopener">Dian-Qing Li</a>,
        and was a visiting Ph.D. student at the
        <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>,
        hosted by Prof.
        <a href="https://cde.nus.edu.sg/cee/staff/fook-hou-lee/" target="_blank" rel="noopener">Fook-Hou Lee</a>.
      </p>

      <p>
        My work lies at the interface of geotechnical engineering, mechanics, computational modelling,
        stochastic analysis, and artificial intelligence, with applications in frozen ground, artificial
        ground freezing, underground construction, hydrate-bearing sediments, and resilient infrastructure.
      </p>

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

    <div class="agenda-grid">

      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 01</div>
          <div class="agenda-theme">Complex ground systems</div>
        </div>

        <div class="agenda-content">
          <h3>Mechanics of ground in extreme and evolving environments</h3>
          <p>
            I study coupled thermal, hydraulic, mechanical, chemical, and phase-change processes in frozen soils,
            artificial ground freezing, hydrate-bearing sediments, and related multiphysical systems.
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


      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 02</div>
          <div class="agenda-theme">Scientific intelligence</div>
        </div>

        <div class="agenda-content">
          <h3>AI that understands mechanics, not merely fits data</h3>
          <p>
            I develop physics-informed and mechanics-guided models that combine constitutive modelling,
            numerical simulation, machine learning, neural operators, and graph-based learning.
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


      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 03</div>
          <div class="agenda-theme">Uncertainty mastery</div>
        </div>

        <div class="agenda-content">
          <h3>Turning uncertainty into actionable engineering knowledge</h3>
          <p>
            I work on uncertainty quantification, stochastic analysis, reliability assessment, Bayesian updating,
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


      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 04</div>
          <div class="agenda-theme">Engineering translation</div>
        </div>

        <div class="agenda-content">
          <h3>From advanced models to safer infrastructure decisions</h3>
          <p>
            My group aims to translate frontier geomechanics and AI into practical tools for underground construction,
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
        <h3 class="kq-news-heading kq-news-awards">Awards &amp; Honors</h3>
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
        <h3 class="kq-news-heading kq-news-research">Research &amp; Publications</h3>
        <ul class="kq-news-list">
          <li>[2026] Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.</li>
          <li>[2026] Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em> in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em>.</li>
          <li>[2025] Published <em>Physics-informed neural networks for solving steady-state temperature field in artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>State of the art of mechanical behaviors of frozen soils through experimental investigation</em> in <em>Cold Regions Science and Technology</em>.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading kq-news-funding">Funding</h3>
        <ul class="kq-news-list">
          <li>[2025–2026] Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical coupling in hydrate-bearing sediments using physics-informed neural networks.</li>
          <li>[2025–2029] Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project on digital twins for coastal resilience under extreme storm surges in Hong Kong.</li>
          <li>[2024–2026] Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed multi-fidelity neural networks for intelligent rectification of shield machine attitude in layered soils.</li>
          <li>[2022] Received the <strong>Centrally Funded Postdoctoral Fellowship HK$763,555</strong> for thermo-hydro-mechanical modelling of artificial ground freezing.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading kq-news-service">Academic Service</h3>
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
    src="//clustrmaps.com/map_v2.js?d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=faf9f6&cmo=465f7a&cmn=b6424b&ct=1f2328">
    </script>
  </section>

</div>
