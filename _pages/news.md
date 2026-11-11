---
layout: page
title: News
permalink: /news/
description: Research news, academic activities, and updates.
nav: true
nav_order: 6
---

<style>
/* Timeline */
.nw-year {
  font-size: 1.6rem;
  font-weight: 500;
  margin: 2.5rem 0 1.2rem;
}

.nw-timeline {
  margin-left: 0.5rem;
}

.nw-item {
  display: grid;
  grid-template-columns: 3.8rem 1fr;
  column-gap: 0.8rem;
  line-height: 1.5;
}

.nw-badge {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  padding-top: 0.05rem;
  line-height: 1.15;
  text-align: right;
}

.nw-badge-month {
  color: var(--global-theme-color);
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
}

.nw-badge-day {
  font-size: 1.15rem;
  font-weight: 700;
  white-space: nowrap;
}

.nw-body {
  position: relative;
  padding-bottom: 1.9rem;
  padding-left: 1.6rem;
  border-left: 2px solid rgba(128, 128, 128, 0.35);
}

.nw-body::before {
  content: "";
  position: absolute;
  left: -6px;
  top: 0.4rem;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background: var(--global-theme-color);
}

.nw-text-ko {
  font-size: 0.95rem;
  margin-top: 0.2rem;
}

/* Photo buttons */
.nw-photos {
  margin-top: 0.45rem;
}

.nw-photos:empty {
  display: none;
}

.nw-photo-link {
  display: inline-flex;
  align-items: center;
  gap: 0.35rem;
  padding: 0;
  border: none;
  background: transparent;
  color: var(--global-theme-color);
  font: inherit;
  font-size: 0.85rem;
  font-weight: 500;
  cursor: pointer;
}

.nw-photo-link:hover {
  text-decoration: underline;
}

/* Lightbox */
.nw-lightbox[hidden] {
  display: none !important;
}

.nw-lightbox {
  position: fixed;
  inset: 0;
  z-index: 9999;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 3.5rem 3rem;
  background: rgba(0, 0, 0, 0.9);
}

.nw-lightbox-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.7rem;
  max-width: 100%;
}

.nw-lightbox-img {
  display: block;
  max-width: 85vw;
  max-height: 78vh;
  width: auto;
  height: auto;
  object-fit: contain;
  border-radius: 4px;
}

.nw-lightbox-caption {
  color: #ddd;
  font-size: 0.85rem;
  text-align: center;
}

.nw-lightbox button {
  position: absolute;
  padding: 0.5rem;
  border: none;
  background: transparent;
  color: #fff;
  cursor: pointer;
}

.nw-lightbox-close {
  top: 1rem;
  right: 1.5rem;
  font-size: 2rem;
}

.nw-lightbox-prev,
.nw-lightbox-next {
  top: 50%;
  transform: translateY(-50%);
  font-size: 2.5rem;
}

.nw-lightbox-prev {
  left: 1rem;
}

.nw-lightbox-next {
  right: 1rem;
}

.nw-lightbox button[hidden] {
  display: none;
}

@media (max-width: 600px) {
  .nw-item {
    display: block;
    position: relative;
    padding-bottom: 1.9rem;
    padding-left: 1.6rem;
    border-left: 2px solid rgba(128, 128, 128, 0.35);
  }

  .nw-item::before {
    content: "";
    position: absolute;
    left: -6px;
    top: 0.4rem;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background: var(--global-theme-color);
  }

  .nw-badge {
    flex-direction: row;
    align-items: baseline;
    gap: 0.4rem;
    margin-bottom: 0.2rem;
  }

  .nw-body {
    padding: 0;
    border-left: none;
  }

  .nw-body::before {
    display: none;
  }

  .nw-lightbox {
    padding: 3rem 0.5rem;
  }

  .nw-lightbox-img {
    max-width: 95vw;
    max-height: 75vh;
  }

  .nw-lightbox-prev {
    left: 0.2rem;
  }

  .nw-lightbox-next {
    right: 0.2rem;
  }
}
</style>

