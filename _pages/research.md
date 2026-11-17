---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research program of Dr. Sakirman in Islamic astronomy, crescent visibility, twilight, astronomical photometry, digital imaging, Hijri calendar studies, and Islamic legal reasoning."
---

<style>

/* =========================================================
   HIDE AUTOMATIC TITLE
========================================================= */

.page__title {
  display: none !important;
}


/* =========================================================
   GENERAL
========================================================= */

.research-section {
  width: 100%;
}

.research-hero {
  margin-bottom: 3rem;
}

.research-kicker,
.research-section-label {
  display: inline-block;
  margin-bottom: 0.55rem;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.10em;
  text-transform: uppercase;
  opacity: 0.62;
}

.research-title {
  margin: 0 0 0.85rem 0;
  font-size: 1.75rem;
  line-height: 1.3;
  font-weight: 700;
}

.research-subtitle {
  max-width: 900px;
  margin: 0 0 0.9rem 0;
  font-size: 1.18rem;
  line-height: 1.5;
  font-weight: 700;
}

.research-hero-text {
  max-width: 880px;
  margin: 0 0 1rem 0;
  font-size: 0.94rem;
  line-height: 1.8;
}

.research-section-block {
  margin-top: 3rem;
}

.research-section-title {
  margin: 0 0 0.6rem 0;
  padding-bottom: 0.55rem;
  border-bottom: 1px solid rgba(127,127,127,0.30);
  font-size: 1.25rem;
  line-height: 1.4;
}

.research-section-intro {
  max-width: 850px;
  margin: 0 0 1.4rem 0;
  font-size: 0.9rem;
  line-height: 1.75;
  opacity: 0.84;
}


/* =========================================================
   RESEARCH THEMES
========================================================= */

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.15rem;
}

