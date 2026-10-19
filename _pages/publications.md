---
layout: page
permalink: /publications/
title: Publications
description: Journal articles and conference presentations.
nav: true
nav_order: 2
---

<style>
.publications .author em { font-style: normal; font-weight: 400; color: var(--global-theme-color); border-bottom: 1px solid var(--global-theme-color) !important; text-decoration: none !important; }
.pub-section-title { margin-top: 2.8rem; font-size: 1.7rem; font-weight: 700; }
.publications .abbr { display: none; }
.publications .row > .col-sm-8, .publications .row > .col-sm-10 { flex: 0 0 100%; max-width: 100%; box-sizing: border-box; border-left: 3px solid rgba(128, 128, 128, 0.3); padding-left: 1rem; margin-bottom: 1.1rem; }
.publications h2 { float: none !important; text-align: left !important; margin: 2rem 0 0.8rem !important; font-size: 1.3rem !important; font-weight: 700 !important; color: var(--global-theme-color) !important; opacity: 1 !important; }
.pub-sep { margin: 0 0.1rem; opacity: 0.4; }
.pub-tag { font-size: 0.85rem; font-weight: 500; opacity: 0.65; }
.pub-impact { font-size: 0.85rem; font-weight: 600; color: var(--global-theme-color); }
.pub-summary { display: flex; flex-wrap: wrap; gap: 0.5rem 2rem; margin: 0.5rem 0 1.5rem; padding: 0.8rem 1.1rem; font-size: 0.95rem; border: 1px solid rgba(128, 128, 128, 0.35); border-radius: 8px; }
.pub-summary:empty { display: none; }
</style>

<div class="pub-summary" id="pub-summary"></div>

{% include bib_search.liquid %}

<h2 class="pub-section-title">Journal Articles</h2>

<div class="publications">

{% bibliography --query @article %}

</div>

<h2 class="pub-section-title">Conference Papers and Presentations</h2>

<div class="publications">

{% bibliography --query @inproceedings %}

</div>

<script>
(function () {
  var order = { 'SCIE': 1, 'KCI': 2, 'International': 1, 'Domestic': 2 };
  var labels = ['Journal Articles', 'Conference Papers and Presentations'];
  var boxes = document.querySelectorAll('.publications');
  var target = document.getElementById('pub-summary');
  if (!target || boxes.length < 2) { return; }
  var html = '';
  for (var i = 0; i < 2; i++) {
    var tally = {};
    boxes[i].querySelectorAll('.pub-tag').forEach(function (el) {
      var t = el.getAttribute('data-tag');
      tally[t] = (tally[t] || 0) + 1;
    });
    var parts = Object.keys(tally)
      .sort(function (a, b) { return (order[a] || 9) - (order[b] || 9); })
      .map(function (t) { return t + ' ' + tally[t]; });
    var n = boxes[i].querySelectorAll('li').length;
    html += '<div><strong>' + labels[i] + ' ' + n + '</strong>' + (parts.length ? ' (' + parts.join(' · ') + ')' : '') + '</div>';
  }
  target.innerHTML = html;
})();
</script>
