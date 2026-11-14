---
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
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

.research-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
}

.research-card {
  border: 1px solid rgba(128,128,128,0.28);
  border-radius: 10px;
  overflow: hidden;
  background: rgba(128,128,128,0.035);
}

.research-card a {
  display: block;
}

.research-card img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  display: block;
  transition: transform 0.25s ease;
}

.research-card a:hover img {
  transform: scale(1.02);
}

.research-card-content {
  padding: 1rem 1.1rem 1.15rem 1.1rem;
}

.research-card h3 {
  margin-top: 0;
  margin-bottom: 0.55rem;
  font-size: 1.08em;
}

.research-card p {
  margin-bottom: 0.7rem;
  line-height: 1.6;
  font-size: 0.94em;
}

.research-tag {
  display: inline-block;
  border: 1px solid rgba(128,128,128,0.30);
  border-radius: 999px;
  padding: 0.18rem 0.55rem;
  margin: 0.15rem 0.2rem 0.15rem 0;
  font-size: 0.72em;
  letter-spacing: 0.02em;
}

.method-box {
  margin-top: 1.5rem;
  border: 1px solid rgba(128,128,128,0.28);
  border-radius: 10px;
  padding: 1.25rem;
}

.method-flow {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 0.55rem;
  margin-top: 1rem;
}

.method-step {
  border: 1px solid rgba(128,128,128,0.30);
  border-radius: 8px;
  padding: 0.55rem 0.75rem;
  font-size: 0.88em;
}

.method-arrow {
  opacity: 0.55;
  font-weight: 700;
}

.software-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 1.25rem;
  margin-top: 1.8rem;
}

.software-card {
  border: 1px solid rgba(128,128,128,0.28);
  border-radius: 10px;
  overflow: hidden;
  background: rgba(128,128,128,0.035);
}

.software-card a {
  display: block;
}

.software-card img {
  width: 100%;
  height: 240px;
  object-fit: cover;
  display: block;
  transition: transform 0.25s ease;
}

.software-card a:hover img {
  transform: scale(1.02);
}

.software-content {
  padding: 1.1rem 1.2rem 1.25rem 1.2rem;
}

.software-content h3 {
  margin-top: 0;
  margin-bottom: 0.7rem;
}

.software-content p {
  line-height: 1.7;
}

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

.roadmap-box {
  text-align: center;
  margin-top: 1.5rem;
}

.roadmap-box a {
  display: inline-block;
}

.roadmap-box img {
  width: 100%;
  max-width: 760px;
  height: auto;
  border-radius: 8px;
}

.project-list {
  margin-top: 1.2rem;
}

.project-list li {
  margin-bottom: 0.8rem;
  line-height: 1.55;
}

@media (max-width: 760px) {
  .research-grid,
  .software-grid {
    grid-template-columns: 1fr;
  }

  .research-hero h1 {
    font-size: 1.7em;
  }

  .research-card img,
  .software-card img {
    height: 200px;
  }

  .method-arrow {
    display: none;
  }

  .method-step {
    width: 100%;
  }
}
</style>


<div class="research-hero">

  <div class="research-kicker">Research Program</div>

  <h1>
    From astronomical observation to Islamic legal reasoning
  </h1>

  <p>
    My research explores the intersection of <strong>Islamic astronomy,
    observational science, and Islamic law</strong>. It focuses particularly on
    crescent visibility, twilight, sky brightness, digital imaging, astronomical
    photometry, Hijri calendar systems, and the integration of scientific evidence
    with Islamic legal reasoning.
  </p>

  <p>
    A central objective of this research program is to develop
    <strong>evidence-based approaches to astronomy for Islamic religious practices</strong>,
    linking observation, quantitative analysis, and legal interpretation in the
    study of the <em>hilal</em>, prayer times, qibla direction, and the Hijri calendar.
  </p>

</div>


