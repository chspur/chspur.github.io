---
layout: page
title: test1
permalink: /test1/
navbar: false
---

<ul>
  {% for test in site.test_collection %}
    <li><a href="{{ test.url }}">{{ test.title }}</a></li>
  {% endfor %}
</ul>