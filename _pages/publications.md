---
layout: page
permalink: /publications/
title: publications
description: <span style="color:blue">*</span> denotes equal contribution
years: [2017,2018,2019,2020,2021,2022,2023]
nav: true
nav_order: 1
---

An up-to-date list is available on [Google Scholar](https://scholar.google.com/citations?user=XCaHtRUAAAAJ&hl=en).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
