---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
/* ===============================
   Homepage redesign for Kai-Qi Li
   =============================== */

:root {
  --kq-navy: #0f172a;
  --kq-blue: #2563eb;
  --kq-blue-light: #dbeafe;
  --kq-text: #334155;
  --kq-muted: #64748b;
  --kq-border: #dbe3ef;
  --kq-bg: #f8fafc;
  --kq-card: #ffffff;
  --kq-soft: #f1f5f9;
}

.page__content {
  font-size: 1rem;
}

.kq-home {
  max-width: 1160px;
  margin: 0 auto;
}

/* ---------- Hero ---------- */

.kq-hero {
  position: relative;
  margin: 0 0 2.2rem;
  padding: 3.2rem 3.6rem;
  border: 1px solid var(--kq-border);
  border-radius: 28px;
  background:
    radial-gradient(circle at 92% 5%, rgba(37, 99, 235, 0.16), transparent 34%),
    linear-gradient(135deg, #ffffff 0%, #f8fbff 52%, #eef5ff 100%);
  box-shadow: 0 20px 45px rgba(15, 23, 42, 0.08);
}

.kq-hero h1 {
  margin: 0 0 0.7rem;
  font-size: clamp(2.6rem, 6vw, 4.6rem);
  line-height: 0.98;
  letter-spacing: -0.055em;
  color: var(--kq-navy);
  font-weight: 850;
}

.kq-hero-position {
  margin: 0 0 1.7rem;
  max-width: 950px;
  font-size: clamp(1.05rem, 1.7vw, 1.35rem);
  line-height: 1.55;
  color: var(--kq-text);
  font-weight: 700;
}

.kq-hero-tagline {
  margin: 0 0 1.45rem;
  max-width: 980px;
  font-size: clamp(1.08rem, 1.8vw, 1.45rem);
  line-height: 1.45;
  color: var(--kq-navy);
  font-weight: 800;
}

.kq-hero-tagline span {
  color: var(--kq-blue);
}

.kq-hero-desc {
  margin: 0 0 2.1rem;
  max-width: 960px;
  font-size: clamp(1.02rem, 1.7vw, 1.28rem);
  line-height: 1.75;
  color: #53657f;
}

.kq-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
}

.kq-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-width: 160px;
  padding: 0.86rem 1.35rem;
  border-radius: 999px;
  font-size: 1rem;
  font-weight: 800;
  text-decoration: none !important;
  transition: all 0.18s ease;
}

.kq-btn-primary {
  color: #fff !important;
  background: var(--kq-blue);
  box-shadow: 0 14px 28px rgba(37, 99, 235, 0.22);
}

.kq-btn-primary:hover {
  transform: translateY(-1px);
  background: #1d4ed8;
}

.kq-btn-secondary {
  color: var(--kq-text) !important;
  background: rgba(255, 255, 255, 0.72);
  border: 1px solid #cbd5e1;
}

.kq-btn-secondary:hover {
  transform: translateY(-1px);
  border-color: var(--kq-blue);
  color: var(--kq-blue) !important;
}

/* ---------- Metrics ---------- */

.kq-metrics {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 1.1rem;
  margin: 0 0 3rem;
}

.kq-metric {
  padding: 1.35rem 1.55rem;
  border: 1px solid var(--kq-border);
  border-radius: 22px;
  background: var(--kq-card);
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.045);
}

.kq-metric-number {
  display: block;
  margin-bottom: 0.35rem;
  font-size: 1.75rem;
  line-height: 1;
  color: var(--kq-navy);
  font-weight: 850;
  letter-spacing: -0.03em;
}

.kq-metric-label {
  color: var(--kq-muted);
  font-weight: 700;
  font-size: 0.95rem;
}

/* ---------- Section layout ---------- */

.kq-section {
  margin: 3.3rem 0;
}

.kq-section-header {
  margin-bottom: 1.4rem;
}

.kq-section-kicker {
  margin: 0 0 0.55rem;
  color: var(--kq-blue);
  font-size: 0.82rem;
  font-weight: 850;
  letter-spacing: 0.16em;
  text-transform: uppercase;
}

.kq-section-title {
  margin: 0;
  color: var(--kq-navy);
  font-size: clamp(1.75rem, 3vw, 2.45rem);
  line-height: 1.2;
  letter-spacing: -0.035em;
  font-weight: 850;
}

.kq-section-subtitle {
  margin: 0.85rem 0 0;
  max-width: 980px;
  color: var(--kq-muted);
  font-size: 1.12rem;
  line-height: 1.75;
}

/* ---------- About ---------- */

.kq-about-card {
  padding: 2.35rem 2.6rem;
  border: 1px solid var(--kq-border);
  border-radius: 26px;
  background: #fff;
  box-shadow: 0 16px 42px rgba(15, 23, 42, 0.055);
}

