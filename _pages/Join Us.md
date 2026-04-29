---
title: "Join Us"
layout: page
permalink: /join-us/
---

<style>
.join-page {
  max-width: 1080px;
  margin: 0 auto;
  padding: 36px 22px 72px;
  color: #1f2937;
  font-size: 16px;
  line-height: 1.75;
}

.join-page * {
  box-sizing: border-box;
}

.join-hero {
  position: relative;
  overflow: hidden;
  border-radius: 26px;
  padding: 56px 52px;
  margin-bottom: 46px;
  color: #ffffff;
  background:
    radial-gradient(circle at 12% 20%, rgba(96, 165, 250, 0.42), transparent 32%),
    radial-gradient(circle at 88% 15%, rgba(14, 165, 233, 0.35), transparent 30%),
    linear-gradient(135deg, #020617 0%, #0f172a 38%, #1e3a8a 72%, #0369a1 100%);
  box-shadow: 0 24px 60px rgba(15, 23, 42, 0.22);
}

.join-hero::after {
  content: "";
  position: absolute;
  right: -120px;
  bottom: -120px;
  width: 320px;
  height: 320px;
  border-radius: 50%;
  background: rgba(255, 255, 255, 0.08);
}

.join-eyebrow {
  display: inline-block;
  margin-bottom: 18px;
  padding: 6px 13px;
  border: 1px solid rgba(219, 234, 254, 0.35);
  border-radius: 999px;
  color: #dbeafe;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.join-hero h1 {
  margin: 0 0 18px;
  color: #ffffff;
  font-size: 46px;
  line-height: 1.12;
  letter-spacing: -0.04em;
}

.join-hero .lead {
  max-width: 850px;
  margin: 0;
  color: #e0f2fe;
  font-size: 19px;
  line-height: 1.75;
}

.join-hero .lead strong {
  color: #ffffff;
}

.join-hero .tagline {
  max-width: 820px;
  margin-top: 24px;
  padding-top: 22px;
  border-top: 1px solid rgba(219, 234, 254, 0.22);
  color: #bfdbfe;
  font-size: 18px;
  font-weight: 700;
}

.join-section {
  margin-top: 52px;
}

.join-section-title {
  margin: 0 0 20px;
  color: #0f172a;
  font-size: 28px;
  line-height: 1.25;
  letter-spacing: -0.025em;
}

.join-section-title::after {
  content: "";
  display: block;
  width: 52px;
  height: 4px;
  margin-top: 12px;
  border-radius: 999px;
  background: linear-gradient(90deg, #2563eb, #06b6d4);
}

.join-intro {
  max-width: 920px;
  color: #4b5563;
  font-size: 17px;
}

.join-quote {
  margin: 28px 0;
  padding: 24px 28px;
  border-left: 5px solid #2563eb;
  border-radius: 0 18px 18px 0;
  background: #f8fafc;
  color: #0f172a;
  font-size: 20px;
  font-weight: 750;
  line-height: 1.6;
}

.join-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
  margin-top: 24px;
}

.join-grid.three {
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.join-card {
  position: relative;
  height: 100%;
  padding: 24px 24px 22px;
  border: 1px solid #e5e7eb;
  border-radius: 20px;
  background: #ffffff;
  box-shadow: 0 12px 34px rgba(15, 23, 42, 0.055);
  transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease;
}

.join-card:hover {
  transform: translateY(-3px);
  border-color: #bfdbfe;
  box-shadow: 0 18px 42px rgba(37, 99, 235, 0.11);
}

.join-card h3 {
  margin: 0 0 10px;
  color: #1e3a8a;
  font-size: 18px;
  line-height: 1.35;
}

.join-card p {
  margin: 0;
  color: #4b5563;
  line-height: 1.7;
}

.join-number {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 34px;
  height: 34px;
  margin-bottom: 14px;
  border-radius: 50%;
  background: #eff6ff;
  color: #1d4ed8;
  font-weight: 800;
  font-size: 14px;
}

.join-highlight {
  margin: 30px 0 0;
  padding: 24px 26px;
  border: 1px solid #bae6fd;
  border-radius: 20px;
  background: linear-gradient(135deg, #f0f9ff, #ffffff);
  color: #0f172a;
}

.join-highlight strong {
  color: #075985;
}

.join-list {
  margin: 18px 0 0;
  padding-left: 0;
  list-style: none;
}

.join-list li {
  position: relative;
  margin: 10px 0;
  padding-left: 28px;
  color: #374151;
}

.join-list li::before {
  content: "✓";
  position: absolute;
  left: 0;
  top: 0;
  color: #2563eb;
  font-weight: 900;
}

.position-pills {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 22px;
}

.position-pills span {
  display: inline-flex;
  align-items: center;
  padding: 8px 14px;
  border-radius: 999px;
  background: #eff6ff;
  color: #1e40af;
  font-size: 14px;
  font-weight: 700;
}

.apply-box {
  margin-top: 26px;
  padding: 30px;
  border-radius: 24px;
  background: #0f172a;
  color: #e5e7eb;
  box-shadow: 0 20px 50px rgba(15, 23, 42, 0.18);
}

.apply-box h3 {
  margin: 0 0 14px;
  color: #ffffff;
  font-size: 23px;
}

.apply-box p {
  margin: 10px 0;
  color: #cbd5e1;
}

.subject-line {
  margin: 18px 0;
  padding: 16px 18px;
  border-radius: 14px;
  background: rgba(255, 255, 255, 0.08);
  color: #ffffff;
  font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace;
  font-size: 15px;
  overflow-x: auto;
}

.email-link {
  display: inline-block;
  margin-top: 12px;
  color: #93c5fd;
  font-size: 22px;
  font-weight: 800;
  text-decoration: none;
}

.email-link:hover {
  color: #bfdbfe;
  text-decoration: underline;
}

.final-note {
  margin-top: 44px;
  padding: 30px;
  border-radius: 24px;
  background:
    linear-gradient(135deg, rgba(37, 99, 235, 0.08), rgba(6, 182, 212, 0.08)),
    #ffffff;
  border: 1px solid #dbeafe;
  color: #1f2937;
  font-size: 18px;
}

.final-note strong {
  color: #1d4ed8;
}

@media (max-width: 900px) {
  .join-grid,
  .join-grid.three {
    grid-template-columns: 1fr;
  }

  .join-hero {
    padding: 40px 30px;
  }

  .join-hero h1 {
    font-size: 36px;
  }

  .join-hero .lead {
    font-size: 17px;
  }
}

@media (max-width: 560px) {
  .join-page {
    padding: 24px 16px 56px;
  }

  .join-hero {
    border-radius: 20px;
    padding: 34px 24px;
  }

  .join-hero h1 {
    font-size: 32px;
  }

  .join-section-title {
    font-size: 24px;
  }

  .join-card {
    padding: 21px;
  }

  .apply-box {
    padding: 24px;
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
    <div class="tagline">
      We aim to build an internationally leading research group that advances fundamental science and delivers high-impact engineering solutions.
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Why This Group?</h2>

    <div class="join-intro">
      <p>
        Modern geotechnical and hydraulic engineering is entering a new era.
        Deep underground construction, climate-driven permafrost degradation, offshore energy infrastructure,
        aging dams and tunnels, and uncertain geo-hazards all demand methods that go beyond traditional engineering practice.
      </p>

      <p>
        Our group is built around a central idea:
      </p>
    </div>

    <div class="join-quote">
      The future of geomechanics lies in the integration of physics, computation, data, and intelligence.
    </div>

    <div class="join-intro">
      <p>
        We aim to create models, algorithms, and engineering tools that are mathematically rigorous,
        computationally powerful, physically interpretable, experimentally grounded, and useful for real-world decision-making.
      </p>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Research Philosophy</h2>

    <div class="join-grid">
      <div class="join-card">
        <h3>Physics First, Data Smart</h3>
        <p>
          We develop models that respect the laws of mechanics while learning from experimental, field,
          and simulation data. The goal is reliability beyond a training dataset.
        </p>
      </div>

      <div class="join-card">
        <h3>Uncertainty as Information</h3>
        <p>
          Geomaterials are heterogeneous, data are sparse, and environments are changing.
          We quantify uncertainty rigorously and turn it into safer engineering decisions.
        </p>
      </div>

      <div class="join-card">
        <h3>AI for Scientific Discovery</h3>
        <p>
          We use machine learning not as a black box, but as a tool to discover constitutive laws,
          multiscale patterns, hidden variables, and failure mechanisms.
        </p>
      </div>

      <div class="join-card">
        <h3>Theory–Simulation–Experiment Loop</h3>
        <p>
          Real progress comes from closing the loop between mathematical theory, numerical simulation,
          laboratory experiments, and field observations.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Research Directions</h2>

    <div class="join-intro">
      <p>
        Our work spans several interconnected directions, from fundamental mechanics to large-scale engineering applications.
      </p>
    </div>

    <div class="join-grid">
      <div class="join-card">
        <div class="join-number">01</div>
        <h3>Frozen-Ground and Cold-Region Geomechanics</h3>
        <p>
          Constitutive modelling of frozen soils and ice-rich geomaterials; artificial ground freezing for deep excavations and tunnels;
          permafrost degradation under climate change; frost heave, thaw settlement, and cold-region infrastructure resilience.
        </p>
      </div>

      <div class="join-card">
        <div class="join-number">02</div>
        <h3>Multi-Physics Coupling in Geomaterials</h3>
        <p>
          Thermo–hydro–mechanical–chemical processes; phase change and freeze–thaw cycles;
          unsaturated and reactive porous media; coupled modelling for hydropower dams, energy geostructures,
          offshore foundations, and underground infrastructure.
        </p>
      </div>

      <div class="join-card">
        <div class="join-number">03</div>
        <h3>Multi-Scale Modelling of Geomaterials</h3>
        <p>
          Grain-scale DEM and micromechanics; microstructure-informed constitutive models;
          FEM–DEM coupling; bridging pore-scale physics, meso-scale deformation, and engineering-scale prediction.
        </p>
      </div>

      <div class="join-card">
        <div class="join-number">04</div>
        <h3>Geotechnical Risk and Reliability Engineering</h3>
        <p>
          Spatial variability and random fields; random finite element methods; Bayesian inversion and model updating;
          reliability analysis of slopes, foundations, tunnels, dams, and major infrastructure under geological and climatic uncertainty.
        </p>
      </div>

      <div class="join-card">
        <div class="join-number">05</div>
        <h3>AI-Enabled Computational Mechanics</h3>
        <p>
          Physics-informed neural networks; neural operators for PDEs; differentiable simulation;
          data-driven constitutive discovery; and high-dimensional surrogate modelling for expensive geomechanical systems.
        </p>
      </div>

      <div class="join-card">
        <div class="join-number">06</div>
        <h3>Large Language Models for Engineering Science</h3>
        <p>
          LLM-powered scientific agents for geotechnical reasoning and design; knowledge extraction from literature, codes,
          and case histories; automated hypothesis generation, simulation workflows, and AI copilots for engineers.
        </p>
      </div>
    </div>

    <div class="join-highlight">
      <strong>Student-led ideas are strongly encouraged.</strong>
      The best projects often begin with a sharp question from a student, followed by rigorous thinking,
      careful modelling, and persistent exploration.
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

    <div class="join-grid four" style="margin-top: 28px;">
      <div class="join-card">
        <h3>Engineering</h3>
        <p>
          Civil engineering, geotechnical engineering, hydraulic engineering, offshore engineering,
          underground engineering, and environmental engineering.
        </p>
      </div>

      <div class="join-card">
        <h3>Mechanics and Mathematics</h3>
        <p>
          Solid mechanics, computational mechanics, applied mathematics, numerical analysis,
          statistics, probability, and uncertainty quantification.
        </p>
      </div>

      <div class="join-card">
        <h3>Physical and Earth Sciences</h3>
        <p>
          Physics, geophysics, geology, materials science, porous media, cryosphere science,
          and climate-related geosystems.
        </p>
      </div>

      <div class="join-card">
        <h3>Computing and AI</h3>
        <p>
          Computer science, machine learning, scientific computing, data science,
          large language models, AI agents, and scientific foundation models.
        </p>
      </div>
    </div>

    <div class="join-highlight">
      Applications are welcome regardless of gender, nationality, institution, or prior research field.
      What matters most is the potential to grow into an independent, rigorous, and creative researcher.
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">What I Look For</h2>

    <div class="join-intro">
      <p>
        You do not need to match every item below. I especially value:
      </p>
    </div>

    <ul class="join-list">
      <li>Deep curiosity about scientific and engineering problems</li>
      <li>Strong self-motivation and the ability to work independently</li>
      <li>Rigor in mechanics, mathematics, computation, experiments, or data analysis</li>
      <li>Intellectual honesty and respect for evidence</li>
      <li>Willingness to learn across disciplines</li>
      <li>Clear communication in writing, coding, presentation, or discussion</li>
      <li>Kindness, reliability, and responsibility as a collaborator</li>
    </ul>

    <div class="join-highlight">
      If you are not yet an expert but are serious, disciplined, and excited to learn,
      you are strongly encouraged to reach out.
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">Group Culture</h2>

    <div class="join-grid three">
      <div class="join-card">
        <h3>Ambitious Science</h3>
        <p>
          We pursue important questions, publish high-quality work, and aim for international impact.
        </p>
      </div>

      <div class="join-card">
        <h3>Serious Mentorship</h3>
        <p>
          Students and researchers will receive regular discussions, technical guidance,
          writing feedback, and long-term career support.
        </p>
      </div>

      <div class="join-card">
        <h3>Independence and Ownership</h3>
        <p>
          You will be encouraged to develop your own ideas, define your research identity,
          and take ownership of your scientific direction.
        </p>
      </div>

      <div class="join-card">
        <h3>International Visibility</h3>
        <p>
          The group will actively support international collaborations, conference presentations,
          research visits, and academic exchanges.
        </p>
      </div>

      <div class="join-card">
        <h3>Open and Respectful Environment</h3>
        <p>
          We value clarity, honesty, kindness, and mutual respect. Students are collaborators, not labor.
        </p>
      </div>

      <div class="join-card">
        <h3>Sustainable Excellence</h3>
        <p>
          High ambition and personal well-being are not contradictory.
          We aim for long-term, healthy, and meaningful academic growth.
        </p>
      </div>
    </div>
  </section>

  <section class="join-section">
    <h2 class="join-section-title">How to Apply</h2>

    <div class="apply-box">
      <h3>Email Subject</h3>
      <p>Please send an email with the following subject line:</p>

      <div class="subject-line">[Join Us] Your Name – Institution – Position</div>

      <p>Example:</p>

      <div class="subject-line">[Join Us] Jane Doe – Wuhan University – PhD</div>

      <h3 style="margin-top: 28px;">Application Materials</h3>

      <ul class="join-list">
        <li>Curriculum Vitae</li>
        <li>Representative publications or research works, if available</li>
        <li>Contact information for three referees</li>
        <li>A brief introduction or research statement</li>
      </ul>

      <p>
        If you do not yet have publications, you may include course projects, thesis work,
        code repositories, technical reports, or other evidence of research potential.
      </p>

      <p>
        Your brief introduction may include your academic background, research interests,
        technical strengths, why you are interested in this group, and what kind of research question you would like to explore.
      </p>

      <h3 style="margin-top: 28px;">Contact</h3>

      <p>Please send your application to:</p>

      <a class="email-link" href="mailto:kqceeli@163.com">kqceeli@163.com</a>

      <p style="margin-top: 20px;">
        I read every email personally. If you are curious, ambitious, and excited by interdisciplinary research,
        I would be very happy to hear from you.
      </p>
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
