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
<summary>2024</summary>
  <details>
  <summary>December</summary>
    <ul>
      {% for post in site.categories.12 %}
        <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
      {% endfor %}
    </ul>
  </details>

  <details>
  <summary>November</summary>
    <ul>
      {% for post in site.categories.11 %}
        <li><a href="{{ post.url }}" class="archive-link">{{ post.date | date: "%B %-d, %Y" }} - {{ post.title }}</a></li>
      {% endfor %}
    </ul>
  </details>
</details>