---
layout: page
title: Blog Archive
# <ul>
#   {% for post in site.categories.plans %}
#     <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
#   {% endfor %}
# </ul>
---
{% for category in site.categories.posts %}
  <p>{{ category.title }}</p>
{% endfor %}
  <ul>
    {% for post in site.categories.posts %}
      <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>