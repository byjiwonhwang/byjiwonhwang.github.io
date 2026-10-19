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
.pub-impact { display: inline-block; margin-top: 0.3rem; padding: 0.05rem 0.6rem; font-size: 0.8rem; font-style: normal; font-weight: 600; color: var(--global-theme-color); border: 1px solid var(--global-theme-color); border-radius: 999px; }
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
