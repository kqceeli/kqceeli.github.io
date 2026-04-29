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
   Clean Academic Homepage
   ========================================================= */

:root {
  --kq-ink: #111827;
  --kq-text: #374151;
  --kq-muted: #6b7280;

  --kq-paper: #ffffff;
  --kq-soft: #f7f7f4;
  --kq-warm: #fbfaf7;

  --kq-line: #e7e5df;
  --kq-line-soft: #f0eee8;

  --kq-accent: #0f766e;
  --kq-accent-dark: #115e59;
  --kq-red: #9f2f3a;
  --kq-gold: #a16207;

  --kq-shadow: rgba(17, 24, 39, 0.06);
}

.kq-home {
  max-width: 1040px;
  margin: 0 auto;
  padding: 0 0 3.5rem;
  color: var(--kq-text);
  line-height: 1.68;
}

.kq-home * {
  box-sizing: border-box;
}

.kq-home a {
  color: var(--kq-accent-dark);
  text-decoration: none;
  border-bottom: 1px solid rgba(15, 118, 110, 0.28);
  transition: color 0.18s ease, border-color 0.18s ease;
}

.kq-home a:hover {
  color: var(--kq-red);
  border-bottom-color: rgba(159, 47, 58, 0.45);
}

/* =========================================================
   Hero
   ========================================================= */

.kq-hero {
  position: relative;
  margin: 0.5rem 0 1.6rem;
  padding: 2.15rem 2.35rem 2.25rem;
  border-radius: 24px;
  border: 1px solid rgba(15, 118, 110, 0.14);
  background:
    radial-gradient(circle at 92% 0%, rgba(15, 118, 110, 0.11), transparent 30%),
    linear-gradient(135deg, rgba(15, 118, 110, 0.08), rgba(180, 83, 9, 0.055)),
    #fbfaf6;
  overflow: hidden;
  box-shadow: 0 14px 36px rgba(17, 24, 39, 0.055);
}

.kq-hero::after {
  content: "";
  position: absolute;
  right: -80px;
  top: -90px;
  width: 230px;
  height: 230px;
  border-radius: 999px;
  background: rgba(15, 118, 110, 0.07);
}

.kq-hero-inner {
  position: relative;
  z-index: 1;
  max-width: 860px;
}

.kq-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  margin-bottom: 1rem;
  color: var(--kq-accent-dark);
  font-size: 0.76rem;
  font-weight: 850;
  letter-spacing: 0.09em;
  text-transform: uppercase;
}

.kq-eyebrow::before {
  content: "";
  width: 0.44rem;
  height: 0.44rem;
  border-radius: 999px;
  background: var(--kq-accent);
}

.kq-hero h1 {
  margin: 0;
  color: var(--kq-ink);
  font-size: clamp(1.85rem, 3.2vw, 2.55rem);
  line-height: 1.12;
  font-weight: 850;
  letter-spacing: -0.035em;
}

.kq-position {
  margin: 0.9rem 0 0;
  max-width: 760px;
  color: #374151;
  font-size: 0.96rem;
  line-height: 1.65;
  font-weight: 650;
}

.kq-hero-desc {
  max-width: 790px;
  margin: 1.15rem 0 0;
  color: var(--kq-text);
  font-size: 1rem;
  line-height: 1.78;
}

.kq-hero-desc strong {
  color: var(--kq-ink);
  font-weight: 780;
}

.kq-hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.45rem;
}

.kq-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.62rem 0.95rem;
  border-radius: 999px;
  font-size: 0.86rem;
  font-weight: 760;
  line-height: 1;
  border-bottom: none !important;
}

.kq-button-primary {
  background: var(--kq-accent-dark);
  color: #ffffff !important;
}

.kq-button-primary:hover {
  background: #0f4f4b;
  color: #ffffff !important;
}

.kq-button-secondary {
  background: #ffffff;
  color: var(--kq-ink) !important;
  border: 1px solid var(--kq-line);
}

.kq-button-secondary:hover {
  color: var(--kq-accent-dark) !important;
  border-color: rgba(15, 118, 110, 0.28);
}

/* =========================================================
   Metrics
   ========================================================= */

.kq-metrics {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.82rem;
  margin: 1.15rem 0 2.35rem;
}

.kq-metric {
  padding: 1rem 1.05rem;
  border-radius: 18px;
  border: 1px solid var(--kq-line);
  background: #ffffff;
  box-shadow: 0 8px 22px var(--kq-shadow);
}

.kq-metric-number {
  display: block;
  color: var(--kq-ink);
  font-size: 1.28rem;
  line-height: 1.1;
  font-weight: 880;
  letter-spacing: -0.035em;
}

.kq-metric-label {
  display: block;
  margin-top: 0.34rem;
  color: var(--kq-muted);
  font-size: 0.76rem;
  line-height: 1.4;
  font-weight: 680;
}

/* =========================================================
   Common Sections
   ========================================================= */

