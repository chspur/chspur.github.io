---
layout: page
title: Other
permalink: /other/
---

  <ul>
    {% for post in site.categories.other %}
      <li><a href="{{ post.url }}" class="other-link">{{ post.title }}</a></li>
    {% endfor %}
  </ul>