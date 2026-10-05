---
layout: page
permalink: /publications/
title: publications
description:
nav: 3
---
<!-- _pages/publications.md -->
<h2>Journal articles & conference papers</h2>
<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[keywords=published]* %}
</div>

<h2>Working papers</h2>
<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[keywords=workingpaper]* %}
</div>