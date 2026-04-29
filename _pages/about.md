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
   Academic PI-style homepage
   ========================================================= */

.home-page {
  max-width: 940px;
  margin: 0 auto;
  color: #1f2937;
  font-size: 0.96rem;
  line-height: 1.68;
}

/* ---------- Hero ---------- */

.home-hero {
  max-width: 880px;
  margin: 0 0 1.6rem;
  padding: 2.45rem 2.55rem 2.35rem;
  border-radius: 24px;
  background:
    radial-gradient(circle at top right, rgba(37, 99, 235, 0.13), transparent 38%),
    linear-gradient(135deg, #ffffff 0%, #f8fafc 52%, #eef4ff 100%);
  border: 1px solid #dbe5f3;
  box-shadow: 0 18px 42px rgba(15, 23, 42, 0.075);
}

.home-hero h1 {
  margin: 0 0 0.65rem;
  color: #0f172a;
  font-size: clamp(2.25rem, 4vw, 3.05rem);
  line-height: 1.05;
  letter-spacing: -0.045em;
  font-weight: 850;
}

.home-subtitle {
  max-width: 800px;
  margin: 0 0 1.15rem;
  color: #334155;
  font-size: 0.98rem;
  line-height: 1.58;
  font-weight: 700;
}

.home-mission {
  max-width: 790px;
  margin: 0 0 1rem;
  color: #0f172a;
  font-size: clamp(1.05rem, 2vw, 1.26rem);
  line-height: 1.48;
  font-weight: 820;
  letter-spacing: -0.02em;
}

.home-mission span {
  color: #2563eb;
}

.home-lead {
  max-width: 790px;
  margin: 0;
  color: #52637a;
  font-size: 0.95rem;
  line-height: 1.75;
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
  padding: 0.58rem 1.05rem;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 760;
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

/* ---------- Metrics ---------- */

.profile-metrics {
  max-width: 880px;
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.75rem;
  margin: 0 0 1rem;
}

.metric-card {
  padding: 0.95rem 1rem;
  border-radius: 16px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.035);
}

.metric-value {
  margin-bottom: 0.22rem;
  color: #0f172a;
  font-size: 1.12rem;
  line-height: 1.25;
  font-weight: 850;
}

.metric-label {
  color: #64748b;
  font-size: 0.72rem;
  line-height: 1.45;
  font-weight: 720;
}

/* ---------- Profile indicators ---------- */

.profile-indicators {
  max-width: 880px;
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.75rem;
  margin: 0 0 2.35rem;
}

.indicator-card {
  padding: 0.9rem 0.95rem;
  border-radius: 16px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
}

.indicator-value {
  margin-bottom: 0.25rem;
  color: #0f172a;
  font-size: 0.9rem;
  line-height: 1.38;
  font-weight: 820;
}

.indicator-label {
  color: #64748b;
  font-size: 0.71rem;
  line-height: 1.45;
  font-weight: 700;
}

/* ---------- Common section ---------- */

.home-section {
  max-width: 880px;
  margin: 2.45rem 0;
}

.home-section-header {
  margin-bottom: 1.05rem;
  padding-bottom: 0.72rem;
  border-bottom: 1px solid #e5e7eb;
}

.home-section-kicker {
  margin: 0 0 0.38rem;
  color: #475569;
  font-size: 0.72rem;
  font-weight: 850;
  letter-spacing: 0.13em;
  text-transform: uppercase;
}

.home-section h2 {
  margin: 0;
  color: #0f172a;
  font-size: 1.36rem;
  line-height: 1.35;
  letter-spacing: -0.026em;
  font-weight: 850;
}

.home-section-intro {
  max-width: 820px;
  margin: 0.85rem 0 0;
  color: #5b6f8a;
  font-size: 0.93rem;
  line-height: 1.7;
}

.home-highlight {
  color: #0f172a;
  font-weight: 760;
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
  color: #52637a;
  font-size: 0.94rem;
  line-height: 1.75;
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
  padding: 1.2rem 1.3rem;
  border-radius: 20px;
  background:
    linear-gradient(135deg, rgba(15, 23, 42, 0.97), rgba(30, 41, 59, 0.97));
  box-shadow: 0 16px 34px rgba(15, 23, 42, 0.14);
}

.agenda-manifesto-title {
  margin: 0 0 0.42rem;
  color: #ffffff;
  font-size: 1.02rem;
  line-height: 1.45;
  font-weight: 820;
  letter-spacing: -0.012em;
}

.agenda-manifesto-title span {
  color: #93c5fd;
}

.agenda-manifesto p {
  margin: 0;
  color: #dbe4ef;
  font-size: 0.9rem;
  line-height: 1.68;
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
  gap: 0.36rem;
}

.agenda-number {
  color: #2563eb;
  font-size: 0.78rem;
  font-weight: 850;
  letter-spacing: 0.04em;
}

.agenda-theme {
  color: #64748b;
  font-size: 0.78rem;
  font-weight: 760;
  line-height: 1.45;
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
  margin: 0 0 0.72rem;
  color: #5b6f8a;
  font-size: 0.91rem;
  line-height: 1.7;
}

.agenda-question {
  margin-top: 0.68rem;
  padding: 0.72rem 0.82rem;
  border-radius: 14px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  color: #334155;
  font-size: 0.86rem;
  line-height: 1.58;
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
  max-width: 880px;
  margin: 2.35rem 0;
  padding: 1.35rem 1.5rem;
  border-radius: 22px;
  background:
    radial-gradient(circle at top right, rgba(59, 130, 246, 0.12), transparent 34%),
    linear-gradient(135deg, #ffffff 0%, #f8fafc 60%, #eef4ff 100%);
  border: 1px solid #dbe3ef;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.055);
}

.vision-box h2 {
  margin: 0 0 0.65rem;
  color: #0f172a;
  font-size: 1.18rem;
  line-height: 1.36;
  font-weight: 850;
  letter-spacing: -0.025em;
}

.vision-box p {
  margin: 0;
  color: #52637a;
  font-size: 0.93rem;
  line-height: 1.7;
}

/* ---------- Selected News ---------- */

.news-board {
  display: grid;
  gap: 1rem;
}

.news-category {
  padding: 1.18rem 1.25rem;
  border-radius: 20px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 10px 26px rgba(15, 23, 42, 0.04);
}

.news-category-header {
  display: flex;
  align-items: center;
  gap: 0.65rem;
  margin-bottom: 0.85rem;
}

.news-dot {
  width: 9px;
  height: 9px;
  border-radius: 999px;
  flex: 0 0 auto;
}

.news-dot-awards {
  background: #dc2626;
}

.news-dot-research {
  background: #7c3aed;
}

.news-dot-funding {
  background: #2563eb;
}

.news-dot-service {
  background: #16a34a;
}

.news-category h3 {
  margin: 0;
  color: #0f172a;
  font-size: 1rem;
  line-height: 1.35;
  font-weight: 850;
  letter-spacing: -0.015em;
}

.news-list {
  display: grid;
  gap: 0.62rem;
}

.news-item {
  display: grid;
  grid-template-columns: 74px minmax(0, 1fr);
  gap: 0.72rem;
  padding-top: 0.62rem;
  border-top: 1px solid #eef2f7;
}

.news-item:first-child {
  padding-top: 0;
  border-top: none;
}

.news-date {
  color: #2563eb;
  font-size: 0.75rem;
  line-height: 1.5;
  font-weight: 850;
  letter-spacing: 0.02em;
}

.news-text {
  color: #52637a;
  font-size: 0.9rem;
  line-height: 1.62;
}

.news-text strong {
  color: #0f172a;
  font-weight: 800;
}

.news-text em {
  color: #334155;
}

.news-text a {
  color: #1d4ed8;
  text-decoration: none;
  border-bottom: 1px solid rgba(37, 99, 235, 0.25);
}

.news-text a:hover {
  color: #1e40af;
  border-bottom-color: rgba(30, 64, 175, 0.55);
}

/* ---------- Collaboration ---------- */

.home-note {
  max-width: 880px;
  margin: 2rem 0 1.2rem;
  padding: 1.08rem 1.22rem;
  border-radius: 18px;
  background: #f8fafc;
  border: 1px solid #dbe3ef;
  color: #334155;
  font-size: 0.92rem;
  line-height: 1.65;
}

.home-note strong {
  color: #0f172a;
  font-weight: 850;
}

.home-note a {
  color: #1d4ed8;
  font-weight: 760;
  text-decoration: none;
  border-bottom: 1px solid rgba(37, 99, 235, 0.25);
}

/* ---------- Visitor map ---------- */

.visitor-map {
  max-width: 880px;
  margin: 1.35rem 0 0;
  padding-top: 1rem;
  border-top: 1px solid #e5e7eb;
  min-height: 120px;
}

.visitor-map-title {
  margin: 0 0 0.55rem;
  color: #64748b;
  font-size: 0.72rem;
  font-weight: 800;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

.visitor-map-inner {
  max-width: 320px;
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

  .profile-metrics,
  .profile-indicators {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .agenda-card {
    grid-template-columns: 1fr;
    gap: 0.65rem;
  }

  .news-item {
    grid-template-columns: 1fr;
    gap: 0.18rem;
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
    <h1>Kai-Qi Li, Ph.D.</h1>

    <p class="home-subtitle">
      NSFC Excellent Young Scientists Fund Overseas Awardee · Incoming Professor,
      School of Water Resources and Hydropower Engineering, Wuhan University
    </p>

    <p class="home-mission">
      Shaping the future of <span>geotechnics</span> through intelligence and uncertainty mastery.
    </p>

    <p class="home-lead">
      My research develops mechanics-grounded, data-enabled, and uncertainty-aware methods
      for understanding, modelling, and managing complex geotechnical systems.
    </p>

    <div class="home-actions">
      <a href="/join-us/" class="home-btn home-btn-primary">Join the Group</a>
      <a href="/publications/" class="home-btn home-btn-secondary">Publications</a>
      <a href="/cv/" class="home-btn home-btn-secondary">Curriculum Vitae</a>
    </div>
  </section>


  <section class="profile-metrics" aria-label="Research metrics">
    <div class="metric-card">
      <div class="metric-value">40+</div>
      <div class="metric-label">Journal papers</div>
    </div>

    <div class="metric-card">
      <div class="metric-value">1,500+</div>
      <div class="metric-label">Citations</div>
    </div>

    <div class="metric-card">
      <div class="metric-value">23</div>
      <div class="metric-label">h-index</div>
    </div>

    <div class="metric-card">
      <div class="metric-value">5</div>
      <div class="metric-label">ESI Highly Cited Papers</div>
    </div>
  </section>


  <section class="profile-indicators" aria-label="Profile highlights">
    <div class="indicator-card">
      <div class="indicator-value">NSFC EYSF Overseas</div>
      <div class="indicator-label">National-level early-career talent award</div>
    </div>

    <div class="indicator-card">
      <div class="indicator-value">Wuhan University</div>
      <div class="indicator-label">Incoming Professor</div>
    </div>

    <div class="indicator-card">
      <div class="indicator-value">PolyU · WHU · NUS</div>
      <div class="indicator-label">International research training</div>
    </div>

    <div class="indicator-card">
      <div class="indicator-value">Mechanics · Data · UQ · AI</div>
      <div class="indicator-label">Core methodological focus</div>
    </div>
  </section>


  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">About</p>
      <h2>Towards intelligent geomechanics: bridging physics, data, and uncertainty</h2>
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
        I received my Ph.D. in Geotechnical Engineering from Wuhan University under the supervision of
        Prof. <a href="https://scholar.google.com/citations?user=O6MLOGQAAAAJ&hl=zh-CN">Yong Liu</a> and
        Prof. <a href="https://scholar.google.com/citations?user=8mV4Gy4AAAAJ&hl=en">Dian-Qing Li</a>,
        and was a visiting Ph.D. student at the
        <a href="https://nus.edu.sg">National University of Singapore</a>, hosted by
        Prof. <a href="https://scholar.google.com/citations?user=hEHH6sYAAAAJ&hl=zh-CN&oi=sra">Fook-Hou Lee</a>.
      </p>

      <p>
        My work lies at the interface of geotechnical engineering, mechanics, computational modelling,
        stochastic analysis, and artificial intelligence, with applications in frozen ground,
        artificial ground freezing, underground construction, hydrate-bearing sediments, and resilient infrastructure.
      </p>
    </div>
  </section>


  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">Research Agenda</p>
      <h2>Intelligent geotechnics for uncertain, evolving, and high-consequence ground systems</h2>
      <p class="home-section-intro">
        My group aims to develop the next generation of geotechnical methods that integrate
        physical modelling, computational intelligence, uncertainty quantification, and engineering judgement.
      </p>
    </div>

    <div class="agenda-manifesto">
      <div class="agenda-manifesto-title">
        A research program for <span>mechanics-informed intelligence under uncertainty</span>
      </div>
      <p>
        The ground is heterogeneous, history-dependent, multiphysical, and only partially observable.
        Our goal is to build models that learn from data, respect mechanics, quantify uncertainty,
        and support safer infrastructure decisions.
      </p>
    </div>

    <div class="agenda-grid">

      <div class="agenda-card">
        <div class="agenda-index">
          <div class="agenda-number">Agenda 01</div>
          <div class="agenda-theme">Complex Ground Systems</div>
        </div>

        <div class="agenda-content">
          <h3>Mechanics of ground in extreme and evolving environments</h3>
          <p>
            We study geomaterials and ground systems governed by coupled thermal, hydraulic,
            mechanical, chemical, and phase-change processes, including frozen soils, artificial
            ground freezing, and hydrate-bearing sediments.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can we predict ground behaviour when temperature, water, stress, microstructure,
            and environmental loading evolve together?
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
          <div class="agenda-theme">Scientific Intelligence</div>
        </div>

        <div class="agenda-content">
          <h3>AI models that understand mechanics, not merely fit data</h3>
          <p>
            We develop physics-informed and mechanics-guided methods that combine constitutive
            modelling, numerical simulation, machine learning, neural operators, and graph-based learning.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can artificial intelligence become a scientific engine for geomechanics while
            remaining interpretable, transferable, and reliable?
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
          <div class="agenda-theme">Uncertainty Mastery</div>
        </div>

        <div class="agenda-content">
          <h3>From uncertain data to reliable engineering decisions</h3>
          <p>
            We work on uncertainty quantification, stochastic analysis, reliability assessment,
            Bayesian updating, and risk-informed design for geotechnical systems with limited and evolving data.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can we quantify what we do not know, update predictions as evidence accumulates,
            and make safer decisions in uncertain ground?
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
          <div class="agenda-theme">Engineering Translation</div>
        </div>

        <div class="agenda-content">
          <h3>Computational tools for safer and more resilient infrastructure</h3>
          <p>
            We translate advanced models into practical workflows for underground construction,
            cold-region infrastructure, coastal and marine geotechnics, and large-scale civil infrastructure.
          </p>

          <div class="agenda-question">
            <strong>Core question:</strong>
            How can frontier geomechanics and AI improve safety, resilience, sustainability,
            and confidence in engineering practice?
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
      I envision a new generation of geotechnical engineering in which physical insight,
      computational intelligence, and uncertainty reasoning are developed as a unified framework.
      The goal is not only to predict ground behaviour more accurately, but also to explain predictions,
      evaluate confidence, and support decisions that matter for infrastructure safety and resilience.
    </p>
  </section>


  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">Selected News</p>
      <h2>Recent highlights in awards, research, funding, and academic service</h2>
    </div>

    <div class="news-board">

      <div class="news-category">
        <div class="news-category-header">
          <span class="news-dot news-dot-awards"></span>
          <h3>Awards & Honors</h3>
        </div>

        <div class="news-list">
          <div class="news-item">
            <div class="news-date">2026</div>
            <div class="news-text">
              Awarded the <strong>NSFC Excellent Young Scientists Fund Overseas</strong> and will join
              <strong>Wuhan University</strong> as an Incoming Professor.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2025</div>
            <div class="news-text">
              Shortlisted for the <strong>JC STEM Early Career Research Fellowship</strong>.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2024</div>
            <div class="news-text">
              Awarded the <strong>PolyU Distinguished Postdoctoral Fellowship</strong>.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2024</div>
            <div class="news-text">
              Received the <strong>2023 Hubei Province Science & Technology Progress Award</strong>
              for the project <em>Risk Prevention and Control of Artificial Ground Freezing Technique
              in Water-Rich Stratum</em>
              (<a href="https://www.hubei.gov.cn/zfwj/ezf/202407/t20240726_5280385.shtml">Link</a>).
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2023</div>
            <div class="news-text">
              Received the <strong>2023 Academic Innovation Award</strong> from Wuhan University.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2021</div>
            <div class="news-text">
              Received the <strong>Excellence in Teaching Award</strong> from Wuhan University.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2020</div>
            <div class="news-text">
              Named one of <strong>Wuhan University’s Top 10 Academic Stars</strong>
              (<a href="https://service.whu.edu.cn/info/1005/2179.htm">Official announcement</a>;
              <a href="https://risk.whu.edu.cn/info/1034/1301.htm">More</a>).
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2016</div>
            <div class="news-text">
              Awarded the <strong>Top 10 Future Star Undergraduate</strong> by the China Water Resources
              Education Association
              (<a href="https://sljzw.hhu.edu.cn/2019/0415/c11821a189595/page.htm">Link</a>).
            </div>
          </div>
        </div>
      </div>


      <div class="news-category">
        <div class="news-category-header">
          <span class="news-dot news-dot-research"></span>
          <h3>Research & Publications</h3>
        </div>

        <div class="news-list">
          <div class="news-item">
            <div class="news-date">2026</div>
            <div class="news-text">
              Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time
              in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2026</div>
            <div class="news-text">
              Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network
              for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2025</div>
            <div class="news-text">
              Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em>
              in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em>
              (<a href="https://doi.org/10.1061/JGGEFK.GTENG-13437">DOI</a>).
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2025</div>
            <div class="news-text">
              Published <em>Physics-informed neural networks for solving steady-state temperature field in
              artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em>
              (<a href="https://doi.org/10.1139/cgj-2024-0650">DOI</a>).
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2025</div>
            <div class="news-text">
              Published <em>State of the art of mechanical behaviors of frozen soils through experimental
              investigation</em> in <em>Cold Regions Science and Technology</em>
              (<a href="https://doi.org/10.1016/j.coldregions.2025.104497">DOI</a>).
            </div>
          </div>
        </div>
      </div>


      <div class="news-category">
        <div class="news-category-header">
          <span class="news-dot news-dot-funding"></span>
          <h3>Funding</h3>
        </div>

        <div class="news-list">
          <div class="news-item">
            <div class="news-date">2025–2026</div>
            <div class="news-text">
              Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical
              coupling in hydrate-bearing sediments using physics-informed neural networks.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2025–2029</div>
            <div class="news-text">
              Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project
              on digital twins for coastal resilience under extreme storm surges in Hong Kong.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2024–2026</div>
            <div class="news-text">
              Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed
              multi-fidelity neural networks for intelligent rectification of shield machine attitude
              in layered soils.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2022</div>
            <div class="news-text">
              Received the <strong>Centrally Funded Postdoctoral Fellowship</strong>
              (<strong>HK$763,555</strong>) for a project on thermo-hydro-mechanical modelling
              for artificial ground freezing.
            </div>
          </div>
        </div>
      </div>


      <div class="news-category">
        <div class="news-category-header">
          <span class="news-dot news-dot-service"></span>
          <h3>Academic Service</h3>
        </div>

        <div class="news-list">
          <div class="news-item">
            <div class="news-date">2025</div>
            <div class="news-text">
              Serving as Co-chair of Mini-Symposium 9:
              <em>Multiphysics Modeling of Geo-engineering and Geohazards</em> at
              <strong>IACMAG 2025</strong>, Hong Kong.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2024</div>
            <div class="news-text">
              Joined the <strong>Early-career Editorial Panel</strong> for the
              <em>European Journal of Soil Science</em>
              (<a href="https://bsssjournals.onlinelibrary.wiley.com/hub/journal/13652389/editorialboard.html">Link</a>).
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2024</div>
            <div class="news-text">
              Served as Session Chair at the <strong>12th National Conference on Engineering Geology</strong>,
              Shenzhen.
            </div>
          </div>

          <div class="news-item">
            <div class="news-date">2023</div>
            <div class="news-text">
              Served as Secretary of the <strong>International Symposium on Innovations in Geotechnical
              Engineering towards Sustainability</strong> — IGES 2023.
            </div>
          </div>
        </div>
      </div>

    </div>
  </section>


  <div class="home-note">
    <strong>Collaborations and prospective students are welcome.</strong>
    I am interested in working with motivated students, researchers, and practitioners on problems
    at the interface of geomechanics, computation, uncertainty, and artificial intelligence.
    Please see <a href="/join-us/">Join Us</a> for opportunities.
  </div>


  <div class="visitor-map">
    <div class="visitor-map-title">Visitors</div>
    <div class="visitor-map-inner">
      <script type="text/javascript" id="clustrmaps"
        src="https://cdn.clustrmaps.com/map_v2.js?cl=80afe5&w=270&t=tt&d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=ffffff&cmo=1a72b0&cmn=ff5353&ct=000000">
      </script>
    </div>
  </div>

</div>
