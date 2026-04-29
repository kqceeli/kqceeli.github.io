---
layout: single
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.home-page {
  max-width: 1040px;
  margin: 0 auto;
  color: #263238;
  line-height: 1.72;
  font-size: 0.98rem;
}

.home-hero {
  position: relative;
  padding: 2.4rem 2.2rem 2.2rem;
  margin: 0.3rem 0 2rem;
  border-radius: 22px;
  background:
    radial-gradient(circle at top left, rgba(37, 99, 235, 0.10), transparent 34%),
    radial-gradient(circle at bottom right, rgba(14, 116, 144, 0.10), transparent 34%),
    linear-gradient(135deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e2e8f0;
  box-shadow: 0 14px 36px rgba(15, 23, 42, 0.07);
}

.home-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0.34rem 0.76rem;
  margin-bottom: 1rem;
  border-radius: 999px;
  background: #eff6ff;
  color: #1d4ed8;
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0.035em;
  text-transform: uppercase;
}

.home-eyebrow::before {
  content: "";
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: #2563eb;
}

.home-hero h1 {
  margin: 0 0 0.55rem;
  font-size: clamp(2rem, 4vw, 3.1rem);
  line-height: 1.08;
  letter-spacing: -0.04em;
  color: #0f172a;
  font-weight: 800;
}

.home-subtitle {
  margin: 0 0 1.1rem;
  color: #334155;
  font-size: 1.06rem;
  font-weight: 600;
}

.home-lead {
  max-width: 850px;
  margin: 0;
  color: #475569;
  font-size: 1.02rem;
}

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1.55rem;
}

.home-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 42px;
  padding: 0.65rem 1.05rem;
  border-radius: 999px;
  font-size: 0.88rem;
  font-weight: 700;
  text-decoration: none !important;
  transition: all 0.18s ease;
}

.home-btn-primary {
  background: #0f172a;
  color: #ffffff !important;
  border: 1px solid #0f172a;
}

.home-btn-primary:hover {
  transform: translateY(-1px);
  background: #1e293b;
}

.home-btn-secondary {
  background: #ffffff;
  color: #1e293b !important;
  border: 1px solid #cbd5e1;
}

.home-btn-secondary:hover {
  transform: translateY(-1px);
  border-color: #94a3b8;
  background: #f8fafc;
}

.home-metrics {
  display: grid;
  grid-template-columns: repeat(4, minmax(0, 1fr));
  gap: 0.9rem;
  margin: 1.25rem 0 2.2rem;
}

.home-metric {
  padding: 1.05rem 1rem;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 8px 24px rgba(15, 23, 42, 0.045);
}

.home-metric-number {
  display: block;
  color: #0f172a;
  font-size: 1.55rem;
  line-height: 1.1;
  font-weight: 800;
  letter-spacing: -0.03em;
}

.home-metric-label {
  display: block;
  margin-top: 0.28rem;
  color: #64748b;
  font-size: 0.78rem;
  font-weight: 650;
  text-transform: uppercase;
  letter-spacing: 0.035em;
}

.home-section {
  margin: 2.1rem 0;
}

.home-section-header {
  margin-bottom: 1rem;
}

.home-section-kicker {
  margin: 0 0 0.25rem;
  color: #2563eb;
  font-size: 0.78rem;
  font-weight: 800;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.home-section h2 {
  margin: 0;
  color: #0f172a;
  font-size: 1.55rem;
  letter-spacing: -0.025em;
}

.home-section p {
  color: #475569;
}

.home-about-card {
  padding: 1.45rem 1.55rem;
  border-radius: 20px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  box-shadow: 0 10px 26px rgba(15, 23, 42, 0.045);
}

.home-about-card p {
  margin: 0 0 1rem;
}

.home-about-card p:last-child {
  margin-bottom: 0;
}

.home-highlight {
  color: #0f172a;
  font-weight: 750;
}

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.9rem;
}

.research-card {
  padding: 1.15rem 1.15rem 1.05rem;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
  transition: all 0.18s ease;
}

.research-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 12px 28px rgba(15, 23, 42, 0.06);
}

