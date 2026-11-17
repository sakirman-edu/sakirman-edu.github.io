---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
description: "Research program of Dr. Sakirman in Islamic astronomy, crescent visibility, twilight, astronomical photometry, digital imaging, Hijri calendar studies, and Islamic legal reasoning."
---

<style>

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

.research-hero-title {
  margin: 0 0 0.85rem 0;
  max-width: 900px;
  font-size: 1.65rem;
  line-height: 1.35;
  font-weight: 700;
}

.research-hero-text {
  max-width: 880px;
  margin: 0 0 1rem 0;
  font-size: 0.96rem;
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


/* IMAGE */

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

  transition:
    transform 0.45s ease;
}

.research-card:hover img {
  transform: scale(1.055);
}


/* THEME BADGE */

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


/* CARD CONTENT */

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
   METHODOLOGY
========================================================= */

.methodology-intro {
  margin-bottom: 1.5rem;
}

.methodology-intro p {
  max-width: 880px;
  line-height: 1.8;
}


/* =========================================================
   RESEARCH LOOP
========================================================= */

.research-loop-wrapper {
  position: relative;
  max-width: 820px;
  min-height: 620px;
  margin: 2rem auto 2.5rem;
}

.research-loop-center {
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  width: 210px;
  height: 210px;

  padding: 1.2rem;
  border: 1px solid #00b8d9;
  border-radius: 50%;

  text-align: center;

  transform: translate(-50%, -50%);

  box-shadow:
    0 0 0 8px rgba(0,184,217,0.04),
    0 0 25px rgba(0,184,217,0.13);

  animation: researchLoopGlow 3s ease-in-out infinite;
}

.research-loop-center small {
  margin-bottom: 0.35rem;
  font-size: 0.66rem;
  font-weight: 700;
  letter-spacing: 0.11em;
  text-transform: uppercase;
  opacity: 0.6;
}

.research-loop-center strong {
  font-size: 1rem;
  line-height: 1.45;
}

@keyframes researchLoopGlow {

  0%,
  100% {
    box-shadow:
      0 0 0 8px rgba(0,184,217,0.04),
      0 0 18px rgba(0,184,217,0.10);
  }

  50% {
    box-shadow:
      0 0 0 11px rgba(0,184,217,0.06),
      0 0 30px rgba(0,184,217,0.22);
  }

}


.method-box {
  position: absolute;
  width: 225px;
  padding: 0.8rem 0.9rem;

  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 10px;

  background: transparent;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.method-box:hover {
  border-color: #00b8d9;
  transform: translateY(-3px);
}

.method-number {
  display: block;
  margin-bottom: 0.25rem;
  font-size: 0.65rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  opacity: 0.5;
}

.method-box strong {
  display: block;
  margin-bottom: 0.2rem;
  font-size: 0.84rem;
}

.method-box span {
  display: block;
  font-size: 0.72rem;
  line-height: 1.45;
  opacity: 0.7;
}


/* LOOP POSITIONS */

.method-1 {
  top: 2%;
  left: 50%;
  transform: translateX(-50%);
}

.method-1:hover {
  transform: translateX(-50%) translateY(-3px);
}

.method-2 {
  top: 18%;
  right: 0;
}

.method-3 {
  top: 43%;
  right: -2%;
}

.method-4 {
  bottom: 3%;
  right: 10%;
}

.method-5 {
  bottom: 3%;
  left: 10%;
}

.method-6 {
  top: 43%;
  left: -2%;
}

.method-7 {
  top: 18%;
  left: 0;
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
  border-top: 1px solid rgba(127,127,127,0.18);
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
   CURRENT RESEARCH / PROJECT CARDS
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

  border: 1px solid rgba(127,127,127,0.20);
  border-radius: 10px;

  transition: transform 0.45s ease;
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
   RESPONSIVE
========================================================= */

@media (max-width: 900px) {

  .research-loop-wrapper {
    min-height: auto;
  }

  .research-loop-center {
    position: relative;
    top: auto;
    left: auto;

    width: 180px;
    height: 180px;

    margin: 0 auto 1.2rem;

    transform: none;
  }

  .method-box,
  .method-1,
  .method-2,
  .method-3,
  .method-4,
  .method-5,
  .method-6,
  .method-7 {
    position: relative;
    top: auto;
    right: auto;
    bottom: auto;
    left: auto;

    width: 100%;
    margin-bottom: 0.65rem;

    transform: none;
  }

  .method-box:hover,
  .method-1:hover {
    transform: none;
  }

}


@media (max-width: 768px) {

  .research-hero-title {
    font-size: 1.45rem;
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
  .future-card:hover {
    transform: none;
  }

  .research-card:hover img,
  .software-card:hover img {
    transform: none;
  }

}


@media (max-width: 480px) {

  .research-hero-title {
    font-size: 1.35rem;
  }

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

  <h1 class="research-hero-title">
    From astronomical observation to Islamic legal reasoning
  </h1>

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


    <!-- THEME 01 -->

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



    <!-- THEME 02 -->

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



    <!-- THEME 03 -->

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



    <!-- THEME 04 -->

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

  <div class="methodology-intro">

    <p>
      The research workflow integrates astronomical observation, digital
      imaging, quantitative photometry, contrast analysis, astronomical
      interpretation, and Islamic legal analysis.
    </p>

  </div>


  <div class="research-loop-wrapper">


    <div class="research-loop-center">

      <small>
        Research Loop
      </small>

      <strong>
        From Observation<br>
        to Evidence
      </strong>

    </div>



    <div class="method-box method-1">

      <span class="method-number">01</span>

      <strong>Crescent Observation</strong>

      <span>hilal · twilight · geometry</span>

    </div>



    <div class="method-box method-2">

      <span class="method-number">02</span>

      <strong>Digital Image Acquisition</strong>

      <span>camera · telescope · RAW</span>

    </div>



    <div class="method-box method-3">

      <span class="method-number">03</span>

      <strong>Image Pre-Processing</strong>

      <span>calibration · Siril</span>

    </div>



    <div class="method-box method-4">

      <span class="method-number">04</span>

      <strong>Aperture Photometry</strong>

      <span>IRIS · intensity</span>

    </div>



    <div class="method-box method-5">

      <span class="method-number">05</span>

      <strong>Contrast Analysis</strong>

      <span>Weber contrast</span>

    </div>



    <div class="method-box method-6">

      <span class="method-number">06</span>

      <strong>Astronomical Interpretation</strong>

      <span>visibility · atmosphere</span>

    </div>



    <div class="method-box method-7">

      <span class="method-number">07</span>

      <strong>Islamic Legal Analysis</strong>

      <span>hisab–rukyat · maqāṣid</span>

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


</div>
