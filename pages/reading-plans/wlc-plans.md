---
layout: page
title: Reading Plans (Westminster Larger Catechism)
permalink: /wlc-plans/
navbar: false
published: false
---

<ul>
  {% for plan in site.wlc reversed %}
    <li><a href="{{ plan.url }}">{{ plan.title }}</a></li>
  {% endfor %}
</ul>