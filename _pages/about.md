---
layout: page
title: Home
permalink: /
---
<div class="post">
        <header class="post-header">
          <h1 class="post-title">
            {% if site.title == "blank" -%}<span class="font-weight-bold">{{ site.first_name }}</span> {{ site.middle_name }} {{ site.last_name }}{%- else -%}{{ site.title }}{%- endif %}
          </h1>
          <p class="desc">{{ page.subtitle }}</p>
        </header>
<div>

Creating sustainable agricultural management
<div class="header-bar">
 <div class="row">
  {% include cover.html path="assets/img/devon-daniel-5nMYtBODiAM-unsplash.jpg" title="cropland soils" class="img-fluid rounded z-depth-1" %}
 </div>
</div>

<div class="header-bar">
  <h2>Welcome to a soil acidification world</h2>
  Soils play a vital role in the Earth’s ecosystem and support terrestrial life on the planet.
  However, it was estimated that acidic soil covers 30% of ice-free land and 50% of potential croplands worldwide.

  {% include figure.html path="assets/img/World_Soil_pH.png" title="Soil pH distribution" class="img-fluid rounded z-depth-1" %}

  Global variation in soil pH
  <div class="caption">
    (Red = acidic soil. Yellow = neutral soil. Blue = alkaline soil. Black = no data. Source: https://en.wikipedia.org/wiki/Soil_pH)
  </div>
</div>

<div class="header-bar">
  <h2>Why soil acidification is important?</h2>
  {% include video.html path="assets/video/acidification.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  
  Acidification of agricultural soils
  <div class="caption">
    (Source: https://vro.agriculture.vic.gov.au/dpi/vro/vrosite.nsf/pages/soilhealth_acidification)
  </div>
</div>