---
layout: page
title: Blog Archive (Novemeber 2024)
permalink: /2024-11-archive/
navbar: false
---

<ul>
  {% for post in site.categories.2024-11 %}
    <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
  {% endfor %}
</ul>