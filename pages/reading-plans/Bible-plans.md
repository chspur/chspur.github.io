---
layout: page
title: Reading Plans (Bible)
permalink: /Bible-plans/
navbar: false
---

<ul>
  {% for plan in site.categories.Bible %}
    <li><a href="{{ plan.url }}">{{ plan.title }}</a></li>
  {% endfor %}
</ul>