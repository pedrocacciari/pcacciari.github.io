---
layout: default
title: GRMM – Geomechanics & Rock Mass Modeling
---

<section id="about-GRMM">
  <h2>About GRMM</h2>
  <p>Content about the group...</p>
</section>

<section id="publications">
  <h2>Publications</h2>
  {% for pub in site.data.publications %}
    <div style="padding-left: 2em;">
      <p><strong>[{{ pub.year }}]</strong>  <strong>{{ pub.title }}</strong></p>
      <p style="color: gray; font-size: 0.9em;">{{ pub.authors }}</p>
      <p><em>{{ pub.journal }}</em></p>
      <p><a href="{{ pub.doi }}" target="_blank" rel="noopener noreferrer">{{ pub.doi }}</a></p>
    </div>
  {% endfor %}
</section>

<section id="teaching-material">
  <h2>Courses taught</h2>
  <h3>GLQ3425</h3>
  <p>Introduction à la mécanique des roches (French only)</p>

  <h3>GLQ8175</h3>
  <p>Mécanique des roches appliquée (French only)</p>

  <h3>GML6002</h3>
  <p>Mécanique des roches II (Hybrid fr/en)</p>
</section>