<div class="nw-year">2026</div>
<div class="nw-timeline">

<!-- #18 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Dec</span>
<span class="nw-badge-day">1–2</span>
</div>
<div class="nw-body">
<div class="nw-text">Poster presentation at the 8th Korea Occupational Safety, Health and Environment Forum on an outdoor work risk assessment system designed to protect construction workers from combined exposure to extreme heat and air pollution. · <a href="https://8thkosheforum.notion.site/" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">제8회 숲과나눔 환경학술포럼에서 폭염 및 대기오염물질 노출로부터 옥외 건설노동자를 보호하기 위한 실외작업 위험성평가 시스템을 포스터 발표할 예정입니다.</div>
<div class="nw-photos" data-news="18" data-alt="8th Korea Occupational Safety, Health and Environment Forum"></div>
</div>
</div>

<!-- #19 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Nov</span>
<span class="nw-badge-day">3</span>
</div>
<div class="nw-body">
<div class="nw-text">Software copyright registered for "Outdoor Work Risk Assessment System for Construction Sites Based on Thermal Environment and Air Pollutant Concentrations" (Registration No. C-2026-056348). · <a href="https://www.cros.or.kr/psnsys/cmmn/infoPage.do?w2xPath=/ui/twc/sch/swRscOtct/swRscOtctDtl.xml" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">'열환경 및 대기오염물질 농도 기반 건설현장 실외작업 위험도 평가 시스템'의 소프트웨어 저작권을 등록했습니다(등록번호: C-2026-056348).</div>
<div class="nw-photos" data-news="19" data-alt="Software Copyright Registration 2026"></div>
</div>
</div>

<!-- #15 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Oct</span>
<span class="nw-badge-day">28</span>
</div>
<div class="nw-body">
<div class="nw-text">Presentation at the Fall Conference of the Korean Society of Safety on a thermal comfort–air quality integrated index (ERI) for compound environmental risk assessment at construction sites.</div>
<div class="nw-text-ko">한국안전학회 추계학술대회에서 건설현장 복합 환경위험 평가를 위한 열쾌적성·공기질 통합지수(ERI)를 발표했습니다.</div>
<div class="nw-photos" data-news="15" data-alt="Fall Conference of the Korean Society of Safety 2026"></div>
</div>
</div>
<!-- #16 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Oct</span>
<span class="nw-badge-day">8</span>
</div>
<div class="nw-body">
<div class="nw-text">Exhibited research outcomes at the Seoul Smart Life Week booth as a representative research fellow of the Seoul Future Talent Foundation.</div>
<div class="nw-text-ko">서울스마트라이프위크 부스에서 서울미래인재재단 대표 연구생으로 연구 성과물을 전시했습니다.</div>
<div class="nw-photos" data-news="16" data-alt="Exhibition booth at Seoul Smart Life Week"></div>
</div>
</div>

<!-- #14 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Jun</span>
<span class="nw-badge-day">22–26</span>
</div>
<div class="nw-body">
<div class="nw-text">Attended the 43rd International Symposium on Automation and Robotics in Construction (ISARC) in Singapore. · <a href="https://doi.org/10.22260/ISARC2026/0099" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">싱가포르에서 열린 제43회 건설 자동화·로보틱스 국제 심포지엄(ISARC)에 참석했습니다.</div>
<div class="nw-photos" data-news="14" data-alt="ISARC 2026 in Singapore"></div>
</div>
</div>
<!-- #13 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Jun</span>
<span class="nw-badge-day">19</span>
</div>
<div class="nw-body">
<div class="nw-text">Received the AI SeoulTech Research Support Program Scholarship from the Seoul Future Talent Foundation.</div>
<div class="nw-text-ko">서울미래인재재단의 AI서울테크 연구지원사업 장학금을 받았습니다.</div>
<div class="nw-photos" data-news="13" data-alt="AI SeoulTech Research Support Program Scholarship"></div>
</div>
</div>

