---
layout: page
title: Blog Archive
permalink: /:title/
# <ul>
#   {% for post in site.categories.plans %}
#     <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
#   {% endfor %}
# </ul>
---

<ul>
  {% for post in site.categories.posts %}
    <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
  {% endfor %}
</ul>