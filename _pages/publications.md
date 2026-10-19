---
layout: page
permalink: /publications/
title: Publications
description: Journal articles and conference presentations.
nav: true
nav_order: 2
---

<style>
.publications .author em { font-style: normal; font-weight: 700; color: var(--global-theme-color); }
.pub-section-title { margin-top: 2.5rem; }
</style>

{% include bib_search.liquid %}

<h2 class="pub-section-title">Journal Articles</h2>

<div class="publications">

{% bibliography --query @article %}

</div>

<h2 class="pub-section-title">Conference Papers and Presentations</h2>

<div class="publications">

{% bibliography --query @inproceedings %}

</div>
