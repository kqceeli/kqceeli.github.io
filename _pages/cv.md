---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-page {
  max-width: 980px;
  margin: 0 auto;
  color: #263238;
  line-height: 1.65;
  font-size: 0.98rem;
}

.cv-page * {
  box-sizing: border-box;
}

.cv-hero {
  padding: 2.2rem 2rem;
  margin-bottom: 2rem;
  border-radius: 18px;
  background: linear-gradient(135deg, #f7fbff 0%, #eef6fb 52%, #f9fbfc 100%);
  border: 1px solid #e2edf3;
}

.cv-hero h1 {
  margin: 0 0 0.45rem 0;
  font-size: 2.1rem;
  font-weight: 700;
  color: #17324d;
  letter-spacing: -0.02em;
}

.cv-subtitle {
  margin: 0 0 1rem 0;
  font-size: 1.05rem;
  color: #476274;
  font-weight: 500;
}

.cv-summary {
  max-width: 820px;
  margin: 0;
  color: #37474f;
  font-size: 0.98rem;
}

.cv-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1.25rem;
}

.cv-tag {
  display: inline-flex;
  align-items: center;
  padding: 0.35rem 0.75rem;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid #d8e7ef;
  color: #35566b;
  font-size: 0.82rem;
  font-weight: 600;
}

.cv-stats {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0.85rem;
  margin: 1.5rem 0 2.2rem 0;
}

.cv-stat {
  padding: 1.1rem 0.9rem;
  border-radius: 14px;
  background: #ffffff;
  border: 1px solid #e5edf1;
  text-align: center;
  box-shadow: 0 5px 18px rgba(38, 50, 56, 0.04);
}

.cv-stat-number {
  display: block;
  font-size: 1.55rem;
  line-height: 1.1;
  font-weight: 700;
  color: #1f5f8b;
}

.cv-stat-label {
  display: block;
  margin-top: 0.35rem;
  font-size: 0.78rem;
  color: #607d8b;
  font-weight: 600;
}

.cv-section {
  margin-bottom: 2.2rem;
}

.cv-section-title {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin: 0 0 1.1rem 0;
  font-size: 1.35rem;
  font-weight: 700;
  color: #17324d;
}

.cv-section-title::after {
  content: "";
  flex: 1;
  height: 1px;
  background: linear-gradient(to right, #c8dce8, transparent);
}

.cv-card {
  padding: 1.15rem 1.25rem;
  border-radius: 15px;
  background: #ffffff;
  border: 1px solid #e5edf1;
  box-shadow: 0 5px 18px rgba(38, 50, 56, 0.035);
  margin-bottom: 0.9rem;
}

.cv-card h3 {
  margin: 0 0 0.35rem 0;
  font-size: 1.02rem;
  color: #263238;
  font-weight: 700;
}

.cv-card p {
  margin: 0.18rem 0;
  color: #526772;
  font-size: 0.92rem;
}

.cv-meta {
  display: inline-block;
  margin-bottom: 0.35rem;
  font-size: 0.82rem;
  font-weight: 700;
  color: #1f5f8b;
}

.cv-timeline {
  position: relative;
  padding-left: 1.2rem;
}

.cv-timeline::before {
  content: "";
  position: absolute;
  top: 0.35rem;
  bottom: 0.35rem;
  left: 0.24rem;
  width: 2px;
  background: #d6e6ee;
}

.cv-timeline-item {
  position: relative;
  padding-left: 1.1rem;
  margin-bottom: 1rem;
}

.cv-timeline-item::before {
  content: "";
  position: absolute;
  top: 0.42rem;
  left: -0.06rem;
  width: 0.55rem;
  height: 0.55rem;
  border-radius: 50%;
  background: #2b7da8;
  box-shadow: 0 0 0 4px #eef6fb;
}

.cv-two-col {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 0.9rem;
}

.cv-highlight-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 0.9rem;
  margin-bottom: 1.2rem;
}

.cv-highlight {
  padding: 1rem 1.05rem;
  border-radius: 14px;
  background: #f8fbfd;
  border: 1px solid #dfeaf0;
}

.cv-highlight-year {
  display: inline-block;
  margin-bottom: 0.25rem;
  color: #1f5f8b;
  font-weight: 700;
  font-size: 0.82rem;
}

