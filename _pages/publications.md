---
layout: page
permalink: /publications/
title: Publications
description: Papers by categories in reversed chronological order.
years: [2022, 2021, 2020, 2019, 2018]
nav: true
---
<!-- _pages/publications.md -->

See also [google scholar](https://scholar.google.com/citations?user=UfOqjbwAAAAJ&hl=en) for a complete publication history.

<div class="publications">
<h1 class="year">Preprints</h1>

{%- for y in page.years %}
    {% bibliography -f preprints -q @*[year={{y}}]* %}
{% endfor %}

</div>

<br>
<hr>
<br>

<div class="publications">
<h1 class="year">Peer-Reviewed Articles</h1>

{%- for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
