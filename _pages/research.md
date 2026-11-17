---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research program of Dr. Sakirman in Islamic astronomy, crescent visibility, twilight, astronomical photometry, digital imaging, Hijri calendar studies, and Islamic legal reasoning."
---

<style>

/* =========================================================
   HIDE AUTOMATIC ARCHIVE TITLE
========================================================= */

.page__title {
  display: none !important;
}


/* =========================================================
   RESEARCH PAGE
========================================================= */

.research-section {
  width: 100%;
}


/* =========================================================
   HERO
========================================================= */

.research-hero {
  margin-bottom: 3rem;
}

.research-kicker {
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

.research-hero-text:last-child {
  margin-bottom: 0;
}


/* =========================================================
   SECTION HEADINGS
========================================================= */

.research-section-block {
  margin-top: 3rem;
}

.research-section-label {
  display: inline-block;
  margin-bottom: 0.55rem;

  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.10em;
  text-transform: uppercase;

  opacity: 0.62;
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


/* =========================================================
   THEME BADGE
========================================================= */

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
  line-height: 1;
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
   INTERACTIVE RESEARCH LOOP
========================================================= */

.interactive-research-loop {
  display: grid;
  grid-template-columns: minmax(0, 1.08fr) minmax(320px, 0.92fr);
  gap: 3rem;
  align-items: center;

  margin-top: 2rem;
}


/* =========================================================
   LOOP DIAGRAM
========================================================= */

.loop-diagram {
  position: relative;

  width: min(100%, 660px);
  aspect-ratio: 1 / 1;

  margin: 0 auto;
}


/* OUTER STATIC CIRCLE */

.loop-outer-ring {
  position: absolute;
  inset: 5%;

  border: 1px solid rgba(110,140,210,0.22);
  border-radius: 50%;
}


/* INNER STATIC CIRCLE */

.loop-inner-ring {
  position: absolute;
  inset: 25%;

  border: 1px dashed rgba(110,140,210,0.18);
  border-radius: 50%;
}


/* =========================================================
   ROTATING DASHED RING
========================================================= */

.loop-rotating-ring {
  position: absolute;
  inset: 15%;

  border-radius: 50%;

  border:
    3px dashed rgba(0,184,217,0.85);

  animation:
    rotateResearchRing 15s linear infinite;

  box-shadow:
    0 0 18px rgba(0,184,217,0.05);

  pointer-events: none;
}

.loop-rotating-ring::before {
  content: "";

  position: absolute;
  inset: -3px;

  border-radius: 50%;

  border:
    3px dashed rgba(172,100,255,0.40);

  transform: rotate(35deg);
}

@keyframes rotateResearchRing {

  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }

}


/* =========================================================
   CENTER
========================================================= */

.loop-center {
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  width: 245px;
  height: 245px;

  padding: 1.3rem;

  border: 1px solid rgba(0,184,217,0.70);
  border-radius: 50%;

  background:
    radial-gradient(
      circle,
      rgba(100,70,160,0.14) 0%,
      rgba(0,184,217,0.04) 55%,
      transparent 100%
    );

  text-align: center;

  transform: translate(-50%, -50%);

  box-shadow:
    0 0 30px rgba(0,184,217,0.08);

  animation:
    centerPulse 3.2s ease-in-out infinite;
}

@keyframes centerPulse {

  0%,
  100% {
    box-shadow:
      0 0 20px rgba(0,184,217,0.08);
  }

  50% {
    box-shadow:
      0 0 42px rgba(0,184,217,0.20);
  }

}

.loop-center-label {
  margin-bottom: 0.55rem;

  font-size: 0.66rem;
  font-weight: 700;
  letter-spacing: 0.15em;
  text-transform: uppercase;

  opacity: 0.55;
}

.loop-center-title {
  font-size: 1.32rem;
  line-height: 1.35;
  font-weight: 700;
}


/* =========================================================
   LOOP NODES
========================================================= */

.loop-node {
  position: absolute;
  z-index: 5;

  width: 205px;

  padding: 0.8rem 0.9rem;

  border: 1px solid rgba(110,140,210,0.34);
  border-radius: 10px;

  background: rgba(20,25,35,0.10);

  cursor: pointer;

  text-align: left;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease,
    box-shadow 0.22s ease,
    background 0.22s ease;
}

.loop-node:hover {
  border-color: #00b8d9;

  box-shadow:
    0 0 20px rgba(0,184,217,0.12);

  transform: translateY(-3px);
}

.loop-node.active {
  border-color: #00b8d9;

  background:
    rgba(0,184,217,0.06);

  box-shadow:
    0 0 20px rgba(0,184,217,0.14);
}

.loop-node-number {
  display: inline-block;

  margin-right: 0.5rem;

  color: #00c9ee;

  font-size: 0.68rem;
  font-weight: 700;
}

.loop-node-title {
  font-size: 0.8rem;
  line-height: 1.3;
  font-weight: 700;
}

.loop-node-meta {
  display: block;

  margin-top: 0.35rem;

  font-size: 0.66rem;
  line-height: 1.4;

  opacity: 0.58;
}


/* =========================================================
   NODE POSITIONS
========================================================= */

.loop-node-1 {
  top: 1%;
  left: 50%;

  transform: translateX(-50%);
}

.loop-node-1:hover {
  transform:
    translateX(-50%)
    translateY(-3px);
}

.loop-node-2 {
  top: 20%;
  right: -2%;
}

.loop-node-3 {
  top: 46%;
  right: -4%;
}

.loop-node-4 {
  bottom: 1%;
  right: 13%;
}

.loop-node-5 {
  bottom: 1%;
  left: 13%;
}

.loop-node-6 {
  top: 46%;
  left: -4%;
}

.loop-node-7 {
  top: 20%;
  left: -2%;
}


/* =========================================================
   DETAILS PANEL
========================================================= */

.loop-details {
  width: 100%;
}

.loop-detail-item {
  display: flex;

  gap: 1rem;

  padding: 1rem 0;

  border-bottom:
    1px dashed rgba(127,127,127,0.22);

  cursor: pointer;

  opacity: 0.48;

  transition:
    opacity 0.2s ease,
    transform 0.2s ease;
}

.loop-detail-item:hover {
  opacity: 0.80;
}

.loop-detail-item.active {
  opacity: 1;
}

.loop-detail-item.active .loop-detail-number {
  background: rgba(0,184,217,0.08);

  box-shadow:
    0 0 12px rgba(0,184,217,0.08);
}

.loop-detail-number {
  flex: 0 0 auto;

  display: flex;
  align-items: center;
  justify-content: center;

  width: 36px;
  height: 30px;

  border:
    1px solid rgba(0,184,217,0.55);

  border-radius: 7px;

  color: #00c9ee;

  font-size: 0.72rem;
  font-weight: 700;
}

.loop-detail-text {
  margin: 0;

  font-size: 0.91rem;
  line-height: 1.7;
}

.loop-detail-text strong {
  font-weight: 700;
}


/* =========================================================
   SOFTWARE
========================================================= */

.software-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));

  gap: 1.15rem;
}

