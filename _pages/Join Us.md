---
title: "Join Us"
layout: page
permalink: /join-us/
---

<style>
.join-page {
  max-width: 1100px;
  margin: 0 auto;
  padding: 36px 22px 76px;
  color: #111827;
  font-size: 16px;
  line-height: 1.7;
}

.join-page * {
  box-sizing: border-box;
}

.join-hero {
  position: relative;
  overflow: hidden;
  border-radius: 28px;
  padding: 62px 56px;
  margin-bottom: 54px;
  color: #ffffff;
  background:
    radial-gradient(circle at 10% 20%, rgba(59, 130, 246, 0.46), transparent 30%),
    radial-gradient(circle at 88% 18%, rgba(14, 165, 233, 0.38), transparent 32%),
    linear-gradient(135deg, #020617 0%, #0f172a 42%, #1e3a8a 76%, #075985 100%);
  box-shadow: 0 26px 64px rgba(15, 23, 42, 0.24);
}

.join-hero::after {
  content: "";
  position: absolute;
  right: -120px;
  bottom: -120px;
  width: 340px;
  height: 340px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.08);
}

.join-eyebrow {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin-bottom: 20px;
  padding: 7px 14px;
  border: 1px solid rgba(219, 234, 254, 0.36);
  border-radius: 999px;
  color: #dbeafe;
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
  background: #38bdf8;
}

.join-hero h1 {
  max-width: 880px;
  margin: 0 0 20px;
  color: #ffffff;
  font-size: 48px;
  line-height: 1.08;
  letter-spacing: -0.045em;
}

.join-hero .lead {
  max-width: 880px;
  margin: 0;
  color: #e0f2fe;
  font-size: 19px;
  line-height: 1.75;
}

.join-hero .lead strong {
  color: #ffffff;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 30px;
}

.hero-pill {
  display: inline-flex;
  align-items: center;
  padding: 9px 15px;
  border-radius: 999px;
  background: rgba(255, 255, 255, 0.10);
  border: 1px solid rgba(219, 234, 254, 0.25);
  color: #eff6ff;
  font-size: 14px;
  font-weight: 700;
}

.join-section {
  margin-top: 56px;
}

.join-section-title {
  margin: 0 0 22px;
  color: #0f172a;
  font-size: 29px;
  line-height: 1.25;
  letter-spacing: -0.03em;
}

