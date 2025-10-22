---
title: 1920s Popular Music
layout: base
date: 2025-10-21
---

{% include jumbotron.html
  height="50vh"
  image-path="/assets/images/396-banner.jpg"
  title=""
%}

# Popular Music in the 1920s

{% include figure.html
  class="right"
  width="33%"
  caption="Duke Ellington in New York City"
  image-path="/assets/images/duke-ellington-nyc.jpg"
  source-url="https://commons.wikimedia.org/wiki/File:Xanthan.svg"
%}

Welcome! On this site you will find webpages created by students in HIST 396-06 The History of Popular Music in the United States, 1830-1940. Each team of students was assigned a song made popular by a particular artist in the 1920s. They were asked to ask questions about the song and artist, and to explore what the song can tell us about the social and historical context in which it was created. 

<br style="clear: both">

{% assign essays = site.pages | where_exp: "page", "page.path contains 'essays/'" %}

{% include card-grid.html cards = essays %}

<br style="clear: both">