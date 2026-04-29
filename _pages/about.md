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
   ========================================================= */

:root {
  --kq-navy: #0f172a;
  --kq-blue: #2563eb;
  --kq-blue-dark: #1d4ed8;
  --kq-blue-soft: #eff6ff;
  --kq-text: #263238;
  --kq-muted: #5f6f85;
  --kq-light: #f8fbff;
  --kq-border: #dbe5f2;
  --kq-border-soft: #e7eef8;
  --kq-red: #dc2626;
  --kq-purple: #7e57c2;
  --kq-green: #16a34a;
  --kq-amber: #d97706;
}

.kq-home {
  max-width: 980px;
  margin: 0 auto;
  color: var(--kq-text);
  line-height: 1.65;
}

.kq-home a {
  color: var(--kq-blue-dark);
  text-decoration: none;
}

.kq-home a:hover {
  text-decoration: underline;
}

.kq-blue-text {
  color: var(--kq-blue);
}

/* =========================================================
   Hero
   ========================================================= */

.kq-hero {
  margin: 0.3rem 0 2rem;
  padding: 2rem 2.1rem 1.8rem;
  border: 1px solid var(--kq-border);
  border-radius: 22px;
  background:
    radial-gradient(circle at top right, rgba(37, 99, 235, 0.10), transparent 32%),
    linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.055);
}

.kq-hero-kicker {
  margin-bottom: 0.55rem;
  color: var(--kq-blue);
  font-size: 0.72rem;
  line-height: 1.2;
  font-weight: 800;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.kq-hero h1 {
  margin: 0;
  color: var(--kq-navy);
  font-size: clamp(1.75rem, 3vw, 2.35rem);
  line-height: 1.15;
  font-weight: 850;
  letter-spacing: -0.035em;
}

.kq-hero-position {
  margin: 0.55rem 0 0;
  color: #475569;
  font-size: 0.93rem;
  line-height: 1.55;
}

.kq-hero-tagline {
  max-width: 790px;
  margin: 1.05rem 0 0;
  color: var(--kq-navy);
  font-size: clamp(1.05rem, 1.8vw, 1.32rem);
  line-height: 1.45;
  font-weight: 780;
  letter-spacing: -0.025em;
}

.kq-hero-summary {
  max-width: 820px;
  margin: 0.75rem 0 0;
  color: var(--kq-muted);
  font-size: 0.88rem;
  line-height: 1.75;
}

.kq-hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1.2rem;
}

.kq-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.48rem 0.78rem;
  border-radius: 999px;
  font-size: 0.74rem;
  line-height: 1.2;
  font-weight: 760;
  border: 1px solid var(--kq-border);
  background: #ffffff;
  color: var(--kq-navy) !important;
  text-decoration: none !important;
}

.kq-btn-primary {
  border-color: var(--kq-blue);
  background: var(--kq-blue);
  color: #ffffff !important;
}

.kq-btn:hover {
  transform: translateY(-1px);
  box-shadow: 0 7px 18px rgba(15, 23, 42, 0.08);
}

/* =========================================================
   Highlight Metrics
   ========================================================= */

.kq-metrics {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0.75rem;
  margin: 1.2rem 0 2rem;
}

.kq-metric-card {
  padding: 0.95rem 0.95rem 0.9rem;
  border: 1px solid var(--kq-border);
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 7px 20px rgba(15, 23, 42, 0.035);
}

.kq-metric-number {
  color: var(--kq-blue);
  font-size: 1.05rem;
  line-height: 1.25;
  font-weight: 850;
  letter-spacing: -0.02em;
}

.kq-metric-label {
  margin-top: 0.28rem;
  color: var(--kq-muted);
  font-size: 0.72rem;
  line-height: 1.45;
  font-weight: 650;
}

/* =========================================================
   Common Section
   ========================================================= */

.kq-section,
.home-section {
  margin: 2.15rem 0;
}

.kq-section-head,
.home-section-header {
  margin-bottom: 0.95rem;
  padding-bottom: 0.65rem;
  border-bottom: 1px solid var(--kq-border-soft);
}