.cv-highlight-title {
  margin: 0;
  color: #263238;
  font-weight: 700;
  font-size: 0.95rem;
}

.cv-highlight-org {
  margin-top: 0.25rem;
  color: #607d8b;
  font-size: 0.84rem;
}

.cv-award-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.cv-award-list li {
  padding: 0.62rem 0;
  border-bottom: 1px solid #eef3f6;
  color: #455a64;
  font-size: 0.92rem;
}

.cv-award-list li:last-child {
  border-bottom: none;
}

.cv-award-year {
  display: inline-block;
  min-width: 4.7rem;
  color: #1f5f8b;
  font-weight: 700;
}

.cv-funding-card {
  padding: 1.25rem 1.35rem;
  border-radius: 16px;
  background: #ffffff;
  border: 1px solid #e2ebf0;
  box-shadow: 0 5px 18px rgba(38, 50, 56, 0.035);
  margin-bottom: 1rem;
}

.cv-funding-title {
  margin: 0 0 0.65rem 0;
  font-size: 1.02rem;
  font-weight: 700;
  color: #263238;
  line-height: 1.45;
}

.cv-funding-grid {
  display: grid;
  grid-template-columns: 120px 1fr;
  row-gap: 0.35rem;
  column-gap: 0.8rem;
  font-size: 0.9rem;
}

.cv-label {
  color: #607d8b;
  font-weight: 700;
}

.cv-value {
  color: #455a64;
}

.cv-role {
  display: inline-block;
  padding: 0.18rem 0.55rem;
  border-radius: 999px;
  background: #eef6fb;
  color: #1f5f8b;
  font-size: 0.78rem;
  font-weight: 700;
}

.cv-note {
  padding: 1rem 1.15rem;
  margin-top: 1.2rem;
  border-radius: 14px;
  background: #fbfcfd;
  border: 1px solid #e5edf1;
  color: #607d8b;
  font-size: 0.9rem;
}

@media screen and (max-width: 760px) {
  .cv-hero {
    padding: 1.5rem 1.2rem;
  }

  .cv-hero h1 {
    font-size: 1.65rem;
  }

  .cv-stats,
  .cv-two-col,
  .cv-highlight-grid {
    grid-template-columns: 1fr;
  }

  .cv-funding-grid {
    grid-template-columns: 1fr;
    row-gap: 0.15rem;
  }

  .cv-label {
    margin-top: 0.35rem;
  }
}
</style>

