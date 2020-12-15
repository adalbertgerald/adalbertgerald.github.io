---
layout: page
permalink: /publications/
title: publications
description: Peer-reviewed publications by year in reversed chronological order.
years: [2021, 2020, 2019, 2018, 2017, 2015]
order: 3
---

{% for y in page.years %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}