<!-- #12 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">May</span>
<span class="nw-badge-day">27</span>
</div>
<div class="nw-body">
<div class="nw-text">Korean patent registered (No. 10-2971446): an apparatus and method for calculating accident occurrence probability based on an outdoor thermal comfort index. · <a href="https://doi.org/10.8080/1020220090720" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">실외 열쾌적성 지수 기반 사고발생 확률 산출 장치 및 방법에 대한 특허가 등록되었습니다(등록번호 10-2971446).</div>
<div class="nw-photos" data-news="12" data-alt="Patent registration"></div>
</div>
</div>
<!-- #11 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">May</span>
<span class="nw-badge-day">13</span>
</div>
<div class="nw-body">
<div class="nw-text">Presentation at the Spring Conference of the Korean Society of Safety on a risk assessment framework linking thermal comfort prediction and accident probability.</div>
<div class="nw-text-ko">한국안전학회 춘계학술대회에서 열쾌적성 예측과 사고확률을 연계한 위험도 평가 프레임워크를 발표했습니다.</div>
<div class="nw-photos" data-news="11" data-alt="2026 Spring Conference of the Korean Society of Safety"></div>
</div>
</div>

<!-- #10 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Feb</span>
<span class="nw-badge-day">5</span>
</div>
<div class="nw-body">
<div class="nw-text">Attended the 12th “Conversation with Future Scientists” hosted by the President at the Cheong Wa Dae State Guest House, and received the Presidential Science Scholarship certificate and medal.</div>
<div class="nw-text-ko">대통령 주재로 청와대 영빈관에서 열린 제12회 미래과학자와의 대화에 참석하여 대통령과학장학증서와 메달을 수여받았습니다.</div>
<div class="nw-photos" data-news="10" data-alt="Conversation with Future Scientists at Cheong Wa Dae"></div>
</div>
</div>

</div>

<div class="nw-year">2025</div>
<div class="nw-timeline">

<!-- #17 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Dec</span>
<span class="nw-badge-day">31</span>
</div>
<div class="nw-body">
<div class="nw-text">Paper published in the Journal of the Korean Society of Safety on the relationship between outdoor thermal environment, thermal comfort, and occupational accidents in the construction industry: a systematic review. · <a href="https://kiss.kstudy.com/Detail/Ar?key=4277456" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">건설업에서 실외 열환경 및 열쾌적성과 산업재해의 관계에 대한 체계적 고찰 논문이 한국안전학회지에 게재되었습니다.</div>
<div class="nw-photos" data-news="17" data-alt="Journal of the Korean Society of Safety"></div>
</div>
</div>

<!-- #9 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Nov</span>
<span class="nw-badge-day">16</span>
</div>
<div class="nw-body">
<div class="nw-text">Received the AI SeoulTech Graduate Scholarship from the Seoul Scholarship Foundation.</div>
<div class="nw-text-ko">서울장학재단의 AI서울테크 대학원 장학금을 받았습니다.</div>
<div class="nw-photos" data-news="9" data-alt="AI SeoulTech Graduate Scholarship"></div>
</div>
</div>
<!-- #8 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Nov</span>
<span class="nw-badge-day">12</span>
</div>
<div class="nw-body">
<div class="nw-text">Presentation at the Fall Conference of the Korean Society of Safety on a site-based weather data correction model for outdoor thermal comfort assessment.</div>
<div class="nw-text-ko">한국안전학회 추계학술대회에서 실외 열쾌적성 평가를 위한 현장 기반 기상 데이터 보정 모델을 발표했습니다.</div>
<div class="nw-photos" data-news="8" data-alt="Fall Conference of the Korean Society of Safety 2025"></div>
</div>
</div>

<!-- #7 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Oct</span>
<span class="nw-badge-day">31</span>
</div>
<div class="nw-body">
<div class="nw-text">Paper published in the Journal of the Korean Society of Safety on problems in the estimation of full-time equivalent workers in the Korean construction industry. · <a href="https://doi.org/10.14346/JKOSOS.2025.40.5.45" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">국내 건설업 상시근로자 수 산출방식의 문제점에 관한 논문이 한국안전학회지에 게재되었습니다.</div>
<div class="nw-photos" data-news="7" data-alt="Journal of the Korean Society of Safety"></div>
</div>
</div>

