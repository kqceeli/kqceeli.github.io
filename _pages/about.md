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
   Clean Academic / Nature + Science Inspired Design
   For about_11.md
   ========================================================= */

/* ---------- Theme Variables ---------- */
:root {
  --kq-ink: #111827;
  --kq-text: #374151;
  --kq-muted: #6b7280;

  --kq-paper: #ffffff;
  --kq-soft: #f7f7f4;
  --kq-warm: #fbfaf6;

  --kq-line: #e4e1d8;
  --kq-line-soft: #efede6;

  --kq-accent: #0b766d;
  --kq-accent-dark: #075f59;
  --kq-accent-soft: rgba(11, 118, 109, 0.1);

  --kq-red: #a23a42;
  --kq-gold: #a16207;

  --kq-shadow: rgba(17, 24, 39, 0.075);
}


/* =========================================================
   Global Page Adjustment
   ========================================================= */

.page__content {
  font-size: 0.98rem;
  line-height: 1.75;
  color: var(--kq-text);
}

.page__content p {
  margin-top: 0;
  margin-bottom: 1rem;
}

.page__content a {
  color: var(--kq-accent-dark);
  text-decoration: none;
}

.page__content a:hover {
  color: var(--kq-red);
  text-decoration: underline;
}

.kq-home {
  max-width: 1080px;
  margin: 0 auto;
  padding: 0.2rem 0 3.5rem;
}


/* =========================================================
   Top Navigation Enhancement
   ========================================================= */

.masthead {
  border-bottom: 1px solid #e8e5dc;
  background: rgba(255, 255, 255, 0.94);
  backdrop-filter: blur(10px);
}

.greedy-nav {
  background: transparent;
}

.greedy-nav .site-title {
  color: #1f2937;
  font-weight: 800;
}

.greedy-nav a {
  color: #4b5563;
  font-weight: 550;
}

.greedy-nav a:hover {
  color: var(--kq-accent-dark);
}

.greedy-nav .visible-links a::before {
  background: var(--kq-accent-dark);
}


/* =========================================================
   Author Sidebar Enhancement
   ========================================================= */

.author__avatar img {
  max-width: 150px;
  border-radius: 50%;
  border: 3px solid #f1efe8;
  box-shadow: 0 10px 28px rgba(17, 24, 39, 0.12);
}

.author__content {
  margin-top: 0.75rem;
}

.author__name {
  font-size: 1.05rem;
  font-weight: 800;
  color: #1f2937;
}

.author__bio {
  color: #4b5563;
  line-height: 1.55;
}

.author__urls-wrapper button {
  border-radius: 999px;
}


/* =========================================================
   Hero Section
   ========================================================= */

.kq-hero {
  position: relative;
  margin: 0.45rem 0 1.6rem;
  padding: 2.25rem 2.45rem 2.35rem;
  border-radius: 24px;
  border: 1px solid rgba(15, 118, 110, 0.14);
  background:
    radial-gradient(circle at 92% 0%, rgba(15, 118, 110, 0.11), transparent 30%),
    linear-gradient(135deg, rgba(15, 118, 110, 0.08), rgba(180, 83, 9, 0.055)),
    var(--kq-warm);
  overflow: hidden;
  box-shadow: 0 14px 36px rgba(17, 24, 39, 0.055);
}

.kq-hero::after {
  content: "";
  position: absolute;
  right: -55px;
  top: -65px;
  width: 190px;
  height: 190px;
  border-radius: 999px;
  background: rgba(15, 118, 110, 0.075);
}

.kq-hero > * {
  position: relative;
  z-index: 1;
}

/* Hide the top small label such as GEOMECHANICS · COMPUTATION · AI */
.kq-eyebrow,
.kq-hero-kicker,
.hero-kicker,
.hero-eyebrow {
  display: none !important;
}

.kq-hero h1 {
  margin: 0;
  color: var(--kq-ink);
  font-size: clamp(1.95rem, 3.4vw, 2.75rem);
  line-height: 1.1;
  font-weight: 850;
  letter-spacing: -0.04em;
}

.kq-position {
  margin: 1.05rem 0 0;
  max-width: 780px;
  color: #374151;
  font-size: 0.98rem;
  line-height: 1.65;
  font-weight: 650;
}

.kq-intro {
  margin: 1.75rem 0 0;
  max-width: 790px;
  color: var(--kq-text);
  font-size: 1rem;
  line-height: 1.8;
}

.kq-intro strong {
  color: var(--kq-ink);
  font-weight: 760;
}


/* ---------- Hero Buttons ---------- */

.kq-hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.65rem;
}

