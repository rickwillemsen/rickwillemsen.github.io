---
layout: page
permalink: /publications/
title: Publications
description:
nav: 3
---
<!-- _pages/publications.md -->
<h2>Publications</h2>
<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[keywords=published]* %}
</div>

<h2>Working papers and preprints</h2>
<div class="publications">
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[keywords=workingpaper]* %}
</div>