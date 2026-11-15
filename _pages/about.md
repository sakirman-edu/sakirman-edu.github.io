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
  display: grid;
  grid-template-columns: minmax(0, 1.05fr) minmax(430px, 0.95fr);
  gap: 2.6rem;
  align-items: center;

  min-height: 560px;

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
   LUNAR SYSTEM VISUAL
========================================================= */

.lunar-system {
  position: relative;

  width: 500px;
  height: 500px;

  max-width: 100%;

  margin: 0 auto;
}


/* =========================================================
   EARTH
========================================================= */

.earth {
  position: absolute;

  top: 50%;
  left: 42%;

  width: 116px;
  height: 116px;

  transform: translate(-50%, -50%);

  border-radius: 50%;

  background:
    radial-gradient(circle at 38% 35%,
      #78d9ff 0%,
      #2779b8 28%,
      #155083 60%,
      #0b2844 100%);

  box-shadow:
    0 0 8px rgba(0,184,217,0.55),
    0 0 28px rgba(0,184,217,0.28);

  z-index: 5;

  animation: earthPulse 4s ease-in-out infinite;
}

.earth::before {
  content: "";

  position: absolute;

  width: 48px;
  height: 30px;

  top: 25px;
  left: 22px;

  border-radius: 60% 40% 55% 45%;

  background: rgba(90,180,100,0.8);

  transform: rotate(-20deg);
}

.earth::after {
  content: "";

  position: absolute;

  width: 36px;
  height: 23px;

  bottom: 23px;
  right: 19px;

  border-radius: 50%;

  background: rgba(90,180,100,0.68);

  transform: rotate(22deg);
}

@keyframes earthPulse {

  0%,
  100% {
    box-shadow:
      0 0 8px rgba(0,184,217,0.45),
      0 0 24px rgba(0,184,217,0.20);
  }

  50% {
    box-shadow:
      0 0 14px rgba(0,184,217,0.72),
      0 0 36px rgba(0,184,217,0.32);
  }

}

.earth-label {
  position: absolute;

  top: calc(50% + 72px);
  left: 42%;

  transform: translateX(-50%);

  font-size: 0.66rem;
  font-weight: 700;

  letter-spacing: 0.08em;
  text-transform: uppercase;

  opacity: 0.72;
}


/* =========================================================
   SUN
========================================================= */

.sun {
  position: absolute;

  top: 50%;
  right: 1%;

  width: 92px;
  height: 92px;

  transform: translateY(-50%);

  border-radius: 50%;

  background:
    radial-gradient(circle at 35% 35%,
      #fff7a6 0%,
      #ffd12f 22%,
      #ff9814 55%,
      #e85b00 100%);

  box-shadow:
    0 0 15px rgba(255,187,0,0.70),
    0 0 38px rgba(255,137,0,0.40);

  animation: sunGlow 3s ease-in-out infinite;
}

@keyframes sunGlow {

  0%,
  100% {
    box-shadow:
      0 0 13px rgba(255,187,0,0.55),
      0 0 28px rgba(255,137,0,0.30);
  }

  50% {
    box-shadow:
      0 0 22px rgba(255,205,60,0.85),
      0 0 48px rgba(255,137,0,0.52);
  }

}

.sun-label {
  position: absolute;

  top: calc(50% + 58px);
  right: 24px;

  font-size: 0.64rem;
  font-weight: 700;

  letter-spacing: 0.08em;
  text-transform: uppercase;

  opacity: 0.72;
}


/* =========================================================
   LUNAR ORBIT
========================================================= */

.lunar-orbit {
  position: absolute;

  top: 50%;
  left: 42%;

  width: 350px;
  height: 350px;

  transform: translate(-50%, -50%);

  border: 1px solid rgba(200,220,255,0.22);
  border-radius: 50%;

  z-index: 1;
}

.lunar-orbit::after {
  content: "";

  position: absolute;

  inset: 34px;

  border: 1px dashed rgba(0,184,217,0.16);
  border-radius: 50%;

  animation: innerOrbit 28s linear infinite;
}

@keyframes innerOrbit {

  from {
    transform: rotate(0deg);
  }

  to {
    transform: rotate(360deg);
  }

}


/* =========================================================
   PHASE NODE
========================================================= */

.moon-phase {
  position: absolute;

  width: 62px;
  height: 62px;

  margin-left: -31px;
  margin-top: -31px;

  border-radius: 50%;

  z-index: 10;

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;

  animation: phaseGlow 16s linear infinite;
}

.moon-phase:hover {
  transform: scale(1.12);
}


/* moon base */

.moon-disc {
  position: absolute;

  inset: 0;

  overflow: hidden;

  border-radius: 50%;

  background:
    radial-gradient(circle at 35% 28%,
      #d7dbe3 0%,
      #a7adba 42%,
      #727986 75%,
      #444a54 100%);

  box-shadow:
    inset -7px -5px 12px rgba(0,0,0,0.30);
}


/* =========================================================
   PHASE SHADOWS
========================================================= */

.moon-new .moon-disc {
  background: #151922;
  box-shadow:
    inset 0 0 12px rgba(255,255,255,0.04);
}

.moon-waxing-crescent .moon-disc::after {
  content: "";

  position: absolute;

  width: 58px;
  height: 58px;

  top: 2px;
  left: -7px;

  border-radius: 50%;

  background: #151922;
}

.moon-first-quarter .moon-disc::after {
  content: "";

  position: absolute;

  width: 50%;
  height: 100%;

  left: 0;
  top: 0;

  background: #151922;
}

.moon-waxing-gibbous .moon-disc::after {
  content: "";

  position: absolute;

  width: 40px;
  height: 58px;

  left: -17px;
  top: 2px;

  border-radius: 50%;

  background: #151922;
}

.moon-full .moon-disc {
  background:
    radial-gradient(circle at 35% 28%,
      #eceff3 0%,
      #c5cad2 42%,
      #969da8 76%,
      #686f79 100%);
}

.moon-waning-gibbous .moon-disc::after {
  content: "";

  position: absolute;

  width: 40px;
  height: 58px;

  right: -17px;
  top: 2px;

  border-radius: 50%;

  background: #151922;
}

.moon-last-quarter .moon-disc::after {
  content: "";

  position: absolute;

  width: 50%;
  height: 100%;

  right: 0;
  top: 0;

  background: #151922;
}

.moon-waning-crescent .moon-disc::after {
  content: "";

  position: absolute;

  width: 58px;
  height: 58px;

  top: 2px;
  right: -7px;

  border-radius: 50%;

  background: #151922;
}


/* =========================================================
   MOON POSITIONS
========================================================= */

.phase-new {
  top: 50%;
  left: calc(42% + 175px);

  animation-delay: 0s;
}

.phase-waxing-crescent {
  top: calc(50% - 124px);
  left: calc(42% + 124px);

  animation-delay: -2s;
}

.phase-first-quarter {
  top: calc(50% - 175px);
  left: 42%;

  animation-delay: -4s;
}

.phase-waxing-gibbous {
  top: calc(50% - 124px);
  left: calc(42% - 124px);

  animation-delay: -6s;
}

.phase-full {
  top: 50%;
  left: calc(42% - 175px);

  animation-delay: -8s;
}

.phase-waning-gibbous {
  top: calc(50% + 124px);
  left: calc(42% - 124px);

  animation-delay: -10s;
}

.phase-last-quarter {
  top: calc(50% + 175px);
  left: 42%;

  animation-delay: -12s;
}

.phase-waning-crescent {
  top: calc(50% + 124px);
  left: calc(42% + 124px);

  animation-delay: -14s;
}


/* =========================================================
   ACTIVE PHASE ANIMATION
========================================================= */

@keyframes phaseGlow {

  0%,
  9%,
  100% {
    box-shadow:
      0 0 0 1px rgba(0,184,217,0.10);

    transform: scale(1);
  }

  12.5%,
  20% {
    box-shadow:
      0 0 0 2px rgba(0,184,217,0.85),
      0 0 16px rgba(0,184,217,0.70),
      0 0 30px rgba(0,184,217,0.30);

    transform: scale(1.08);
  }

  24%,
  100% {
    box-shadow:
      0 0 0 1px rgba(0,184,217,0.10);

    transform: scale(1);
  }

}


/* stronger emphasis on hilal */

.phase-waxing-crescent {
  filter: drop-shadow(0 0 4px rgba(0,184,217,0.28));
}


/* =========================================================
   PHASE LABELS
========================================================= */

.phase-label {
  position: absolute;

  white-space: nowrap;

  font-size: 0.56rem;
  font-weight: 600;

  letter-spacing: 0.03em;

  opacity: 0.68;
}

.phase-new .phase-label {
  left: 72px;
  top: 22px;
}

.phase-waxing-crescent .phase-label {
  left: 70px;
  top: -1px;
}

.phase-first-quarter .phase-label {
  top: -24px;
  left: 50%;

  transform: translateX(-50%);
}

.phase-waxing-gibbous .phase-label {
  right: 70px;
  top: -2px;
}

.phase-full .phase-label {
  right: 72px;
  top: 22px;
}

.phase-waning-gibbous .phase-label {
  right: 70px;
  top: 46px;
}

.phase-last-quarter .phase-label {
  top: 72px;
  left: 50%;

  transform: translateX(-50%);
}

.phase-waning-crescent .phase-label {
  left: 70px;
  top: 47px;
}


/* =========================================================
   VISUAL CAPTION
========================================================= */

.lunar-caption {
  position: absolute;

  left: 42%;
  bottom: -5px;

  transform: translateX(-50%);

  width: 100%;

  color: #00b8d9;

  text-align: center;

  font-size: 0.64rem;
  font-weight: 700;

  letter-spacing: 0.09em;
  text-transform: uppercase;

  opacity: 0.76;
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

@media (max-width: 1100px) {

  .home-hero {
    grid-template-columns: 1fr;
  }

  .lunar-system {
    margin-top: 1rem;
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

  .lunar-system {
    transform: scale(0.78);
    transform-origin: top center;

    margin-bottom: -90px;
  }

}


@media (max-width: 520px) {

  .lunar-system {
    transform: scale(0.62);

    margin-left: -55px;
    margin-bottom: -165px;
  }

}


/* =========================================================
   REDUCED MOTION
========================================================= */

@media (prefers-reduced-motion: reduce) {

  .moon-phase,
  .lunar-orbit::after,
  .sun,
  .earth {
    animation: none !important;
  }

}

</style>


<!-- ======================================================
     HERO
====================================================== -->

<div class="home-hero">


  <!-- LEFT SIDE -->

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


  <!-- RIGHT SIDE : LUNAR PHASE SYSTEM -->

  <div class="lunar-system">


    <div class="lunar-orbit"></div>


    <!-- EARTH -->

    <div class="earth"></div>

    <div class="earth-label">
      Earth
    </div>


    <!-- SUN -->

    <div class="sun"></div>

    <div class="sun-label">
      Sun
    </div>


    <!-- 1 NEW MOON -->

    <div class="moon-phase moon-new phase-new">

      <div class="moon-disc"></div>

      <span class="phase-label">
        New Moon
      </span>

    </div>


    <!-- 2 WAXING CRESCENT -->

    <div class="moon-phase moon-waxing-crescent phase-waxing-crescent">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Waxing Crescent / Hilal
      </span>

    </div>


    <!-- 3 FIRST QUARTER -->

    <div class="moon-phase moon-first-quarter phase-first-quarter">

      <div class="moon-disc"></div>

      <span class="phase-label">
        First Quarter
      </span>

    </div>


    <!-- 4 WAXING GIBBOUS -->

    <div class="moon-phase moon-waxing-gibbous phase-waxing-gibbous">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Waxing Gibbous
      </span>

    </div>


    <!-- 5 FULL MOON -->

    <div class="moon-phase moon-full phase-full">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Full Moon
      </span>

    </div>


    <!-- 6 WANING GIBBOUS -->

    <div class="moon-phase moon-waning-gibbous phase-waning-gibbous">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Waning Gibbous
      </span>

    </div>


    <!-- 7 LAST QUARTER -->

    <div class="moon-phase moon-last-quarter phase-last-quarter">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Last Quarter
      </span>

    </div>


    <!-- 8 WANING CRESCENT -->

    <div class="moon-phase moon-waning-crescent phase-waning-crescent">

      <div class="moon-disc"></div>

      <span class="phase-label">
        Waning Crescent
      </span>

    </div>


    <div class="lunar-caption">
      Lunar Cycle · Crescent Visibility · Hijri Calendar
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
