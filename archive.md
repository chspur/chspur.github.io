---
layout: page
title: Blog Archive
# <ul>
#   {% for post in site.categories.plans %}
#     <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
#   {% endfor %}
# </ul>
---
<style>
  a.color:link, a.color:visited {
  color: #222288;
}
</style>

<ul>
  {% for post in site.categories.posts %}
    <li><a href="{{ post.url }}" class="color">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
  {% endfor %}
</ul>