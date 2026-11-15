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
   HOMEPAGE GENERAL
========================================================= */

.home-hero {
  position: relative;
  display: grid;
  grid-template-columns: minmax(0, 1.05fr) minmax(360px, 0.95fr);
  gap: 2.5rem;
  align-items: center;

  min-height: 520px;
  margin-bottom: 3rem;
  padding: 2.2rem 0 2.8rem 0;
}

.home-hero-copy {
  position: relative;
  z-index: 5;
}

.home-kicker {
  display: inline-block;
  margin-bottom: 0.8rem;

  color: #00b8d9;

  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  text-transform: uppercase;
}

.home-title {
  margin: 0 0 0.8rem 0;

  font-size: 2.45rem;
  line-height: 1.08;
  letter-spacing: -0.025em;
}

.home-subtitle {
  margin: 0 0 1.15rem 0;

  font-size: 1rem;
  font-weight: 600;
  line-height: 1.6;

  opacity: 0.82;
}

.home-intro {
  max-width: 720px;
  margin: 0;

  font-size: 0.98rem;
  line-height: 1.82;

  opacity: 0.88;
}


/* =========================================================
   HERO TAGS
========================================================= */

.home-hero-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;

  margin-top: 1.3rem;
}

.home-hero-tag {
  display: inline-block;

  padding: 0.38rem 0.68rem;

  border: 1px solid rgba(0,184,217,0.38);
  border-radius: 999px;

  color: #00b8d9;

  font-size: 0.7rem;
  font-weight: 600;

  background: rgba(0,184,217,0.035);
}


/* =========================================================
   HERO ACTIONS
========================================================= */

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.7rem;

  margin-top: 1.5rem;
}

.home-button {
  display: inline-block;

  padding: 0.62rem 0.9rem;

  border: 1px solid rgba(127,127,127,0.34);
  border-radius: 8px;

  font-size: 0.82rem;
  font-weight: 700;

  text-decoration: none !important;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease,
    color 0.22s ease;
}

.home-button:hover,
.home-button:focus {
  border-color: #00b8d9 !important;
  color: #00b8d9 !important;

  transform: translateY(-2px);

  text-decoration: none !important;
}

.home-button-primary {
  border-color: #00b8d9;
  color: #00b8d9 !important;
}


/* =========================================================
   HERO VISUAL
========================================================= */

.home-visual {
  position: relative;

  width: 100%;
  min-height: 430px;

  display: flex;
  align-items: center;
  justify-content: center;
}


/* outer ring */

.home-orbit-outer {
  position: absolute;

  width: 360px;
  height: 360px;

  border: 1px solid rgba(120,145,200,0.18);
  border-radius: 50%;
}


/* middle orbit */

.home-orbit {
  position: absolute;

  width: 285px;
  height: 285px;

  border: 1px dashed rgba(0,184,217,0.50);
  border-radius: 50%;

  animation: homeOrbitRotate 22s linear infinite;
}

.home-orbit::before {
  content: "";

  position: absolute;
  top: -5px;
  left: 50%;

  width: 10px;
  height: 10px;

  transform: translateX(-50%);

  background: #00b8d9;

  border-radius: 50%;

  box-shadow:
    0 0 12px rgba(0,184,217,0.65);
}

@keyframes homeOrbitRotate {

  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }

}


/* inner ring */

.home-orbit-inner {
  position: absolute;

  width: 205px;
  height: 205px;

  border: 1px dotted rgba(120,145,200,0.18);
  border-radius: 50%;
}


/* =========================================================
   CRESCENT
========================================================= */

.home-crescent-wrap {
  position: relative;

  width: 210px;
  height: 210px;

  display: flex;
  align-items: center;
  justify-content: center;

  z-index: 4;
}

.home-crescent {
  position: relative;

  width: 126px;
  height: 126px;

  border-radius: 50%;

  background: #00b8d9;

  box-shadow:
    0 0 14px rgba(0,184,217,0.35),
    0 0 32px rgba(0,184,217,0.18);

  animation: crescentGlow 3.2s ease-in-out infinite;
}

.home-crescent::after {
  content: "";

  position: absolute;

  width: 118px;
  height: 118px;

  top: -2px;
  left: 25px;

  border-radius: 50%;

  background: var(--global-bg-color);
}

