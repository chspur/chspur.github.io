---
layout: page
title: Reading Plans (Belgic Confession)
permalink: /bc-plans/
navbar: false
published: false
---

<ul>
  {% for plan in site.bc reversed %}
    <li><a href="{{ plan.url }}">{{ plan.title }}</a></li>
  {% endfor %}
</ul>