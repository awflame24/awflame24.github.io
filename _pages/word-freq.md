---
layout: page
permalink: /word-freq/
title: word-freq
nav: true
nav_order: 4
---

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<h2>텍스트 입력</h2>
<textarea id="textInput" type="text" placeholder="분석할 텍스트를 입력하세요."></textarea>
<button onclick="updateChart()">제출</button>
<h2>단어 빈도 시각화</h2>
<div style="width: 400px; height: 400px;">
    <canvas id="myChart"></canvas>
</div>
<script src="/assets/js/word-freq.js"></script>