.research-card {
  overflow: hidden;
  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;
  background: transparent;
  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.research-card:hover {
  border-color: #00b8d9;
  transform: translateY(-3px);
}

.research-image-link {
  position: relative;
  display: block;
  width: 100%;
  overflow: hidden;
  border-bottom: 1px solid rgba(127,127,127,0.20);
}

.research-card img {
  display: block;
  width: 100%;
  height: 230px;
  object-fit: cover;
  transition: transform 0.45s ease;
}

.research-card:hover img {
  transform: scale(1.055);
}

.research-theme-badge {
  position: absolute;
  top: 14px;
  left: 14px;
  z-index: 5;
  display: inline-block;
  padding: 0.38rem 0.58rem;
  border: 1px solid rgba(255,255,255,0.30);
  border-radius: 6px;
  background: rgba(20,20,20,0.72);
  color: #ffffff !important;
  font-size: 0.66rem;
  font-weight: 700;
  letter-spacing: 0.07em;
  text-transform: uppercase;
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
}

.research-card-content {
  padding: 1.15rem 1.2rem 1.3rem;
}

.research-card h3 {
  margin: 0 0 0.6rem 0;
  font-size: 1.05rem;
  line-height: 1.4;
}

.research-card p {
  margin: 0;
  font-size: 0.86rem;
  line-height: 1.7;
  opacity: 0.8;
}


/* =========================================================
   RESEARCH LOOP
========================================================= */

.research-loop-stage {
  width: 100%;
  margin: 1.8rem auto 2.2rem;
}

.research-loop-wrap {
  position: relative;
  width: 620px;
  max-width: 100%;
  height: 620px;
  margin: 0 auto;
}


/* =========================================================
   STATIC RINGS
========================================================= */

.loop-outer-ring {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 425px;
  height: 425px;
  border: 1px solid rgba(110,140,190,0.18);
  border-radius: 50%;
  transform: translate(-50%, -50%);
}

.loop-inner-ring {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 250px;
  height: 250px;
  border: 1px dashed rgba(110,140,190,0.16);
  border-radius: 50%;
  transform: translate(-50%, -50%);
}


/* =========================================================
   ROTATING ORBIT
========================================================= */

.loop-orbit {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 345px;
  height: 345px;
  border: 2px dashed rgba(0,184,217,0.82);
  border-radius: 50%;
  transform: translate(-50%, -50%);
  animation: rotateOrbit 16s linear infinite;
  pointer-events: none;
  filter: drop-shadow(0 0 5px rgba(0,184,217,0.16));
}

.loop-orbit::before {
  content: "";
  position: absolute;
  inset: -2px;
  border: 2px dashed rgba(166,105,255,0.28);
  border-radius: 50%;
  transform: rotate(38deg);
}


/* =========================================================
   ORBITING SUN
========================================================= */

.loop-sun {
  position: absolute;
  top: -11px;
  left: 50%;
  width: 22px;
  height: 22px;
  margin-left: -11px;
  border-radius: 50%;
  border: 2px solid rgba(255,255,255,0.78);

  background:
    radial-gradient(
      circle,
      #ffffff 0%,
      #c9fbff 18%,
      #00d7f3 45%,
      #0098b4 68%,
      transparent 72%
    );

  box-shadow:
    0 0 8px rgba(0,220,255,0.95),
    0 0 18px rgba(0,210,245,0.62),
    0 0 32px rgba(0,184,217,0.35);

  z-index: 10;
}

@keyframes rotateOrbit {
  from {
    transform:
      translate(-50%, -50%)
      rotate(0deg);
  }

  to {
    transform:
      translate(-50%, -50%)
      rotate(360deg);
  }
}


/* =========================================================
   CENTER
========================================================= */

.loop-center {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 205px;
  height: 205px;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  padding: 1rem;

  border: 1px solid rgba(0,184,217,0.56);
  border-radius: 50%;

  background:
    radial-gradient(
      circle,
      rgba(0,184,217,0.08) 0%,
      rgba(0,184,217,0.02) 62%,
      transparent 100%
    );

  text-align: center;

  transform: translate(-50%, -50%);

  box-shadow:
    0 0 24px rgba(0,184,217,0.08),
    inset 0 0 20px rgba(0,184,217,0.03);

  animation: centerGlow 3.2s ease-in-out infinite;

  z-index: 3;
}

@keyframes centerGlow {

  0%,
  100% {
    box-shadow:
      0 0 18px rgba(0,184,217,0.07),
      inset 0 0 18px rgba(0,184,217,0.02);
  }

  50% {
    box-shadow:
      0 0 34px rgba(0,184,217,0.17),
      inset 0 0 25px rgba(0,184,217,0.05);
  }

}

.loop-center-label {
  margin-bottom: 0.45rem;
  font-size: 0.62rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  opacity: 0.58;
}

.loop-center-title {
  font-size: 1.15rem;
  line-height: 1.4;
  font-weight: 700;
}


/* =========================================================
   LOOP NODES
========================================================= */

.loop-node {
  position: absolute;
  z-index: 6;

  width: 170px;
  min-height: 76px;

  padding: 0.70rem 0.82rem;

  border: 1px solid rgba(115,140,195,0.32);
  border-radius: 10px;

  background: rgba(42,42,42,0.94);

  cursor: pointer;

  overflow: hidden;

  transition:
    width 0.35s ease,
    min-height 0.35s ease,
    border-color 0.25s ease,
    background 0.25s ease,
    box-shadow 0.25s ease,
    transform 0.25s ease;
}

.loop-node:hover {
  border-color: rgba(0,184,217,0.65);
}

.loop-node.active {
  width: 220px;
  min-height: 118px;

  border-color: #00b8d9;

  background:
    rgba(0,184,217,0.06);

  box-shadow:
    0 0 18px rgba(0,184,217,0.14);
}

.loop-node-number {
  display: inline-block;
  margin-right: 0.38rem;
  color: #00cbea;
  font-size: 0.65rem;
  font-weight: 700;
}

.loop-node-title {
  font-size: 0.74rem;
  line-height: 1.35;
  font-weight: 700;
}

.loop-node-meta {
  display: block;
  margin-top: 0.30rem;
  font-size: 0.61rem;
  line-height: 1.35;
  opacity: 0.58;
}


/* =========================================================
   ACTIVE DESCRIPTION
========================================================= */

.loop-node-description {
  max-height: 0;
  margin: 0;
  overflow: hidden;
  opacity: 0;

  font-size: 0.68rem;
  line-height: 1.55;

  transition:
    max-height 0.35s ease,
    opacity 0.30s ease,
    margin-top 0.30s ease;
}

.loop-node.active .loop-node-description {
  max-height: 110px;
  margin-top: 0.55rem;
  opacity: 0.82;
}


/* =========================================================
   NODE POSITIONS
========================================================= */

.loop-node-1 {
  top: 5px;
  left: 50%;
  transform: translateX(-50%);
}

.loop-node-1.active {
  transform:
    translateX(-50%)
    translateY(-2px);
}


.loop-node-2 {
  top: 122px;
  right: 0;
}

.loop-node-2.active {
  right: -20px;
}


.loop-node-3 {
  bottom: 122px;
  right: 0;
}

.loop-node-3.active {
  right: -20px;
}


.loop-node-4 {
  bottom: 5px;
  left: 50%;
  transform: translateX(-50%);
}

.loop-node-4.active {
  transform:
    translateX(-50%)
    translateY(2px);
}


.loop-node-5 {
  bottom: 122px;
  left: 0;
}

.loop-node-5.active {
  left: -20px;
}


.loop-node-6 {
  top: 122px;
  left: 0;
}

.loop-node-6.active {
  left: -20px;
}


/* =========================================================
   SOFTWARE / PROJECTS
========================================================= */

.software-grid,
.future-grid,
.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1rem;
}