.kq-about-card p {
  margin: 0 0 1.3rem;
  color: #53657f;
  font-size: 1.11rem;
  line-height: 1.85;
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

/* ---------- Research Agenda ---------- */

.kq-research-lead {
  padding: 2.25rem 2.45rem;
  border-radius: 26px;
  color: #e5edf8;
  background:
    radial-gradient(circle at 90% 15%, rgba(96, 165, 250, 0.28), transparent 32%),
    linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
  box-shadow: 0 18px 42px rgba(15, 23, 42, 0.16);
}

.kq-research-lead h3 {
  margin: 0 0 0.85rem;
  color: #ffffff;
  font-size: clamp(1.25rem, 2.2vw, 1.75rem);
  line-height: 1.35;
  letter-spacing: -0.02em;
  font-weight: 850;
}

.kq-research-lead h3 span {
  color: #93c5fd;
}

.kq-research-lead p {
  margin: 0;
  max-width: 980px;
  color: #d2deee;
  font-size: 1.08rem;
  line-height: 1.75;
}

.kq-agenda-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.15rem;
  margin-top: 1.4rem;
}

.kq-agenda-card {
  display: grid;
  grid-template-columns: 230px 1fr;
  gap: 1.7rem;
  padding: 2rem;
  border: 1px solid var(--kq-border);
  border-radius: 24px;
  background: #fff;
  box-shadow: 0 14px 32px rgba(15, 23, 42, 0.045);
}

.kq-agenda-label {
  color: var(--kq-blue);
  font-size: 0.95rem;
  font-weight: 850;
  letter-spacing: 0.02em;
}

.kq-agenda-topic {
  margin-top: 0.35rem;
  color: var(--kq-muted);
  font-size: 0.93rem;
  line-height: 1.5;
  font-weight: 750;
}

.kq-agenda-card h4 {
  margin: 0 0 0.75rem;
  color: var(--kq-navy);
  font-size: 1.35rem;
  line-height: 1.35;
  font-weight: 850;
  letter-spacing: -0.02em;
}

.kq-agenda-card p {
  margin: 0;
  color: #53657f;
  font-size: 1.04rem;
  line-height: 1.75;
}

.kq-question {
  margin-top: 1rem;
  padding: 1rem 1.15rem;
  border: 1px solid #dbeafe;
  border-radius: 16px;
  background: #f8fbff;
  color: #475569;
  line-height: 1.65;
}

.kq-question strong {
  color: var(--kq-navy);
}

/* ---------- Selected News ---------- */

.kq-news-wrap {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.15rem;
}

.kq-news-card {
  padding: 1.65rem 1.8rem;
  border: 1px solid var(--kq-border);
  border-radius: 22px;
  background: #fff;
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.045);
}

.kq-news-card h3 {
  margin: 0 0 1rem;
  color: var(--kq-navy);
  font-size: 1.18rem;
  font-weight: 850;
}

.kq-news-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.kq-news-list li {
  position: relative;
  margin: 0 0 0.9rem;
  padding-left: 1.15rem;
  color: #53657f;
  line-height: 1.6;
}

.kq-news-list li:last-child {
  margin-bottom: 0;
}

.kq-news-list li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.63em;
  width: 6px;
  height: 6px;
  border-radius: 50%;
  background: var(--kq-blue);
}

.kq-news-date {
  color: var(--kq-blue);
  font-weight: 850;
}

/* ---------- Join ---------- */

