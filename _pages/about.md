---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* ================================
   HOMEPAGE
================================ */

.home-hero {
  margin-bottom: 2.4rem;
}

.home-kicker {
  display: inline-block;
  margin-bottom: 0.7rem;
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  opacity: 0.62;
}

.home-title {
  margin: 0 0 0.75rem 0;
  font-size: 1.75rem;
  line-height: 1.25;
}

.home-subtitle {
  margin: 0 0 1rem 0;
  max-width: 780px;
  font-size: 1rem;
  line-height: 1.7;
  font-weight: 600;
  opacity: 0.82;
}

.home-intro {
  max-width: 800px;
  margin: 0;
  line-height: 1.8;
  opacity: 0.86;
}


/* ================================
   HERO ACTIONS
================================ */

.home-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-top: 1.3rem;
}

.home-button {
  display: inline-block;
  padding: 0.58rem 0.85rem;
  border: 1px solid rgba(127,127,127,0.35);
  border-radius: 8px;
  font-size: 0.82rem;
  font-weight: 700;
  text-decoration: none;
}

.home-button:hover {
  opacity: 0.75;
}


/* ================================
   SUMMARY CARDS
================================ */

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


/* ================================
   SECTION
================================ */

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


/* ================================
   RESEARCH TAGS
================================ */

.home-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.55rem;
  margin-top: 1rem;
}

.home-tag {
  display: inline-block;
  padding: 0.48rem 0.72rem;
  border: 1px solid rgba(127,127,127,0.28);
  border-radius: 999px;
  font-size: 0.78rem;
  line-height: 1.2;
  text-decoration: none;
  color: inherit;
  cursor: pointer;
}

.home-tag:hover,
.home-tag:focus {
  text-decoration: none;
}


/* ================================
   RESEARCH FOCUS
================================ */

.home-focus {
  border-left: 3px solid currentColor;
  padding: 0.2rem 0 0.2rem 1rem;
  margin-top: 1rem;
}

.home-focus p {
  margin: 0;
  line-height: 1.75;
}


/* ================================
   QUICK LINKS
================================ */

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
  text-decoration: none;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.home-link-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 14px rgba(0,0,0,0.07);
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


/* ================================
   RESPONSIVE
================================ */

@media (max-width: 900px) {

  .home-summary-grid {
    grid-template-columns: 1fr;
  }

}

@media (max-width: 768px) {

  .home-link-grid {
    grid-template-columns: 1fr;
  }

  .home-title {
    font-size: 1.5rem;
  }

}
</style>


<div class="home-hero">

  <div class="home-kicker">
    Academic Profile
  </div>

  <h1 class="home-title">
    Dr. Sakirman, M.S.I.
  </h1>

  <div class="home-subtitle">
    Islamic Law · Islamic Astronomy · Crescent Visibility · Hijri Calendar Studies
  </div>

  <p class="home-intro">
    I am a lecturer and researcher at the
    <strong>Faculty of Sharia and the Graduate Program of UIN Jurai Siwo Lampung, Indonesia</strong>.
    My academic work focuses on the intersection of
    <strong>Islamic law and Islamic astronomy (<em>Ilmu Falak</em>)</strong>,
    particularly the use of astronomical evidence in Islamic legal reasoning,
    crescent visibility research, and Hijri calendar determination.
  </p>

  <div class="home-actions">

    <a class="home-button" href="/research/">
      Research
    </a>

    <a class="home-button" href="/main-publications/">
      Main Publications
    </a>

    <a class="home-button" href="/teaching/">
      Teaching
    </a>

    <a class="home-button" href="/cv/">
      Academic CV
    </a>

  </div>

</div>



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



<div class="home-section">

  <h2 class="home-section-title">
    Explore Academic Work
  </h2>

  <p class="home-section-intro">
    Explore research, publications, teaching activities, and academic
    information through the main sections of this website.
  </p>

  <div class="home-link-grid">


    <a class="home-link-card" href="/research/">

      <strong>
        Research →
      </strong>

      <span>
        Research themes, methodology, current projects,
        research roadmap, and astronomical studies.
      </span>

    </a>


    <a class="home-link-card" href="/main-publications/">

      <strong>
        Main Publications →
      </strong>

      <span>
        Selected academic works in Islamic astronomy,
        Hijri calendar studies, and Islamic law.
      </span>

    </a>


    <a class="home-link-card" href="/publications/">

      <strong>
        Full Publications →
      </strong>

      <span>
        Complete academic publication record organized
        chronologically.
      </span>

    </a>


    <a class="home-link-card" href="/teaching/">

      <strong>
        Teaching →
      </strong>

      <span>
        Undergraduate, master's, and doctoral courses,
        learning materials, and academic teaching activities.
      </span>

    </a>


    <a class="home-link-card" href="/cv/">

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