.software-card,
.project-card,
.future-card {
  overflow: hidden;
  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;
  background: transparent;
  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.software-card:hover,
.project-card:hover,
.future-card:hover {
  border-color: #00b8d9;
  transform: translateY(-3px);
}

.software-card img {
  display: block;
  width: 100%;
  height: 220px;
  object-fit: contain;
  padding: 1rem;
  transition: transform 0.45s ease;
}

.software-card:hover img {
  transform: scale(1.04);
}

.software-content,
.project-card,
.future-card {
  padding: 1rem 1.2rem 1.2rem;
}

.software-content h3,
.project-card h3,
.future-card h3 {
  margin: 0 0 0.5rem 0;
  font-size: 1rem;
}

.software-content p,
.project-card p,
.future-card p {
  margin: 0;
  font-size: 0.84rem;
  line-height: 1.7;
  opacity: 0.8;
}


/* =========================================================
   ROADMAP
========================================================= */

.roadmap-wrapper {
  margin-top: 1.4rem;
  text-align: center;
}

.roadmap-wrapper img {
  display: block;
  width: 100%;
  max-width: 680px;
  height: auto;
  margin: 0 auto;
  border: 1px solid rgba(127,127,127,0.20);
  border-radius: 10px;
  transition: transform 0.45s ease;
}

.roadmap-wrapper img:hover {
  transform: scale(1.025);
}


/* =========================================================
   OUTPUTS
========================================================= */

.research-output-list {
  margin: 0;
  padding-left: 1.2rem;
}

.research-output-list li {
  margin-bottom: 0.65rem;
  line-height: 1.65;
}


/* =========================================================
   FOOTER NAV
========================================================= */

.research-footer-nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0.7rem;
  margin-top: 3rem;
  padding-top: 1.5rem;
  border-top: 1px solid rgba(127,127,127,0.22);
}

.research-footer-button {
  display: inline-block;
  padding: 0.55rem 0.85rem;
  border: 1px solid rgba(127,127,127,0.30);
  border-radius: 8px;
  font-size: 0.78rem;
  font-weight: 700;
  text-decoration: none !important;
  transition:
    color 0.2s ease,
    border-color 0.2s ease,
    transform 0.2s ease;
}