@keyframes crescentGlow {

  0%,
  100% {
    box-shadow:
      0 0 12px rgba(0,184,217,0.28),
      0 0 26px rgba(0,184,217,0.12);
  }

  50% {
    box-shadow:
      0 0 20px rgba(0,184,217,0.55),
      0 0 42px rgba(0,184,217,0.28);
  }

}


/* =========================================================
   PIXEL PARTICLES
========================================================= */

.pixel {
  position: absolute;

  width: 5px;
  height: 5px;

  background: #00b8d9;

  opacity: 0.55;

  border-radius: 1px;

  animation: pixelFloat 4.5s ease-in-out infinite;
}

.pixel-1 {
  top: 25%;
  left: 27%;
  animation-delay: 0s;
}

.pixel-2 {
  top: 35%;
  right: 23%;
  animation-delay: 0.6s;
}

.pixel-3 {
  bottom: 28%;
  left: 24%;
  animation-delay: 1.1s;
}

.pixel-4 {
  bottom: 20%;
  right: 30%;
  animation-delay: 1.6s;
}

.pixel-5 {
  top: 18%;
  right: 34%;
  animation-delay: 2.1s;
}

.pixel-6 {
  bottom: 35%;
  right: 17%;
  animation-delay: 2.6s;
}

@keyframes pixelFloat {

  0%,
  100% {
    transform: translateY(0) scale(1);
    opacity: 0.35;
  }

  50% {
    transform: translateY(-10px) scale(1.3);
    opacity: 0.85;
  }

}


/* =========================================================
   VISUAL LABEL
========================================================= */

.home-visual-label {
  position: absolute;

  bottom: 28px;
  left: 50%;

  transform: translateX(-50%);

  width: 100%;

  text-align: center;

  font-size: 0.68rem;
  letter-spacing: 0.12em;
  text-transform: uppercase;

  color: #00b8d9;

  opacity: 0.78;
}


/* =========================================================
   SUMMARY CARDS
========================================================= */

.home-summary-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));

  gap: 0.9rem;

  margin: 2.2rem 0 2.8rem 0;
}

.home-summary-card {
  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;

  padding: 1rem 1.1rem;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.home-summary-card:hover {
  border-color: #00b8d9;
  transform: translateY(-3px);
}

.home-summary-label {
  margin-bottom: 0.4rem;

  font-size: 0.67rem;
  font-weight: 700;

  letter-spacing: 0.06em;
  text-transform: uppercase;

  opacity: 0.58;
}

.home-summary-title {
  margin-bottom: 0.4rem;

  font-size: 0.95rem;
  font-weight: 700;

  line-height: 1.4;
}

.home-summary-text {
  margin: 0;

  font-size: 0.82rem;
  line-height: 1.6;

  opacity: 0.76;
}


/* =========================================================
   SECTION
========================================================= */

.home-section {
  margin-top: 2.8rem;
}

.home-section-title {
  margin: 0 0 0.9rem 0;

  font-size: 1.25rem;
  line-height: 1.35;
}

.home-section-intro {
  max-width: 780px;

  margin: 0 0 1rem 0;

  line-height: 1.7;

  opacity: 0.82;
}


/* =========================================================
   RESEARCH FOCUS
========================================================= */

.home-focus {
  border-left: 3px solid #00b8d9;

  padding: 0.2rem 0 0.2rem 1rem;

  margin-top: 1rem;
}

.home-focus p {
  margin: 0;

  line-height: 1.75;
}


/* =========================================================
   RESEARCH INTERESTS
========================================================= */

.home-tags {
  display: flex;
  flex-wrap: wrap;

  gap: 0.55rem;

  margin-top: 1rem;
}

.home-tag,
.home-tag:link,
.home-tag:visited {
  display: inline-block;

  padding: 0.48rem 0.72rem;

  border: 1px solid rgba(127,127,127,0.28);
  border-radius: 999px;

  color: #00b8d9 !important;

  font-size: 0.78rem;
  line-height: 1.2;

  text-decoration: none !important;

  transition:
    transform 0.2s ease,
    border-color 0.2s ease;
}

.home-tag:hover,
.home-tag:focus {
  border-color: #00b8d9 !important;

  transform: translateY(-2px);

  text-decoration: none !important;
}


/* =========================================================
   QUICK LINKS
========================================================= */

.home-link-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));

  gap: 0.9rem;

  margin-top: 1rem;
}

.home-link-card {
  display: block;

  border: 1px solid rgba(127,127,127,0.25);
  border-radius: 12px;

  padding: 1rem 1.1rem;

  text-decoration: none !important;

  transition:
    transform 0.22s ease,
    border-color 0.22s ease;
}

