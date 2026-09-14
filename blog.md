---
layout: default
title: Blog
---

# The De-Abstractification of Abstract Nonsense.

Here are my posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