<div class="research-section">

  <div class="research-kicker">Research Themes</div>

  <h2>Four Research Themes</h2>

  <p class="research-intro">
    My research is organized around four interconnected themes linking
    crescent observation, quantitative image analysis, Hijri calendar studies,
    and digital methods in contemporary Islamic astronomy.
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

        <h3>Crescent Visibility and Twilight</h3>

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
             alt="IRIS-based analysis of crescent Moon images">

      </a>

      <div class="research-card-content">

        <h3>Astronomical Photometry and Digital Imaging</h3>

        <p>
          Measuring the intensity of the crescent and the surrounding
          twilight background through digital imaging and aperture-based
          analysis. This approach is used to quantify signal, background
          brightness, and contrast under difficult observational conditions.
        </p>

        <span class="research-tag">Photometry</span>
        <span class="research-tag">IRIS</span>
        <span class="research-tag">Digital Imaging</span>
        <span class="research-tag">Contrast</span>

      </div>

    </div>


    <div class="research-card">

      <a href="{{ base_path }}/images/Picture11.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/Picture11.png"
             alt="Astronomical parameters for Hijri calendar studies">

      </a>

      <div class="research-card-content">

        <h3>Hijri Calendar and Hisab–Rukyat Integration</h3>

        <p>
          Examining astronomical parameters and observational criteria used
          in determining the beginning of Hijri months, while addressing the
          relationship between <em>hisab</em>, <em>rukyat</em>, crescent
          visibility criteria, and Islamic legal reasoning.
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
             alt="Digital image processing for crescent Moon analysis">

      </a>

      <div class="research-card-content">

        <h3>Digital Image Processing for Crescent Detection</h3>

        <p>
          Exploring computational image-processing techniques to enhance,
          identify, and analyze faint crescent signals embedded in strong
          twilight illumination. Digital processing supports more objective
          detection and quantitative evaluation of the young Moon.
        </p>

        <span class="research-tag">Image Processing</span>
        <span class="research-tag">Crescent Detection</span>
        <span class="research-tag">Digital Astronomy</span>
        <span class="research-tag">Ilmu Falak</span>

      </div>

    </div>

  </div>

</div>


<div class="research-section">

  <div class="research-kicker">Methodology</div>

  <h2>From Observation to Quantitative Evidence</h2>

  <p class="research-intro">
    My methodological approach connects direct astronomical observation
    with digital image processing, photometric measurement, quantitative
    interpretation, and Islamic legal analysis.
  </p>

  <div class="method-box">

    <div class="method-flow">

      <div class="method-step">
        Crescent Observation
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Digital Image Acquisition
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Image Pre-Processing
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Aperture Photometry
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Contrast Analysis
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Astronomical Interpretation
      </div>

      <div class="method-arrow">→</div>

      <div class="method-step">
        Islamic Legal Analysis
      </div>

    </div>

  </div>


  <div class="software-grid">


    <div class="software-card">

      <a href="{{ base_path }}/images/software-siril.png"
         target="_blank"
         rel="noopener noreferrer">

        <img src="{{ base_path }}/images/software-siril.png"
             alt="Siril software used for astronomical image processing">

      </a>

      <div class="software-content">

        <h3>Siril-Based Astronomical Image Processing</h3>

        <p>
          <strong>Siril</strong> is used in the image-processing stage to improve
          the quality of astronomical images obtained during crescent observation.
          The software supports image calibration, enhancement, alignment,
          contrast adjustment, and other preprocessing procedures needed before
          quantitative measurements are performed.
        </p>

        <p style="margin-bottom:0;">
          In crescent visibility research, this processing helps reduce visual
          interference and strengthen the distinction between the faint lunar
          signal and the surrounding twilight background. The resulting images
          provide a cleaner and more consistent basis for subsequent photometric
          and contrast analysis.
        </p>

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

        <h3>IRIS-Based Crescent Photometry</h3>

        <p>
          <strong>IRIS</strong> is used for quantitative analysis of the crescent
          signal and the surrounding <em>syafaq</em> or twilight background.
          Aperture-based measurements are applied to selected regions of the
          image to obtain numerical values representing crescent intensity and
          background-sky intensity.
        </p>

        <p style="margin-bottom:0;">
          These measurements are then used to calculate the relative contrast
          between the crescent and twilight background. The procedure provides
          empirical evidence for evaluating crescent detectability and supports
          the development of scientifically grounded crescent-visibility criteria
          for Hijri calendar determination.
        </p>

      </div>

    </div>


  </div>

