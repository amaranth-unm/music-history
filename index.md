---
title: 1920s Popular Music
layout: base
date: 2025-10-21
---

<div class="masthead-band" aria-label="Music history masthead">
  <div class="masthead-band-inner">
    <span class="masthead-kicker">Popular music in America</span>
    <span class="masthead-divider" aria-hidden="true"></span>
    <span class="masthead-label">Case Studies</span>
  </div>
</div>

{% include jumbotron.html
  height="52vh"
  image-path="/assets/images/1920s-banner-3.png"
  title="The Roaring Twenties"
  text="Jazz, dance halls, radio, and the sound of a new era"
%}

<div class="home-hero-intro">
  <div class="home-intro-grid">
    <div class="home-intro-copy">
      <div class="eyebrow">A decade in motion</div>
      <h2>Popular Music in the 1920s</h2>
      <p>
        The 1920s transformed music from a local ritual into a national obsession.
        New recording technologies, a booming nightlife culture, and the rise of radio
        turned songs into shared experiences across cities and households alike. The six essays below tell the history of a specific song as an example of these trends.
      </p>
    </div>
  </div>
</div>

<div class="ornamental-divider" aria-hidden="true"></div>

<div class="section-header">
  <h2>Essays</h2>
  <span class="section-rule" aria-hidden="true"></span>
</div>

<br style="clear: both">

{% assign essays = site.pages | where_exp: "page", "page.path contains 'essays/'" %}

<div class="gallery-wall">
  {% include card-grid.html cards = essays %}
</div>

<br style="clear: both">