.research-footer-button:hover {
  color: #00b8d9 !important;
  border-color: #00b8d9 !important;
  transform: translateY(-2px);
}


/* =========================================================
   RESPONSIVE
========================================================= */

@media (max-width: 768px) {

  .research-grid,
  .software-grid,
  .future-grid,
  .project-grid {
    grid-template-columns: 1fr;
  }

  .research-loop-wrap {
    width: 540px;
    height: 540px;
  }

  .loop-node {
    width: 150px;
  }

  .loop-node.active {
    width: 190px;
  }

  .loop-node-2,
  .loop-node-3 {
    right: 0;
  }

  .loop-node-5,
  .loop-node-6 {
    left: 0;
  }

  .research-footer-nav {
    justify-content: flex-start;
  }

}

@media (max-width: 600px) {

  .research-loop-wrap {
    display: none;
  }

}

</style>


<div class="research-section">


<!-- =====================================================
     HERO
===================================================== -->

<section class="research-hero">

  <div class="research-kicker">
    Research Program
  </div>

  <h1 class="research-title">
    Research
  </h1>

  <h2 class="research-subtitle">
    From astronomical observation to Islamic legal reasoning
  </h2>

  <p class="research-hero-text">
    My research explores the intersection of
    <strong>Islamic astronomy, observational science, and Islamic law</strong>.
    It focuses particularly on crescent visibility, twilight, sky brightness,
    astronomical photometry, digital image processing, Hijri calendar systems,
    and the integration of scientific evidence with Islamic legal reasoning.
  </p>

  <p class="research-hero-text">
    A central objective of this research program is to develop
    <strong>evidence-based approaches to astronomy for Islamic religious practices</strong>,
    linking observation, quantitative analysis, and legal interpretation in the
    study of the <em>hilal</em>, prayer times, qibla direction, and the Hijri calendar.
  </p>

</section>


<!-- =====================================================
     RESEARCH THEMES
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Research Themes
  </div>

  <h2 class="research-section-title">
    Four Research Themes
  </h2>

  <p class="research-section-intro">
    My research is organized around four interconnected themes covering
    observational astronomy, quantitative measurement, Hijri calendar studies,
    and digital image processing.
  </p>


  <div class="research-grid">


    <article class="research-card">

      <a
        href="/images/hilal-twilight.jpg"
        target="_blank"
        class="research-image-link"
      >

        <span class="research-theme-badge">
          THEME 01
        </span>

        <img
          src="/images/hilal-twilight.jpg"
          alt="Crescent visibility and twilight research"
        >

      </a>

      <div class="research-card-content">

        <h3>
          Crescent Visibility and Twilight
        </h3>

        <p>
          Investigation of young crescent visibility in relation to solar
          depression, twilight intensity, atmospheric conditions, lunar
          geometry, and observational constraints.
        </p>

      </div>

    </article>


    <article class="research-card">

      <a
        href="/images/Analisis-IRIS.png"
        target="_blank"
        class="research-image-link"
      >

        <span class="research-theme-badge">
          THEME 02
        </span>

        <img
          src="/images/Analisis-IRIS.png"
          alt="Astronomical photometry and sky brightness analysis"
        >

      </a>

      <div class="research-card-content">

        <h3>
          Astronomical Photometry and Sky Brightness
        </h3>

        <p>
          Quantitative analysis of crescent intensity, twilight brightness,
          aperture photometry, Weber contrast, sky quality, and observational thresholds.
        </p>

      </div>

    </article>


    <article class="research-card">

      <a
        href="/images/kalender-hijriyah-2027.jpg"
        target="_blank"
        class="research-image-link"
      >

        <span class="research-theme-badge">
          THEME 03
        </span>

        <img
          src="/images/kalender-hijriyah-2027.jpg"
          alt="Hijri calendar and hisab rukyat studies"
        >

      </a>

      <div class="research-card-content">

        <h3>
          Hijri Calendar and Hisab–Rukyat
        </h3>

        <p>
          Study of lunar calendrical systems, crescent visibility criteria,
          astronomical calculation, observational evidence, institutional
          authority, and Islamic legal reasoning.
        </p>

      </div>

    </article>


    <article class="research-card">

      <a
        href="/images/olah-citra.jpg"
        target="_blank"
        class="research-image-link"
      >

        <span class="research-theme-badge">
          THEME 04
        </span>

        <img
          src="/images/olah-citra.jpg"
          alt="Digital imaging for crescent observation"
        >

      </a>

      <div class="research-card-content">

        <h3>
          Digital Imaging and Astronomical Evidence
        </h3>

        <p>
          Application of digital cameras, telescopes, image processing,
          calibration, enhancement, and quantitative analysis to improve
          crescent detection and astronomical documentation.
        </p>

      </div>

    </article>


  </div>

