---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024,2023,2019,2018]
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
