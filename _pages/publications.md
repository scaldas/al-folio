---
layout: page
permalink: /publications/
title: Publications
description: #publications by categories in reversed chronological order.
years: [2021, 2020, 2019, 2018]
nav: true
sort: 3
---

<!-- _pages/publications.md -->
<div class="publications">

<p>An up-to-date list is available on <a href="https://scholar.google.com/citations?user=u15oBdQAAAAJ" target="_blank">Google Scholar</a>.</p>

<h1> conferences & journals </h1>
{% bibliography -f papers -q @*[category=conference]* %}

<h1> workshops </h1>
{% bibliography -f papers -q @*[category=workshop]* %}

</div>
