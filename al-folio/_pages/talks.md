---
layout: page
permalink: /talks/
title: talks
description: presentations in reversed chronological order.
years: [2019,2018]
nav: true
---

Slides for conference presenatations can be found in each entry in [publications]({{site.baseurl}}/publications/) page.

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>