.software-card {
  overflow: hidden;

  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;

  background: transparent;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.software-card:hover {
  border-color: #00b8d9;

  transform: translateY(-3px);
}

.software-card a {
  display: block;
  overflow: hidden;
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
  transform: scale(1.045);
}

.software-content {
  padding: 1rem 1.2rem 1.2rem;

  border-top:
    1px solid rgba(127,127,127,0.18);
}

.software-content h3 {
  margin: 0 0 0.45rem 0;

  font-size: 1rem;
}

.software-content p {
  margin: 0;

  font-size: 0.84rem;
  line-height: 1.65;

  opacity: 0.78;
}


/* =========================================================
   PROJECT / FUTURE CARDS
========================================================= */

.project-card,
.future-card {
  padding: 1.2rem 1.25rem;

  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;

  background: transparent;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.project-card:hover,
.future-card:hover {
  border-color: #00b8d9;

  transform: translateY(-3px);
}

.project-card h3,
.future-card h3 {
  margin: 0 0 0.55rem 0;

  font-size: 1rem;
}

.project-card p,
.future-card p {
  margin: 0;

  font-size: 0.86rem;
  line-height: 1.7;

  opacity: 0.8;
}


/* =========================================================
   FUTURE DIRECTIONS
========================================================= */

.future-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));

  gap: 1rem;
}