.kq-kicker,
.home-section-kicker {
  margin: 0 0 0.38rem;
  color: var(--kq-blue);
  font-size: 0.7rem;
  line-height: 1.2;
  font-weight: 800;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.kq-section-title,
.home-section-header h2 {
  margin: 0;
  color: var(--kq-navy);
  font-size: clamp(1.08rem, 1.7vw, 1.34rem) !important;
  line-height: 1.35;
  font-weight: 820;
  letter-spacing: -0.02em;
}

.kq-section-subtitle,
.home-section-intro {
  max-width: 820px;
  margin: 0.45rem 0 0;
  color: var(--kq-muted);
  font-size: 0.82rem;
  line-height: 1.68;
}

/* =========================================================
   About
   ========================================================= */

.kq-about-panel {
  padding: 1.15rem 1.25rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.035);
}

.kq-about-panel p {
  margin: 0.55rem 0;
  color: #405168;
  font-size: 0.84rem;
  line-height: 1.75;
}

.kq-about-panel p:first-child {
  margin-top: 0;
}

.kq-about-panel p:last-child {
  margin-bottom: 0;
}

/* =========================================================
   Research Agenda - Original Content, Refined Style
   ========================================================= */

.agenda-manifesto {
  margin: 1.05rem 0 1rem;
  padding: 1.1rem 1.25rem;
  border: 1px solid #cfe0f5;
  border-radius: 18px;
  background:
    radial-gradient(circle at top right, rgba(37, 99, 235, 0.08), transparent 32%),
    linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.04);
}

.agenda-manifesto-title {
  margin: 0 0 0.5rem;
  color: var(--kq-navy);
  font-size: 0.96rem;
  line-height: 1.45;
  font-weight: 820;
  letter-spacing: -0.015em;
}

.agenda-manifesto-title span {
  color: var(--kq-blue);
}

.agenda-manifesto p {
  margin: 0;
  color: #4f6178;
  font-size: 0.81rem;
  line-height: 1.72;
}

.agenda-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 0.9rem;
}

.agenda-card {
  display: grid;
  grid-template-columns: 185px minmax(0, 1fr);
  gap: 1rem;
  padding: 1.05rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.035);
}

.agenda-index {
  padding: 0.85rem 0.85rem;
  border-radius: 14px;
  background: linear-gradient(180deg, #f8fbff 0%, #eff6ff 100%);
  border: 1px solid #dbeafe;
}

.agenda-number {
  color: var(--kq-blue);
  font-size: 0.67rem;
  line-height: 1.3;
  font-weight: 850;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.agenda-theme {
  margin-top: 0.42rem;
  color: var(--kq-navy);
  font-size: 0.88rem;
  line-height: 1.35;
  font-weight: 820;
  letter-spacing: -0.015em;
}

.agenda-content h3 {
  margin: 0 0 0.45rem;
  color: var(--kq-navy);
  font-size: 0.95rem !important;
  line-height: 1.38;
  font-weight: 820;
  letter-spacing: -0.015em;
}

.agenda-content p {
  margin: 0 0 0.65rem;
  color: #4f6178;
  font-size: 0.8rem;
  line-height: 1.68;
}

.agenda-question {
  margin: 0.7rem 0 0.75rem;
  padding: 0.7rem 0.85rem;
  border-left: 3px solid var(--kq-blue);
  border-radius: 10px;
  background: #f8fbff;
  color: #43546b;
  font-size: 0.76rem;
  line-height: 1.62;
}

.agenda-question strong {
  color: var(--kq-navy);
  font-weight: 800;
}

.agenda-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.32rem;
}

.agenda-tags span {
  display: inline-flex;
  align-items: center;
  padding: 0.17rem 0.45rem;
  border-radius: 999px;
  background: #f1f5f9;
  color: #52627a;
  font-size: 0.61rem;
  line-height: 1.35;
  font-weight: 650;
}

/* =========================================================
   Selected News
   ========================================================= */

.kq-news-panel {
  padding: 1.1rem 1.35rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.035);
}