.kq-section,
.home-section {
  margin: 2.5rem 0;
}

.kq-section-header,
.home-section-header {
  max-width: 820px;
  margin-bottom: 1.05rem;
  padding-bottom: 0.8rem;
  border-bottom: 1px solid var(--kq-line);
}

.kq-section-title,
.home-section-title {
  margin: 0;
  color: var(--kq-ink);
  font-size: clamp(1.45rem, 2.2vw, 1.85rem) !important;
  line-height: 1.24;
  font-weight: 860;
  letter-spacing: -0.04em;
}

.kq-section-subtitle,
.home-section-subtitle {
  max-width: 760px;
  margin: 0.42rem 0 0;
  color: var(--kq-muted);
  font-size: 0.9rem;
  line-height: 1.65;
}

/* =========================================================
   About
   ========================================================= */

.kq-card {
  position: relative;
  padding: 1.35rem 1.45rem;
  border-radius: 20px;
  border: 1px solid var(--kq-line);
  background: #ffffff;
  box-shadow: 0 10px 28px var(--kq-shadow);
}

.kq-card::before {
  content: "";
  position: absolute;
  left: 1.45rem;
  right: 1.45rem;
  top: 0;
  height: 3px;
  border-radius: 999px;
  background: linear-gradient(90deg, var(--kq-accent), rgba(161, 98, 7, 0.72));
}

.kq-card p {
  margin: 0.72rem 0;
  color: var(--kq-text);
  font-size: 0.92rem;
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
  font-weight: 780;
}

/* =========================================================
   Research Agenda
   ========================================================= */

.agenda-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.92rem;
}