<!-- #6 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Sep</span>
<span class="nw-badge-day">17</span>
</div>
<div class="nw-body">
<div class="nw-text">Received the Grand Prize at the Industrial Safety Cooperative Research Paper Competition. · <a href="https://www.ispf.or.kr/select/foudNesMain/foudNesMainInfo.do?cmmntyId=2024030013&amp;nttNo=555" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">산업안전 상생 논문 경진대회에서 대상을 받았습니다.</div>
<div class="nw-photos" data-news="6" data-alt="Industrial Safety Cooperative Research Paper Competition"></div>
</div>
</div>

<!-- #5 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Jun</span>
<span class="nw-badge-day">5</span>
</div>
<div class="nw-body">
<div class="nw-text">Selected for the Presidential Science Scholarship (Graduate), 23rd Cohort. · <a href="https://www.safetyin.co.kr/news/articleView.html?idxno=21930" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">대통령과학장학금(대학원) 제23기 장학생으로 선정되었습니다.</div>
<div class="nw-photos" data-news="5" data-alt="Presidential Science Scholarship"></div>
</div>
</div>

<!-- #4 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Mar</span>
<span class="nw-badge-day">2</span>
</div>
<div class="nw-body">
<div class="nw-text">Started the M.S. program in Safety Engineering at Seoul National University of Science and Technology.</div>
<div class="nw-text-ko">서울과학기술대학교 안전공학과 석사과정에 입학했습니다.</div>
<div class="nw-photos" data-news="4" data-alt="Start of the M.S. program"></div>
</div>
</div>

</div>

<div class="nw-year">2023</div>
<div class="nw-timeline">

<!-- #3 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Apr</span>
<span class="nw-badge-day">1</span>
</div>
<div class="nw-body">
<div class="nw-text">Paper published in Sustainable Cities and Society on outdoor thermal comfort index groups for quantifying climate impact on construction accidents. · <a href="https://doi.org/10.1016/j.scs.2023.104431" target="_blank" rel="noopener noreferrer">Link</a></div>
<div class="nw-text-ko">건설 사고에 대한 기후 영향을 정량화하기 위한 실외 열쾌적성 지수 그룹 논문이 Sustainable Cities and Society에 게재되었습니다.</div>
<div class="nw-photos" data-news="3" data-alt="Sustainable Cities and Society"></div>
</div>
</div>

</div>

<div class="nw-year">2022</div>
<div class="nw-timeline">

<!-- #2 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Jul</span>
<span class="nw-badge-day">4</span>
</div>
<div class="nw-body">
<div class="nw-text">Joined LG Display (Paju) as a Safety Manager.</div>
<div class="nw-text-ko">LG디스플레이 파주 사업장에 안전 관리자로 입사했습니다.</div>
<div class="nw-photos" data-news="2" data-alt="LG Display"></div>
</div>
</div>

<!-- #1 -->
<div class="nw-item">
<div class="nw-badge">
<span class="nw-badge-month">Feb</span>
<span class="nw-badge-day">17</span>
</div>
<div class="nw-body">
<div class="nw-text">Graduated with a B.S. in Safety Engineering from Seoul National University of Science and Technology.</div>
<div class="nw-text-ko">서울과학기술대학교 안전공학과를 졸업했습니다(학사).</div>
<div class="nw-photos" data-news="1" data-alt="B.S. graduation"></div>
</div>
</div>

</div>