.kq-button {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 0.68rem 1.05rem;
  border-radius: 999px;
  border: 1px solid transparent;
  font-size: 0.86rem;
  line-height: 1;
  font-weight: 760;
  letter-spacing: 0.01em;
  text-decoration: none !important;
  transition: all 0.18s ease;
}

.kq-button-primary {
  color: #ffffff !important;
  background: var(--kq-accent-dark);
  border-color: var(--kq-accent-dark);
  box-shadow: 0 10px 22px rgba(7, 95, 89, 0.18);
}

.kq-button-primary:hover {
  color: #ffffff !important;
  background: #064e49;
  transform: translateY(-1px);
}

.kq-button-secondary {
  color: var(--kq-accent-dark) !important;
  background: rgba(255, 255, 255, 0.72);
  border-color: rgba(15, 118, 110, 0.24);
}

.kq-button-secondary:hover {
  color: #064e49 !important;
  background: #ffffff;
  border-color: rgba(15, 118, 110, 0.38);
  transform: translateY(-1px);
}


/* =========================================================
   Metrics
   ========================================================= */

.kq-metrics {
  max-width: 820px;
  margin: 1.35rem auto 1.85rem;
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.85rem;
}

.kq-metric {
  position: relative;
  min-height: auto;
  padding: 0.95rem 1rem 1rem;
  border-radius: 16px;
  border: 1px solid var(--kq-line);
  background: linear-gradient(180deg, #ffffff 0%, #fbfaf7 100%);
  box-shadow: 0 8px 20px rgba(17, 24, 39, 0.06);
  overflow: hidden;
}

.kq-metric::before {
  content: "";
  position: absolute;
  left: 1rem;
  top: 0;
  width: 42px;
  height: 3px;
  border-radius: 999px;
  background: var(--kq-accent);
}

.kq-metric-number {
  display: block;
  color: var(--kq-ink);
  font-size: 1.5rem;
  line-height: 1.05;
  font-weight: 860;
  letter-spacing: -0.04em;
}

.kq-metric-label {
  display: block;
  margin-top: 0.45rem;
  color: var(--kq-muted);
  font-size: 0.8rem;
  line-height: 1.3;
  font-weight: 700;
}


/* =========================================================
   Section Common Style
   ========================================================= */

.kq-section {
  margin-top: 1.45rem;
  padding: 1.55rem 1.65rem;
  border-radius: 22px;
  border: 1px solid var(--kq-line);
  background: var(--kq-paper);
  box-shadow: 0 10px 28px rgba(17, 24, 39, 0.045);
}

.kq-section-soft {
  background:
    linear-gradient(135deg, rgba(15, 118, 110, 0.045), rgba(180, 83, 9, 0.035)),
    #fffdf8;
}

.kq-section-head {
  margin-bottom: 1.1rem;
}

.kq-section-title {
  margin: 0;
  color: var(--kq-ink);
  font-size: 1.22rem;
  line-height: 1.25;
  font-weight: 850;
  letter-spacing: -0.025em;
}

.kq-section-subtitle {
  margin: 0.42rem 0 0;
  max-width: 760px;
  color: var(--kq-muted);
  font-size: 0.92rem;
  line-height: 1.65;
}


/* =========================================================
   Research / Interest Cards
   ========================================================= */

.kq-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 0.95rem;
}

.kq-card {
  position: relative;
  padding: 1.15rem 1.15rem 1.2rem;
  border-radius: 18px;
  border: 1px solid var(--kq-line-soft);
  background: #ffffff;
  box-shadow: 0 7px 18px rgba(17, 24, 39, 0.04);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.kq-card:hover {
  transform: translateY(-2px);
  border-color: rgba(15, 118, 110, 0.22);
  box-shadow: 0 12px 26px rgba(17, 24, 39, 0.07);
}

.kq-card h3 {
  margin: 0 0 0.55rem;
  color: var(--kq-ink);
  font-size: 1rem;
  line-height: 1.35;
  font-weight: 820;
}

.kq-card p {
  margin: 0;
  color: var(--kq-text);
  font-size: 0.9rem;
  line-height: 1.65;
}

.kq-tag {
  display: inline-flex;
  align-items: center;
  margin-bottom: 0.72rem;
  padding: 0.28rem 0.55rem;
  border-radius: 999px;
  color: var(--kq-accent-dark);
  background: var(--kq-accent-soft);
  font-size: 0.68rem;
  line-height: 1;
  font-weight: 800;
  letter-spacing: 0.045em;
  text-transform: uppercase;
}


/* =========================================================
   News / Updates
   ========================================================= */

.kq-news-list {
  display: grid;
  gap: 0.75rem;
  margin: 0;
  padding: 0;
  list-style: none;
}

.kq-news-item {
  display: grid;
  grid-template-columns: 92px minmax(0, 1fr);
  gap: 0.95rem;
  align-items: start;
  padding: 0.9rem 0;
  border-bottom: 1px solid var(--kq-line-soft);
}

.kq-news-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
}