/* =========================================================
   ROADMAP
========================================================= */

.roadmap-wrapper {
  margin-top: 1.4rem;

  text-align: center;
}

.roadmap-wrapper a {
  display: inline-block;

  overflow: hidden;

  border-radius: 10px;
}

.roadmap-wrapper img {
  display: block;

  width: 100%;
  max-width: 680px;
  height: auto;

  margin: 0 auto;

  border:
    1px solid rgba(127,127,127,0.20);

  border-radius: 10px;

  transition:
    transform 0.45s ease;
}

.roadmap-wrapper a:hover img {
  transform: scale(1.025);
}


/* =========================================================
   SELECTED PROJECTS
========================================================= */

.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));

  gap: 1rem;
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
   FOOTER NAVIGATION
========================================================= */

.research-footer-nav {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;

  gap: 0.7rem;

  margin-top: 3rem;
  padding-top: 1.5rem;

  border-top:
    1px solid rgba(127,127,127,0.22);
}

.research-footer-button {
  display: inline-block;

  padding: 0.55rem 0.85rem;

  border:
    1px solid rgba(127,127,127,0.30);

  border-radius: 8px;

  font-size: 0.78rem;
  font-weight: 700;

  text-decoration: none !important;

  transition:
    color 0.2s ease,
    border-color 0.2s ease,
    transform 0.2s ease;
}

.research-footer-button:hover,
.research-footer-button:focus {
  color: #00b8d9 !important;

  border-color: #00b8d9 !important;

  transform: translateY(-2px);
}


/* =========================================================
   RESPONSIVE
========================================================= */

@media (max-width: 1100px) {

  .interactive-research-loop {
    grid-template-columns: 1fr;
  }

  .loop-details {
    margin-top: 1rem;
  }

}


@media (max-width: 768px) {

  .research-title {
    font-size: 1.5rem;
  }

  .research-subtitle {
    font-size: 1.05rem;
  }

  .research-grid,
  .software-grid,
  .future-grid,
  .project-grid {
    grid-template-columns: 1fr;
  }

  .research-card img {
    height: 210px;
  }

  .research-card:hover,
  .software-card:hover,
  .project-card:hover,
  .future-card:hover,
  .research-footer-button:hover {
    transform: none;
  }

  .research-card:hover img,
  .software-card:hover img {
    transform: none;
  }

  .research-footer-nav {
    justify-content: flex-start;
  }

}


@media (max-width: 700px) {

  .loop-diagram {
    display: none;
  }

  .interactive-research-loop {
    display: block;
  }

  .loop-detail-item {
    opacity: 1;
  }

}


