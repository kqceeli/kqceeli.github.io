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
   Homepage for Kai-Qi Li
   Scoped design for Minimal Mistakes / Jekyll
   ========================================================= */

.home-page {
  max-width: 940px;
  margin: 0 auto;
  color: #1f2937;
  font-size: 0.96rem;
  line-height: 1.72;
}

/* ---------- Hero ---------- */

.home-hero {
  position: relative;
  max-width: 860px;
  margin: 0 0 2.2rem;
  padding: 2.25rem 2.3rem 2.15rem;
  border-radius: 24px;
  background:
    radial-gradient(circle at top right, rgba(37, 99, 235, 0.13), transparent 38%),
    linear-gradient(135deg, #ffffff 0%, #f8fafc 52%, #eef4ff 100%);
  border: 1px solid #e2e8f0;
  box-shadow: 0 18px 42px rgba(15, 23, 42, 0.07);
  overflow: hidden;
}

.home-hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background:
    linear-gradient(90deg, rgba(37, 99, 235, 0.09), transparent 42%),
    radial-gradient(circle at bottom left, rgba(14, 165, 233, 0.10), transparent 40%);
  pointer-events: none;
}

.home-hero-inner {
  position: relative;
  z-index: 1;
}

.home-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  margin-bottom: 0.85rem;
  padding: 0.28rem 0.72rem;
  border-radius: 999px;
  background: rgba(37, 99, 235, 0.08);
  border: 1px solid rgba(37, 99, 235, 0.16);
  color: #1d4ed8;
  font-size: 0.72rem;
  font-weight: 800;
  letter-spacing: 0.09em;
  text-transform: uppercase;
}

.home-hero h1 {
  margin: 0 0 0.55rem;
  color: #0f172a;
  font-size: clamp(2.05rem, 3.5vw, 2.85rem);
  line-height: 1.08;
  letter-spacing: -0.04em;
  font-weight: 850;
}

.home-subtitle {
  max-width: 760px;
  margin: 0 0 0.95rem;
  color: #334155;
  font-size: 0.98rem;
  line-height: 1.58;
  font-weight: 650;
}

.home-mission {
  max-width: 790px;
  margin: 1.05rem 0 1.05rem;
  color: #0f172a;
  font-size: clamp(1.05rem, 2.0vw, 1.32rem);
  line-height: 1.5;
  font-weight: 800;
  letter-spacing: -0.025em;
}

.home-mission span {
  color: #2563eb;
}

.home-lead {
  max-width: 780px;
  margin: 0;
  color: #475569;
  font-size: 0.95rem;
  line-height: 1.78;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.72rem;
  margin-top: 1.45rem;
}

.home-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 40px;
  padding: 0.58rem 1rem;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 750;
  text-decoration: none !important;
  transition: all 0.18s ease;
}

.home-btn-primary {
  background: #1d4ed8;
  border: 1px solid #1d4ed8;
  color: #ffffff !important;
  box-shadow: 0 10px 22px rgba(37, 99, 235, 0.20);
}

.home-btn-primary:hover {
  background: #1e40af;
  transform: translateY(-1px);
}

.home-btn-secondary {
  background: #ffffff;
  border: 1px solid #cbd5e1;
  color: #334155 !important;
}

.home-btn-secondary:hover {
  border-color: #94a3b8;
  color: #0f172a !important;
  transform: translateY(-1px);
}

/* ---------- Section common ---------- */

.home-section {
  max-width: 860px;
  margin: 2.45rem 0;
}

.home-section-header {
  margin-bottom: 1.05rem;
  padding-bottom: 0.7rem;
  border-bottom: 1px solid #e5e7eb;
}

.home-section-kicker {
  margin: 0 0 0.32rem;
  color: #475569;
  font-size: 0.72rem;
  font-weight: 850;
  letter-spacing: 0.13em;
  text-transform: uppercase;
}

.home-section h2 {
  margin: 0;
  color: #0f172a;
  font-size: 1.34rem;
  line-height: 1.34;
  letter-spacing: -0.026em;
  font-weight: 850;
}

.home-section-intro {
  max-width: 800px;
  margin: 0.85rem 0 0;
  color: #64748b;
  font-size: 0.94rem;
  line-height: 1.74;
}

.home-highlight {
  color: #0f172a;
  font-weight: 750;
}

/* ---------- About ---------- */

.home-about-card {
  padding: 1.45rem 1.55rem;
  border-radius: 20px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 10px 28px rgba(15, 23, 42, 0.045);
}

.home-about-card p {
  margin: 0 0 0.95rem;
  color: #475569;
  font-size: 0.94rem;
  line-height: 1.78;
}

.home-about-card p:last-child {
  margin-bottom: 0;
}

.home-about-card a {
  color: #1d4ed8;
  text-decoration: none;
  border-bottom: 1px solid rgba(37, 99, 235, 0.25);
}

.home-about-card a:hover {
  color: #1e40af;
  border-bottom-color: rgba(30, 64, 175, 0.55);
}

/* ---------- Research Agenda ---------- */

