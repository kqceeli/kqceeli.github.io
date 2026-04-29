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
   Kai-Qi Li Homepage
   Clean, compact, unified academic homepage style
   ========================================================= */

:root {
  --kq-navy: #0f172a;
  --kq-blue: #2563eb;
  --kq-blue-soft: #eff6ff;
  --kq-red: #d62728;
  --kq-purple: #9467bd;
  --kq-green: #2ca02c;
  --kq-text: #475569;
  --kq-muted: #64748b;
  --kq-border: #dbe4f0;
  --kq-bg: #f8fafc;
  --kq-card: #ffffff;
}

.kq-home {
  max-width: 930px;
  margin: 0 auto;
  color: var(--kq-text);
  font-size: 0.92rem;
  line-height: 1.68;
}

.kq-home * {
  box-sizing: border-box;
}

.kq-home p {
  margin-top: 0;
  font-size: 0.92rem;
  line-height: 1.68;
}

.kq-home a {
  color: var(--kq-blue);
  text-decoration-thickness: 1px;
  text-underline-offset: 3px;
}

.kq-home strong {
  color: var(--kq-navy);
  font-weight: 700;
}

/* ================= Hero ================= */

.kq-hero {
  margin: 0 0 1.35rem;
  padding: 1.8rem 2rem;
  border: 1px solid var(--kq-border);
  border-radius: 20px;
  background:
    radial-gradient(circle at 92% 8%, rgba(37, 99, 235, 0.10), transparent 34%),
    linear-gradient(135deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 10px 26px rgba(15, 23, 42, 0.05);
}

.kq-hero h1 {
  margin: 0 0 0.45rem;
  color: var(--kq-navy);
  font-size: clamp(1.85rem, 3.2vw, 2.45rem);
  line-height: 1.1;
  letter-spacing: -0.035em;
  font-weight: 800;
}

.kq-position {
  margin: 0 0 0.95rem;
  color: #52627a;
  font-size: 0.95rem;
  line-height: 1.55;
  font-weight: 650;
}

.kq-tagline {
  margin: 0 0 0.85rem;
  max-width: 800px;
  color: var(--kq-navy);
  font-size: 1.02rem;
  line-height: 1.52;
  font-weight: 700;
}

.kq-tagline span {
  color: var(--kq-blue);
}

.kq-hero-desc {
  margin: 0 0 1.2rem;
  max-width: 820px;
  color: var(--kq-muted);
  font-size: 0.9rem;
  line-height: 1.7;
}

.kq-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.65rem;
}

.kq-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 0.52rem 0.9rem;
  border-radius: 999px;
  font-size: 0.82rem;
  font-weight: 700;
  text-decoration: none !important;
  transition: all 0.18s ease;
  white-space: nowrap;
}

.kq-btn-primary {
  color: #ffffff !important;
  background: var(--kq-blue);
  box-shadow: 0 8px 18px rgba(37, 99, 235, 0.20);
}

.kq-btn-primary:hover {
  transform: translateY(-1px);
  background: #1d4ed8;
}

.kq-btn-secondary {
  color: #334155 !important;
  background: #ffffff;
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
  gap: 0.8rem;
  margin: 0 0 2.15rem;
}

.kq-metric {
  padding: 0.85rem 1rem;
  border: 1px solid var(--kq-border);
  border-radius: 16px;
  background: var(--kq-card);
  box-shadow: 0 8px 20px rgba(15, 23, 42, 0.035);
}

.kq-metric-number {
  display: block;
  margin-bottom: 0.22rem;
  color: var(--kq-navy);
  font-size: 1.18rem;
  line-height: 1;
  font-weight: 800;
}

.kq-metric-label {
  display: block;
  color: var(--kq-muted);
  font-size: 0.76rem;
  line-height: 1.35;
  font-weight: 650;
}

/* ================= General Section ================= */

.kq-section {
  margin: 2.35rem 0;
}

.kq-section-header {
  margin-bottom: 0.9rem;
  padding-bottom: 0.65rem;
  border-bottom: 1px solid #e5eaf2;
}