.join-section-title::after {
  content: "";
  display: block;
  width: 54px;
  height: 4px;
  margin-top: 12px;
  border-radius: 999px;
  background: linear-gradient(90deg, #2563eb, #06b6d4);
}

.join-intro {
  max-width: 900px;
  color: #4b5563;
  font-size: 17px;
}

.join-intro p {
  margin: 0 0 14px;
}

.join-quote {
  margin: 28px 0;
  padding: 25px 30px;
  border-left: 5px solid #2563eb;
  border-radius: 0 20px 20px 0;
  background: linear-gradient(135deg, #f8fafc, #ffffff);
  color: #0f172a;
  font-size: 21px;
  font-weight: 800;
  line-height: 1.55;
  box-shadow: 0 12px 30px rgba(15, 23, 42, 0.045);
}

.join-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 20px;
  margin-top: 26px;
}

.join-grid.three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.join-card {
  position: relative;
  min-height: 100%;
  padding: 26px 26px 24px;
  border: 1px solid #e5e7eb;
  border-radius: 22px;
  background: #ffffff;
  box-shadow: 0 14px 36px rgba(15, 23, 42, 0.055);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.join-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 20px 46px rgba(37, 99, 235, 0.12);
}

.join-card h3 {
  margin: 0 0 10px;
  color: #1e3a8a;
  font-size: 18px;
  line-height: 1.35;
  letter-spacing: -0.01em;
}

.join-card p {
  margin: 0;
  color: #4b5563;
  font-size: 15.5px;
  line-height: 1.65;
}

.philosophy-card {
  padding: 24px 25px;
}

.philosophy-card p {
  font-size: 15.5px;
}

.direction-card {
  padding: 25px 25px 23px;
}

.direction-top {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 14px;
}

.direction-number {
  display: inline-flex;
  flex: 0 0 auto;
  align-items: center;
  justify-content: center;
  width: 34px;
  height: 34px;
  border-radius: 50%;
  background: #eff6ff;
  color: #1d4ed8;
  font-weight: 900;
  font-size: 13px;
}

.direction-card h3 {
  margin: 0;
}

.keyword-row {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 16px;
}

.keyword {
  display: inline-flex;
  align-items: center;
  padding: 6px 10px;
  border-radius: 999px;
  background: #f1f5f9;
  color: #334155;
  font-size: 13px;
  font-weight: 700;
  line-height: 1.2;
}

.keyword.blue {
  background: #eff6ff;
  color: #1d4ed8;
}

.join-highlight {
  margin: 30px 0 0;
  padding: 24px 27px;
  border: 1px solid #bae6fd;
  border-radius: 22px;
  background: linear-gradient(135deg, #f0f9ff, #ffffff);
  color: #0f172a;
  font-size: 16.5px;
  line-height: 1.7;
}

.join-highlight strong {
  color: #075985;
}

.position-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 11px;
  margin-top: 22px;
}

.position-pills span {
  display: inline-flex;
  align-items: center;
  padding: 9px 15px;
  border-radius: 999px;
  background: #eff6ff;
  color: #1e40af;
  font-size: 14px;
  font-weight: 800;
}

.profile-list {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 14px;
  margin-top: 24px;
}

.profile-item {
  padding: 17px 19px;
  border-radius: 16px;
  background: #f8fafc;
  border: 1px solid #e5e7eb;
  color: #374151;
  font-size: 15.5px;
  line-height: 1.55;
}

.profile-item strong {
  color: #1e3a8a;
}

.apply-panel {
  margin-top: 28px;
  overflow: hidden;
  border-radius: 26px;
  background: #0f172a;
  box-shadow: 0 24px 58px rgba(15, 23, 42, 0.20);
}

.apply-header {
  padding: 32px 34px 24px;
  color: #ffffff;
  background:
    radial-gradient(circle at 12% 20%, rgba(59, 130, 246, 0.24), transparent 32%),
    linear-gradient(135deg, #0f172a, #111827);
}

.apply-header h3 {
  margin: 0 0 10px;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: -0.02em;
}

.apply-header p {
  margin: 0;
  color: #cbd5e1;
  font-size: 16px;
}

.apply-content {
  padding: 30px 34px 34px;
}

.apply-block {
  margin-bottom: 28px;
}

.apply-block:last-child {
  margin-bottom: 0;
}

.apply-label {
  margin: 0 0 13px;
  color: #ffffff;
  font-size: 18px;
  font-weight: 850;
}

.subject-line {
  margin: 12px 0 0;
  padding: 16px 18px;
  border-radius: 15px;
  background: #1e293b;
  color: #ffffff;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace;
  font-size: 14.5px;
  font-weight: 700;
  overflow-x: auto;
  border: 1px solid rgba(148, 163, 184, 0.22);
}

.apply-note {
  margin: 12px 0 0;
  color: #cbd5e1;
  font-size: 15.5px;
  line-height: 1.7;
}

.material-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 12px;
  margin-top: 14px;
}

.material-card {
  display: flex;
  gap: 12px;
  align-items: flex-start;
  padding: 16px 17px;
  border-radius: 16px;
  background: #ffffff;
  color: #1f2937;
  border: 1px solid rgba(226, 232, 240, 0.95);
}

.material-check {
  display: inline-flex;
  flex: 0 0 auto;
  align-items: center;
  justify-content: center;
  width: 23px;
  height: 23px;
  margin-top: 1px;
  border-radius: 50%;
  background: #eff6ff;
  color: #2563eb;
  font-size: 14px;
  font-weight: 900;
}

.material-card strong {
  display: block;
  margin-bottom: 3px;
  color: #0f172a;
  font-size: 15.5px;
}

.material-card span {
  display: block;
  color: #64748b;
  font-size: 14px;
  line-height: 1.45;
}

.email-link {
  display: inline-flex;
  align-items: center;
  margin-top: 8px;
  color: #93c5fd;
  font-size: 23px;
  font-weight: 900;
  text-decoration: none;
}

.email-link:hover {
  color: #bfdbfe;
  text-decoration: underline;
}

.final-note {
  margin-top: 48px;
  padding: 32px 34px;
  border-radius: 26px;
  background:
    linear-gradient(135deg, rgba(37, 99, 235, 0.08), rgba(6, 182, 212, 0.08)),
    #ffffff;
  border: 1px solid #dbeafe;
  color: #1f2937;
  font-size: 18px;
  line-height: 1.75;
}

.final-note strong {
  color: #1d4ed8;
}

@media (max-width: 960px) {
  .join-grid,
  .join-grid.three,
  .profile-list,
  .material-grid {
    grid-template-columns: 1fr;
  }

  .join-hero {
    padding: 46px 34px;
  }

  .join-hero h1 {
    font-size: 38px;
  }

  .join-hero .lead {
    font-size: 17px;
  }
}

@media (max-width: 560px) {
  .join-page {
    padding: 24px 16px 58px;
  }

  .join-hero {
    border-radius: 22px;
    padding: 36px 25px;
  }

  .join-hero h1 {
    font-size: 32px;
  }

  .join-section-title {
    font-size: 25px;
  }

  .join-card {
    padding: 22px;
  }

  .apply-header,
  .apply-content {
    padding-left: 24px;
    padding-right: 24px;
  }

  .email-link {
    font-size: 20px;
  }
}
</style>

<div class="join-page">

  <section class="join-hero">
    <div class="join-eyebrow">Join the Group</div>

    <h1>Geomechanics, Computation, and Artificial Intelligence</h1>

    <p class="lead">
      I am joining the <strong>School of Water Resources and Hydropower Engineering, Wuhan University</strong>,
      where I am building a new research group at the frontier of
      <strong>geomechanics, computational mechanics, uncertainty quantification, and artificial intelligence</strong>.
    </p>

    <div class="hero-actions">
      <span class="hero-pill">World-class research ambition</span>
      <span class="hero-pill">Physics-informed AI</span>
      <span class="hero-pill">Computational geomechanics</span>
      <span class="hero-pill">Risk and reliability</span>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Vision</h2>

    <div class="join-intro">
      <p>
        Our goal is to build an internationally leading research group that advances fundamental geomechanics
        and develops next-generation computational tools for complex engineering systems.
      </p>
    </div>

    <div class="join-quote">
      We integrate physics, computation, uncertainty, and AI to understand, predict, and design safer geo-infrastructure.
    </div>

    <div class="join-intro">
      <p>
        We welcome students and researchers who are curious, disciplined, ambitious, and willing to work across disciplinary boundaries.
      </p>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Research Philosophy</h2>

    <div class="join-grid">
      <div class="join-card philosophy-card">
        <h3>Physics First, Data Smart</h3>
        <p>
          Models should respect mechanics, while learning efficiently from experiments, simulations, and field data.
        </p>
      </div>

      <div class="join-card philosophy-card">
        <h3>Uncertainty as Information</h3>
        <p>
          Geological variability and limited data are not obstacles only; they are central parts of engineering decision-making.
        </p>
      </div>

      <div class="join-card philosophy-card">
        <h3>AI for Scientific Discovery</h3>
        <p>
          We use AI to discover patterns, accelerate simulation, infer hidden variables, and support interpretable mechanics.
        </p>
      </div>

      <div class="join-card philosophy-card">
        <h3>Theory–Simulation–Experiment Loop</h3>
        <p>
          Strong research should connect rigorous theory, numerical modelling, laboratory evidence, and field observations.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Research Directions</h2>

    <div class="join-intro">
      <p>
        Current and future projects include the following interconnected directions.
      </p>
    </div>

    <div class="join-grid">
      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">01</div>
          <h3>Frozen-Ground and Cold-Region Geomechanics</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">Frozen soils</span>
          <span class="keyword">Artificial ground freezing</span>
          <span class="keyword">Permafrost</span>
          <span class="keyword">Freeze–thaw</span>
          <span class="keyword">Cold-region infrastructure</span>
        </div>
      </div>

      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">02</div>
          <h3>Multi-Physics Coupling in Geomaterials</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">THMC coupling</span>
          <span class="keyword">Phase change</span>
          <span class="keyword">Porous media</span>
          <span class="keyword">Hydropower dams</span>
          <span class="keyword">Underground infrastructure</span>
        </div>
      </div>

      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">03</div>
          <h3>Multi-Scale Modelling of Geomaterials</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">Micromechanics</span>
          <span class="keyword">DEM</span>
          <span class="keyword">FEM–DEM</span>
          <span class="keyword">Constitutive modelling</span>
          <span class="keyword">Microstructure</span>
        </div>
      </div>

      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">04</div>
          <h3>Geotechnical Risk and Reliability</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">Spatial variability</span>
          <span class="keyword">Random fields</span>
          <span class="keyword">Bayesian updating</span>
          <span class="keyword">Reliability analysis</span>
          <span class="keyword">Decision-making</span>
        </div>
      </div>

      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">05</div>
          <h3>AI-Enabled Computational Mechanics</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">PINNs</span>
          <span class="keyword">Neural operators</span>
          <span class="keyword">Differentiable simulation</span>
          <span class="keyword">Surrogate modelling</span>
          <span class="keyword">Scientific ML</span>
        </div>
      </div>

      <div class="join-card direction-card">
        <div class="direction-top">
          <div class="direction-number">06</div>
          <h3>Large Language Models for Engineering Science</h3>
        </div>
        <div class="keyword-row">
          <span class="keyword blue">LLM agents</span>
          <span class="keyword">Engineering reasoning</span>
          <span class="keyword">Knowledge extraction</span>
          <span class="keyword">Automated workflows</span>
          <span class="keyword">AI copilots</span>
        </div>
      </div>
    </div>

    <div class="join-highlight">
      <strong>Student-led ideas are strongly encouraged.</strong>
      If you have a sharp question, a bold idea, or a technical skill that can open a new direction,
      I would be very happy to hear from you.
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Open Positions</h2>

    <div class="join-intro">
      <p>
        I am actively recruiting motivated researchers at different career stages.
      </p>
    </div>

    <div class="position-pills">
      <span>Ph.D. Students</span>
      <span>Master’s Students</span>
      <span>Research Assistants</span>
      <span>Postdoctoral Researchers</span>
      <span>Visiting Students</span>
      <span>Visiting Scholars</span>
    </div>

    <div class="profile-list">
      <div class="profile-item">
        <strong>Engineering:</strong> civil, geotechnical, hydraulic, offshore, underground, and environmental engineering.
      </div>

      <div class="profile-item">
        <strong>Mechanics and Mathematics:</strong> solid mechanics, computational mechanics, numerical methods, statistics, and uncertainty quantification.
      </div>

      <div class="profile-item">
        <strong>Earth and Physical Sciences:</strong> geology, geophysics, physics, materials science, porous media, and cryosphere science.
      </div>

      <div class="profile-item">
        <strong>Computing and AI:</strong> scientific computing, machine learning, data science, LLMs, AI agents, and foundation models.
      </div>
    </div>

    <div class="join-highlight">
      Applications are welcome regardless of nationality, institution, gender, or previous research field.
      What matters most is curiosity, rigor, motivation, and the potential to grow.
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">What I Look For</h2>

    <div class="join-grid three">
      <div class="join-card">
        <h3>Curiosity</h3>
        <p>
          You ask deep questions and want to understand how complex systems really work.
        </p>
      </div>

      <div class="join-card">
        <h3>Rigor</h3>
        <p>
          You care about evidence, logic, mathematics, mechanics, computation, or experimental quality.
        </p>
      </div>

      <div class="join-card">
        <h3>Independence</h3>
        <p>
          You are willing to think, learn, code, test, write, and improve with persistence.
        </p>
      </div>

      <div class="join-card">
        <h3>Ambition</h3>
        <p>
          You want to produce high-quality work with international visibility and long-term value.
        </p>
      </div>

      <div class="join-card">
        <h3>Openness</h3>
        <p>
          You are excited to learn across mechanics, computation, data, and engineering applications.
        </p>
      </div>

      <div class="join-card">
        <h3>Integrity</h3>
        <p>
          You value honesty, responsibility, kindness, and respect as part of serious research.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Group Culture</h2>

    <div class="join-grid three">
      <div class="join-card">
        <h3>High Standards</h3>
        <p>
          We aim for rigorous, creative, and internationally competitive research.
        </p>
      </div>

      <div class="join-card">
        <h3>Serious Mentorship</h3>
        <p>
          Students will receive regular research discussions, technical guidance, and writing feedback.
        </p>
      </div>

      <div class="join-card">
        <h3>Global Perspective</h3>
        <p>
          We support international collaborations, conference presentations, and academic exchanges.
        </p>
      </div>

      <div class="join-card">
        <h3>Ownership</h3>
        <p>
          You will be encouraged to develop your own ideas and build your research identity.
        </p>
      </div>

      <div class="join-card">
        <h3>Respect</h3>
        <p>
          We value clear communication, intellectual honesty, and a supportive group environment.
        </p>
      </div>

      <div class="join-card">
        <h3>Sustainable Excellence</h3>
        <p>
          We pursue ambitious research while supporting long-term, healthy academic growth.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">How to Apply</h2>

    <div class="apply-panel">
      <div class="apply-header">
        <h3>Application Instructions</h3>
        <p>
          Please send a concise email with your background, interests, and the position you are applying for.
        </p>
      </div>

      <div class="apply-content">
        <div class="apply-block">
          <div class="apply-label">Email Subject</div>

          <div class="subject-line">[Join Us] Your Name – Institution – Position</div>

          <p class="apply-note">Example:</p>

          <div class="subject-line">[Join Us] Jane Doe – Wuhan University – PhD</div>
        </div>

        <div class="apply-block">
          <div class="apply-label">Application Materials</div>

          <div class="material-grid">
            <div class="material-card">
              <div class="material-check">✓</div>
              <div>
                <strong>Curriculum Vitae</strong>
                <span>Your education, experience, skills, and publications if available.</span>
              </div>
            </div>

            <div class="material-card">
              <div class="material-check">✓</div>
              <div>
                <strong>Research Works</strong>
                <span>Publications, thesis, reports, code, projects, or other representative work.</span>
              </div>
            </div>

            <div class="material-card">
              <div class="material-check">✓</div>
              <div>
                <strong>Three Referees</strong>
                <span>Names and contact information of three academic or professional referees.</span>
              </div>
            </div>

            <div class="material-card">
              <div class="material-check">✓</div>
              <div>
                <strong>Brief Statement</strong>
                <span>Your interests, strengths, motivation, and possible research questions.</span>
              </div>
            </div>
          </div>

          <p class="apply-note">
            Publications are not required for early-stage students. Strong course projects, coding experience,
            experimental skills, or original research ideas are also valuable.
          </p>
        </div>

        <div class="apply-block">
          <div class="apply-label">Contact</div>

          <p class="apply-note">Please send your application to:</p>

          <a class="email-link" href="mailto:kqceeli@163.com">kqceeli@163.com</a>

          <p class="apply-note" style="margin-top: 18px;">
            I read every email personally. If you are curious, ambitious, and excited by interdisciplinary research,
            I would be very happy to hear from you.
          </p>
        </div>
      </div>
    </div>
  </section>

  <div class="final-note">
    Great research requires both imagination and discipline.
    If you want to work at the intersection of <strong>geomechanics, computation, uncertainty, and AI</strong>,
    and if you are eager to help build a world-class research group from the beginning, please get in touch.
    <br><br>
    <strong>Let us build something meaningful together.</strong>
  </div>

</div>
