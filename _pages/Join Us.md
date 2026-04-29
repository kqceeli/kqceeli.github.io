---
title: "Join Us"
layout: page
permalink: /join-us/
---

<style>
.join-page {
  --ink: #111827;
  --muted: #5b6472;
  --soft: #f7f7f4;
  --line: #e7e5df;
  --accent: #0f766e;
  --accent-dark: #115e59;
  --warm: #b45309;

  max-width: 1040px;
  margin: 0 auto;
  padding: 42px 22px 80px;
  color: var(--ink);
  font-size: 16px;
  line-height: 1.7;
}

.join-page * {
  box-sizing: border-box;
}

.join-hero {
  display: grid;
  grid-template-columns: 1.35fr 0.65fr;
  gap: 36px;
  align-items: center;
  padding: 54px 48px;
  border-radius: 28px;
  background:
    linear-gradient(135deg, rgba(15, 118, 110, 0.08), rgba(180, 83, 9, 0.06)),
    #fbfaf7;
  border: 1px solid var(--line);
}

.join-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 18px;
  color: var(--accent-dark);
  font-size: 13px;
  font-weight: 800;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.join-eyebrow::before {
  content: "";
  width: 7px;
  height: 7px;
  border-radius: 50%;
  background: var(--accent);
}

.join-hero h1 {
  margin: 0 0 18px;
  max-width: 760px;
  font-size: 46px;
  line-height: 1.08;
  letter-spacing: -0.045em;
  color: #111827;
}

.join-hero p {
  margin: 0;
  max-width: 760px;
  color: var(--muted);
  font-size: 18px;
  line-height: 1.75;
}

.join-hero strong {
  color: var(--ink);
}

.hero-card {
  padding: 28px;
  border-radius: 22px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 16px 40px rgba(17, 24, 39, 0.06);
}

.hero-card-title {
  margin: 0 0 14px;
  color: var(--accent-dark);
  font-size: 15px;
  font-weight: 900;
  letter-spacing: 0.04em;
  text-transform: uppercase;
}

.hero-list {
  margin: 0;
  padding: 0;
  list-style: none;
}

.hero-list li {
  padding: 10px 0;
  border-top: 1px solid #f0eee8;
  color: #374151;
  font-size: 15.5px;
}

.hero-list li:first-child {
  border-top: none;
}

.join-section {
  margin-top: 58px;
}

.section-head {
  display: flex;
  align-items: flex-end;
  justify-content: space-between;
  gap: 24px;
  margin-bottom: 24px;
}

.section-head h2 {
  margin: 0;
  color: var(--ink);
  font-size: 30px;
  line-height: 1.25;
  letter-spacing: -0.035em;
}

.section-head p {
  margin: 0;
  max-width: 560px;
  color: var(--muted);
  font-size: 16px;
}

.quote {
  padding: 28px 30px;
  border-radius: 24px;
  background: #111827;
  color: #f9fafb;
  font-size: 22px;
  line-height: 1.55;
  font-weight: 750;
  letter-spacing: -0.015em;
}

.quote span {
  color: #a7f3d0;
}

.card-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 18px;
}

.card {
  padding: 24px;
  border-radius: 22px;
  background: #ffffff;
  border: 1px solid var(--line);
  box-shadow: 0 12px 32px rgba(17, 24, 39, 0.045);
}

.card h3 {
  margin: 0 0 10px;
  color: #1f2937;
  font-size: 18px;
  line-height: 1.35;
}

.card p {
  margin: 0;
  color: var(--muted);
  font-size: 15.5px;
  line-height: 1.65;
}

.research-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
}

.research-item {
  padding: 18px 20px;
  border-radius: 18px;
  background: var(--soft);
  border: 1px solid var(--line);
}

.research-item strong {
  display: block;
  margin-bottom: 6px;
  color: #1f2937;
  font-size: 16px;
}

.research-item span {
  color: var(--muted);
  font-size: 15px;
}