.kq-kicker {
  margin: 0 0 0.3rem;
  color: var(--kq-blue);
  font-size: 0.68rem;
  line-height: 1.2;
  font-weight: 800;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.kq-section-title {
  margin: 0;
  color: var(--kq-navy);
  font-size: clamp(1.22rem, 2vw, 1.55rem);
  line-height: 1.28;
  letter-spacing: -0.025em;
  font-weight: 800;
}

.kq-section-subtitle {
  margin: 0.42rem 0 0;
  max-width: 830px;
  color: var(--kq-muted);
  font-size: 0.88rem;
  line-height: 1.65;
}

/* ================= About ================= */

.kq-card {
  padding: 1.35rem 1.5rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: var(--kq-card);
  box-shadow: 0 9px 22px rgba(15, 23, 42, 0.04);
}

.kq-card p {
  margin-bottom: 0.85rem;
}

.kq-card p:last-child {
  margin-bottom: 0;
}

/* ================= Research Agenda ================= */

.kq-agenda {
  padding: 1.35rem;
  border: 1px solid var(--kq-border);
  border-radius: 20px;
  background: linear-gradient(180deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 9px 22px rgba(15, 23, 42, 0.04);
}

.kq-agenda-intro {
  display: grid;
  grid-template-columns: 1.05fr 1fr;
  gap: 1rem;
  margin-bottom: 1rem;
}

.kq-agenda-statement,
.kq-principles {
  border: 1px solid #dbeafe;
  border-radius: 16px;
  background: #ffffff;
}

.kq-agenda-statement {
  padding: 1.1rem 1.2rem;
}

.kq-agenda-statement h3 {
  margin: 0 0 0.5rem;
  color: var(--kq-navy);
  font-size: 1.02rem;
  line-height: 1.38;
  font-weight: 800;
  letter-spacing: -0.015em;
}

.kq-agenda-statement h3 span {
  color: var(--kq-blue);
}

.kq-agenda-statement p {
  margin: 0;
  color: var(--kq-muted);
  font-size: 0.86rem;
  line-height: 1.65;
}

.kq-principles {
  display: grid;
  grid-template-columns: 1fr;
  overflow: hidden;
}

.kq-principle {
  padding: 0.82rem 1rem;
  border-bottom: 1px solid #e5eaf2;
}

.kq-principle:last-child {
  border-bottom: none;
}

.kq-principle-label {
  margin-bottom: 0.18rem;
  color: var(--kq-blue);
  font-size: 0.66rem;
  font-weight: 800;
  letter-spacing: 0.10em;
  text-transform: uppercase;
}

.kq-principle-title {
  margin: 0 0 0.18rem;
  color: var(--kq-navy);
  font-size: 0.88rem;
  line-height: 1.35;
  font-weight: 750;
}

.kq-principle p {
  margin: 0;
  color: var(--kq-muted);
  font-size: 0.8rem;
  line-height: 1.52;
}

.kq-agenda-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0.85rem;
}

.kq-agenda-card {
  position: relative;
  padding: 1.05rem 1rem;
  border: 1px solid var(--kq-border);
  border-radius: 16px;
  background: #ffffff;
  box-shadow: 0 7px 18px rgba(15, 23, 42, 0.035);
}

.kq-agenda-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 1rem;
  bottom: 1rem;
  width: 3px;
  border-radius: 999px;
  background: var(--kq-blue);
}

.kq-agenda-num {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 1.65rem;
  height: 1.65rem;
  margin-bottom: 0.58rem;
  border-radius: 999px;
  color: var(--kq-blue);
  background: var(--kq-blue-soft);
  font-size: 0.68rem;
  font-weight: 800;
}

.kq-agenda-card h4 {
  margin: 0 0 0.45rem;
  color: var(--kq-navy);
  font-size: 0.93rem;
  line-height: 1.35;
  font-weight: 800;
  letter-spacing: -0.01em;
}