.home-link-card:hover {
  border-color: #00b8d9;

  transform: translateY(-3px);

  text-decoration: none !important;
}

.home-link-card strong {
  display: block;

  margin-bottom: 0.35rem;

  font-size: 0.95rem;
}

.home-link-card span {
  display: block;

  font-size: 0.8rem;
  line-height: 1.55;

  opacity: 0.72;
}


/* =========================================================
   RESPONSIVE
========================================================= */

@media (max-width: 1050px) {

  .home-hero {
    grid-template-columns: 1fr;
  }

  .home-visual {
    min-height: 400px;
  }

}


@media (max-width: 900px) {

  .home-summary-grid {
    grid-template-columns: 1fr;
  }

}


@media (max-width: 768px) {

  .home-title {
    font-size: 1.9rem;
  }

  .home-link-grid {
    grid-template-columns: 1fr;
  }

  .home-visual {
    min-height: 340px;
  }

  .home-orbit-outer {
    width: 300px;
    height: 300px;
  }

  .home-orbit {
    width: 245px;
    height: 245px;
  }

  .home-orbit-inner {
    width: 180px;
    height: 180px;
  }

  .home-crescent {
    width: 105px;
    height: 105px;
  }

  .home-crescent::after {
    width: 98px;
    height: 98px;
    left: 21px;
  }

}


@media (prefers-reduced-motion: reduce) {

  .home-orbit,
  .home-crescent,
  .pixel {
    animation: none !important;
  }

}

</style>


<!-- ======================================================
     HERO
====================================================== -->

<div class="home-hero">


  <!-- LEFT -->

  <div class="home-hero-copy">

    <div class="home-kicker">
      Islamic Law · Islamic Astronomy
    </div>

    <h1 class="home-title">
      Dr. Sakirman, M.S.I.
    </h1>

    <div class="home-subtitle">
      Lecturer · Researcher · UIN Jurai Siwo Lampung
    </div>

    <p class="home-intro">
      My academic work explores the intersection of
      <strong>Islamic law and Islamic astronomy (<em>Ilmu Falak</em>)</strong>,
      with particular attention to crescent visibility, twilight,
      sky brightness, astronomical photometry, digital imaging,
      hisab–rukyat, and scientifically informed Hijri calendar studies.
    </p>


    <div class="home-hero-tags">

      <span class="home-hero-tag">
        Crescent Visibility
      </span>

      <span class="home-hero-tag">
        Twilight / Syafaq
      </span>

      <span class="home-hero-tag">
        Hisab–Rukyat
      </span>

      <span class="home-hero-tag">
        Hijri Calendar
      </span>

    </div>


    <div class="home-actions">

      <a class="home-button home-button-primary"
         href="/research/">
        Explore My Research →
      </a>

      <a class="home-button"
         href="/main-publications/">
        Main Publications
      </a>

      <a class="home-button"
         href="/cv/">
        Academic CV
      </a>

    </div>

  </div>


  <!-- RIGHT -->

  <div class="home-visual">

    <div class="home-orbit-outer"></div>

    <div class="home-orbit"></div>

    <div class="home-orbit-inner"></div>


    <div class="home-crescent-wrap">

      <div class="home-crescent"></div>

    </div>


    <span class="pixel pixel-1"></span>
    <span class="pixel pixel-2"></span>
    <span class="pixel pixel-3"></span>
    <span class="pixel pixel-4"></span>
    <span class="pixel pixel-5"></span>
    <span class="pixel pixel-6"></span>


    <div class="home-visual-label">
      Observation · Imaging · Photometry · Interpretation
    </div>

  </div>

</div>


<!-- ======================================================
     SUMMARY
====================================================== -->

<div class="home-summary-grid">


  <div class="home-summary-card">

    <div class="home-summary-label">
      Research Area
    </div>

    <div class="home-summary-title">
      Islamic Astronomy
    </div>

    <p class="home-summary-text">
      Crescent visibility, twilight, sky brightness,
      astronomical observation, photometry, and digital imaging.
    </p>

  </div>


  <div class="home-summary-card">

    <div class="home-summary-label">
      Legal Studies
    </div>

    <div class="home-summary-title">
      Islamic Law
    </div>

    <p class="home-summary-text">
      Islamic legal reasoning, maqāṣid al-sharī‘ah,
      astronomical evidence, and contemporary Islamic law.
    </p>

  </div>


  <div class="home-summary-card">

    <div class="home-summary-label">
      Academic Leadership
    </div>

    <div class="home-summary-title">
      Teaching, Research, and Publication
    </div>

    <p class="home-summary-text">
      Doctoral program leadership, academic supervision,
      curriculum development, and scholarly journal development.
    </p>

  </div>