</div>


<div class="research-section">

  <div class="research-kicker">Current Research Focus</div>

  <h2>Twilight, Sky Brightness, and Crescent Visibility</h2>

  <p>
    My current research focuses on the relationship between
    <strong>twilight conditions, sky brightness, atmospheric conditions,
    and crescent visibility in tropical and low-latitude environments</strong>.
    This work investigates how variations in background sky brightness influence
    the detectability of the young crescent Moon and the measurable contrast
    between the crescent signal and its surrounding twilight background.
  </p>

  <p>
    The research integrates observational astronomy, digital imaging,
    aperture photometry, contrast analysis, astronomical modeling, and
    Islamic legal interpretation. Its broader objective is to contribute to
    the development of <strong>scientifically grounded crescent visibility
    criteria and evidence-based Hijri calendar systems</strong>.
  </p>

</div>


<div class="research-section">

  <div class="research-kicker">Future Directions</div>

  <h2>Research Questions Ahead</h2>

  <p class="research-intro">
    Several questions guide the next phase of my research.
  </p>


  <div class="future-card">

    <strong>1. How does tropical twilight influence crescent visibility?</strong>

    Understanding the relationship between sky brightness, solar depression,
    atmospheric conditions, lunar geometry, and visual or digital crescent detection.

  </div>


  <div class="future-card">

    <strong>2. Can photometric contrast improve crescent visibility criteria?</strong>

    Developing quantitative indicators based on crescent intensity,
    twilight-background intensity, Weber contrast, and digital image analysis.

  </div>


  <div class="future-card">

    <strong>3. How can astronomical evidence strengthen Hijri calendar systems?</strong>

    Connecting observational data, computational astronomy, crescent visibility
    criteria, and calendar unification with Islamic legal reasoning.

  </div>


  <div class="future-card">

    <strong>4. How can astronomy better support Islamic religious practices?</strong>

    Expanding the application of observational and computational astronomy
    to crescent observation, prayer times, qibla direction, Hijri calendar
    determination, and other dimensions of contemporary <em>Ilmu Falak</em>.

  </div>

</div>


<div class="research-section">

  <div class="research-kicker">Research Roadmap</div>

  <h2>Long-Term Research Trajectory</h2>

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


<div class="research-section">

  <div class="research-kicker">Selected Projects</div>

  <h2>Current and Recent Research Projects</h2>

  <ul class="project-list">

    <li>
      <strong>Crescent Visibility and Twilight Observation at Timau</strong><br>
      Observational study of twilight brightness and crescent visibility using
      sky-brightness measurements, digital imaging, and photometric analysis
      under dark-sky observational conditions.
    </li>

    <li>
      <strong>Lunar Photometry and Digital Imaging</strong><br>
      Application of aperture photometry and digital image analysis to compare
      crescent intensity, twilight-background intensity, and quantitative
      contrast during early lunar visibility.
    </li>

    <li>
      <strong>Hijri Calendar and Hisab–Rukyat Integration</strong><br>
      Investigation of astronomical visibility criteria, observational evidence,
      Islamic legal reasoning, and institutional approaches to the development
      of Hijri calendar systems.
    </li>

    <li>
      <strong>QGIS-Based Visualization of Prayer Times</strong><br>
      Integration of geographical coordinates and astronomical parameters
      to visualize spatial variations in prayer times and their relationship
      with geographical position.
    </li>

  </ul>

</div>


<div class="research-section">

  <div class="research-kicker">Research Outputs</div>

  <h2>Publications and Scholarly Work</h2>

  <p>
    Research outputs are published across the fields of Islamic astronomy,
    crescent visibility, observational astronomy, digital image analysis,
    Hijri calendar studies, Islamic law, and related interdisciplinary areas.
  </p>

  <p>
    <strong>
      <a href="/main-publications/">
        View Main Publications →
      </a>
    </strong>

    &nbsp;&nbsp;·&nbsp;&nbsp;

    <strong>
      <a href="/publications/">
        View Full Publications →
      </a>
    </strong>
  </p>

</div>