.agenda-manifesto {
  margin-bottom: 1rem;
  padding: 1.25rem 1.35rem;
  border-radius: 20px;
  background:
    linear-gradient(135deg, rgba(15, 23, 42, 0.97), rgba(30, 41, 59, 0.97));
  box-shadow: 0 16px 34px rgba(15, 23, 42, 0.14);
}

.agenda-manifesto-title {
  margin: 0 0 0.45rem;
  color: #ffffff;
  font-size: 1.05rem;
  line-height: 1.45;
  font-weight: 850;
  letter-spacing: -0.018em;
}

.agenda-manifesto-title span {
  color: #93c5fd;
}

.agenda-manifesto p {
  margin: 0;
  color: #dbe4ef;
  font-size: 0.92rem;
  line-height: 1.76;
}

.agenda-grid {
  display: grid;
  gap: 1rem;
}

.agenda-card {
  display: grid;
  grid-template-columns: 170px minmax(0, 1fr);
  gap: 1.15rem;
  padding: 1.28rem 1.35rem;
  border-radius: 20px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 10px 26px rgba(15, 23, 42, 0.045);
}

.agenda-index {
  display: flex;
  flex-direction: column;
  gap: 0.38rem;
}

.agenda-number {
  color: #2563eb;
  font-size: 0.72rem;
  font-weight: 900;
  letter-spacing: 0.13em;
  text-transform: uppercase;
}

.agenda-theme {
  color: #64748b;
  font-size: 0.75rem;
  font-weight: 750;
  line-height: 1.45;
  text-transform: uppercase;
  letter-spacing: 0.045em;
}

.agenda-content h3 {
  margin: 0 0 0.5rem;
  color: #0f172a;
  font-size: 1.04rem;
  line-height: 1.38;
  font-weight: 850;
  letter-spacing: -0.018em;
}

.agenda-content p {
  margin: 0 0 0.75rem;
  color: #64748b;
  font-size: 0.91rem;
  line-height: 1.72;
}

.agenda-question {
  margin-top: 0.7rem;
  padding: 0.75rem 0.85rem;
  border-radius: 14px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  color: #334155;
  font-size: 0.86rem;
  line-height: 1.62;
}

.agenda-question strong {
  color: #0f172a;
  font-weight: 800;
}

.agenda-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.42rem;
  margin-top: 0.75rem;
}

.agenda-tags span {
  display: inline-flex;
  align-items: center;
  padding: 0.23rem 0.58rem;
  border-radius: 999px;
  background: #eff6ff;
  border: 1px solid #dbeafe;
  color: #1e40af;
  font-size: 0.72rem;
  font-weight: 700;
}

/* ---------- Vision ---------- */

.vision-box {
  max-width: 860px;
  margin: 2.45rem 0;
  padding: 1.5rem 1.6rem;
  border-radius: 22px;
  background:
    radial-gradient(circle at top right, rgba(59, 130, 246, 0.13), transparent 34%),
    linear-gradient(135deg, #ffffff 0%, #f8fafc 60%, #eef4ff 100%);
  border: 1px solid #dbe3ef;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.055);
}

.vision-box h2 {
  margin: 0 0 0.7rem;
  color: #0f172a;
  font-size: 1.22rem;
  line-height: 1.36;
  font-weight: 850;
  letter-spacing: -0.025em;
}

.vision-box p {
  margin: 0;
  color: #475569;
  font-size: 0.94rem;
  line-height: 1.78;
}

/* ---------- Highlights ---------- */

.highlight-list {
  display: grid;
  gap: 0.72rem;
}

.highlight-item {
  padding: 1rem 1.1rem;
  border-radius: 16px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.035);
}

