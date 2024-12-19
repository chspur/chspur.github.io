---
layout: page
title: Blog Archive
# <ul>
#   {% for post in site.categories.plans %}
#     <li><a href="{{ post.url }}">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
#   {% endfor %}
# </ul>
---

<details>
<summary><h2>December 2024</h2></summary>
  <ul>
    {% for post in site.categories.12 %}
      <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
</details>

<details>
<summary><h2>November 2024</h2></summary>
  <ul>
    {% for post in site.categories.11 %}
      <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
</details>
