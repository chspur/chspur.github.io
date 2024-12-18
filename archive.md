---
layout: page
title: Blog Archive
# <ul>
#   {% for post in site.categories.plans %}
#     <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
#   {% endfor %}
# </ul>
---
{% for month in (11..12) %}
  {% for post in site.categories.month %}
    <p>{{ post.title }}</p>
  {% endfor %}
{% endfor %}  
