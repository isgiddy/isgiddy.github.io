---
layout: full-width
title: CV
permalink: /cv/
order: 6
---

<header class="page-header">
  <p class="kicker">Curriculum vitae</p>
  <h1 class="page-title">Isabelle Giddy</h1>
  <p class="page-lede">Senior Researcher at the Southern Ocean Carbon-Climate Observatory, CSIR. Physical oceanographer working on air–sea interaction and upper-ocean turbulence.</p>
</header>

<section class="cv-section">
  <h2 class="section-label">Positions</h2>
  <div class="cv-entry">
    <span class="cv-when">Current</span>
    <div class="cv-what">
      <span class="cv-title">Senior Researcher</span>
      <span class="cv-where">Southern Ocean Carbon-Climate Observatory (SOCCO), CSIR, South Africa</span>
    </div>
  </div>
  <div class="cv-entry">
    <span class="cv-when">Previously</span>
    <div class="cv-what">
      <span class="cv-title">VR International Postdoctoral Fellow</span>
      <span class="cv-where">University of Gothenburg, with affiliation at the University of Bergen &amp; NASA Ames</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="section-label">Education</h2>
  <div class="cv-entry">
    <span class="cv-when">2018–2023</span>
    <div class="cv-what">
      <span class="cv-title">Ph.D. in Physical Oceanography</span>
      <span class="cv-where">University of Gothenburg &amp; University of Cape Town</span>
    </div>
  </div>
  <div class="cv-entry">
    <span class="cv-when">2013–2014</span>
    <div class="cv-what">
      <span class="cv-title">M.Sc. in Physical Oceanography</span>
      <span class="cv-where">University of Cape Town</span>
    </div>
  </div>
  <div class="cv-entry">
    <span class="cv-when">2008–2011</span>
    <div class="cv-what">
      <span class="cv-title">B.Sc. (Hons) in Physical Oceanography and Marine Ecology</span>
      <span class="cv-where">University of Cape Town</span>
    </div>
  </div>
</section>

<section class="cv-section">
  <h2 class="section-label">Publications</h2>
  <ul class="pub-list">
    {% for pub in site.data.publications %}
      {% include publication.html pub=pub %}
    {% endfor %}
  </ul>
</section>

<section class="cv-section">
  <h2 class="section-label">Research interests</h2>
  <ul class="tag-list">
    <li>Air–sea interactions</li>
    <li>Boundary layer turbulence</li>
    <li>Wind–wave–current interactions</li>
    <li>Observing the ocean with autonomous platforms</li>
  </ul>
</section>