</section>


<!-- =====================================================
     METHODOLOGY
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Methodology
  </div>

  <h2 class="research-section-title">
    From Observation to Evidence
  </h2>

  <p class="research-section-intro">
    The research workflow integrates astronomical observation,
    digital imaging, image processing, quantitative measurement,
    astronomical interpretation, and Islamic legal reasoning.
  </p>


  <div class="research-loop-stage">

    <div class="research-loop-wrap">


      <div class="loop-outer-ring"></div>

      <div class="loop-inner-ring"></div>


      <div class="loop-orbit">

        <div class="loop-sun"></div>

      </div>


      <div class="loop-center">

        <span class="loop-center-label">
          Research Loop
        </span>

        <div class="loop-center-title">
          From Observation<br>
          to Evidence
        </div>

      </div>


      <div class="loop-node loop-node-1 active" data-step="1">

        <span class="loop-node-number">
          01
        </span>

        <span class="loop-node-title">
          Crescent Observation
        </span>

        <span class="loop-node-meta">
          hilal · twilight · geometry
        </span>

        <p class="loop-node-description">
          Establishes the empirical basis through direct observation
          of the <em>hilal</em>, twilight conditions, lunar geometry,
          and atmospheric circumstances.
        </p>

      </div>


      <div class="loop-node loop-node-2" data-step="2">

        <span class="loop-node-number">
          02
        </span>

        <span class="loop-node-title">
          Digital Image Acquisition
        </span>

        <span class="loop-node-meta">
          camera · telescope · RAW
        </span>

        <p class="loop-node-description">
          Records astronomical observations using digital cameras
          and telescopes while preserving RAW image data for
          subsequent quantitative analysis.
        </p>

      </div>


      <div class="loop-node loop-node-3" data-step="3">

        <span class="loop-node-number">
          03
        </span>

        <span class="loop-node-title">
          Image Pre-Processing
        </span>

        <span class="loop-node-meta">
          calibration · Siril
        </span>

        <p class="loop-node-description">
          Prepares observational data through calibration,
          correction, enhancement, and astronomical image
          processing using software such as Siril.
        </p>

      </div>


      <div class="loop-node loop-node-4" data-step="4">

        <span class="loop-node-number">
          04
        </span>

        <span class="loop-node-title">
          Photometry & Contrast
        </span>

        <span class="loop-node-meta">
          IRIS · Weber contrast
        </span>

        <p class="loop-node-description">
          Measures crescent intensity, twilight brightness,
          and visual separation between the crescent and the
          background sky using IRIS and Weber contrast.
        </p>

      </div>


      <div class="loop-node loop-node-5" data-step="5">

        <span class="loop-node-number">
          05
        </span>

        <span class="loop-node-title">
          Astronomical Interpretation
        </span>

        <span class="loop-node-meta">
          visibility · atmosphere
        </span>

        <p class="loop-node-description">
          Connects quantitative measurements with atmospheric
          conditions, lunar geometry, twilight brightness,
          and crescent visibility criteria.
        </p>

      </div>


      <div class="loop-node loop-node-6" data-step="6">

        <span class="loop-node-number">
          06
        </span>

        <span class="loop-node-title">
          Islamic Legal Analysis
        </span>

        <span class="loop-node-meta">
          hisab–rukyat · maqāṣid
        </span>

        <p class="loop-node-description">
          Interprets astronomical evidence through
          <em>hisab–rukyat</em>, Islamic jurisprudence,
          and maqāṣid al-sharīʿah.
        </p>

      </div>


    </div>

  </div>