.highlight-date {
  margin-bottom: 0.25rem;
  color: #2563eb;
  font-size: 0.74rem;
  font-weight: 850;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.highlight-item p {
  margin: 0;
  color: #475569;
  font-size: 0.91rem;
  line-height: 1.68;
}

.highlight-item strong {
  color: #0f172a;
  font-weight: 800;
}

/* ---------- Collaboration ---------- */

.home-note {
  max-width: 860px;
  margin: 2.15rem 0 1.4rem;
  padding: 1.25rem 1.38rem;
  border-radius: 20px;
  background: #f8fafc;
  border: 1px solid #dbe3ef;
  color: #334155;
  font-size: 0.95rem;
  line-height: 1.74;
}

.home-note strong {
  color: #0f172a;
  font-weight: 850;
}

/* ---------- Visitor map ---------- */

.visitor-map {
  max-width: 860px;
  margin: 1.5rem 0 0;
  padding-top: 0.8rem;
  border-top: 1px solid #e5e7eb;
  opacity: 0.88;
}

/* ---------- Responsive ---------- */

@media (max-width: 760px) {
  .home-page {
    max-width: 100%;
  }

  .home-hero {
    padding: 1.75rem 1.35rem;
    border-radius: 20px;
  }

  .home-section,
  .vision-box,
  .home-note,
  .visitor-map {
    max-width: 100%;
  }

  .agenda-card {
    grid-template-columns: 1fr;
    gap: 0.65rem;
  }

  .agenda-index {
    gap: 0.2rem;
  }

  .home-actions {
    gap: 0.55rem;
  }

  .home-btn {
    width: 100%;
  }
}
</style>

<div class="home-page">

  <section class="home-hero">
    <div class="home-hero-inner">
      <div class="home-eyebrow">Geomechanics · Computation · Artificial Intelligence</div>

      <h1>Kai-Qi Li, Ph.D.</h1>

      <p class="home-subtitle">
        NSFC Excellent Young Scientists Fund Overseas Awardee · Incoming Professor,
        School of Water Resources and Hydropower Engineering, Wuhan University
      </p>

      <p class="home-mission">
        Shaping the future of <span>geotechnics</span> through intelligence &amp; uncertainty mastery.
      </p>

      <p class="home-lead">
        My research develops mechanics-grounded, uncertainty-aware, and intelligence-enabled methods
        for understanding, modelling, and predicting complex geotechnical systems. I am particularly
        interested in ground systems where multiphysics, limited data, spatial variability, and engineering
        decision-making are deeply intertwined.
      </p>

      <div class="home-actions">
        <a href="/join-us/" class="home-btn home-btn-primary">Join the Group</a>
        <a href="/publications/" class="home-btn home-btn-secondary">Publications</a>
        <a href="/cv/" class="home-btn home-btn-secondary">Curriculum Vitae</a>
      </div>
    </div>
  </section>


  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">About</p>
      <h2>Advancing geotechnical science across mechanics, uncertainty, computation, and data</h2>
    </div>

    <div class="home-about-card">
      <p>
        I am an <span class="home-highlight">NSFC Excellent Young Scientists Fund Overseas Awardee</span>
        and will join the <span class="home-highlight">School of Water Resources and Hydropower Engineering,
        Wuhan University</span> as an Incoming Professor.
      </p>

      <p>
        I am currently a Postdoctoral Fellow in the Department of Civil and Environmental Engineering at
        <a href="https://www.polyu.edu.hk/cee">The Hong Kong Polytechnic University</a>, working with
        Prof. <a href="https://www.polyu.edu.hk/cee/people/academic-staff/prof-zhen-yu-yin">Zhen-Yu Yin</a>.
        I received my Ph.D. from Wuhan University under the supervision of
        Prof. <a href="https://scholar.google.com/citations?user=O6MLOGQAAAAJ&hl=zh-CN">Yong Liu</a> and
        Prof. <a href="https://scholar.google.com/citations?user=8mV4Gy4AAAAJ&hl=en">Dian-Qing Li</a>,
        and was a visiting Ph.D. student at the
        <a href="https://nus.edu.sg">National University of Singapore</a>, hosted by
        Prof. <a href="https://scholar.google.com/citations?user=hEHH6sYAAAAJ&hl=zh-CN&oi=sra">Fook-Hou Lee</a>.
      </p>

      <p>
        My work aims to build predictive tools that are not only accurate, but also physically interpretable,
        reliable under uncertainty, and useful for engineering judgement. I seek to connect fundamental
        geomechanics with emerging computational intelligence to address challenging problems in underground
        construction, cold-region engineering, energy geotechnics, and infrastructure resilience.
      </p>
    </div>
  </section>


  <section class="home-section">
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


  <section class="vision-box">
    <h2>Research Vision</h2>
    <p>
      My long-term vision is to help establish a new paradigm for geotechnical engineering in which
      mechanics provides the foundation, computation provides the scale, data provides the evidence,
      and uncertainty provides the language for decision-making. I believe the future of geotechnics
      will be shaped by researchers who can move fluently across physical understanding, computational
      intelligence, and real engineering impact.
    </p>
  </section>


  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">News & Highlights</p>
      <h2>Recent updates</h2>
    </div>

    <div class="highlight-list">

      <div class="highlight-item">
        <div class="highlight-date">2025</div>
        <p>
          Selected as an <strong>NSFC Excellent Young Scientists Fund Overseas Awardee</strong>.
        </p>
      </div>

      <div class="highlight-item">
        <div class="highlight-date">2025</div>
        <p>
          Will join the <strong>School of Water Resources and Hydropower Engineering,
          Wuhan University</strong> as an Incoming Professor.
        </p>
      </div>

      <div class="highlight-item">
        <div class="highlight-date">Ongoing</div>
        <p>
          Building a research group at the frontier of <strong>geomechanics, uncertainty quantification,
          computational modelling, and artificial intelligence</strong>.
        </p>
      </div>

    </div>
  </section>


  <div class="home-note">
    <strong>Collaborations and prospective students are welcome.</strong>
    I am interested in working with researchers, students, and practitioners who are excited by challenging
    problems at the intersection of geomechanics, computation, uncertainty, and artificial intelligence.
    If you are motivated by rigorous science, open collaboration, and real engineering impact, please feel
    free to get in touch.
  </div>


  <div class="visitor-map">
    <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=ffffff&cmo=1a72b0&cmn=ff5353&ct=000000'></script>
  </div>

</div>