.kq-news-group {
  margin-top: 1.05rem;
  padding-top: 0.95rem;
  border-top: 1px solid var(--kq-border-soft);
}

.kq-news-group:first-child {
  margin-top: 0;
  padding-top: 0;
  border-top: none;
}

.kq-news-heading {
  position: relative;
  margin: 0 0 0.52rem;
  padding-left: 1rem;
  font-size: 0.9rem !important;
  line-height: 1.35;
  font-weight: 820;
  letter-spacing: -0.01em;
}

.kq-news-heading::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.48em;
  width: 0.42rem;
  height: 0.42rem;
  border-radius: 999px;
}

.kq-news-awards {
  color: var(--kq-red);
}

.kq-news-awards::before {
  background: var(--kq-red);
}

.kq-news-research {
  color: var(--kq-purple);
}

.kq-news-research::before {
  background: var(--kq-purple);
}

.kq-news-funding {
  color: var(--kq-blue);
}

.kq-news-funding::before {
  background: var(--kq-blue);
}

.kq-news-service {
  color: var(--kq-green);
}

.kq-news-service::before {
  background: var(--kq-green);
}

.kq-news-list {
  margin: 0;
  padding-left: 1rem;
}

.kq-news-list li {
  margin: 0.33rem 0;
  color: #4f6178;
  font-size: 0.78rem;
  line-height: 1.62;
}

.kq-news-list li::marker {
  color: #9aa9bc;
}

.kq-news-list strong {
  color: #111827;
  font-weight: 750;
}

.kq-news-list em {
  color: #374151;
}

/* =========================================================
   Join / Collaboration
   ========================================================= */

.kq-join-panel {
  padding: 1.25rem 1.35rem;
  border: 1px solid #cfe0f5;
  border-radius: 18px;
  background:
    radial-gradient(circle at top right, rgba(37, 99, 235, 0.09), transparent 35%),
    linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 8px 22px rgba(15, 23, 42, 0.04);
}

.kq-join-panel h2 {
  margin: 0;
  color: var(--kq-navy);
  font-size: 1.05rem !important;
  line-height: 1.35;
  font-weight: 820;
  letter-spacing: -0.02em;
}

.kq-join-panel p {
  max-width: 820px;
  margin: 0.55rem 0 0;
  color: #4f6178;
  font-size: 0.83rem;
  line-height: 1.7;
}

.kq-join-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 0.95rem;
}

/* =========================================================
   Visitors
   ========================================================= */

.kq-visitors {
  margin: 1.7rem 0 0;
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
    grid-template-columns: repeat(2, 1fr);
  }

  .agenda-card {
    grid-template-columns: 1fr;
  }

  .kq-hero {
    padding: 1.6rem 1.4rem;
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

  .kq-section-title,
  .home-section-header h2 {
    font-size: 1.06rem !important;
  }

  .kq-section-subtitle,
  .home-section-intro {
    font-size: 0.8rem;
  }

  .kq-news-panel,
  .kq-about-panel,
  .kq-join-panel,
  .agenda-manifesto {
    padding: 1rem;
  }

  .agenda-card {
    padding: 0.95rem;
  }

  .agenda-content h3,
  .kq-news-heading {
    font-size: 0.86rem !important;
  }

  .agenda-content p,
  .agenda-question,
  .kq-news-list li {
    font-size: 0.75rem;
  }
}
</style>


