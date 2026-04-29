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
   Refined faculty-style layout
   ========================================================= */

:root {
  --kq-navy: #0f172a;
  --kq-blue: #2563eb;
  --kq-blue-dark: #1d4ed8;
  --kq-sky: #dbeafe;
  --kq-text: #334155;
  --kq-muted: #64748b;
  --kq-light: #f8fafc;
  --kq-soft: #f1f5f9;
  --kq-border: #dbe3ef;
  --kq-card: #ffffff;
  --kq-gold: #b45309;
}

/* Global adjustment inside the page */
.page__content {
  font-size: 0.96rem;
  line-height: 1.65;
}

.page__content p,
.page__content li {
  font-size: 0.96rem;
}

.kq-home {
  max-width: 1040px;
  margin: 0 auto;
  color: var(--kq-text);
}

/* ================= Hero ================= */

.kq-hero {
  position: relative;
  margin: 0 0 1.8rem;
  padding: 2.4rem 2.7rem;
  border: 1px solid var(--kq-border);
  border-radius: 24px;
  background:
    radial-gradient(circle at 92% 10%, rgba(37, 99, 235, 0.13), transparent 32%),
    linear-gradient(135deg, #ffffff 0%, #f8fbff 55%, #eef5ff 100%);
  box-shadow: 0 16px 38px rgba(15, 23, 42, 0.075);
}

.kq-hero h1 {
  margin: 0 0 0.55rem;
  color: var(--kq-navy);
  font-size: clamp(2.15rem, 4.2vw, 3.25rem);
  line-height: 1.02;
  letter-spacing: -0.045em;
  font-weight: 850;
}

.kq-hero-position {
  margin: 0 0 1.15rem;
  max-width: 850px;
  color: #475569;
  font-size: 1.02rem;
  line-height: 1.55;
  font-weight: 700;
}

.kq-hero-tagline {
  margin: 0 0 1rem;
  max-width: 850px;
  color: var(--kq-navy);
  font-size: clamp(1.08rem, 1.8vw, 1.32rem);
  line-height: 1.45;
  font-weight: 800;
}

.kq-hero-tagline span {
  color: var(--kq-blue);
}

.kq-hero-desc {
  margin: 0 0 1.6rem;
  max-width: 860px;
  color: #53657f;
  font-size: 1rem;
  line-height: 1.72;
}

.kq-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}

.kq-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.68rem 1.08rem;
  border-radius: 999px;
  font-size: 0.9rem;
  font-weight: 800;
  text-decoration: none !important;
  transition: all 0.18s ease;
  white-space: nowrap;
}

.kq-btn-primary {
  color: #ffffff !important;
  background: var(--kq-blue);
  box-shadow: 0 10px 22px rgba(37, 99, 235, 0.22);
}

.kq-btn-primary:hover {
  transform: translateY(-1px);
  background: var(--kq-blue-dark);
}

.kq-btn-secondary {
  color: #334155 !important;
  background: rgba(255, 255, 255, 0.76);
  border: 1px solid #cbd5e1;
}

.kq-btn-secondary:hover {
  transform: translateY(-1px);
  color: var(--kq-blue) !important;
  border-color: var(--kq-blue);
}

/* ================= Metrics ================= */

.kq-metrics {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0.9rem;
  margin: 0 0 2.4rem;
}

.kq-metric {
  padding: 1rem 1.15rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.045);
}

.kq-metric-number {
  display: block;
  margin-bottom: 0.25rem;
  color: var(--kq-navy);
  font-size: 1.42rem;
  line-height: 1;
  font-weight: 850;
  letter-spacing: -0.025em;
}

.kq-metric-label {
  display: block;
  color: var(--kq-muted);
  font-size: 0.82rem;
  line-height: 1.35;
  font-weight: 750;
}

/* ================= Section basics ================= */

.kq-section {
  margin: 2.8rem 0;
}

.kq-section-header {
  margin-bottom: 1.15rem;
}