<script>
(function () {
  var base = '{{ "/assets/img/" | relative_url }}';
  var exts = ['jpg', 'jpeg', 'png', 'webp'];

  /* Create lightbox */
  var lightbox = document.createElement('div');
  lightbox.className = 'nw-lightbox';
  lightbox.hidden = true;
  lightbox.setAttribute('role', 'dialog');
  lightbox.setAttribute('aria-modal', 'true');
  lightbox.setAttribute('aria-label', 'News photos');

  lightbox.innerHTML = `
    <button class="nw-lightbox-close" aria-label="Close">×</button>
    <button class="nw-lightbox-prev" aria-label="Previous photo">‹</button>
    <div class="nw-lightbox-content">
      <img class="nw-lightbox-img" alt="">
      <div class="nw-lightbox-caption"></div>
    </div>
    <button class="nw-lightbox-next" aria-label="Next photo">›</button>
  `;

  document.body.appendChild(lightbox);

  var display = lightbox.querySelector('.nw-lightbox-img');
  var caption = lightbox.querySelector('.nw-lightbox-caption');
  var prev = lightbox.querySelector('.nw-lightbox-prev');
  var next = lightbox.querySelector('.nw-lightbox-next');
  var close = lightbox.querySelector('.nw-lightbox-close');

  var photos = [];
  var current = 0;
  var currentAlt = '';
  var opener = null;

  function showPhoto() {
    display.src = photos[current];
    display.alt = currentAlt;
    caption.textContent =
      currentAlt + ' · ' + (current + 1) + ' / ' + photos.length;

    prev.hidden = photos.length <= 1;
    next.hidden = photos.length <= 1;
  }

  function openLightbox(items, alt) {
    photos = items.slice();
    current = 0;
    currentAlt = alt;
    opener = document.activeElement;

    lightbox.hidden = false;
    document.body.style.overflow = 'hidden';
    showPhoto();
    close.focus();
  }

  function closeLightbox() {
    lightbox.hidden = true;
    display.removeAttribute('src');
    document.body.style.overflow = '';
    if (opener) opener.focus();
  }

  function movePhoto(step) {
    current = (current + step + photos.length) % photos.length;
    showPhoto();
  }

  prev.addEventListener('click', function () {
    movePhoto(-1);
  });

  next.addEventListener('click', function () {
    movePhoto(1);
  });

  close.addEventListener('click', closeLightbox);

  lightbox.addEventListener('click', function (e) {
    if (e.target === lightbox) closeLightbox();
  });

  document.addEventListener('keydown', function (e) {
    if (lightbox.hidden) return;

    if (e.key === 'Escape') closeLightbox();
    if (e.key === 'ArrowLeft' && photos.length > 1) movePhoto(-1);
    if (e.key === 'ArrowRight' && photos.length > 1) movePhoto(1);

    if (e.key === 'Tab') {
      var focusable = [close];
      if (photos.length > 1) focusable.push(prev, next);
      var first = focusable[0];
      var last = focusable[focusable.length - 1];

      if (e.shiftKey && document.activeElement === first) {
        e.preventDefault();
        last.focus();
      } else if (!e.shiftKey && document.activeElement === last) {
        e.preventDefault();
        first.focus();
      }
    }
  });

  /* Detect image extensions */
  function tryExt(name, i, done) {
    if (i >= exts.length) {
      done(null);
      return;
    }

    var url = base + name + '.' + exts[i];
    var img = new Image();

    img.onload = function () {
      done(url);
    };

    img.onerror = function () {
      tryExt(name, i + 1, done);
    };

    img.src = url;
  }

  /* Load up to four photos */
  function loadPhotos(box, n, k, items, button) {
    if (k > 4) return;

    var name = 'news_' + n + (k > 1 ? '_' + k : '');

    tryExt(name, 0, function (url) {
      if (!url) return;

      items.push(url);

      button.textContent = '▧ View photos (' + items.length + ')';

      if (!button.isConnected) {
        box.appendChild(button);
      }

      loadPhotos(box, n, k + 1, items, button);
    });
  }

  /* Initialize news photos */
  document.querySelectorAll('.nw-photos').forEach(function (box) {
    var n = box.getAttribute('data-news');
    var alt = box.getAttribute('data-alt') || 'News photos';
    var items = [];

    var button = document.createElement('button');
    button.type = 'button';
    button.className = 'nw-photo-link';

    button.addEventListener('click', function () {
      openLightbox(items, alt);
    });

    loadPhotos(box, n, 1, items, button);
  });
})();
</script>