</div>


<!-- ======================================================
     CURRENT RESEARCH FOCUS
====================================================== -->

<div class="home-section">

  <h2 class="home-section-title">
    Current Research Focus
  </h2>

  <div class="home-focus">

    <p>
      My current research examines
      <strong>crescent visibility, twilight (<em>syafaq</em>), sky brightness,
      atmospheric conditions, hisab–rukyat, digital imaging, and astronomical photometry</strong>.
      Particular attention is given to how atmospheric conditions and lunar geometry
      influence the visibility of the young crescent Moon in tropical and
      low-latitude environments and how these findings can contribute to
      scientifically informed Hijri calendar criteria.
    </p>

  </div>

</div>


<!-- ======================================================
     RESEARCH INTERESTS
====================================================== -->

<div class="home-section">

  <h2 class="home-section-title">
    Research Interests
  </h2>

  <div class="home-tags">

    <a class="home-tag"
       href="/research-interests/#crescent-visibility">
      Crescent Visibility
    </a>

    <a class="home-tag"
       href="/research-interests/#twilight-syafaq">
      Twilight / Syafaq
    </a>

    <a class="home-tag"
       href="/research-interests/#sky-brightness">
      Sky Brightness
    </a>

    <a class="home-tag"
       href="/research-interests/#hisab-rukyat">
      Hisab–Rukyat
    </a>

    <a class="home-tag"
       href="/research-interests/#hijri-calendar">
      Hijri Calendar
    </a>

    <a class="home-tag"
       href="/research-interests/#islamic-astronomy">
      Islamic Astronomy
    </a>

    <a class="home-tag"
       href="/research-interests/#astronomical-photometry">
      Astronomical Photometry
    </a>

    <a class="home-tag"
       href="/research-interests/#digital-imaging">
      Digital Imaging
    </a>

    <a class="home-tag"
       href="/research-interests/#astronomical-evidence">
      Astronomical Evidence
    </a>

    <a class="home-tag"
       href="/research-interests/#islamic-law">
      Islamic Law
    </a>

    <a class="home-tag"
       href="/research-interests/#maqasid-al-shariah">
      Maqāṣid al-Sharī‘ah
    </a>

    <a class="home-tag"
       href="/research-interests/#islamic-family-law">
      Islamic Family Law
    </a>

  </div>

</div>


<!-- ======================================================
     EXPLORE ACADEMIC WORK
====================================================== -->

<div class="home-section">

  <h2 class="home-section-title">
    Explore Academic Work
  </h2>

  <p class="home-section-intro">
    Explore research, publications, teaching activities, and academic
    information through the main sections of this website.
  </p>


  <div class="home-link-grid">


    <a class="home-link-card"
       href="/research/">

      <strong>
        Research →
      </strong>

      <span>
        Research themes, methodology, current projects,
        research roadmap, and astronomical studies.
      </span>

    </a>


    <a class="home-link-card"
       href="/main-publications/">

      <strong>
        Main Publications →
      </strong>

      <span>
        Selected academic works in Islamic astronomy,
        Hijri calendar studies, and Islamic law.
      </span>

    </a>


    <a class="home-link-card"
       href="/publications/">

      <strong>
        Full Publications →
      </strong>

      <span>
        Complete academic publication record organized
        chronologically.
      </span>

    </a>


    <a class="home-link-card"
       href="/teaching/">

      <strong>
        Teaching →
      </strong>

      <span>
        Undergraduate, master's, and doctoral courses,
        learning materials, and academic teaching activities.
      </span>

    </a>


    <a class="home-link-card"
       href="/cv/">

      <strong>
        Academic CV →
      </strong>

      <span>
        Education, academic appointments, research expertise,
        leadership, editorial service, and professional activities.
      </span>

    </a>


    <a class="home-link-card"
       href="https://scholar.google.com/citations?hl=en&user=eCtpuO8AAAAJ"
       target="_blank"
       rel="noopener noreferrer">

      <strong>
        Google Scholar →
      </strong>

      <span>
        Citation profile and publication records available
        through Google Scholar.
      </span>

    </a>


  </div>

</div>
