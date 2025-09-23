---
layout: page
title: Reading Plans (Westminster Shorter Catechism)
permalink: /wsc-plans/
navbar: false
published: false
---

<ul>
  {% for plan in site.wsc reversed %}
    <li><a href="{{ plan.url }}">{{ plan.title }}</a></li>
  {% endfor %}
</ul>