---
layout: page
permalink: /publications/
title: publications
description: Publications grouped by year and category, in reverse chronological order.
nav: true
nav_order: 1
---
<!-- _pages/publications.md
     Each paper is placed one-by-one via a single-condition query on its `pubid`
     (the same reliable mechanism as the homepage's `selected`).
     To add a paper: give it `pubid = {something}` in papers.bib, then add one
     line below under the desired year / category heading. -->
<div class="publications">
     
  <h2 class="year">2026</h2>
  <h3 class="category">Domestic Conferences</h3>
  {% bibliography -f papers -q @*[pubid=ISEC:ICS26]* %}
  {% bibliography -f papers -q @*[pubid=SCIS:MHTCS26]* %}
  {% bibliography -f papers -q @*[pubid=SCIS:MHCS26]* %}

  <h2 class="year">2025</h2>
  <h3 class="category">International Conferences</h3>
  {% bibliography -f papers -q @*[pubid=MobiSecSHCS25]* %}
  {% bibliography -f papers -q @*[pubid=SecITCMCHS25]* %}
  {% bibliography -f papers -q @*[pubid=PCCHS25]* %}
  <h3 class="category">Domestic Conferences</h3>
  {% bibliography -f papers -q @*[pubid=ISEC:ICS25]* %}
  {% bibliography -f papers -q @*[pubid=CSS:SHCS25]* %}
  {% bibliography -f papers -q @*[pubid=CSS:MCHS25]* %}

  <h2 class="year">2024</h2>
  <h3 class="category">International Conferences</h3>
  {% bibliography -f papers -q @*[pubid=CANSCHHTS24]* %}
  {% bibliography -f papers -q @*[pubid=NSSMCHS24]* %}
  <h3 class="category">Preprints</h3>
  {% bibliography -f papers -q @*[pubid=ePrintCHS24]* %}
  <h3 class="category">Domestic Conferences</h3>
  {% bibliography -f papers -q @*[pubid=CSS:CHHTS24]* %}
  {% bibliography -f papers -q @*[pubid=ISEC:MCHS24]* %}
  {% bibliography -f papers -q @*[pubid=SCIS:CHHS24]* %}

  <h2 class="year">2023</h2>
  <h3 class="category">International Conferences</h3>
  {% bibliography -f papers -q @*[pubid=ISPECCHS23]* %}
  {% bibliography -f papers -q @*[pubid=ProvSecCHS23]* %}
  <h3 class="category">Preprints</h3>
  {% bibliography -f papers -q @*[pubid=ePrintCHHS23]* %}
  <h3 class="category">Domestic Conferences</h3>
  {% bibliography -f papers -q @*[pubid=ISEC:CHS23b]* %}
  {% bibliography -f papers -q @*[pubid=ISEC:CHS23a]* %}

</div>