.agenda-card {
  position: relative;
  min-height: 100%;
  padding: 1.25rem 1.25rem 1.15rem;
  border-radius: 20px;
  border: 1px solid var(--kq-line);
  background: #ffffff;
  box-shadow: 0 8px 22px var(--kq-shadow);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.agenda-card:hover {
  transform: translateY(-2px);
  border-color: rgba(15, 118, 110, 0.28);
  box-shadow: 0 14px 30px rgba(17, 24, 39, 0.075);
}

.agenda-top {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 1rem;
  margin-bottom: 0.85rem;
}

.agenda-number {
  display: inline-flex;
  padding: 0.25rem 0.52rem;
  border-radius: 999px;
  background: rgba(15, 118, 110, 0.08);
  color: var(--kq-accent-dark);
  font-size: 0.68rem;
  line-height: 1.25;
  font-weight: 850;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.agenda-theme {
  color: var(--kq-muted);
  font-size: 0.74rem;
  line-height: 1.35;
  font-weight: 730;
  text-align: right;
}

.agenda-content h3 {
  margin: 0 0 0.5rem;
  color: var(--kq-ink);
  font-size: 1.02rem !important;
  line-height: 1.38;
  font-weight: 840;
  letter-spacing: -0.02em;
}

.agenda-content p {
  margin: 0 0 0.82rem;
  color: var(--kq-text);
  font-size: 0.84rem;
  line-height: 1.68;
}

.agenda-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.38rem;
}

.agenda-tags span {
  display: inline-flex;
  align-items: center;
  padding: 0.2rem 0.52rem;
  border-radius: 999px;
  border: 1px solid var(--kq-line-soft);
  background: var(--kq-soft);
  color: #4b5563;
  font-size: 0.64rem;
  line-height: 1.35;
  font-weight: 690;
}

/* =========================================================
   News
   ========================================================= */

.kq-news-panel {
  display: grid;
  gap: 0.72rem;
}

.kq-news-group {
  border-radius: 18px;
  border: 1px solid var(--kq-line);
  background: #ffffff;
  box-shadow: 0 8px 22px var(--kq-shadow);
  overflow: hidden;
}

.kq-news-group summary {
  cursor: pointer;
  list-style: none;
  padding: 0.96rem 1.15rem;
  color: var(--kq-ink);
  font-size: 0.94rem;
  line-height: 1.35;
  font-weight: 830;
  letter-spacing: -0.015em;
  background: linear-gradient(180deg, #ffffff 0%, #fbfbfa 100%);
}

.kq-news-group summary::-webkit-details-marker {
  display: none;
}

.kq-news-group summary::after {
  content: "+";
  float: right;
  color: var(--kq-muted);
  font-weight: 850;
}

.kq-news-group[open] summary::after {
  content: "−";
}

.kq-news-list {
  margin: 0;
  padding: 0 1.35rem 1.05rem 2.2rem;
}

.kq-news-list li {
  margin: 0.42rem 0;
  color: var(--kq-text);
  font-size: 0.8rem;
  line-height: 1.64;
}

.kq-news-list li::marker {
  color: #a3a3a3;
}

.kq-news-list strong {
  color: var(--kq-ink);
  font-weight: 760;
}

.kq-news-list em {
  color: #2f343a;
}

.news-awards summary {
  color: var(--kq-red);
}

.news-research summary {
  color: var(--kq-accent-dark);
}

.news-funding summary {
  color: var(--kq-gold);
}

.news-service summary {
  color: var(--kq-ink);
}

/* =========================================================
   Visitors
   ========================================================= */

.kq-visitors {
  margin: 2.2rem 0 0;
  padding-top: 1.05rem;
  border-top: 1px solid var(--kq-line);
}

.kq-visitors-title {
  margin: 0 0 0.65rem;
  color: var(--kq-muted);
  font-size: 0.72rem;
  line-height: 1.3;
  font-weight: 780;
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

  .agenda-grid {
    grid-template-columns: 1fr;
  }

  .kq-hero {
    padding: 2rem 1.7rem;
  }
}

@media (max-width: 600px) {
  .kq-home {
    max-width: 100%;
  }

  .kq-hero {
    padding: 1.7rem 1.35rem;
    border-radius: 22px;
  }

  .kq-hero h1 {
    font-size: 2rem;
  }

  .kq-hero-desc {
    font-size: 0.94rem;
  }

  .kq-metrics {
    grid-template-columns: 1fr;
  }

  .kq-card {
    padding: 1.12rem;
  }

  .kq-card::before {
    left: 1.12rem;
    right: 1.12rem;
  }

  .agenda-card {
    padding: 1.08rem;
  }

  .agenda-top {
    display: block;
  }

  .agenda-theme {
    margin-top: 0.45rem;
    text-align: left;
  }

  .kq-news-group summary {
    padding: 0.88rem 1rem;
  }

  .kq-news-list {
    padding: 0 1rem 0.95rem 1.85rem;
  }

  .kq-news-list li {
    font-size: 0.76rem;
  }
}
</style>


<div class="kq-home">

  <!-- ================= Hero ================= -->
  <section class="kq-hero">
    <div class="kq-hero-inner">

      <div class="kq-eyebrow">Geomechanics · Computation · AI</div>

      <h1>Kai-Qi Li, Ph.D.</h1>

      <p class="kq-position">
        Incoming Professor, School of Water Resources and Hydropower Engineering, Wuhan University
      </p>

      <p class="kq-hero-desc">
        I develop <strong>mechanics-grounded</strong>, <strong>data-enabled</strong>, and
        <strong>uncertainty-aware</strong> methods to reveal, predict, and manage complex
        geotechnical systems under evolving environmental and engineering conditions.
      </p>

      <div class="kq-hero-actions">
        <a class="kq-button kq-button-primary" href="/join-us/">Join Us</a>
        <a class="kq-button kq-button-secondary" href="/publications/">Publications</a>
        <a class="kq-button kq-button-secondary" href="/cv/">CV</a>
      </div>

    </div>
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
        <div class="agenda-top">
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
        <div class="agenda-top">
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
        <div class="agenda-top">
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
        <div class="agenda-top">
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

      <details class="kq-news-group news-awards" open>
        <summary>Awards &amp; Honors</summary>
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
      </details>


      <details class="kq-news-group news-research">
        <summary>Research &amp; Publications</summary>
        <ul class="kq-news-list">
          <li>[2026] Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.</li>
          <li>[2026] Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em> in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em>.</li>
          <li>[2025] Published <em>Physics-informed neural networks for solving steady-state temperature field in artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>State of the art of mechanical behaviors of frozen soils through experimental investigation</em> in <em>Cold Regions Science and Technology</em>.</li>
        </ul>
      </details>


      <details class="kq-news-group news-funding">
        <summary>Funding</summary>
        <ul class="kq-news-list">
          <li>[2025–2026] Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical coupling in hydrate-bearing sediments using physics-informed neural networks.</li>
          <li>[2025–2029] Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project on digital twins for coastal resilience under extreme storm surges in Hong Kong.</li>
          <li>[2024–2026] Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed multi-fidelity neural networks for intelligent rectification of shield machine attitude in layered soils.</li>
          <li>[2022] Received the <strong>Centrally Funded Postdoctoral Fellowship HK$763,555</strong> for thermo-hydro-mechanical modelling of artificial ground freezing.</li>
        </ul>
      </details>


      <details class="kq-news-group news-service">
        <summary>Academic Service</summary>
        <ul class="kq-news-list">
          <li>[2025] Serving as Co-chair of Mini-Symposium 9: <em>Multiphysics Modeling of Geo-engineering and Geohazards</em> at <strong>IACMAG 2025</strong>, Hong Kong.</li>
          <li>[2024] Joined the <strong>Early-career Editorial Panel</strong> for the <em>European Journal of Soil Science</em>.</li>
          <li>[2024] Served as Session Chair at the <strong>12th National Conference on Engineering Geology</strong>, Shenzhen.</li>
          <li>[2023] Served as Secretary of the <strong>International Symposium on Innovations in Geotechnical Engineering towards Sustainability</strong>, IGES 2023.</li>
        </ul>
      </details>

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