<div class="cv-page">

  <section class="cv-hero">
    <h1>Curriculum Vitae</h1>

    <p class="cv-subtitle">
      Kai-Qi Li · Incoming Professor, Wuhan University
    </p>

    <p class="cv-summary">
      My academic training and research experience span geotechnical engineering, hydraulic structure engineering,
      computational geomechanics, uncertainty quantification, and data-driven methods for complex geo-systems.
      My work aims to advance mechanics-informed and AI-enabled approaches for safer, more resilient, and more
      intelligent infrastructure systems.
    </p>

    <div class="cv-tags">
      <span class="cv-tag">Geotechnical Engineering</span>
      <span class="cv-tag">Computational Geomechanics</span>
      <span class="cv-tag">Uncertainty Quantification</span>
      <span class="cv-tag">AI for Geo-Systems</span>
      <span class="cv-tag">Infrastructure Resilience</span>
    </div>
  </section>

  <section class="cv-stats">
    <div class="cv-stat">
      <span class="cv-stat-number">3</span>
      <span class="cv-stat-label">Academic Institutions</span>
    </div>

    <div class="cv-stat">
      <span class="cv-stat-number">5</span>
      <span class="cv-stat-label">Research Projects</span>
    </div>

    <div class="cv-stat">
      <span class="cv-stat-number">15+</span>
      <span class="cv-stat-label">Selected Awards</span>
    </div>

    <div class="cv-stat">
      <span class="cv-stat-number">PI</span>
      <span class="cv-stat-label">Independent Research Funding</span>
    </div>
  </section>

  <section class="cv-section">
    <h2 class="cv-section-title">Academic Appointments</h2>

    <div class="cv-timeline">

      <div class="cv-timeline-item">
        <div class="cv-card">
          <span class="cv-meta">Incoming</span>
          <h3>Professor</h3>
          <p>School of Water Resources and Hydropower Engineering, Wuhan University</p>
        </div>
      </div>

      <div class="cv-timeline-item">
        <div class="cv-card">
          <span class="cv-meta">2022–Present</span>
          <h3>Postdoctoral Fellow</h3>
          <p>The Hong Kong Polytechnic University</p>
        </div>
      </div>

    </div>
  </section>

  <section class="cv-section">
    <h2 class="cv-section-title">Education</h2>

    <div class="cv-timeline">

      <div class="cv-timeline-item">
        <div class="cv-card">
          <span class="cv-meta">2017–2022</span>
          <h3>Ph.D. in Hydraulic Structure Engineering</h3>
          <p>Wuhan University, China</p>
        </div>
      </div>

      <div class="cv-timeline-item">
        <div class="cv-card">
          <span class="cv-meta">2021–2022</span>
          <h3>Visiting Ph.D. Student in Geotechnical Engineering</h3>
          <p>National University of Singapore, Singapore</p>
        </div>
      </div>

      <div class="cv-timeline-item">
        <div class="cv-card">
          <span class="cv-meta">2013–2017</span>
          <h3>B.E. in Water Resources and Hydropower Engineering</h3>
          <p>Northwest A&amp;F University, China</p>
        </div>
      </div>

    </div>
  </section>

  <section class="cv-section">
    <h2 class="cv-section-title">Selected Honors and Awards</h2>

    <div class="cv-highlight-grid">

      <div class="cv-highlight">
        <span class="cv-highlight-year">2024</span>
        <p class="cv-highlight-title">PolyU Distinguished Postdoctoral Fellowship</p>
        <div class="cv-highlight-org">The Hong Kong Polytechnic University</div>
      </div>

      <div class="cv-highlight">
        <span class="cv-highlight-year">2024</span>
        <p class="cv-highlight-title">Hubei Provincial Science and Technology Progress Award</p>
        <div class="cv-highlight-org">Hubei Provincial People's Government, China</div>
      </div>

      <div class="cv-highlight">
        <span class="cv-highlight-year">2020</span>
        <p class="cv-highlight-title">Top 10 Academic Star</p>
        <div class="cv-highlight-org">Wuhan University · University-wide, only 10 recipients</div>
      </div>

      <div class="cv-highlight">
        <span class="cv-highlight-year">2016</span>
        <p class="cv-highlight-title">Top 10 Future Star Undergraduate</p>
        <div class="cv-highlight-org">Ministry of Education of China · Nationwide, only 10 recipients</div>
      </div>

    </div>

    <div class="cv-card">
      <ul class="cv-award-list">
        <li><span class="cv-award-year">10/2024</span>PolyU Distinguished Postdoctoral Fellowship, The Hong Kong Polytechnic University</li>
        <li><span class="cv-award-year">03/2024</span>Hubei Provincial Science and Technology Progress Award, Hubei Provincial People's Government, China</li>
        <li><span class="cv-award-year">12/2023</span>Academic Innovation Award, Wuhan University</li>
        <li><span class="cv-award-year">10/2022</span>Centrally Funded Postdoctoral Fellowship, The Hong Kong Polytechnic University</li>
        <li><span class="cv-award-year">06/2022</span>Outstanding Graduate Award, Wuhan University</li>
        <li><span class="cv-award-year">03/2021</span>Excellence in Teaching Award, Wuhan University</li>
        <li><span class="cv-award-year">10/2020</span>Top 10 Academic Star, Wuhan University, university-wide, only 10 recipients</li>
        <li><span class="cv-award-year">12/2019</span>YuGang &amp; SongXiao Scholarship, Wuhan University, top 1%, university-wide</li>
        <li><span class="cv-award-year">10/2019</span>Second Prize, Graduate Academic Report Competition, 10th National Youth Conference on Geomechanics and Geotechnical Engineering</li>
        <li><span class="cv-award-year">06/2019</span>First Prize, 12th Civil Engineering and Mechanics Graduate Academic Forum, Wuhan University</li>
        <li><span class="cv-award-year">04/2019</span>Second Prize, Doctoral Academic Forum, Tsinghua University</li>
        <li><span class="cv-award-year">12/2018</span>Excellent Student Cadre, Wuhan University</li>
        <li><span class="cv-award-year">12/2018</span>Outstanding Graduate Student, Wuhan University</li>
        <li><span class="cv-award-year">09/2018</span>First Class Scholarship, Wuhan University</li>
        <li><span class="cv-award-year">12/2017</span>Excellent New Student Award, Wuhan University</li>
        <li><span class="cv-award-year">12/2016</span>National Scholarship, Ministry of Education of the People's Republic of China</li>
        <li><span class="cv-award-year">07/2016</span>Top 10 Future Star Undergraduate, Ministry of Education of the People's Republic of China, nationwide, only 10 recipients</li>
      </ul>
    </div>
  </section>

  <section class="cv-section">
    <h2 class="cv-section-title">Research Funding</h2>

    <div class="cv-funding-card">
      <h3 class="cv-funding-title">
        Thermo-hydro-mechanical modelling for artificial ground freezing technique
      </h3>

      <div class="cv-funding-grid">
        <div class="cv-label">Period</div>
        <div class="cv-value">01/2023 – 12/2024</div>

        <div class="cv-label">Amount</div>
        <div class="cv-value">HK$ 763,555</div>

        <div class="cv-label">Funded by</div>
        <div class="cv-value">The Hong Kong Polytechnic University</div>

        <div class="cv-label">Role</div>
        <div class="cv-value"><span class="cv-role">Principal Investigator</span></div>
      </div>
    </div>

    <div class="cv-funding-card">
      <h3 class="cv-funding-title">
        Physics-informed multi-fidelity neural network approach for intelligent rectification of shield machine attitude in layered soils
      </h3>

      <div class="cv-funding-grid">
        <div class="cv-label">Period</div>
        <div class="cv-value">01/2024 – 12/2026</div>

        <div class="cv-label">Amount</div>
        <div class="cv-value">HK$ 1,132,781</div>

        <div class="cv-label">Funded by</div>
        <div class="cv-value">Research Grants Council of Hong Kong, General Research Fund</div>

        <div class="cv-label">Role</div>
        <div class="cv-value"><span class="cv-role">Main Participant</span></div>
      </div>
    </div>

    <div class="cv-funding-card">
      <h3 class="cv-funding-title">
        Multi-physics coupling mechanism of deep-sea pipeline and soft marine organic deposits interaction considering time and temperature effects
      </h3>

      <div class="cv-funding-grid">
        <div class="cv-label">Period</div>
        <div class="cv-value">01/2021 – 12/2024</div>

        <div class="cv-label">Amount</div>
        <div class="cv-value">HK$ 1,154,954</div>

        <div class="cv-label">Funded by</div>
        <div class="cv-value">Research Grants Council of Hong Kong, NSFC/RGC Joint Research Scheme</div>

        <div class="cv-label">Role</div>
        <div class="cv-value"><span class="cv-role">Main Participant</span></div>
      </div>
    </div>

    <div class="cv-funding-card">
      <h3 class="cv-funding-title">
        Seepage failure mechanism and risk control of earth-rockfill dams considering spatial variability of geomaterials
      </h3>

      <div class="cv-funding-grid">
        <div class="cv-label">Period</div>
        <div class="cv-value">09/2020 – 01/2022</div>

        <div class="cv-label">Amount</div>
        <div class="cv-value">CNY 580,000</div>

        <div class="cv-label">Funded by</div>
        <div class="cv-value">National Natural Science Foundation of China</div>

        <div class="cv-label">Role</div>
        <div class="cv-value"><span class="cv-role">Co-Investigator</span></div>
      </div>
    </div>

    <div class="cv-funding-card">
      <h3 class="cv-funding-title">
        Risk assessment for tunnel-induced subsidence under complex geological conditions using big data analysis
      </h3>

      <div class="cv-funding-grid">
        <div class="cv-label">Period</div>
        <div class="cv-value">01/2018 – 07/2021</div>

        <div class="cv-label">Amount</div>
        <div class="cv-value">CNY 4,100,000</div>

        <div class="cv-label">Funded by</div>
        <div class="cv-value">NRF-NSFC 3rd Joint Research Grant, Earth Science</div>

        <div class="cv-label">Role</div>
        <div class="cv-value"><span class="cv-role">Co-Investigator</span></div>
      </div>
    </div>

  </section>

  <div class="cv-note">
    A full publication list, teaching and supervision record, and professional service activities are available on the corresponding pages of this website.
  </div>

</div>
