---
layout: page
permalink: /publications/
title: publications
description: <span>*</span> denotes equal contribution.
years: [2024, 2023, 2022, 2021]
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
{% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