.kq-agenda-card p {
  margin: 0 0 0.65rem;
  color: var(--kq-muted);
  font-size: 0.82rem;
  line-height: 1.58;
}

.kq-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.3rem;
}

.kq-tag {
  display: inline-flex;
  padding: 0.18rem 0.46rem;
  border-radius: 999px;
  background: #f1f5f9;
  color: #475569;
  font-size: 0.68rem;
  line-height: 1.35;
  font-weight: 650;
}

/* ================= Selected News ================= */

.kq-news {
  padding: 1.35rem 1.5rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: #ffffff;
  box-shadow: 0 9px 22px rgba(15, 23, 42, 0.04);
}

.kq-news-intro {
  margin: 0 0 1.15rem;
  color: var(--kq-muted);
  font-size: 0.88rem;
  line-height: 1.65;
}

.kq-news-group {
  margin-top: 1.25rem;
  padding-top: 1.05rem;
  border-top: 1px solid #e8edf5;
}

.kq-news-group:first-of-type {
  margin-top: 0.5rem;
}

.kq-news-heading {
  display: flex;
  align-items: center;
  gap: 0.45rem;
  margin: 0 0 0.65rem;
  font-size: 0.98rem;
  line-height: 1.35;
  font-weight: 800;
  letter-spacing: -0.01em;
}

.kq-news-heading::before {
  content: "";
  width: 0.55rem;
  height: 0.55rem;
  border-radius: 999px;
  background: currentColor;
  flex: 0 0 auto;
}

.kq-news-heading.awards {
  color: var(--kq-red);
}

.kq-news-heading.research {
  color: var(--kq-purple);
}

.kq-news-heading.funding {
  color: var(--kq-blue);
}

.kq-news-heading.service {
  color: var(--kq-green);
}

.kq-news-list {
  margin: 0;
  padding-left: 1.05rem;
}

.kq-news-list li {
  margin: 0.45rem 0;
  padding-left: 0.15rem;
  color: var(--kq-text);
  font-size: 0.86rem;
  line-height: 1.58;
}

.kq-news-list li::marker {
  color: #94a3b8;
}

.kq-news-list em {
  color: #334155;
}

/* ================= Join ================= */

