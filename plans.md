---
layout: page
title: Reading Plans
---

  <ul>
    {% for post in site.categories.plans %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>