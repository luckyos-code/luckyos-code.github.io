---
layout: page
permalink: /publications/
title: publications
description: My publications in reversed chronological order.
years: [2025,2024,2023,2020]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