.pill-row {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.pill {
  display: inline-flex;
  align-items: center;
  padding: 9px 14px;
  border-radius: 999px;
  background: #ffffff;
  border: 1px solid var(--line);
  color: #374151;
  font-size: 14.5px;
  font-weight: 700;
}

.pill.highlight {
  background: rgba(15, 118, 110, 0.08);
  border-color: rgba(15, 118, 110, 0.22);
  color: var(--accent-dark);
}

.apply-box {
  display: grid;
  grid-template-columns: 0.9fr 1.1fr;
  gap: 0;
  overflow: hidden;
  border-radius: 26px;
  border: 1px solid var(--line);
  background: #ffffff;
  box-shadow: 0 16px 42px rgba(17, 24, 39, 0.06);
}

.apply-left {
  padding: 34px;
  background:
    linear-gradient(135deg, rgba(15, 118, 110, 0.10), rgba(180, 83, 9, 0.08)),
    #fbfaf7;
}

.apply-left h3 {
  margin: 0 0 12px;
  font-size: 25px;
  letter-spacing: -0.03em;
}

.apply-left p {
  margin: 0;
  color: var(--muted);
}

.email-link {
  display: inline-flex;
  margin-top: 22px;
  color: var(--accent-dark);
  font-size: 22px;
  font-weight: 900;
  text-decoration: none;
}

.email-link:hover {
  text-decoration: underline;
}

.apply-right {
  padding: 34px;
}

.apply-right h4 {
  margin: 0 0 12px;
  font-size: 17px;
  color: #111827;
}

.apply-list {
  margin: 0 0 24px;
  padding-left: 20px;
  color: var(--muted);
}

.apply-list li {
  margin: 7px 0;
}

.subject {
  padding: 14px 16px;
  border-radius: 14px;
  background: #f7f7f4;
  border: 1px solid var(--line);
  color: #374151;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  font-size: 14px;
  overflow-x: auto;
}

.final-note {
  margin-top: 54px;
  padding: 30px 34px;
  border-radius: 24px;
  background: #111827;
  color: #f9fafb;
  font-size: 18px;
  line-height: 1.75;
}

.final-note strong {
  color: #a7f3d0;
}

@media (max-width: 900px) {
  .join-hero,
  .apply-box {
    grid-template-columns: 1fr;
  }

  .card-grid,
  .research-list {
    grid-template-columns: 1fr;
  }

  .section-head {
    display: block;
  }

  .section-head p {
    margin-top: 10px;
  }

  .join-hero h1 {
    font-size: 38px;
  }
}

@media (max-width: 560px) {
  .join-page {
    padding: 28px 16px 64px;
  }

  .join-hero {
    padding: 34px 24px;
    border-radius: 22px;
  }

  .join-hero h1 {
    font-size: 32px;
  }

  .quote {
    font-size: 19px;
  }

  .apply-left,
  .apply-right {
    padding: 26px 22px;
  }

  .email-link {
    font-size: 19px;
  }
}
</style>

<div class="join-page">

  <section class="join-hero">
    <div>
      <div class="join-eyebrow">Join the Group</div>

      <h1>Geomechanics, Computation, and AI</h1>

      <p>
        I am joining the <strong>School of Water Resources and Hydropower Engineering,
        Wuhan University</strong>, where I am building a new research group at the
        intersection of <strong>geomechanics, computational mechanics, uncertainty
        quantification, and artificial intelligence</strong>.
      </p>
    </div>

    <div class="hero-card">
      <div class="hero-card-title">We focus on</div>
      <ul class="hero-list">
        <li>Physics-informed modelling</li>
        <li>Computational geomechanics</li>
        <li>Uncertainty and reliability</li>
        <li>AI for engineering science</li>
      </ul>
    </div>
  </section>

  <section class="join-section">
    <div class="quote">
      We combine <span>physics, computation, uncertainty, and AI</span> to understand,
      predict, and design safer geo-infrastructure.
    </div>
  </section>

  <section class="join-section">
    <div class="section-head">
      <h2>Research Directions</h2>
      <p>
        Current and future projects are organized around the following themes.
        Student-led ideas are very welcome.
      </p>
    </div>

    <div class="research-list">
      <div class="research-item">
        <strong>Frozen-Ground and Cold-Region Geomechanics</strong>
        <span>Frozen soils, artificial ground freezing, permafrost, freeze–thaw processes.</span>
      </div>

      <div class="research-item">
        <strong>Multi-Physics Coupling in Geomaterials</strong>
        <span>Thermal–hydraulic–mechanical coupling, phase change, porous media.</span>
      </div>

      <div class="research-item">
        <strong>Multi-Scale Modelling</strong>
        <span>Micromechanics, DEM, FEM–DEM, constitutive modelling, microstructure.</span>
      </div>

      <div class="research-item">
        <strong>Risk, Reliability, and Uncertainty</strong>
        <span>Spatial variability, random fields, Bayesian updating, decision-making.</span>
      </div>

      <div class="research-item">
        <strong>AI-Enabled Computational Mechanics</strong>
        <span>PINNs, neural operators, surrogate models, differentiable simulation.</span>
      </div>

      <div class="research-item">
        <strong>LLMs for Engineering Science</strong>
        <span>AI agents, knowledge extraction, engineering reasoning, automated workflows.</span>
      </div>
    </div>
  </section>

  <section class="join-section">
    <div class="section-head">
      <h2>Open Positions</h2>
      <p>
        I welcome motivated students and researchers from diverse academic backgrounds.
      </p>
    </div>

    <div class="pill-row">
      <span class="pill highlight">Ph.D. Students</span>
      <span class="pill highlight">Master’s Students</span>
      <span class="pill">Postdoctoral Researchers</span>
      <span class="pill">Research Assistants</span>
      <span class="pill">Visiting Students</span>
      <span class="pill">Visiting Scholars</span>
    </div>
  </section>

  <section class="join-section">
    <div class="section-head">
      <h2>Who I Am Looking For</h2>
      <p>
        You do not need to fit every category. Curiosity, rigor, and the willingness
        to learn matter most.
      </p>
    </div>

    <div class="card-grid">
      <div class="card">
        <h3>Strong Motivation</h3>
        <p>
          You are curious about scientific problems and willing to work deeply on them.
        </p>
      </div>

      <div class="card">
        <h3>Technical Foundation</h3>
        <p>
          Backgrounds in mechanics, engineering, mathematics, computing, AI, or earth science are welcome.
        </p>
      </div>

      <div class="card">
        <h3>Research Mindset</h3>
        <p>
          You value rigor, independence, clear communication, and academic integrity.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <div class="section-head">
      <h2>Group Culture</h2>
      <p>
        The group aims to be ambitious, supportive, international, and intellectually open.
      </p>
    </div>

    <div class="card-grid">
      <div class="card">
        <h3>High Standards</h3>
        <p>
          We aim for rigorous research with international visibility and long-term value.
        </p>
      </div>

      <div class="card">
        <h3>Serious Mentorship</h3>
        <p>
          Students will receive regular research discussions, technical guidance, and writing feedback.
        </p>
      </div>

      <div class="card">
        <h3>Academic Growth</h3>
        <p>
          You will be encouraged to develop your own ideas and build your research identity.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <div class="section-head">
      <h2>How to Apply</h2>
      <p>
        Please send a concise email introducing your background, interests, and the position you are applying for.
      </p>
    </div>

    <div class="apply-box">
      <div class="apply-left">
        <h3>Get in touch</h3>
        <p>
          If you are excited by interdisciplinary research in geomechanics,
          computation, uncertainty, and AI, I would be happy to hear from you.
        </p>

        <a class="email-link" href="mailto:kqceeli@163.com">kqceeli@163.com</a>
      </div>

      <div class="apply-right">
        <h4>Email subject</h4>
        <div class="subject">[Join Us] Your Name – Institution – Position</div>

        <br>

        <h4>Suggested materials</h4>
        <ul class="apply-list">
          <li>Curriculum vitae</li>
          <li>Brief statement of research interests</li>
          <li>Representative work, if available</li>
          <li>Names and contacts of referees, if available</li>
        </ul>

        <p style="margin:0;color:#5b6472;font-size:15px;">
          Publications are not required for early-stage students. Strong coursework,
          coding projects, experimental experience, or original ideas are also valuable.
        </p>
      </div>
    </div>
  </section>

  <div class="final-note">
    Great research requires both <strong>imagination and discipline</strong>.
    If you want to help build a new research group from the beginning,
    please get in touch.
    <br><br>
    <strong>Let us build something meaningful together.</strong>
  </div>

</div>
