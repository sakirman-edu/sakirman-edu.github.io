---
title: "Research"
permalink: /research/
author_profile: true
description: "Research on Islamic astronomy, crescent visibility, tropical twilight, astronomical photometry, digital image processing, and Hijri calendar studies."
---

{% include base_path %}

<style>

/* =========================================================
   GENERAL RESEARCH PAGE
========================================================= */

.research-hero {
  margin-bottom: 3rem;
}

.research-kicker {
  font-size: 0.78em;
  text-transform: uppercase;
  letter-spacing: 0.14em;
  font-weight: 700;
  opacity: 0.75;
  margin-bottom: 0.6rem;
}

.research-hero h1 {
  font-size: 2.2em;
  line-height: 1.2;
  margin-bottom: 1rem;
}

.research-hero p {
  font-size: 1.02em;
  line-height: 1.75;
  max-width: 850px;
}

.research-section {
  margin-top: 3.5rem;
  margin-bottom: 3rem;
}

.research-section h2 {
  margin-bottom: 0.5rem;
}

.research-intro {
  opacity: 0.9;
  margin-bottom: 1.5rem;
}


/* =========================================================
   GRIDS
========================================================= */

.research-grid,
.software-grid,
.project-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
}


/* =========================================================
   RESEARCH / SOFTWARE / PROJECT CARDS
========================================================= */

.research-card,
.software-card,
.project-card {
  border: 1px solid rgba(128,128,128,0.28);
  border-radius: 10px;
  overflow: hidden;
  background: rgba(128,128,128,0.035);
}

.research-card a,
.software-card a {
  display: block;
}

.research-card img,
.software-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
  transition: transform 0.25s ease;
}

.research-card a:hover img,
.software-card a:hover img {
  transform: scale(1.02);
}

.research-card-content,
.software-content,
.project-card {
  padding: 1rem 1.1rem 1.15rem 1.1rem;
}

.research-card h3,
.software-content h3,
.project-card h3 {
  margin-top: 0;
  margin-bottom: 0.55rem;
  font-size: 1.08em;
}

.research-card p,
.software-content p,
.project-card p {
  margin-bottom: 0.7rem;
  line-height: 1.6;
  font-size: 0.94em;
}


/* =========================================================
   TAGS
========================================================= */

.research-tag {
  display: inline-block;
  border: 1px solid rgba(128,128,128,0.30);
  border-radius: 999px;
  padding: 0.18rem 0.55rem;
  margin: 0.15rem 0.2rem 0.15rem 0;
  font-size: 0.72em;
  letter-spacing: 0.02em;
}


/* =========================================================
   INTERACTIVE CIRCULAR METHODOLOGY
========================================================= */

.method-simulation {
  margin-top: 2rem;
}

.method-circle-wrap {
  position: relative;
  width: 700px;
  max-width: 100%;
  height: 700px;
  margin: 2rem auto 1rem auto;
}


/* Animated orbit */

.method-orbit {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 480px;
  height: 480px;
  transform: translate(-50%, -50%);
  border: 1px dashed rgba(0,184,217,0.60);
  border-radius: 50%;
  animation: methodRotate 28s linear infinite;
}

.method-orbit::before {
  content: "";
  position: absolute;
  top: -5px;
  left: 50%;
  width: 10px;
  height: 10px;
  background: #00b8d9;
  border-radius: 50%;
  transform: translateX(-50%);
}

@keyframes methodRotate {
  from {
    transform: translate(-50%, -50%) rotate(0deg);
  }

  to {
    transform: translate(-50%, -50%) rotate(360deg);
  }
}


/* Center */

.method-center {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 210px;
  height: 210px;
  transform: translate(-50%, -50%);
  border: 2px solid #00b8d9;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 1.5rem;
  background: var(--global-bg-color);
  z-index: 5;
}

