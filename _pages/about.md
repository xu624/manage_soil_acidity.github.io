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
  <h2>WELCOME TO A SOIL ACIDIFICATION WORLD</h2>
  Soils play a vital role in the Earth’s ecosystem and support terrestrial life on the planet.
  However, it was estimated that acidic soil covers 30% of ice-free land and 50% of potential croplands worldwide.

  {% include figure.html path="assets/img/World_Soil_pH.png" title="Soil pH distribution" class="img-fluid rounded z-depth-1" %}

  Global variation in soil pH
  <div class="caption">
    (Red = acidic soil. Yellow = neutral soil. Blue = alkaline soil. Black = no data. Source: https://en.wikipedia.org/wiki/Soil_pH)
  </div>
</div>

<div class="header-bar">
  <h2>WHY SOIL ACIDIFICATION IS IMPORTANT?</h2>
  {% include video.html path="assets/video/acidification.mp4" class="img-fluid rounded z-depth-1" controls=true %}
  
  Acidification of agricultural soils
  <div class="caption">
    (Source: https://vro.agriculture.vic.gov.au/dpi/vro/vrosite.nsf/pages/soilhealth_acidification)
  </div>
</div>

<!-- Add a diagram -->
<div class="header-bar">
<h2>MITIGATION STRATEGIES FOR SOIL ACIDIFICATION</h2>
{% include figure.html path="assets/img/Zeng_mitigation.bmp" title="Mitigation stragety" class="img-fluid rounded z-depth-1" %}

 Strategies for mitigating soil acidification in intensive farming systems
  <div class="caption">
    (Source: Zeng et al. (2017). https://doi.org/10.1021/acs.est.6b05491)
  </div>
</div>

<!-- Add a table -->

<div class="header-bar">
<h2>HOW DOES MY RESEARCH CONTRIBUTE TO SUSTAINABLE SOIL ACIDITY MANAGEMENT?</h2>
<table>
<colgroup>
<col width="33%" />
<col width="33%" />
<col width="33%" />
</colgroup>
<thead>
<tr class="header">
<th>Problems</th>
<th>Objectives</th>
<th>Research Outputs</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">Lacking assessments of main drivers of soil acidification on different soil types and land uses</td>
<td markdown="span">To understand the drivers of soil acidification in different cropping systems at regional level</td>
<td markdown="span">Major drivers of soil acidification over 30 years in a typical agricultural county</td>
</tr>
<tr>
<td markdown="span">Optimal combination of mineral fertilizers, organic manure, and lime for specific crops in a given paddock is lacking</td>
<td markdown="span">To assess the impacts of management on cropland acidification, guiding manure recycling and liming</td>
<td markdown="span">Optimal fertilizer, manure and liming strategies to reduce soil acidification and nutrient losses </td>
</tr>
<tr>
<td markdown="span">Limited insight into the spatially optimal manure recycling to mitigate soil acidification</td>
<td markdown="span">To assess the optimal manure recycling rate to reduce soil acidification at regional level</td>
<td markdown="span">Spatially optimal manure recycling strategies to reduce nutrient surpluses and lime requirements</td>
</tr>
</tbody>
</table>
</div>