.kq-section-kicker {
  margin: 0 0 0.38rem;
  color: var(--kq-blue);
  font-size: 0.72rem;
  font-weight: 850;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

.kq-section-title {
  margin: 0;
  color: var(--kq-navy);
  font-size: clamp(1.45rem, 2.5vw, 2rem);
  line-height: 1.22;
  letter-spacing: -0.03em;
  font-weight: 850;
}

.kq-section-subtitle {
  margin: 0.65rem 0 0;
  max-width: 850px;
  color: var(--kq-muted);
  font-size: 0.98rem;
  line-height: 1.68;
}

/* ================= About ================= */

.kq-about-card {
  padding: 1.8rem 2rem;
  border: 1px solid var(--kq-border);
  border-radius: 22px;
  background: #ffffff;
  box-shadow: 0 13px 32px rgba(15, 23, 42, 0.052);
}

.kq-about-card p {
  margin: 0 0 1.05rem;
  color: #4f6178;
  font-size: 0.97rem;
  line-height: 1.78;
}

.kq-about-card p:last-child {
  margin-bottom: 0;
}

.kq-about-card strong {
  color: var(--kq-navy);
}

.kq-about-card a {
  color: var(--kq-blue);
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
}

/* ================= Research Agenda ================= */

.kq-agenda-shell {
  padding: 1.6rem;
  border: 1px solid var(--kq-border);
  border-radius: 24px;
  background:
    linear-gradient(180deg, #f8fbff 0%, #ffffff 55%);
  box-shadow: 0 14px 34px rgba(15, 23, 42, 0.055);
}

.kq-agenda-lead {
  display: grid;
  grid-template-columns: 1.05fr 1.55fr;
  gap: 1.5rem;
  align-items: stretch;
  margin-bottom: 1.2rem;
}

.kq-agenda-statement {
  padding: 1.45rem 1.55rem;
  border-radius: 20px;
  color: #e5edf8;
  background:
    radial-gradient(circle at 88% 14%, rgba(147, 197, 253, 0.26), transparent 35%),
    linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
}

.kq-agenda-statement h3 {
  margin: 0 0 0.7rem;
  color: #ffffff;
  font-size: 1.18rem;
  line-height: 1.35;
  font-weight: 850;
  letter-spacing: -0.02em;
}

.kq-agenda-statement h3 span {
  color: #93c5fd;
}

.kq-agenda-statement p {
  margin: 0;
  color: #d7e2f0;
  font-size: 0.92rem;
  line-height: 1.68;
}

.kq-agenda-principles {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0.75rem;
}

.kq-principle {
  padding: 1.1rem 1rem;
  border: 1px solid #dbeafe;
  border-radius: 18px;
  background: #ffffff;
}

.kq-principle-label {
  margin-bottom: 0.35rem;
  color: var(--kq-blue);
  font-size: 0.74rem;
  font-weight: 850;
  letter-spacing: 0.11em;
  text-transform: uppercase;
}

.kq-principle-title {
  margin: 0 0 0.45rem;
  color: var(--kq-navy);
  font-size: 0.98rem;
  line-height: 1.35;
  font-weight: 850;
}

.kq-principle p {
  margin: 0;
  color: #5b6b80;
  font-size: 0.86rem;
  line-height: 1.58;
}

.kq-agenda-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  margin-top: 1.1rem;
}

.kq-agenda-card {
  position: relative;
  overflow: hidden;
  padding: 1.35rem 1.25rem 1.3rem;
  border: 1px solid var(--kq-border);
  border-radius: 20px;
  background: #ffffff;
  box-shadow: 0 10px 24px rgba(15, 23, 42, 0.04);
}

.kq-agenda-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  width: 5px;
  height: 100%;
  background: linear-gradient(180deg, var(--kq-blue), #93c5fd);
}

.kq-agenda-num {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  margin-bottom: 0.85rem;
  width: 2.15rem;
  height: 2.15rem;
  border-radius: 999px;
  color: #1d4ed8;
  background: #dbeafe;
  font-size: 0.78rem;
  font-weight: 850;
}

.kq-agenda-card h4 {
  margin: 0 0 0.55rem;
  color: var(--kq-navy);
  font-size: 1.02rem;
  line-height: 1.35;
  font-weight: 850;
  letter-spacing: -0.015em;
}

.kq-agenda-card p {
  margin: 0 0 0.85rem;
  color: #53657f;
  font-size: 0.89rem;
  line-height: 1.62;
}

.kq-agenda-keywords {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  margin-top: 0.85rem;
}

.kq-tag {
  display: inline-flex;
  padding: 0.22rem 0.52rem;
  border-radius: 999px;
  color: #1e3a8a;
  background: #eff6ff;
  font-size: 0.73rem;
  line-height: 1.35;
  font-weight: 750;
}

.kq-agenda-question {
  margin-top: 0.85rem;
  padding: 0.75rem 0.8rem;
  border-radius: 14px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  color: #475569;
  font-size: 0.84rem;
  line-height: 1.55;
}

.kq-agenda-question strong {
  color: var(--kq-navy);
}

/* ================= Selected News ================= */

.kq-news {
  padding: 1.55rem 1.7rem;
  border: 1px solid var(--kq-border);
  border-radius: 22px;
  background: #ffffff;
  box-shadow: 0 13px 32px rgba(15, 23, 42, 0.052);
}

.kq-news-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.kq-news-item {
  display: grid;
  grid-template-columns: 105px 1fr;
  gap: 1rem;
  padding: 1.05rem 0;
  border-bottom: 1px solid #e5eaf2;
}

.kq-news-item:first-child {
  padding-top: 0;
}

.kq-news-item:last-child {
  padding-bottom: 0;
  border-bottom: none;
}

.kq-news-date {
  color: var(--kq-blue);
  font-size: 0.84rem;
  font-weight: 850;
  white-space: nowrap;
}

.kq-news-title {
  margin: 0 0 0.25rem;
  color: var(--kq-navy);
  font-size: 0.98rem;
  line-height: 1.42;
  font-weight: 850;
}

.kq-news-desc {
  margin: 0;
  color: #53657f;
  font-size: 0.9rem;
  line-height: 1.62;
}

.kq-news-desc strong {
  color: var(--kq-navy);
}

/* ================= Join ================= */

.kq-join {
  padding: 1.85rem 2rem;
  border-radius: 22px;
  border: 1px solid var(--kq-border);
  background:
    radial-gradient(circle at 86% 16%, rgba(37, 99, 235, 0.12), transparent 36%),
    linear-gradient(135deg, #f8fbff 0%, #ffffff 72%);
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.045);
}

.kq-join h2 {
  margin: 0 0 0.55rem;
  color: var(--kq-navy);
  font-size: 1.55rem;
  line-height: 1.25;
  letter-spacing: -0.025em;
  font-weight: 850;
}

.kq-join p {
  margin: 0 0 1.1rem;
  max-width: 820px;
  color: #53657f;
  font-size: 0.96rem;
  line-height: 1.7;
}

/* ================= Visitor ================= */

.kq-visitor {
  margin-top: 2.3rem;
  padding-top: 1.2rem;
  border-top: 1px solid var(--kq-border);
}

.kq-visitor-title {
  margin-bottom: 0.65rem;
  color: var(--kq-muted);
  font-size: 0.72rem;
  font-weight: 850;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

/* ================= Responsive ================= */

@media (max-width: 980px) {
  .kq-hero {
    padding: 2.1rem 2rem;
  }

  .kq-metrics {
    grid-template-columns: repeat(2, 1fr);
  }

  .kq-agenda-lead {
    grid-template-columns: 1fr;
  }

  .kq-agenda-grid {
    grid-template-columns: 1fr;
  }

  .kq-agenda-principles {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 560px) {
  .page__content {
    font-size: 0.93rem;
  }

  .kq-hero {
    padding: 1.7rem 1.25rem;
    border-radius: 20px;
  }

  .kq-actions {
    flex-direction: column;
  }

  .kq-btn {
    width: 100%;
  }

  .kq-metrics {
    grid-template-columns: 1fr;
  }

  .kq-about-card,
  .kq-agenda-shell,
  .kq-news,
  .kq-join {
    padding: 1.25rem;
  }

  .kq-news-item {
    grid-template-columns: 1fr;
    gap: 0.25rem;
  }
}
</style>


<div class="kq-home">

  <!-- ================= Hero ================= -->
  <section class="kq-hero">
    <h1>Kai-Qi Li, Ph.D.</h1>

    <p class="kq-hero-position">
      Incoming Professor, School of Water Resources and Hydropower Engineering, Wuhan University
    </p>

    <p class="kq-hero-tagline">
      Shaping the future of <span>geotechnics</span> through mechanics, data, and uncertainty quantification.
    </p>

    <p class="kq-hero-desc">
      My research develops mechanics-grounded, data-enabled, and uncertainty-aware methods for
      understanding, modelling, and managing complex geotechnical systems.
    </p>

    <div class="kq-actions">
      <a class="kq-btn kq-btn-primary" href="/join-us/">Join the Group</a>
      <a class="kq-btn kq-btn-secondary" href="/publications/">Publications</a>
      <a class="kq-btn kq-btn-secondary" href="/cv/">Curriculum Vitae</a>
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
      <span class="kq-metric-number">23</span>
      <span class="kq-metric-label">h-index</span>
    </div>

    <div class="kq-metric">
      <span class="kq-metric-number">5</span>
      <span class="kq-metric-label">ESI Highly Cited Papers</span>
    </div>
  </section>


  <!-- ================= About ================= -->
  <section class="kq-section">
    <div class="kq-section-header">
      <h2 class="kq-section-title">About Me</h2>
    </div>

    <div class="kq-about-card">
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
        Prof. Yong Liu and Prof. Dian-Qing Li, and was a visiting Ph.D. student at the
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
  <section class="kq-section">
    <div class="kq-section-header">
      <p class="kq-section-kicker">Research Agenda</p>
      <h2 class="kq-section-title">
        Building intelligent, reliable, and explainable geotechnical systems
      </h2>
      <p class="kq-section-subtitle">
        My group works at the intersection of geomechanics, computation, uncertainty quantification,
        and artificial intelligence, with the goal of transforming how complex ground systems are
        understood, predicted, and managed.
      </p>
    </div>

    <div class="kq-agenda-shell">

      <div class="kq-agenda-lead">
        <div class="kq-agenda-statement">
          <h3>
            A research program for <span>next-generation geotechnics</span>
          </h3>
          <p>
            Future geotechnical engineering must go beyond deterministic prediction.
            We develop models that combine physical understanding, sparse observations,
            data-driven learning, and uncertainty-aware decision-making.
          </p>
        </div>

        <div class="kq-agenda-principles">
          <div class="kq-principle">
            <div class="kq-principle-label">Mechanics</div>
            <h4 class="kq-principle-title">Physics as foundation</h4>
            <p>
              Constitutive behaviour, coupled processes, and engineering mechanisms remain at the core.
            </p>
          </div>

          <div class="kq-principle">
            <div class="kq-principle-label">Intelligence</div>
            <h4 class="kq-principle-title">Data as amplifier</h4>
            <p>
              Machine learning is used to enhance, not replace, scientific and engineering understanding.
            </p>
          </div>

          <div class="kq-principle">
            <div class="kq-principle-label">Reliability</div>
            <h4 class="kq-principle-title">Uncertainty as design input</h4>
            <p>
              Variability, limited data, and model bias are explicitly quantified for robust decisions.
            </p>
          </div>
        </div>
      </div>

      <div class="kq-agenda-grid">

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">01</div>
          <h4>Multiphysics geomechanics of complex ground</h4>
          <p>
            We study geomaterials and ground systems governed by coupled thermal, hydraulic,
            mechanical, chemical, and phase-change processes.
          </p>

          <div class="kq-agenda-keywords">
            <span class="kq-tag">Frozen soil</span>
            <span class="kq-tag">AGF</span>
            <span class="kq-tag">Hydrate sediments</span>
            <span class="kq-tag">THMC coupling</span>
          </div>

          <div class="kq-agenda-question">
            <strong>Question:</strong> How can we predict ground behaviour when temperature,
            water, stress, phase change, and microstructure evolve together?
          </div>
        </article>

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">02</div>
          <h4>Mechanics-informed artificial intelligence</h4>
          <p>
            We develop data-enabled models that embed physical constraints, constitutive
            knowledge, and engineering judgement into learning-based frameworks.
          </p>

          <div class="kq-agenda-keywords">
            <span class="kq-tag">Physics-informed ML</span>
            <span class="kq-tag">Surrogate modelling</span>
            <span class="kq-tag">Inverse analysis</span>
            <span class="kq-tag">Digital twins</span>
          </div>

          <div class="kq-agenda-question">
            <strong>Question:</strong> How can AI become interpretable, physically consistent,
            and trustworthy for geotechnical engineering practice?
          </div>
        </article>

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">03</div>
          <h4>Uncertainty, reliability, and risk-informed decisions</h4>
          <p>
            We quantify uncertainty from spatial variability, limited observations, model bias,
            and changing environments, and translate it into engineering decisions.
          </p>

          <div class="kq-agenda-keywords">
            <span class="kq-tag">Random fields</span>
            <span class="kq-tag">Bayesian updating</span>
            <span class="kq-tag">Reliability</span>
            <span class="kq-tag">Risk</span>
          </div>

          <div class="kq-agenda-question">
            <strong>Question:</strong> How can geotechnical design become robust, adaptive,
            and transparent under incomplete information?
          </div>
        </article>

      </div>
    </div>
  </section>


  <!-- ================= Selected News ================= -->
  <section class="kq-section">
    <div class="kq-section-header">
      <p class="kq-section-kicker">Updates</p>
      <h2 class="kq-section-title">Selected News</h2>
    </div>

    <div class="kq-news">
      <ul class="kq-news-list">

        <li class="kq-news-item">
          <div class="kq-news-date">2025</div>
          <div>
            <h3 class="kq-news-title">Awarded the NSFC Excellent Young Scientists Fund Overseas</h3>
            <p class="kq-news-desc">
              I was selected for the <strong>National Natural Science Foundation of China Excellent Young Scientists Fund Overseas</strong>.
            </p>
          </div>
        </li>

        <li class="kq-news-item">
          <div class="kq-news-date">2025</div>
          <div>
            <h3 class="kq-news-title">Joining Wuhan University as an Incoming Professor</h3>
            <p class="kq-news-desc">
              I will join the <strong>School of Water Resources and Hydropower Engineering, Wuhan University</strong>,
              where I am building a new research group in geomechanics, computation, uncertainty quantification, and AI.
            </p>
          </div>
        </li>

        <li class="kq-news-item">
          <div class="kq-news-date">Recent</div>
          <div>
            <h3 class="kq-news-title">Research profile updated</h3>
            <p class="kq-news-desc">
              My publication record currently includes <strong>40+ journal papers</strong>,
              <strong>1,500+ citations</strong>, an <strong>h-index of 23</strong>, and
              <strong>5 ESI Highly Cited Papers</strong>.
            </p>
          </div>
        </li>

        <li class="kq-news-item">
          <div class="kq-news-date">Recent</div>
          <div>
            <h3 class="kq-news-title">Research directions expanded toward intelligent geotechnics</h3>
            <p class="kq-news-desc">
              Ongoing work focuses on mechanics-informed AI, stochastic geomechanics, frozen ground and
              artificial ground freezing, underground construction, hydrate-bearing sediments, and
              uncertainty-aware infrastructure assessment.
            </p>
          </div>
        </li>

        <li class="kq-news-item">
          <div class="kq-news-date">Openings</div>
          <div>
            <h3 class="kq-news-title">Students and collaborators are welcome</h3>
            <p class="kq-news-desc">
              I welcome motivated students and collaborators interested in geotechnical engineering,
              computational mechanics, uncertainty quantification, and artificial intelligence.
            </p>
          </div>
        </li>

      </ul>
    </div>
  </section>


  <!-- ================= Join Us ================= -->
  <section class="kq-section">
    <div class="kq-join">
      <h2>Join Us</h2>
      <p>
        I am looking for motivated students and collaborators interested in geotechnical engineering,
        mechanics, computational modelling, artificial intelligence, and uncertainty quantification.
      </p>
      <a class="kq-btn kq-btn-primary" href="/join-us/">Opportunities</a>
    </div>
  </section>


  <!-- ================= Visitor Map ================= -->
  <section class="kq-visitor">
    <div class="kq-visitor-title">Visitors</div>
    <script type="text/javascript" id="clustrmaps"
      src="https://cdn.clustrmaps.com/map_v2.js?cl=80afe5&w=270&t=tt&d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=ffffff&cmo=1a72b0&cmn=ff5353&ct=000000">
    </script>
  </section>

</div>