.method-center-kicker {
  display: block;
  margin-bottom: 0.45rem;
  color: #00b8d9;
  font-size: 0.68rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.method-center-title {
  display: block;
  font-size: 0.95rem;
  font-weight: 700;
  line-height: 1.45;
}


/* Nodes */

.method-node {
  position: absolute;
  width: 165px;
  min-height: 78px;
  padding: 0.8rem 0.85rem;
  border: 1px solid rgba(128,128,128,0.32);
  border-radius: 10px;
  background: var(--global-bg-color);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  font-size: 0.78rem;
  font-weight: 700;
  line-height: 1.35;
  cursor: default;
  z-index: 10;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease,
    color 0.22s ease;
}

.method-node:hover,
.method-node:focus {
  border-color: #00b8d9;
  color: #00b8d9;
  outline: none;
}


/* Step numbers */

.method-step-number {
  display: block;
  margin-right: 0.4rem;
  color: #00b8d9;
  font-size: 0.67rem;
}


/* Node positions */

.method-node-1 {
  top: 1%;
  left: 50%;
  transform: translateX(-50%);
}

.method-node-1:hover,
.method-node-1:focus {
  transform: translateX(-50%) translateY(-4px);
}

.method-node-2 {
  top: 18%;
  right: 2%;
}

.method-node-2:hover,
.method-node-2:focus {
  transform: translateY(-4px);
}

.method-node-3 {
  top: 49%;
  right: -1%;
}

.method-node-3:hover,
.method-node-3:focus {
  transform: translateY(-4px);
}

.method-node-4 {
  bottom: 3%;
  right: 16%;
}

.method-node-4:hover,
.method-node-4:focus {
  transform: translateY(-4px);
}

.method-node-5 {
  bottom: 3%;
  left: 16%;
}

.method-node-5:hover,
.method-node-5:focus {
  transform: translateY(-4px);
}

.method-node-6 {
  top: 49%;
  left: -1%;
}

.method-node-6:hover,
.method-node-6:focus {
  transform: translateY(-4px);
}

.method-node-7 {
  top: 18%;
  left: 2%;
}

.method-node-7:hover,
.method-node-7:focus {
  transform: translateY(-4px);
}


/* Tooltip */

.method-node-detail {
  position: absolute;
  bottom: calc(100% + 10px);
  left: 50%;
  width: 245px;
  padding: 0.75rem 0.85rem;

  transform:
    translateX(-50%)
    translateY(6px);

  border: 1px solid rgba(0,184,217,0.60);
  border-radius: 8px;
  background: var(--global-bg-color);

  font-size: 0.72rem;
  font-weight: 400;
  line-height: 1.5;
  text-align: left;
  color: var(--global-text-color);

  opacity: 0;
  visibility: hidden;
  pointer-events: none;

  transition:
    opacity 0.2s ease,
    transform 0.2s ease;

  z-index: 40;
}

.method-node:hover .method-node-detail,
.method-node:focus .method-node-detail {
  opacity: 1;
  visibility: visible;

  transform:
    translateX(-50%)
    translateY(0);
}


/* Cycle note */

.method-cycle-note {
  max-width: 800px;
  margin: 1rem auto 2rem auto;
  padding-top: 1rem;
  border-top: 1px solid rgba(128,128,128,0.25);
  text-align: center;
  font-size: 0.83rem;
  line-height: 1.7;
  opacity: 0.82;
}


/* =========================================================
   ANALYTICAL TOOLS
========================================================= */

.method-tools-heading {
  margin-top: 3rem;
  margin-bottom: 0.5rem;
}

.method-tools-intro {
  max-width: 820px;
  margin-bottom: 1rem;
  line-height: 1.7;
  opacity: 0.9;
}

.software-grid {
  margin-top: 1.8rem;
}

.software-link {
  display: inline-block;
  margin-top: 0.15rem;
  font-size: 0.9em;
  font-weight: 600;
  text-decoration: none;
}

.software-link:hover {
  text-decoration: underline;
}


/* =========================================================
   FUTURE DIRECTIONS
========================================================= */

.future-card {
  border: 1px solid rgba(128,128,128,0.28);
  border-radius: 10px;
  padding: 1rem 1.1rem;
  margin-bottom: 0.9rem;
}

.future-card strong {
  display: block;
  margin-bottom: 0.35rem;
}


/* =========================================================
   ROADMAP
========================================================= */

.roadmap-box {
  text-align: center;
  margin-top: 1.5rem;
}

.roadmap-box a {
  display: inline-block;
}

.roadmap-box img {
  width: 100%;
  max-width: 680px;
  height: auto;
  border-radius: 8px;
}


/* =========================================================
   OUTPUT LINKS
========================================================= */

.output-links {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
  margin-top: 1rem;
}

.output-link {
  display: inline-block;
  border: 1px solid rgba(128,128,128,0.30);
  border-radius: 999px;
  padding: 0.5rem 0.85rem;
  text-decoration: none;
  font-weight: 600;
}

.output-link:hover {
  text-decoration: none;
}


/* =========================================================
   MOBILE
========================================================= */

@media (max-width: 760px) {

  .research-grid,
  .software-grid,
  .project-grid {
    grid-template-columns: 1fr;
  }

  .research-hero h1 {
    font-size: 1.7em;
  }

  .research-card img,
  .software-card img {
    height: 200px;
  }

  .method-circle-wrap {
    width: 100%;
    height: auto;
    margin-top: 1.5rem;
  }

  .method-orbit {
    display: none;
  }

  .method-center {
    position: relative;
    top: auto;
    left: auto;
    width: 185px;
    height: 185px;
    transform: none;
    margin: 0 auto 1.5rem auto;
  }

  .method-node {
    position: relative;
    top: auto !important;
    right: auto !important;
    bottom: auto !important;
    left: auto !important;

    width: 100%;
    min-height: auto;
    margin-bottom: 0.75rem;

    transform: none !important;

    justify-content: flex-start;
    text-align: left;
  }

  .method-node:hover,
  .method-node:focus {
    transform: translateY(-2px) !important;
  }

  .method-node-detail {
    position: relative;
    bottom: auto;
    left: auto;

    width: 100%;
    margin-top: 0.65rem;

    transform: none;

    opacity: 1;
    visibility: visible;

    border: 0;
    border-top: 1px solid rgba(128,128,128,0.25);
  }

}
</style>


<!-- ======================================================
     RESEARCH HERO
====================================================== -->

<div class="research-hero">

  <div class="research-kicker">
    Research Program
  </div>

  <h1>
    From astronomical observation to Islamic legal reasoning
  </h1>

  <p>
    My research explores the intersection of
    <strong>Islamic astronomy, observational science, and Islamic law</strong>.
    It focuses particularly on crescent visibility, twilight, sky brightness,
    astronomical photometry, digital image processing, Hijri calendar systems,
    and the integration of scientific evidence with Islamic legal reasoning.
  </p>

  <p>
    A central objective of this research program is to develop
    <strong>evidence-based approaches to astronomy for Islamic religious practices</strong>,
    linking observation, quantitative analysis, and legal interpretation in the
    study of the <em>hilal</em>, prayer times, qibla direction, and the Hijri calendar.
  </p>

</div>


<!-- ======================================================
     RESEARCH THEMES
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Research Themes
  </div>

  <h2>
    Four Research Themes
  </h2>

  <p class="research-intro">
    My research is organized around four interconnected themes covering
    observational astronomy, quantitative measurement, Hijri calendar studies,
    and digital image processing.
  </p>

  <div class="research-grid">


    <div class="research-card">

      <a href="{{ base_path }}/images/hilal-twilight.jpg"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/hilal-twilight.jpg"
             alt="Young crescent Moon observed during twilight">

      </a>

      <div class="research-card-content">

        <h3>
          Crescent Visibility and Twilight
        </h3>

        <p>
          Investigating the visibility of the young crescent Moon during
          twilight, with particular attention to sky brightness, solar
          depression, atmospheric conditions, lunar geometry, and the
          changing contrast between the crescent and its background.
        </p>

        <span class="research-tag">Hilal</span>
        <span class="research-tag">Twilight</span>
        <span class="research-tag">Sky Brightness</span>
        <span class="research-tag">Visibility</span>

      </div>

    </div>


    <div class="research-card">

      <a href="{{ base_path }}/images/Analisis-IRIS.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/Analisis-IRIS.png"
             alt="Astronomical photometric measurement of crescent Moon images">

      </a>

      <div class="research-card-content">

        <h3>
          Astronomical Photometry and Quantitative Measurement
        </h3>

        <p>
          Quantifying crescent intensity, twilight-background brightness,
          and their relative contrast through aperture-based photometric
          measurement. This approach provides numerical evidence for
          evaluating crescent detectability under changing sky conditions.
        </p>

        <span class="research-tag">Photometry</span>
        <span class="research-tag">Intensity</span>
        <span class="research-tag">Contrast</span>
        <span class="research-tag">Quantitative Analysis</span>

      </div>

    </div>


    <div class="research-card">

      <a href="{{ base_path }}/images/kalender-hijriyah-2027.jpg"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/kalender-hijriyah-2027.jpg"
             alt="Hijri calendar and astronomical calendar determination">

      </a>

      <div class="research-card-content">

        <h3>
          Hijri Calendar and Hisab–Rukyat Integration
        </h3>

        <p>
          Examining the astronomical and juridical foundations of Hijri calendar
          construction, including lunar-cycle parameters, crescent visibility
          criteria, <em>hisab</em> calculations, <em>rukyat</em> observations,
          and their integration within contemporary Islamic legal reasoning.
        </p>

        <span class="research-tag">Hijri Calendar</span>
        <span class="research-tag">Hisab</span>
        <span class="research-tag">Rukyat</span>
        <span class="research-tag">MABIMS</span>

      </div>

    </div>


    <div class="research-card">

      <a href="{{ base_path }}/images/olah-citra.jpg"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/olah-citra.jpg"
             alt="Digital image processing for crescent Moon detection">

      </a>

      <div class="research-card-content">

        <h3>
          Digital Image Processing and Crescent Detection
        </h3>

        <p>
          Exploring computational techniques to enhance, identify, and analyze
          faint crescent signals embedded in strong twilight illumination.
          Digital processing supports more objective crescent detection and
          strengthens the reliability of subsequent quantitative analysis.
        </p>

        <span class="research-tag">Image Processing</span>
        <span class="research-tag">Crescent Detection</span>
        <span class="research-tag">Digital Astronomy</span>
        <span class="research-tag">Ilmu Falak</span>

      </div>

    </div>

  </div>

</div>


<!-- ======================================================
     METHODOLOGY
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Methodology
  </div>

  <h2>
    From Observation to Evidence-Based Islamic Legal Analysis
  </h2>

  <p class="research-intro">
    My methodological approach integrates direct astronomical observation,
    digital image acquisition, image preprocessing, quantitative photometric
    measurement, contrast analysis, astronomical interpretation, and Islamic
    legal reasoning. The process is iterative: empirical findings inform
    interpretation, while astronomical and legal questions generate new
    observational problems.
  </p>


  <div class="method-simulation">

    <div class="method-circle-wrap">

      <div class="method-orbit"></div>


      <!-- CENTER -->

      <div class="method-center">

        <div>

          <span class="method-center-kicker">
            RESEARCH LOOP
          </span>

          <span class="method-center-title">
                  </span>

        </div>

      </div>


      <!-- STEP 01 -->

      <div class="method-node method-node-1"
           tabindex="0">

        <span class="method-step-number">
          01
        </span>

        Crescent Observation

        <div class="method-node-detail">
          Direct observation of the young crescent Moon under defined
          astronomical and atmospheric conditions, including lunar altitude,
          elongation, solar depression, horizon condition, and twilight brightness.
        </div>

      </div>


      <!-- STEP 02 -->

      <div class="method-node method-node-2"
           tabindex="0">

        <span class="method-step-number">
          02
        </span>

        Digital Image Acquisition

        <div class="method-node-detail">
          Acquisition of astronomical images using digital cameras or
          observational instruments to create reproducible records of the
          crescent and surrounding twilight sky.
        </div>

      </div>


      <!-- STEP 03 -->

      <div class="method-node method-node-3"
           tabindex="0">

        <span class="method-step-number">
          03
        </span>

        Image Pre-Processing

        <div class="method-node-detail">
          Calibration, alignment, noise reduction, enhancement,
          and contrast adjustment before quantitative photometric measurement.
        </div>

      </div>


      <!-- STEP 04 -->

      <div class="method-node method-node-4"
           tabindex="0">

        <span class="method-step-number">
          04
        </span>

        Aperture Photometry

        <div class="method-node-detail">
          Measurement of crescent intensity and adjacent twilight-background
          intensity using aperture-based astronomical photometry.
        </div>

      </div>


      <!-- STEP 05 -->

      <div class="method-node method-node-5"
           tabindex="0">

        <span class="method-step-number">
          05
        </span>

        Contrast Analysis

        <div class="method-node-detail">
          Evaluation of crescent detectability by comparing crescent intensity
          with surrounding sky-background intensity, including quantitative
          indicators such as Weber contrast.
        </div>

      </div>


      <!-- STEP 06 -->

      <div class="method-node method-node-6"
           tabindex="0">

        <span class="method-step-number">
          06
        </span>

        Astronomical Interpretation

        <div class="method-node-detail">
          Interpretation of observational and photometric evidence in relation
          to lunar geometry, solar depression, atmospheric conditions,
          twilight characteristics, and crescent visibility models.
        </div>

      </div>


      <!-- STEP 07 -->

      <div class="method-node method-node-7"
           tabindex="0">

        <span class="method-step-number">
          07
        </span>

        Islamic Legal Analysis

        <div class="method-node-detail">
          Analysis of astronomical evidence within hisab–rukyat,
          Islamic legal reasoning, maqāṣid al-sharī‘ah,
          institutional authority, and contemporary Hijri calendar studies.
        </div>

      </div>

    </div>


    <div class="method-cycle-note">

      <strong>Iterative Research Cycle:</strong>
      astronomical and Islamic legal questions generate new observational
      problems, allowing the research process to return to observation
      and progressively strengthen its empirical evidence.

    </div>

  </div>


  <!-- ====================================================
       ANALYTICAL TOOLS
  ===================================================== -->

  <div class="research-kicker method-tools-heading">
    Analytical Tools
  </div>

  <h2>
    Software for Image Processing and Photometric Analysis
  </h2>

  <p class="method-tools-intro">
    Digital image processing and quantitative photometric analysis are
    supported by astronomical software used at different stages of the
    methodological workflow. Siril supports image preprocessing, while
    IRIS is used for aperture-based quantitative measurement.
  </p>


  <div class="software-grid">


    <div class="software-card">

      <a href="{{ base_path }}/images/software-siril.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/software-siril.png"
             alt="Siril software used for astronomical image processing">

      </a>

      <div class="software-content">

        <h3>
          Siril-Based Astronomical Image Processing
        </h3>

        <p>
          <strong>Siril</strong> is used for astronomical image preprocessing,
          including calibration, enhancement, alignment, noise reduction, and
          contrast adjustment. These procedures improve image quality and help
          separate faint lunar features from strong twilight background
          illumination before quantitative analysis.
        </p>

        <a class="software-link"
           href="https://siril.org/"
           target="_blank"
           rel="noopener noreferrer">

          Visit Siril Official Website →

        </a>

      </div>

    </div>


    <div class="software-card">

      <a href="{{ base_path }}/images/software-iris.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/software-iris.png"
             alt="IRIS software used for crescent photometric analysis">

      </a>

      <div class="software-content">

        <h3>
          IRIS-Based Crescent Photometry
        </h3>

        <p>
          <strong>IRIS</strong> is used for aperture-based photometric analysis
          of the crescent and adjacent twilight sky. The measurements provide
          quantitative values of crescent intensity, background intensity, and
          relative contrast, supporting objective evaluation of crescent
          detectability and visibility criteria.
        </p>

        <a class="software-link"
           href="https://buil.astrosurf.com/iris-software.html"
           target="_blank"
           rel="noopener noreferrer">

          Visit IRIS Software Page →

        </a>

      </div>

    </div>

  </div>

</div>


<!-- ======================================================
     CURRENT RESEARCH FOCUS
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Current Research Focus
  </div>

  <h2>
    Tropical Twilight, Sky Brightness, and Crescent Visibility
  </h2>

  <p>
    My current research focuses on the relationship between
    <strong>tropical twilight conditions, sky brightness, atmospheric conditions,
    and low-altitude crescent visibility</strong>. Particular attention is given
    to how variations in background sky brightness influence the detectability
    of the young crescent Moon and the measurable contrast between the crescent
    signal and its surrounding twilight background.
  </p>

  <p>
    The research integrates observational astronomy, digital image processing,
    aperture photometry, contrast analysis, astronomical modeling, and Islamic
    legal interpretation. Its broader objective is to contribute to the
    development of <strong>scientifically grounded crescent visibility criteria
    and evidence-based Hijri calendar systems</strong>.
  </p>

</div>


<!-- ======================================================
     FUTURE DIRECTIONS
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Future Directions
  </div>

  <h2>
    Research Questions Ahead
  </h2>

  <p class="research-intro">
    Several questions guide the next phase of my research.
  </p>


  <div class="future-card">

    <strong>
      1. How does tropical twilight influence crescent visibility?
    </strong>

    Understanding the relationship between sky brightness, solar depression,
    atmospheric conditions, lunar geometry, and visual or digital crescent detection.

  </div>


  <div class="future-card">

    <strong>
      2. Can photometric contrast improve crescent visibility criteria?
    </strong>

    Developing quantitative indicators based on crescent intensity,
    twilight-background intensity, Weber contrast, and digital image analysis.

  </div>


  <div class="future-card">

    <strong>
      3. How can astronomical evidence strengthen Hijri calendar systems?
    </strong>

    Connecting observational evidence and crescent visibility criteria with
    calendar development and Islamic legal reasoning.

  </div>


  <div class="future-card">

    <strong>
      4. How can astronomy better support Islamic religious practices?
    </strong>

    Extending observational and computational astronomy to crescent observation,
    prayer times, qibla direction, and Hijri calendar determination.

  </div>

</div>


<!-- ======================================================
     RESEARCH ROADMAP
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Research Roadmap
  </div>

  <h2>
    Long-Term Research Trajectory
  </h2>

  <p class="research-intro">
    The following roadmap presents the long-term trajectory of my research,
    linking crescent observation, astronomical measurement, digital imaging,
    photometric analysis, visibility criteria, Hijri calendar studies,
    and the integration of astronomical evidence with Islamic legal reasoning.
  </p>

  <div class="roadmap-box">

    <a href="{{ base_path }}/images/roadmap-penelitian-hilal.png"
       target="_blank"
       rel="noopener noreferrer">

      <img src="{{ base_path }}/images/roadmap-penelitian-hilal.png"
           alt="Research roadmap on crescent visibility and Islamic astronomy">

    </a>

  </div>

</div>


<!-- ======================================================
     SELECTED PROJECTS
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Selected Projects
  </div>

  <h2>
    Current and Recent Research Projects
  </h2>

  <div class="project-grid">


    <div class="project-card">

      <h3>
        Crescent Visibility and Twilight Observation at Timau
      </h3>

      <p>
        Observational study of twilight brightness and crescent visibility
        using sky-brightness measurements, digital imaging, and photometric
        analysis under dark-sky observational conditions.
      </p>

    </div>


    <div class="project-card">

      <h3>
        Lunar Photometry and Digital Imaging
      </h3>

      <p>
        Application of aperture photometry and digital image analysis to
        compare crescent intensity, twilight-background intensity, and
        quantitative contrast during early lunar visibility.
      </p>

    </div>


    <div class="project-card">

      <h3>
        Hijri Calendar and Hisab–Rukyat Integration
      </h3>

      <p>
        Investigation of astronomical visibility criteria, observational
        evidence, Islamic legal reasoning, and institutional approaches to
        the development of Hijri calendar systems.
      </p>

    </div>


    <div class="project-card">

      <h3>
        QGIS-Based Visualization of Prayer Times
      </h3>

      <p>
        Integration of geographical coordinates and astronomical parameters
        to visualize spatial variations in prayer times and their relationship
        with geographical position.
      </p>

    </div>

  </div>

</div>


<!-- ======================================================
     RESEARCH OUTPUTS
====================================================== -->

<div class="research-section">

  <div class="research-kicker">
    Research Outputs
  </div>

  <h2>
    Publications and Scholarly Work
  </h2>

  <p>
    Research outputs are published across the fields of Islamic astronomy,
    crescent visibility, observational astronomy, digital image analysis,
    Hijri calendar studies, Islamic law, and related interdisciplinary areas.
  </p>

  <div class="output-links">

    <a class="output-link"
       href="/main-publications/">
      Main Publications →
    </a>

    <a class="output-link"
       href="/publications/">
      Full Publications →
    </a>

  </div>

</div>