</section>


<!-- =====================================================
     SOFTWARE
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Research Tools
  </div>

  <h2 class="research-section-title">
    Astronomical Software
  </h2>

  <p class="research-section-intro">
    Digital image processing and photometric analysis form an important part
    of the observational research workflow.
  </p>


  <div class="software-grid">


    <article class="software-card">

      <a
        href="https://siril.org/"
        target="_blank"
        rel="noopener"
      >

        <img
          src="/images/software-siril.png"
          alt="Siril astronomical image processing software"
        >

      </a>

      <div class="software-content">

        <h3>
          Siril
        </h3>

        <p>
          Used for astronomical image calibration,
          preprocessing, stacking, enhancement,
          and preparation of observational image data.
        </p>

      </div>

    </article>


    <article class="software-card">

      <a
        href="https://buil.astrosurf.com/iris-software.html"
        target="_blank"
        rel="noopener"
      >

        <img
          src="/images/software-iris.png"
          alt="IRIS astronomical image analysis software"
        >

      </a>

      <div class="software-content">

        <h3>
          IRIS
        </h3>

        <p>
          Used for aperture photometry, pixel intensity measurement,
          and quantitative comparison between crescent brightness
          and twilight background.
        </p>

      </div>

    </article>


  </div>

</section>


<!-- =====================================================
     CURRENT RESEARCH
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Current Research
  </div>

  <h2 class="research-section-title">
    Tropical Twilight, Sky Brightness, and Crescent Visibility
  </h2>

  <div class="project-card">

    <p>
      Current research examines the relationship between tropical twilight,
      sky brightness, atmospheric conditions, and the visibility of the young
      lunar crescent. The project combines field observation, digital imaging,
      aperture photometry, and contrast analysis to strengthen empirical
      understanding of crescent detection under tropical atmospheric conditions.
    </p>

  </div>

</section>


<!-- =====================================================
     FUTURE DIRECTIONS
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Future Directions
  </div>

  <h2 class="research-section-title">
    Developing Evidence-Based Islamic Astronomy
  </h2>


  <div class="future-grid">


    <div class="future-card">

      <h3>
        Dark-Sky and Environmental Astronomy
      </h3>

      <p>
        Investigation of light pollution, sky quality,
        atmospheric transparency, and their implications
        for Islamic astronomical observation.
      </p>

    </div>


    <div class="future-card">

      <h3>
        Digital Crescent Detection
      </h3>

      <p>
        Development of quantitative and imaging-based approaches
        for identifying faint lunar crescents under challenging
        twilight conditions.
      </p>

    </div>


    <div class="future-card">

      <h3>
        Hijri Calendar Integration
      </h3>

      <p>
        Integration of observational astronomy, visibility models,
        legal reasoning, institutional authority, and social acceptance.
      </p>

    </div>


    <div class="future-card">

      <h3>
        Islamic Law and Astronomical Evidence
      </h3>

      <p>
        Development of interdisciplinary frameworks connecting
        empirical astronomical evidence with Islamic legal methodology
        and maqāṣid al-sharīʿah.
      </p>

    </div>


  </div>

</section>


<!-- =====================================================
     ROADMAP
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Research Trajectory
  </div>

  <h2 class="research-section-title">
    Long-Term Research Trajectory
  </h2>

  <p class="research-section-intro">
    The long-term research program develops progressively from astronomical
    observation and quantitative measurement toward interdisciplinary
    integration between astronomy, environmental studies, and Islamic law.
  </p>


  <div class="roadmap-wrapper">

    <a
      href="/images/roadmap-penelitian-hilal.png"
      target="_blank"
    >

      <img
        src="/images/roadmap-penelitian-hilal.png"
        alt="Research roadmap on crescent visibility and Islamic astronomy"
      >

    </a>

  </div>