<div class="kq-home">

  <!-- ================= Hero ================= -->
  <section class="kq-hero">

    <div class="kq-hero-kicker">Geomechanics · Computation · Artificial Intelligence</div>

    <h1>Kai-Qi Li, Ph.D.</h1>

    <p class="kq-hero-position">
      Incoming Professor, School of Water Resources and Hydropower Engineering, Wuhan University
    </p>

    <p class="kq-hero-tagline">
      Shaping the future of geotechnics through
      <span class="kq-blue-text">intelligence</span> and
      <span class="kq-blue-text">uncertainty</span> mastery.
    </p>

    <p class="kq-hero-summary">
      My research develops mechanics-based, data-enabled, and uncertainty-aware methods
      for complex geomaterials and geotechnical infrastructure, with particular interests
      in frozen soils, artificial ground freezing, hydrate-bearing sediments, multiphysics
      modelling, physics-informed learning, and risk-informed engineering decisions.
    </p>

    <div class="kq-hero-actions">
      <a class="kq-btn kq-btn-primary" href="/publications/">Publications</a>
      <a class="kq-btn" href="/cv/">CV</a>
      <a class="kq-btn" href="/join-us/">Join Us</a>
      <a class="kq-btn" href="mailto:kqcee.li@polyu.edu.hk">Email</a>
      <a class="kq-btn" href="mailto:kqceeli@163.com">Future Group Contact</a>
    </div>

  </section>


  <!-- ================= Metrics ================= -->
  <section class="kq-metrics">

    <div class="kq-metric-card">
      <div class="kq-metric-number">2026</div>
      <div class="kq-metric-label">NSFC Excellent Young Scientists Fund Overseas</div>
    </div>

    <div class="kq-metric-card">
      <div class="kq-metric-number">PI</div>
      <div class="kq-metric-label">Physics-informed modelling of hydrate-bearing sediments</div>
    </div>

    <div class="kq-metric-card">
      <div class="kq-metric-number">HK$55M+</div>
      <div class="kq-metric-label">Research funding portfolio as PI / key participant / Co-I</div>
    </div>

    <div class="kq-metric-card">
      <div class="kq-metric-number">2024</div>
      <div class="kq-metric-label">PolyU Distinguished Postdoctoral Fellowship</div>
    </div>

  </section>


  <!-- ================= About ================= -->
  <section class="kq-section" id="about">

    <div class="kq-section-head">
      <div class="kq-kicker">About</div>
      <h2 class="kq-section-title">Mechanics, data, and uncertainty for safer ground infrastructure</h2>
    </div>

    <div class="kq-about-panel">
      <p>
        I am an incoming Professor at the School of Water Resources and Hydropower Engineering,
        Wuhan University. I am building a new research group at the interface of geomechanics,
        computational modelling, and artificial intelligence.
      </p>

      <p>
        My work focuses on complex geotechnical systems where geomaterial behaviour,
        environmental loading, sparse observations, and model uncertainty interact.
        I am particularly interested in developing computational tools that are not only
        accurate, but also physically interpretable, uncertainty-aware, and useful for
        engineering decision-making.
      </p>

      <p>
        Current research themes include artificial ground freezing, frozen soil mechanics,
        hydrate-bearing sediments, thermo-hydro-mechanical-chemical coupling,
        physics-informed neural networks, multi-fidelity modelling, Bayesian updating,
        random fields, reliability analysis, and digital twins for geotechnical infrastructure.
      </p>
    </div>

  </section>


  <!-- ================= Research Agenda ================= -->
  <section class="home-section" id="research-agenda">

    <div class="home-section-header">
      <p class="home-section-kicker">Research Agenda</p>
      <h2>From uncertain ground to intelligent and resilient geotechnical infrastructure</h2>
      <p class="home-section-intro">
        My research agenda is organized around a central ambition: to transform geotechnical engineering
        from experience-driven prediction toward mechanics-informed, data-enhanced, and uncertainty-aware
        decision-making. Rather than treating mechanics, computation, uncertainty, and artificial intelligence
        as separate topics, my group will develop integrated frameworks that connect them into a coherent
        scientific and engineering paradigm.
      </p>
    </div>

    <div class="agenda-manifesto">
      <div class="agenda-manifesto-title">
        A long-term research program for <span>intelligent geotechnics under uncertainty</span>
      </div>
      <p>
        The ground is heterogeneous, history-dependent, multiphysical, and only partially observable.
        The next generation of geotechnical methods must therefore learn from data without abandoning
        mechanics, quantify uncertainty rather than ignore it, and support engineering decisions rather
        than only reproduce observations.
      </p>
    </div>

    <div class="agenda-grid">

      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 01</div>
          <div class="agenda-theme">Complex ground systems</div>
        </div>

        <div class="agenda-content">
          <h3>Revealing the mechanics of ground in extreme and evolving environments</h3>
          <p>
            I study how geomaterials and ground systems behave when they are governed by coupled thermal,
            hydraulic, mechanical, chemical, and phase-change processes. This includes frozen soils,
            artificial ground freezing, hydrate-bearing sediments, and other multiphysical systems where
            classical assumptions are often insufficient.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can we describe, model, and predict ground behaviour when temperature, water, stress,
            microstructure, and environmental loading evolve together?
          </div>

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
          <h3>Building AI that understands mechanics, not merely fits data</h3>
          <p>
            I develop physics-informed and mechanics-guided computational methods that combine constitutive
            modelling, numerical simulation, machine learning, neural operators, and graph-based learning.
            The goal is to create intelligent models that remain interpretable, transferable, and trustworthy
            when data are sparse, noisy, or biased.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can artificial intelligence become a scientific engine for geomechanics by embedding physical
            laws, boundary conditions, material behaviour, and engineering constraints?
          </div>

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
          <h3>Turning uncertainty into actionable knowledge for engineering decisions</h3>
          <p>
            I work on uncertainty quantification, stochastic analysis, reliability assessment, and risk-informed
            design for geotechnical systems. My aim is to move beyond deterministic prediction and develop
            decision-support tools that explicitly account for spatial variability, model uncertainty, monitoring
            data, and evolving risk.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can we quantify what we do not know, update predictions as evidence accumulates, and make safer
            decisions for infrastructure built in uncertain ground?
          </div>

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
          <h3>Translating advanced models into safer underground and climate-resilient infrastructure</h3>
          <p>
            A major objective of my group is to connect frontier modelling with engineering practice. We aim to
            develop computational tools, digital workflows, and risk-informed design methods for underground
            construction, cold-region infrastructure, coastal and marine geotechnics, and large-scale civil
            infrastructure under environmental change.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can advanced geomechanics and AI be transformed into practical tools that improve safety,
            resilience, sustainability, and engineering confidence?
          </div>

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

    <div class="kq-section-head">
      <div class="kq-kicker">Updates</div>
      <h2 class="kq-section-title">Selected News</h2>
      <p class="kq-section-subtitle">
        A selection of recent highlights in research, funding, awards, and academic service.
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


  <!-- ================= Join Us ================= -->
  <section class="kq-section" id="join-us">

    <div class="kq-join-panel">
      <h2>Join the group</h2>

      <p>
        I am looking for motivated students and collaborators who are interested in
        geomechanics, computational modelling, artificial intelligence, uncertainty
        quantification, and resilient infrastructure. Students with backgrounds in
        geotechnical engineering, mechanics, applied mathematics, computer science,
        data science, or related areas are welcome to contact me.
      </p>

      <p>
        If you are curious, rigorous, and excited by interdisciplinary research,
        please send me your CV, transcripts if applicable, and a brief description
        of your research interests.
      </p>

      <div class="kq-join-links">
        <a class="kq-btn kq-btn-primary" href="/join-us/">Opportunities</a>
        <a class="kq-btn" href="mailto:kqceeli@163.com">kqceeli@163.com</a>
        <a class="kq-btn" href="mailto:kqcee.li@polyu.edu.hk">kqcee.li@polyu.edu.hk</a>
      </div>
    </div>

  </section>


  <!-- ================= Visitors ================= -->
  <section class="kq-visitors">
    <div class="kq-visitors-title">Visitors</div>
    <script type="text/javascript" id="clustrmaps"
      src="//clustrmaps.com/map_v2.js?d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=ffffff&cmo=1a72b0&cmn=ff5353&ct=000000">
    </script>
  </section>

</div>