.kq-join {
  padding: 2.4rem 2.6rem;
  border-radius: 26px;
  background:
    radial-gradient(circle at 85% 20%, rgba(37, 99, 235, 0.12), transparent 36%),
    linear-gradient(135deg, #f8fbff 0%, #ffffff 70%);
  border: 1px solid var(--kq-border);
}

.kq-join h2 {
  margin: 0 0 0.7rem;
  color: var(--kq-navy);
  font-size: clamp(1.65rem, 3vw, 2.25rem);
  line-height: 1.2;
  letter-spacing: -0.035em;
  font-weight: 850;
}

.kq-join p {
  margin: 0 0 1.3rem;
  max-width: 900px;
  color: #53657f;
  font-size: 1.08rem;
  line-height: 1.75;
}

/* ---------- Visitor map ---------- */

.kq-visitor {
  margin-top: 2.8rem;
  padding-top: 1.5rem;
  border-top: 1px solid var(--kq-border);
}

.kq-visitor-title {
  margin-bottom: 0.8rem;
  color: var(--kq-muted);
  font-size: 0.82rem;
  font-weight: 850;
  letter-spacing: 0.14em;
  text-transform: uppercase;
}

/* ---------- Responsive ---------- */

@media (max-width: 900px) {
  .kq-hero {
    padding: 2.4rem 2rem;
  }

  .kq-metrics {
    grid-template-columns: repeat(2, 1fr);
  }

  .kq-agenda-card {
    grid-template-columns: 1fr;
    gap: 0.9rem;
  }

  .kq-news-wrap {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 560px) {
  .kq-hero {
    padding: 2rem 1.35rem;
    border-radius: 22px;
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
  .kq-research-lead,
  .kq-agenda-card,
  .kq-news-card,
  .kq-join {
    padding: 1.45rem;
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
      My research develops mechanics-grounded, data-enabled, and uncertainty-aware methods
      for understanding, modelling, and managing complex geotechnical systems.
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
        working with Prof. <a href="https://www.polyu.edu.hk/cee/people/academic-staff/prof-yin-zhenyu/" target="_blank" rel="noopener">Zhen-Yu Yin</a>.
        I received my Ph.D. in Geotechnical Engineering from Wuhan University under the supervision of
        Prof. Yong Liu and Prof. Dian-Qing Li, and was a visiting Ph.D. student at the
        <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>,
        hosted by Prof. <a href="https://cde.nus.edu.sg/cee/staff/fook-hou-lee/" target="_blank" rel="noopener">Fook-Hou Lee</a>.
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
        Towards mechanics-informed, data-enabled, and uncertainty-aware geotechnics
      </h2>
      <p class="kq-section-subtitle">
        My group aims to establish new computational and experimental paradigms for geotechnical systems
        by integrating physics-based modelling, data-driven intelligence, and uncertainty quantification.
      </p>
    </div>

    <div class="kq-research-lead">
      <h3>
        A research program for <span>next-generation geotechnical engineering under uncertainty</span>
      </h3>
      <p>
        Ground systems are heterogeneous, history-dependent, multiphysical, and often only partially
        observable. We develop models and methods that learn from data, respect mechanics, quantify
        uncertainty, and support safer engineering decisions for underground, cold-region, energy, and
        infrastructure systems.
      </p>
    </div>

    <div class="kq-agenda-grid">

      <article class="kq-agenda-card">
        <div>
          <div class="kq-agenda-label">Agenda 01</div>
          <div class="kq-agenda-topic">Complex ground systems</div>
        </div>

        <div>
          <h4>Mechanics of ground in extreme and evolving environments</h4>
          <p>
            We study geomaterials and ground systems governed by coupled thermal, hydraulic, mechanical,
            chemical, and phase-change processes, including frozen soils, artificial ground freezing,
            and hydrate-bearing sediments.
          </p>
          <div class="kq-question">
            <strong>Core question:</strong> How can we predict ground behaviour when temperature, water,
            stress, microstructure, and environmental loading evolve together?
          </div>
        </div>
      </article>

      <article class="kq-agenda-card">
        <div>
          <div class="kq-agenda-label">Agenda 02</div>
          <div class="kq-agenda-topic">Data–physics integration</div>
        </div>

        <div>
          <h4>Mechanics-informed intelligence for geotechnical modelling</h4>
          <p>
            We develop data-enabled models that embed physical constraints, constitutive knowledge,
            and engineering judgement into machine learning and computational frameworks.
          </p>
          <div class="kq-question">
            <strong>Core question:</strong> How can artificial intelligence improve prediction while
            remaining interpretable, physically meaningful, and reliable for engineering use?
          </div>
        </div>
      </article>

      <article class="kq-agenda-card">
        <div>
          <div class="kq-agenda-label">Agenda 03</div>
          <div class="kq-agenda-topic">Uncertainty and risk</div>
        </div>

        <div>
          <h4>Uncertainty quantification and decision support for infrastructure</h4>
          <p>
            We quantify uncertainty arising from spatial variability, limited observations, model bias,
            and environmental change, and translate it into risk-informed design and decision-making tools.
          </p>
          <div class="kq-question">
            <strong>Core question:</strong> How can we make geotechnical decisions that are robust,
            transparent, and adaptive under incomplete information?
          </div>
        </div>
      </article>

    </div>
  </section>


  <!-- ================= Selected News ================= -->
  <section class="kq-section">
    <div class="kq-section-header">
      <p class="kq-section-kicker">Updates</p>
      <h2 class="kq-section-title">Selected News</h2>
    </div>

    <div class="kq-news-wrap">

      <div class="kq-news-card">
        <h3>Awards & Appointments</h3>
        <ul class="kq-news-list">
          <li>
            <span class="kq-news-date">2025</span> —
            Awarded the NSFC Excellent Young Scientists Fund Overseas.
          </li>
          <li>
            <span class="kq-news-date">2025</span> —
            Will join Wuhan University as an Incoming Professor.
          </li>
        </ul>
      </div>

      <div class="kq-news-card">
        <h3>Research & Publications</h3>
        <ul class="kq-news-list">
          <li>
            <span class="kq-news-date">2024–2025</span> —
            Continued research on intelligent geotechnics, uncertainty quantification, and multiphysical ground systems.
          </li>
          <li>
            <span class="kq-news-date">Recent</span> —
            40+ journal papers, 1,500+ citations, h-index 23, and 5 ESI Highly Cited Papers.
          </li>
        </ul>
      </div>

      <div class="kq-news-card">
        <h3>Funding & Collaboration</h3>
        <ul class="kq-news-list">
          <li>
            <span class="kq-news-date">Ongoing</span> —
            Seeking collaborations in data–physics fusion, frozen ground engineering, underground construction, and resilient infrastructure.
          </li>
        </ul>
      </div>

      <div class="kq-news-card">
        <h3>Academic Service</h3>
        <ul class="kq-news-list">
          <li>
            <span class="kq-news-date">Ongoing</span> —
            Serving the geotechnical engineering community through peer review, conference activities, and collaborative research.
          </li>
        </ul>
      </div>

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
