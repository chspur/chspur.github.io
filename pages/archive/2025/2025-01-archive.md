---
layout: page
title: Blog Archive (January 2025)
permalink: /2025-01-archive/
navbar: false
---

<ul>
  {% for post in site.categories.2025-01 %}
    <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
  {% endfor %}
</ul>