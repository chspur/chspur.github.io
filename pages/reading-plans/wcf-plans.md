---
layout: page
title: Reading Plans (Westminster Confession of Faith)
permalink: /wcf-plans/
navbar: false
published: false
---

<ul>
  {% for plan in site.wcf reversed %}
    <li><a href="{{ plan.url }}">{{ plan.title }}</a></li>
  {% endfor %}
</ul>