@media (max-width: 480px) {

  .research-card img {
    height: 190px;
  }

  .research-theme-badge {
    top: 10px;
    left: 10px;

    padding: 0.34rem 0.5rem;

    font-size: 0.62rem;
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
          aperture photometry, Weber contrast, sky quality, and observational
          thresholds.
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
    The research workflow integrates astronomical observation, digital imaging,
    quantitative photometry, contrast analysis, astronomical interpretation,
    and Islamic legal reasoning.
  </p>


  <div class="interactive-research-loop">


    <!-- =====================================================
         LEFT: RESEARCH LOOP
    ====================================================== -->

    <div class="loop-diagram">

      <div class="loop-outer-ring"></div>

      <div class="loop-inner-ring"></div>

      <div class="loop-rotating-ring"></div>


      <div class="loop-center">

        <span class="loop-center-label">
          Research Loop
        </span>

        <div class="loop-center-title">
          From Observation<br>
          to Evidence
        </div>

      </div>



      <div
        class="loop-node loop-node-1 active"
        data-step="1"
      >

        <span class="loop-node-number">
          01
        </span>

        <span class="loop-node-title">
          Crescent Observation
        </span>

        <span class="loop-node-meta">
          hilal · twilight · geometry
        </span>

      </div>



      <div
        class="loop-node loop-node-2"
        data-step="2"
      >

        <span class="loop-node-number">
          02
        </span>

        <span class="loop-node-title">
          Digital Image Acquisition
        </span>

        <span class="loop-node-meta">
          camera · telescope · RAW
        </span>

      </div>



      <div
        class="loop-node loop-node-3"
        data-step="3"
      >

        <span class="loop-node-number">
          03
        </span>

        <span class="loop-node-title">
          Image Pre-Processing
        </span>

        <span class="loop-node-meta">
          calibration · Siril
        </span>

      </div>



      <div
        class="loop-node loop-node-4"
        data-step="4"
      >

        <span class="loop-node-number">
          04
        </span>

        <span class="loop-node-title">
          Aperture Photometry
        </span>

        <span class="loop-node-meta">
          IRIS · intensity
        </span>

      </div>



      <div
        class="loop-node loop-node-5"
        data-step="5"
      >

        <span class="loop-node-number">
          05
        </span>

        <span class="loop-node-title">
          Contrast Analysis
        </span>

        <span class="loop-node-meta">
          Weber contrast
        </span>

      </div>



      <div
        class="loop-node loop-node-6"
        data-step="6"
      >

        <span class="loop-node-number">
          06
        </span>

        <span class="loop-node-title">
          Astronomical Interpretation
        </span>

        <span class="loop-node-meta">
          visibility · atmosphere
        </span>

      </div>



      <div
        class="loop-node loop-node-7"
        data-step="7"
      >

        <span class="loop-node-number">
          07
        </span>

        <span class="loop-node-title">
          Islamic Legal Analysis
        </span>

        <span class="loop-node-meta">
          hisab–rukyat · maqāṣid
        </span>

      </div>

    </div>



    <!-- =====================================================
         RIGHT: EXPLANATION
    ====================================================== -->

    <div class="loop-details">


      <div
        class="loop-detail-item active"
        data-step="1"
      >

        <span class="loop-detail-number">
          01
        </span>

        <p class="loop-detail-text">
          <strong>Crescent Observation</strong> establishes the empirical
          foundation of the research through direct observation of the
          <em>hilal</em>, twilight conditions, lunar geometry, and atmospheric
          circumstances.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="2"
      >

        <span class="loop-detail-number">
          02
        </span>

        <p class="loop-detail-text">
          <strong>Digital Image Acquisition</strong> records astronomical
          observations using cameras and telescopes while preserving RAW image
          data for subsequent quantitative analysis.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="3"
      >

        <span class="loop-detail-number">
          03
        </span>

        <p class="loop-detail-text">
          <strong>Image Pre-Processing</strong> prepares observational data
          through calibration, correction, enhancement, and astronomical image
          processing using software such as Siril.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="4"
      >

        <span class="loop-detail-number">
          04
        </span>

        <p class="loop-detail-text">
          <strong>Aperture Photometry</strong> measures pixel intensity and
          astronomical brightness using IRIS to quantify the crescent signal
          and surrounding twilight background.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="5"
      >

        <span class="loop-detail-number">
          05
        </span>

        <p class="loop-detail-text">
          <strong>Contrast Analysis</strong> evaluates the visual separation
          between the crescent and sky background, including the use of Weber
          contrast as a quantitative indicator of visibility.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="6"
      >

        <span class="loop-detail-number">
          06
        </span>

        <p class="loop-detail-text">
          <strong>Astronomical Interpretation</strong> connects photometric
          measurements with atmospheric conditions, lunar geometry, twilight
          brightness, and crescent visibility criteria.
        </p>

      </div>



      <div
        class="loop-detail-item"
        data-step="7"
      >

        <span class="loop-detail-number">
          07
        </span>

        <p class="loop-detail-text">
          <strong>Islamic Legal Analysis</strong> interprets the astronomical
          evidence within the frameworks of <em>hisab–rukyat</em>, Islamic
          jurisprudence, and maqāṣid al-sharīʿah.
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
          Used for astronomical image calibration, preprocessing, stacking,
          enhancement, and preparation of observational image data.
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
          Used for aperture photometry, pixel intensity measurement, and
          quantitative comparison between crescent brightness and twilight
          background.
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
      understanding of crescent detection under tropical atmospheric
      conditions.
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
        Investigation of light pollution, sky quality, atmospheric
        transparency, and their implications for Islamic astronomical
        observation.
      </p>

    </div>



    <div class="future-card">

      <h3>
        Digital Crescent Detection
      </h3>

      <p>
        Development of quantitative and imaging-based approaches for
        identifying faint lunar crescents under challenging twilight
        conditions.
      </p>

    </div>



    <div class="future-card">

      <h3>
        Hijri Calendar Integration
      </h3>

      <p>
        Integration of observational astronomy, visibility models, legal
        reasoning, institutional authority, and social acceptance in Hijri
        calendar studies.
      </p>

    </div>



    <div class="future-card">

      <h3>
        Islamic Law and Astronomical Evidence
      </h3>

      <p>
        Development of interdisciplinary frameworks connecting empirical
        astronomical evidence with Islamic legal methodology and maqāṣid
        al-sharīʿah.
      </p>

    </div>

  </div>

</section>



<!-- =====================================================
     RESEARCH TRAJECTORY
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
        Quantitative investigation of crescent intensity, twilight background,
        and Weber contrast using digital astronomical images.
      </p>

    </div>



    <div class="project-card">

      <h3>
        Timau Observatory Dark-Sky Studies
      </h3>

      <p>
        Investigation of twilight thresholds, sky brightness, environmental
        conditions, and their relevance to astronomical observation.
      </p>

    </div>



    <div class="project-card">

      <h3>
        Digital Imaging for Rukyat al-Hilal
      </h3>

      <p>
        Application of digital cameras, telescopes, image processing, and
        photometric analysis to contemporary crescent observation.
      </p>

    </div>



    <div class="project-card">

      <h3>
        Hijri Calendar and Islamic Legal Reasoning
      </h3>

      <p>
        Study of astronomical criteria, hisab–rukyat, Islamic jurisprudence,
        institutional authority, and social acceptance of Hijri calendar
        systems.
      </p>

    </div>

  </div>

</section>



<!-- =====================================================
     RESEARCH OUTPUTS
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
      Peer-reviewed journal articles in Islamic astronomy, Islamic law,
      crescent visibility, and Hijri calendar studies.
    </li>

    <li>
      Astronomical observation and photometric analysis of the hilal and
      twilight.
    </li>

    <li>
      Research on digital imaging technology for contemporary
      <em>rukyat al-hilal</em>.
    </li>

    <li>
      Interdisciplinary studies connecting astronomy, environmental science,
      Islamic jurisprudence, and maqāṣid al-sharīʿah.
    </li>

    <li>
      Academic books, conference papers, research reports, and teaching
      materials in Islamic astronomy and Islamic law.
    </li>

  </ul>

</section>



<!-- =====================================================
     FOOTER NAVIGATION
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

document.addEventListener("DOMContentLoaded", function () {

  const nodes =
    document.querySelectorAll(".loop-node");

  const details =
    document.querySelectorAll(".loop-detail-item");


  function activateStep(step) {

    nodes.forEach(function (node) {

      if (node.dataset.step === step) {

        node.classList.add("active");

      } else {

        node.classList.remove("active");

      }

    });


    details.forEach(function (detail) {

      if (detail.dataset.step === step) {

        detail.classList.add("active");

      } else {

        detail.classList.remove("active");

      }

    });

  }


  nodes.forEach(function (node) {

    node.addEventListener(
      "click",
      function () {

        activateStep(
          this.dataset.step
        );

      }
    );

  });


  details.forEach(function (detail) {

    detail.addEventListener(
      "click",
      function () {

        activateStep(
          this.dataset.step
        );

      }
    );

  });

});

</script>