.kq-join {
  padding: 1.35rem 1.5rem;
  border: 1px solid var(--kq-border);
  border-radius: 18px;
  background: linear-gradient(135deg, #ffffff 0%, #f8fbff 100%);
  box-shadow: 0 9px 22px rgba(15, 23, 42, 0.04);
}

.kq-join h2 {
  margin: 0 0 0.45rem;
  color: var(--kq-navy);
  font-size: 1.22rem;
  line-height: 1.3;
  font-weight: 800;
  letter-spacing: -0.02em;
}

.kq-join p {
  margin-bottom: 0.9rem;
  max-width: 790px;
  color: var(--kq-muted);
  font-size: 0.9rem;
}

/* ================= Visitor ================= */

.kq-visitor {
  margin-top: 2rem;
  padding-top: 1rem;
  border-top: 1px solid var(--kq-border);
}

.kq-visitor-title {
  margin-bottom: 0.6rem;
  color: var(--kq-muted);
  font-size: 0.68rem;
  font-weight: 800;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

/* ================= Responsive ================= */

@media (max-width: 900px) {
  .kq-metrics {
    grid-template-columns: repeat(2, 1fr);
  }

  .kq-agenda-intro {
    grid-template-columns: 1fr;
  }

  .kq-agenda-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 560px) {
  .kq-home {
    font-size: 0.9rem;
  }

  .kq-hero {
    padding: 1.35rem 1.15rem;
  }

  .kq-hero h1 {
    font-size: 1.85rem;
  }

  .kq-metrics {
    grid-template-columns: 1fr;
  }

  .kq-card,
  .kq-agenda,
  .kq-news,
  .kq-join {
    padding: 1.05rem;
  }

  .kq-actions {
    flex-direction: column;
  }

  .kq-btn {
    width: 100%;
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

    <p class="kq-tagline">
      Shaping the future of <span>geotechnics</span> through intelligence and uncertainty mastery.
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
      <p class="kq-kicker">Research Agenda</p>
      <h2 class="kq-section-title">
        Mechanics-informed intelligence for complex geotechnical systems
      </h2>
      <p class="kq-section-subtitle">
        My group works at the intersection of geomechanics, computation, uncertainty quantification,
        and artificial intelligence.
      </p>
    </div>

    <div class="kq-agenda">

      <div class="kq-agenda-intro">
        <div class="kq-agenda-statement">
          <h3>
            Toward <span>reliable, explainable, and adaptive</span> geotechnical modelling
          </h3>
          <p>
            Future geotechnical engineering requires models that combine physical understanding,
            sparse observations, data-driven learning, and uncertainty-aware decision-making.
          </p>
        </div>

        <div class="kq-principles">
          <div class="kq-principle">
            <div class="kq-principle-label">Mechanics</div>
            <h4 class="kq-principle-title">Physics as foundation</h4>
            <p>Constitutive behaviour, coupled processes, and engineering mechanisms remain central.</p>
          </div>

          <div class="kq-principle">
            <div class="kq-principle-label">Intelligence</div>
            <h4 class="kq-principle-title">Data as amplifier</h4>
            <p>Machine learning is used to enhance, not replace, scientific understanding.</p>
          </div>

          <div class="kq-principle">
            <div class="kq-principle-label">Reliability</div>
            <h4 class="kq-principle-title">Uncertainty as design input</h4>
            <p>Variability, limited data, and model bias are explicitly quantified for robust decisions.</p>
          </div>
        </div>
      </div>

      <div class="kq-agenda-grid">

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">01</div>
          <h4>Multiphysics geomechanics of complex ground</h4>
          <p>
            Coupled thermal, hydraulic, mechanical, chemical, and phase-change processes in
            geomaterials and ground systems.
          </p>
          <div class="kq-tags">
            <span class="kq-tag">Frozen soil</span>
            <span class="kq-tag">AGF</span>
            <span class="kq-tag">Hydrate sediments</span>
            <span class="kq-tag">THMC coupling</span>
          </div>
        </article>

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">02</div>
          <h4>Mechanics-informed artificial intelligence</h4>
          <p>
            Data-enabled models that embed physical constraints, constitutive knowledge,
            and engineering judgement.
          </p>
          <div class="kq-tags">
            <span class="kq-tag">Physics-informed ML</span>
            <span class="kq-tag">Surrogate models</span>
            <span class="kq-tag">Inverse analysis</span>
            <span class="kq-tag">Digital twins</span>
          </div>
        </article>

        <article class="kq-agenda-card">
          <div class="kq-agenda-num">03</div>
          <h4>Uncertainty, reliability, and risk-informed decisions</h4>
          <p>
            Quantifying uncertainty from spatial variability, limited observations,
            model bias, and changing environments.
          </p>
          <div class="kq-tags">
            <span class="kq-tag">Random fields</span>
            <span class="kq-tag">Bayesian updating</span>
            <span class="kq-tag">Reliability</span>
            <span class="kq-tag">Risk</span>
          </div>
        </article>

      </div>
    </div>
  </section>


  <!-- ================= Selected News ================= -->
  <section class="kq-section">
    <div class="kq-section-header">
      <p class="kq-kicker">Updates</p>
      <h2 class="kq-section-title">Selected News</h2>
      <p class="kq-section-subtitle">
        A selection of recent highlights in research, funding, awards, and academic service.
      </p>
    </div>

    <div class="kq-news">

      <div class="kq-news-group">
        <h3 class="kq-news-heading awards">Awards &amp; Honors</h3>
        <ul class="kq-news-list">
          <li>[2026] Awarded the <strong>NSFC Excellent Young Scientists Fund (Overseas)</strong> and will join <strong>Wuhan University</strong> as an incoming professor.</li>
          <li>[2025] Shortlisted for the <strong>JC STEM Early Career Research Fellowship</strong>.</li>
          <li>[2024] Awarded the <strong>PolyU Distinguished Postdoctoral Fellowship</strong> in October 2024.</li>
          <li>[2024] Received the <strong>2023 Hubei Province Science &amp; Technology Progress Award</strong> for the project <em>Risk Prevention and Control of Artificial Ground Freezing Technique in Water-Rich Stratum</em> in April 2024 (<a href="https://www.hubei.gov.cn/zfwj/ezf/202407/t20240726_5280385.shtml" target="_blank" rel="noopener">Link</a>).</li>
          <li>[2023] Received the <strong>2023 Academic Innovation Award</strong> from Wuhan University in March 2023.</li>
          <li>[2021] Received the <strong>Excellence in Teaching Award</strong> from Wuhan University in March 2021.</li>
          <li>[2020] Named one of <strong>Wuhan University’s Top 10 Academic Stars</strong> in October 2020. See the <a href="https://service.whu.edu.cn/info/1005/2179.htm" target="_blank" rel="noopener">official announcement</a> or read more <a href="https://risk.whu.edu.cn/info/1034/1301.htm" target="_blank" rel="noopener">here</a>.</li>
          <li>[2016] Awarded the <strong>Top 10 Future Star Undergraduate</strong> by the China Water Resources Education Association in July 2016 (<a href="https://sljzw.hhu.edu.cn/2019/0415/c11821a189595/page.htm" target="_blank" rel="noopener">Link</a>).</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading research">Research &amp; Publications</h3>
        <ul class="kq-news-list">
          <li>[2026] Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.</li>
          <li>[2026] Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.</li>
          <li>[2025] Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em> in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em> (<a href="https://doi.org/10.1061/JGGEFK.GTENG-13437" target="_blank" rel="noopener">DOI:10.1061/JGGEFK.GTENG-13437</a>).</li>
          <li>[2025] Published <em>Physics-informed neural networks for solving steady-state temperature field in artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em> (<a href="https://doi.org/10.1139/cgj-2024-0650" target="_blank" rel="noopener">DOI:10.1139/cgj-2024-0650</a>).</li>
          <li>[2025] Published <em>State of the art of mechanical behaviors of frozen soils through experimental investigation</em> in <em>Cold Regions Science and Technology</em> (<a href="https://doi.org/10.1016/j.coldregions.2025.104497" target="_blank" rel="noopener">DOI:10.1016/j.coldregions.2025.104497</a>).</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading funding">Funding</h3>
        <ul class="kq-news-list">
          <li>[2025–2026] Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical coupling in hydrate-bearing sediments using physics-informed neural networks.</li>
          <li>[2025–2029] Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project on digital twins for coastal resilience under extreme storm surges in Hong Kong.</li>
          <li>[2024–2026] Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed multi-fidelity neural networks for intelligent rectification of shield machine attitude in layered soils.</li>
          <li>[2022] Received the <strong>Centrally Funded Postdoctoral Fellowship (HK$763,555)</strong> for a project on thermo-hydro-mechanical modelling for artificial ground freezing.</li>
        </ul>
      </div>

      <div class="kq-news-group">
        <h3 class="kq-news-heading service">Academic Service</h3>
        <ul class="kq-news-list">
          <li>[2025] Serving as Co-chair of Mini-Symposium 9: <em>Multiphysics Modeling of Geo-engineering and Geohazards</em> at <strong>IACMAG 2025</strong>, Hong Kong.</li>
          <li>[2024] Joined the <strong>Early-career Editorial Panel</strong> for the <em>European Journal of Soil Science</em> in March 2024 (<a href="https://bsssjournals.onlinelibrary.wiley.com/hub/journal/13652389/editorialboard.html" target="_blank" rel="noopener">Link</a>).</li>
          <li>[2024] Served as Session Chair at the <strong>12th National Conference on Engineering Geology</strong>, Shenzhen.</li>
          <li>[2023] Served as Secretary of the <strong>International Symposium on Innovations in Geotechnical Engineering towards Sustainability (IGES 2023)</strong>.</li>
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
