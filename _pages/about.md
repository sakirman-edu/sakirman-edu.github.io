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
  grid-template-columns: minmax(0, 1.05fr) minmax(390px, 0.95fr);
  gap: 2.6rem;
  align-items: center;

  min-height: 540px;

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
   LUNAR IMAGE VISUAL
========================================================= */

.home-lunar-visual {
  position: relative;

  width: 100%;

  text-align: center;

  padding: 0.8rem 0;
}

.home-lunar-frame {
  position: relative;

  display: inline-block;

  width: 100%;
  max-width: 520px;
}

.home-lunar-frame::before {
  content: "";

  position: absolute;

  top: 50%;
  left: 50%;

  width: 78%;
  height: 78%;

  transform: translate(-50%, -50%);

  border-radius: 50%;

  background:
    radial-gradient(
      circle,
      rgba(0,184,217,0.09) 0%,
      rgba(0,184,217,0.035) 42%,
      rgba(0,184,217,0) 72%
    );

  animation: lunarBackgroundGlow 4.5s ease-in-out infinite;

  pointer-events: none;
}

.home-lunar-visual a {
  display: block;
  position: relative;
  z-index: 2;

  text-decoration: none;
}

.home-lunar-visual img {
  width: 100%;
  max-width: 520px;
  height: auto;

  display: block;

  margin: 0 auto;

  border-radius: 12px;

  animation: lunarVisualFloat 7s ease-in-out infinite;

  filter:
    drop-shadow(0 0 7px rgba(0,184,217,0.10));

  transition:
    transform 0.25s ease,
    filter 0.25s ease;
}

.home-lunar-visual a:hover img,
.home-lunar-visual a:focus img {
  transform: scale(1.025);

  filter:
    drop-shadow(0 0 15px rgba(0,184,217,0.28));
}


/* floating animation */

@keyframes lunarVisualFloat {

  0%,
  100% {
    transform: translateY(0) scale(1);
  }

  50% {
    transform: translateY(-6px) scale(1.018);
  }

}


/* very subtle glow behind visual */

@keyframes lunarBackgroundGlow {

  0%,
  100% {
    opacity: 0.35;
    transform:
      translate(-50%, -50%)
      scale(0.96);
  }

  50% {
    opacity: 0.75;
    transform:
      translate(-50%, -50%)
      scale(1.04);
  }

}


/* =========================================================
   LUNAR VISUAL LABEL
========================================================= */

.home-lunar-caption {
  margin-top: 0.9rem;

  color: #00b8d9;

  font-size: 0.67rem;
  font-weight: 700;

  letter-spacing: 0.08em;
  text-transform: uppercase;

  opacity: 0.78;
}

.home-lunar-description {
  max-width: 480px;

  margin: 0.45rem auto 0 auto;

  font-size: 0.72rem;
  line-height: 1.55;

  opacity: 0.62;
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

.home-link-card:hover,
.home-link-card:focus {
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

  .home-lunar-visual {
    margin-top: 1rem;
  }

  .home-lunar-frame {
    max-width: 580px;
  }

  .home-lunar-visual img {
    max-width: 580px;
  }

}


@media (max-width: 900px) {

  .home-summary-grid {
    grid-template-columns: 1fr;
  }

}


@media (max-width: 768px) {

  .home-hero {
    min-height: auto;
    padding-top: 1.4rem;
  }

  .home-title {
    font-size: 1.9rem;
  }

  .home-link-grid {
    grid-template-columns: 1fr;
  }

  .home-lunar-frame {
    max-width: 100%;
  }

  .home-lunar-visual img {
    max-width: 100%;
  }

}


@media (max-width: 520px) {

  .home-title {
    font-size: 1.65rem;
  }

  .home-subtitle {
    font-size: 0.9rem;
  }

  .home-intro {
    font-size: 0.9rem;
  }

  .home-lunar-caption {
    font-size: 0.58rem;
  }

}


/* =========================================================
   REDUCED MOTION
========================================================= */

@media (prefers-reduced-motion: reduce) {

  .home-lunar-visual img,
  .home-lunar-frame::before {
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


  <!-- RIGHT SIDE -->

  <div class="home-lunar-visual">

    <div class="home-lunar-frame">

      <a href="/images/lunar-phases.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="/images/lunar-phases.png"
             alt="Lunar phases showing the relationship between the Moon, Earth, and sunlight">

      </a>

    </div>


    <div class="home-lunar-caption">
      Lunar Phases · Crescent Visibility · Hijri Calendar
    </div>

    <div class="home-lunar-description">
      The lunar cycle provides the astronomical framework for crescent
      observation, lunar visibility analysis, and Hijri calendar studies.
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