</section>


<!-- =====================================================
     SELECTED PROJECTS
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Selected Projects
  </div>

  <h2 class="research-section-title">
    Research Projects
  </h2>


  <div class="project-grid">


    <div class="project-card">

      <h3>
        Crescent Visibility and Twilight Photometry
      </h3>

      <p>
        Quantitative investigation of crescent intensity,
        twilight background, and Weber contrast using digital astronomical images.
      </p>

    </div>


    <div class="project-card">

      <h3>
        Timau Observatory Dark-Sky Studies
      </h3>

      <p>
        Investigation of twilight thresholds, sky brightness,
        environmental conditions, and their relevance
        to astronomical observation.
      </p>

    </div>


    <div class="project-card">

      <h3>
        Digital Imaging for Rukyat al-Hilal
      </h3>

      <p>
        Application of digital cameras, telescopes,
        image processing, and photometric analysis
        to contemporary crescent observation.
      </p>

    </div>


    <div class="project-card">

      <h3>
        Hijri Calendar and Islamic Legal Reasoning
      </h3>

      <p>
        Study of astronomical criteria, hisab–rukyat,
        Islamic jurisprudence, institutional authority,
        and social acceptance of Hijri calendar systems.
      </p>

    </div>


  </div>

</section>


<!-- =====================================================
     OUTPUTS
===================================================== -->

<section class="research-section-block">

  <div class="research-section-label">
    Research Outputs
  </div>

  <h2 class="research-section-title">
    Scholarly Outputs
  </h2>

  <ul class="research-output-list">

    <li>
      Peer-reviewed journal articles in Islamic astronomy,
      Islamic law, crescent visibility, and Hijri calendar studies.
    </li>

    <li>
      Astronomical observation and photometric analysis
      of the hilal and twilight.
    </li>

    <li>
      Research on digital imaging technology for contemporary
      <em>rukyat al-hilal</em>.
    </li>

    <li>
      Interdisciplinary studies connecting astronomy,
      environmental science, Islamic jurisprudence,
      and maqāṣid al-sharīʿah.
    </li>

    <li>
      Academic books, conference papers, research reports,
      and teaching materials in Islamic astronomy and Islamic law.
    </li>

  </ul>

</section>


<!-- =====================================================
     FOOTER NAV
===================================================== -->

<div class="research-footer-nav">

  <a
    href="/"
    class="research-footer-button"
  >
    ← Back to Home
  </a>

  <a
    href="/main-publications/"
    class="research-footer-button"
  >
    Main Publications
  </a>

  <a
    href="/cv/"
    class="research-footer-button"
  >
    Academic CV →
  </a>

</div>


</div>


<!-- =====================================================
     INTERACTIVE SCRIPT
===================================================== -->

<script>

document.addEventListener(
  "DOMContentLoaded",
  function () {

    const nodes =
      document.querySelectorAll(".loop-node");

    let currentStep = 1;
    let autoPlay = null;


    function activateStep(step) {

      const stepString =
        String(step);

      nodes.forEach(
        function (node) {

          node.classList.toggle(
            "active",
            node.dataset.step === stepString
          );

        }
      );

      currentStep =
        Number(step);

    }


    function startAutoPlay() {

      clearInterval(autoPlay);

      autoPlay =
        setInterval(
          function () {

            currentStep++;

            if (currentStep > 6) {
              currentStep = 1;
            }

            activateStep(
              currentStep
            );

          },
          4500
        );

    }


    nodes.forEach(
      function (node) {

        node.addEventListener(
          "click",
          function () {

            activateStep(
              this.dataset.step
            );

            startAutoPlay();

          }
        );

      }
    );


    activateStep(1);

    startAutoPlay();

  }
);

</script>