.kq-news-date {
  color: var(--kq-accent-dark);
  font-size: 0.78rem;
  line-height: 1.45;
  font-weight: 800;
}

.kq-news-text {
  color: var(--kq-text);
  font-size: 0.92rem;
  line-height: 1.65;
}

.kq-news-text strong {
  color: var(--kq-ink);
}


/* =========================================================
   Selected Publications / Work List
   ========================================================= */

.kq-pub-list {
  display: grid;
  gap: 0.95rem;
  margin: 0;
  padding: 0;
  list-style: none;
}

.kq-pub-item {
  padding: 1rem 1.05rem;
  border-radius: 16px;
  border: 1px solid var(--kq-line-soft);
  background: #ffffff;
}

.kq-pub-title {
  margin: 0 0 0.35rem;
  color: var(--kq-ink);
  font-size: 0.98rem;
  line-height: 1.45;
  font-weight: 800;
}

.kq-pub-meta {
  color: var(--kq-muted);
  font-size: 0.84rem;
  line-height: 1.55;
}

.kq-pub-meta em {
  color: #4b5563;
}


/* =========================================================
   Two-column Layout
   ========================================================= */

.kq-two-col {
  display: grid;
  grid-template-columns: minmax(0, 1.15fr) minmax(260px, 0.85fr);
  gap: 1rem;
  align-items: start;
}

.kq-side-box {
  padding: 1.1rem 1.15rem;
  border-radius: 18px;
  border: 1px solid var(--kq-line-soft);
  background: #fbfaf7;
}

.kq-side-box h3 {
  margin: 0 0 0.6rem;
  color: var(--kq-ink);
  font-size: 0.98rem;
  font-weight: 820;
}

.kq-side-box p,
.kq-side-box li {
  color: var(--kq-text);
  font-size: 0.9rem;
  line-height: 1.65;
}

.kq-side-box ul {
  margin: 0;
  padding-left: 1.1rem;
}


/* =========================================================
   Visitor Map / Script Section
   ========================================================= */

.kq-map {
  margin-top: 1.45rem;
  padding: 1.25rem;
  border-radius: 20px;
  border: 1px solid var(--kq-line);
  background: #ffffff;
  box-shadow: 0 8px 22px rgba(17, 24, 39, 0.045);
  text-align: center;
}

.kq-map-title {
  margin: 0 0 0.8rem;
  color: var(--kq-ink);
  font-size: 1rem;
  font-weight: 800;
}


/* =========================================================
   Small Utilities
   ========================================================= */

.kq-muted {
  color: var(--kq-muted);
}

.kq-highlight {
  color: var(--kq-accent-dark);
  font-weight: 760;
}

.kq-divider {
  height: 1px;
  margin: 1.3rem 0;
  background: var(--kq-line-soft);
}


/* =========================================================
   Responsive
   ========================================================= */

@media (max-width: 1100px) {
  .kq-home {
    max-width: 100%;
  }
}

@media (max-width: 900px) {
  .kq-hero {
    padding: 2rem 1.75rem 2.1rem;
  }

  .kq-metrics {
    max-width: 100%;
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .kq-grid {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .kq-two-col {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 640px) {
  .kq-home {
    padding-bottom: 2.5rem;
  }

  .kq-hero {
    margin-top: 0.2rem;
    padding: 1.7rem 1.35rem 1.85rem;
    border-radius: 20px;
  }

  .kq-hero h1 {
    font-size: 2rem;
    line-height: 1.12;
  }

  .kq-position {
    margin-top: 0.85rem;
    font-size: 0.93rem;
    line-height: 1.6;
  }

  .kq-intro {
    margin-top: 1.4rem;
    font-size: 0.94rem;
    line-height: 1.72;
  }

  .kq-hero-actions {
    gap: 0.6rem;
  }

  .kq-button {
    width: 100%;
  }

  .kq-metrics {
    margin: 1.15rem 0 1.45rem;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 0.7rem;
  }

  .kq-metric {
    padding: 0.82rem 0.85rem 0.88rem;
    border-radius: 15px;
  }

  .kq-metric-number {
    font-size: 1.32rem;
  }

  .kq-metric-label {
    font-size: 0.75rem;
  }

  .kq-section {
    margin-top: 1.15rem;
    padding: 1.25rem 1.15rem;
    border-radius: 18px;
  }

  .kq-section-title {
    font-size: 1.1rem;
  }

  .kq-grid {
    grid-template-columns: 1fr;
  }

  .kq-news-item {
    grid-template-columns: 1fr;
    gap: 0.25rem;
  }

  .kq-news-date {
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
