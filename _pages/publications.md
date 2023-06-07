---
layout: page
permalink: /publications/
title: publications
description:
years: [2023, 2017]
nav: false
nav_order: 1
sort_by:  year
scholar:
  sort_by: year
  order: descending
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
