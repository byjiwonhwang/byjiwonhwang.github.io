---
layout: page
title: Research
permalink: /research/
description: Research themes and ongoing research activities.
nav: true
nav_order: 1
---

<style>
.rs-intro { margin-bottom: 1.8rem; }
.rs-intro .rs-ko { margin: 0.3rem 0 0; padding: 0; border: none; }
.rs-item { display: flex; gap: 2.2rem; align-items: center; padding: 2.4rem 0; }
.rs-item.rs-rev { flex-direction: row-reverse; }
.rs-img { flex: 0 0 42%; max-width: 420px; }
.rs-img img { display: block; width: 100%; height: auto; border-radius: 8px; }
.rs-text { flex: 1 1 0; min-width: 0; }
.rs-num { margin-bottom: 0.3rem; font-size: 0.85rem; font-weight: 700; letter-spacing: 0.08em; color: var(--global-theme-color); }
.rs-text h3 { margin: 0 0 0.7rem; font-size: 1.45rem; font-weight: 700 !important; line-height: 1.3; }
.rs-text p { margin-bottom: 0; line-height: 1.6; }
.rs-ko { margin-top: 0.9rem; font-size: 0.93rem; opacity: 0.7; }
.rs-end { display: none; }
@media (max-width: 700px) {
  .rs-item, .rs-item.rs-rev { flex-direction: column; align-items: stretch; gap: 1.2rem; }
  .rs-img { flex: none; width: 100%; max-width: 100%; }
}
</style>

<div class="rs-intro">
<p>My research covers construction safety as a whole, with a focus on three areas.</p>
<p class="rs-ko">건설안전 전반을 연구하며, 특히 다음 세 가지 분야에 집중하고 있습니다.</p>
</div>

<div class="rs-item">
<div class="rs-img"><img src="{{ '/assets/img/research_1.jpg' | relative_url }}" alt="Risk assessment for outdoor work"></div>
<div class="rs-text">
<div class="rs-num">01</div>
<h3>Risk Assessment for Outdoor Work</h3>
<p>I develop models that assess how outdoor thermal conditions and air pollutants affect construction workers. My work covers site-based weather data correction, machine learning prediction of thermal comfort, and linking the predictions to accident probability. I also develop an integrated index of thermal comfort and air quality to assess compound environmental risk.</p>
<p class="rs-ko">옥외 열환경과 대기오염물질이 건설 근로자에 미치는 영향을 평가하는 모델을 개발합니다. 현장 기반 기상 데이터 보정, 열쾌적성의 머신러닝 예측, 예측값과 사고확률의 연계를 다룹니다. 또한 열쾌적성과 공기질을 통합한 지수를 만들어 복합 환경위험을 평가합니다.</p>
</div>
</div>

<div class="rs-item rs-rev">
<div class="rs-img"><img src="{{ '/assets/img/research_2.jpg' | relative_url }}" alt="AI for construction safety"></div>
<div class="rs-text">
<div class="rs-num">02</div>
<h3>AI for Construction Safety</h3>
<p>I apply AI to smart safety management in construction, including machine learning (ML), computer vision (CV), large language models (LLMs), and vision-language models (VLMs). I also work on an Artificial Intelligence of Things (AIoT) solution that supports worker safety management using real-time outdoor environmental quality.</p>
<p class="rs-ko">ML, CV, LLM, VLM 등 AI를 건설현장의 스마트 안전관리에 적용합니다. 또한 실시간 실외환경질을 활용해 근로자 안전관리를 지원하는 AIoT 솔루션을 연구합니다.</p>
</div>
</div>

<div class="rs-item">
<div class="rs-img"><img src="{{ '/assets/img/research_3.jpg' | relative_url }}" alt="Construction safety regulatory systems"></div>
<div class="rs-text">
<div class="rs-num">03</div>
<h3>Construction Safety Regulatory Systems</h3>
<p>I analyze the structure of construction safety regulatory systems and laws. Topics include how the Serious Accidents Punishment Act is interpreted by different stakeholders, and problems in the estimation of full-time equivalent workers in the Korean construction industry.</p>
<p class="rs-ko">건설안전 제도와 법령의 체계를 분석합니다. 중대재해처벌법에 대한 수용주체별 해석 차이, 국내 건설업 상시근로자 수 산출방식의 문제점 등을 다룹니다.</p>
</div>
</div>

<div class="rs-end"></div>
