---
layout: page
title: Other
---

  <ul>
    {% for post in site.categories.other %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>