.research-card h3 {
  margin: 0 0 0.45rem;
  color: #0f172a;
  font-size: 1rem;
  letter-spacing: -0.01em;
}

.research-card p {
  margin: 0;
  color: #64748b;
  font-size: 0.9rem;
}

.news-wrap {
  display: grid;
  gap: 0.9rem;
}

.news-group {
  padding: 1.15rem 1.2rem;
  border-radius: 18px;
  background: #ffffff;
  border: 1px solid #e2e8f0;
}

.news-group-title {
  display: flex;
  align-items: center;
  gap: 0.55rem;
  margin: 0 0 0.75rem;
  color: #0f172a;
  font-size: 1rem;
  font-weight: 800;
}

.news-dot {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  flex: 0 0 auto;
}

.dot-red { background: #dc2626; }
.dot-blue { background: #2563eb; }
.dot-purple { background: #7c3aed; }
.dot-green { background: #16a34a; }

.news-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.news-list li {
  position: relative;
  padding: 0.48rem 0 0.48rem 1.15rem;
  color: #475569;
  border-top: 1px solid #f1f5f9;
  font-size: 0.94rem;
}

.news-list li:first-child {
  border-top: none;
}

.news-list li::before {
  content: "";
  position: absolute;
  left: 0;
  top: 1.05rem;
  width: 5px;
  height: 5px;
  border-radius: 50%;
  background: #94a3b8;
}

.news-year {
  color: #0f172a;
  font-weight: 800;
}

.vision-box {
  padding: 1.35rem 1.45rem;
  margin-top: 1.5rem;
  border-radius: 20px;
  background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
  color: #e2e8f0;
  box-shadow: 0 16px 36px rgba(15, 23, 42, 0.16);
}

.vision-box h2 {
  margin: 0 0 0.55rem;
  color: #ffffff;
  font-size: 1.35rem;
}

.vision-box p {
  margin: 0;
  color: #cbd5e1;
}

.home-note {
  margin: 1.6rem 0 1rem;
  padding: 1rem 1.15rem;
  border-radius: 16px;
  background: #f8fafc;
  border: 1px solid #e2e8f0;
  color: #475569;
  font-size: 0.94rem;
}

.visitor-map {
  margin: 1.6rem 0 0.4rem;
  text-align: center;
  opacity: 0.92;
}

@media (max-width: 760px) {
  .home-hero {
    padding: 1.8rem 1.35rem;
    border-radius: 18px;
  }

  .home-metrics {
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .research-grid {
    grid-template-columns: 1fr;
  }
}

@media (max-width: 460px) {
  .home-metrics {
    grid-template-columns: 1fr;
  }

  .home-actions {
    flex-direction: column;
  }

  .home-btn {
    width: 100%;
  }
}
</style>

<div class="home-page">

  <section class="home-hero">
    <div class="home-eyebrow">Geomechanics · Computation · AI</div>

    <h1>Kai-Qi Li, Ph.D.</h1>

    <p class="home-subtitle">
      NSFC Excellent Young Scientists Fund (Overseas) Awardee · Incoming Professor at Wuhan University
    </p>

    <p class="home-lead">
      I develop mechanics-based, uncertainty-aware, and AI-enabled methods for understanding and predicting
      complex geotechnical systems, with applications in frozen ground, artificial ground freezing,
      underground infrastructure, and climate-resilient geotechnical engineering.
    </p>

    <div class="home-actions">
      <a href="/join-us/" class="home-btn home-btn-primary">Join the Group</a>
      <a href="/publications/" class="home-btn home-btn-secondary">Publications</a>
      <a href="/cv/" class="home-btn home-btn-secondary">Curriculum Vitae</a>
    </div>
  </section>

  <section class="home-metrics">
    <div class="home-metric">
      <span class="home-metric-number">40+</span>
      <span class="home-metric-label">Journal Papers</span>
    </div>

    <div class="home-metric">
      <span class="home-metric-number">1,500+</span>
      <span class="home-metric-label">Citations</span>
    </div>

    <div class="home-metric">
      <span class="home-metric-number">23</span>
      <span class="home-metric-label">h-index</span>
    </div>

    <div class="home-metric">
      <span class="home-metric-number">5</span>
      <span class="home-metric-label">ESI Highly Cited Papers</span>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">About</p>
      <h2>Building predictive geotechnical science for complex ground systems</h2>
    </div>

    <div class="home-about-card">
      <p>
        I am an <span class="home-highlight">NSFC Excellent Young Scientists Fund (Overseas) Awardee</span>
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
        My research integrates <span class="home-highlight">geomechanics, advanced computation, stochastic analysis,
        and artificial intelligence</span>. A central goal is to move geotechnical engineering from empirical
        prediction toward physically consistent, data-informed, and uncertainty-aware decision-making.
      </p>
    </div>
  </section>

  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">Research Agenda</p>
      <h2>Core research directions</h2>
    </div>

    <div class="research-grid">
      <div class="research-card">
        <h3>Frozen Geomaterials and Artificial Ground Freezing</h3>
        <p>
          Thermo-hydro-mechanical behaviour of frozen soils, freezing-induced processes,
          and risk control in artificial ground freezing.
        </p>
      </div>

      <div class="research-card">
        <h3>Constitutive and Computational Geomechanics</h3>
        <p>
          Physics-based constitutive modelling, numerical simulation, and multiscale analysis
          for complex geomaterials and ground–structure interaction.
        </p>
      </div>

      <div class="research-card">
        <h3>Uncertainty, Reliability, and Risk</h3>
        <p>
          Stochastic modelling, reliability assessment, and uncertainty quantification for
          geotechnical systems under incomplete information.
        </p>
      </div>

      <div class="research-card">
        <h3>AI for Geotechnical Engineering</h3>
        <p>
          Physics-informed machine learning, neural operators, graph neural networks,
          and intelligent computational platforms for geotechnical prediction.
        </p>
      </div>
    </div>
  </section>

  <section class="vision-box">
    <h2>Research Vision</h2>
    <p>
      My long-term vision is to establish a globally visible research program that advances
      the scientific foundation of geotechnical engineering and enables safer, smarter, and more resilient
      infrastructure systems. I am particularly interested in problems where mechanics, uncertainty,
      computation, and data must work together.
    </p>
  </section>

  <section class="home-section">
    <div class="home-section-header">
      <p class="home-section-kicker">Highlights</p>
      <h2>Selected news</h2>
    </div>

    <div class="news-wrap">

      <div class="news-group">
        <h3 class="news-group-title"><span class="news-dot dot-red"></span>Awards & Honors</h3>
        <ul class="news-list">
          <li><span class="news-year">2026</span> Awarded the <strong>NSFC Excellent Young Scientists Fund (Overseas)</strong> and will join <strong>Wuhan University</strong> as an incoming professor.</li>
          <li><span class="news-year">2025</span> Shortlisted for the <strong>JC STEM Early Career Research Fellowship</strong>.</li>
          <li><span class="news-year">2024</span> Awarded the <strong>PolyU Distinguished Postdoctoral Fellowship</strong>.</li>
          <li><span class="news-year">2024</span> Received the <strong>2023 Hubei Province Science & Technology Progress Award</strong> for the project <em>Risk Prevention and Control of Artificial Ground Freezing Technique in Water-Rich Stratum</em> <a href="https://www.hubei.gov.cn/zfwj/ezf/202407/t20240726_5280385.shtml">[Link]</a>.</li>
          <li><span class="news-year">2023</span> Received the <strong>Academic Innovation Award</strong> from Wuhan University.</li>
          <li><span class="news-year">2021</span> Received the <strong>Excellence in Teaching Award</strong> from Wuhan University.</li>
          <li><span class="news-year">2020</span> Named one of <strong>Wuhan University’s Top 10 Academic Stars</strong> <a href="https://service.whu.edu.cn/info/1005/2179.htm">[Announcement]</a>.</li>
          <li><span class="news-year">2016</span> Awarded <strong>Top 10 Future Star Undergraduate</strong> by the China Water Resources Education Association <a href="https://sljzw.hhu.edu.cn/2019/0415/c11821a189595/page.htm">[Link]</a>.</li>
        </ul>
      </div>

      <div class="news-group">
        <h3 class="news-group-title"><span class="news-dot dot-blue"></span>Research & Publications</h3>
        <ul class="news-list">
          <li><span class="news-year">2026</span> Published <em>AGFNN</em>, a smart platform for uncertainty-aware prediction of freezing time in artificial ground freezing, in <em>Tunnelling and Underground Space Technology</em>.</li>
          <li><span class="news-year">2026</span> Published <em>AGF-PINN-HC</em>, a hard-constrained enhanced physics-informed neural network for multi-pipe heat transfer in artificial ground freezing, in <em>Canadian Geotechnical Journal</em>.</li>
          <li><span class="news-year">2025</span> Published <em>Relative ice saturation and unified elastoplastic modeling of frozen soils</em> in the <em>Journal of Geotechnical and Geoenvironmental Engineering</em> <a href="https://doi.org/10.1061/JGGEFK.GTENG-13437">[DOI]</a>.</li>
          <li><span class="news-year">2025</span> Published <em>Physics-informed neural networks for solving steady-state temperature field in artificial ground freezing</em> in the <em>Canadian Geotechnical Journal</em> <a href="https://doi.org/10.1139/cgj-2024-0650">[DOI]</a>.</li>
          <li><span class="news-year">2025</span> Published <em>State of the art of mechanical behaviors of frozen soils through experimental investigation</em> in <em>Cold Regions Science and Technology</em> <a href="https://doi.org/10.1016/j.coldregions.2025.104497">[DOI]</a>.</li>
        </ul>
      </div>

      <div class="news-group">
        <h3 class="news-group-title"><span class="news-dot dot-purple"></span>Funding</h3>
        <ul class="news-list">
          <li><span class="news-year">2025–2026</span> Awarded <strong>HK$841,040</strong> as PI for a PolyU project on thermo-hydro-mechanical-chemical coupling in hydrate-bearing sediments using physics-informed neural networks.</li>
          <li><span class="news-year">2025–2029</span> Participating in a <strong>HK$53.821 million</strong> Theme-based Research Scheme project on digital twins for coastal resilience under extreme storm surges in Hong Kong.</li>
          <li><span class="news-year">2024–2026</span> Participating in a <strong>HK$1.133 million</strong> GRF project on physics-informed multi-fidelity neural networks for intelligent rectification of shield machine attitude in layered soils.</li>
          <li><span class="news-year">2022</span> Received the <strong>Centrally Funded Postdoctoral Fellowship</strong> with funding of <strong>HK$763,555</strong> for thermo-hydro-mechanical modelling of artificial ground freezing.</li>
        </ul>
      </div>

      <div class="news-group">
        <h3 class="news-group-title"><span class="news-dot dot-green"></span>Academic Service</h3>
        <ul class="news-list">
          <li><span class="news-year">2025</span> Serving as Co-chair of Mini-Symposium 9: <em>Multiphysics Modeling of Geo-engineering and Geohazards</em> at <strong>IACMAG 2025</strong>, Hong Kong.</li>
          <li><span class="news-year">2024</span> Joined the <strong>Early-career Editorial Panel</strong> for the <em>European Journal of Soil Science</em> <a href="https://bsssjournals.onlinelibrary.wiley.com/hub/journal/13652389/editorialboard.html">[Link]</a>.</li>
          <li><span class="news-year">2024</span> Served as Session Chair at the <strong>12th National Conference on Engineering Geology</strong>, Shenzhen.</li>
          <li><span class="news-year">2023</span> Served as Secretary of the <strong>International Symposium on Innovations in Geotechnical Engineering towards Sustainability</strong> (IGES 2023).</li>
        </ul>
      </div>

    </div>
  </section>

  <div class="home-note">
    I welcome collaborations with researchers, students, and practitioners interested in geomechanics,
    computational modelling, uncertainty quantification, artificial intelligence, and resilient infrastructure.
  </div>

  <div class="visitor-map">
    <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=80afe5&w=270&t=tt&d=_xxky0Tv5mD5ZfcCUgylwlpQi4eAT7sya9k5lvdB0dU&co=ffffff&cmo=1a72b0&cmn=ff5353&ct=000000'></script>
  </div>

</div>
