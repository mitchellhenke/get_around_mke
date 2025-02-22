---
layout: page
title: Get Around
---

<ul>
  {% for post in collections.get_around.resources %}
    <li>
      <a href="{{ post.relative_url }}">{{ post.data.title }}</a>
    </li>
  {% endfor %}
</ul>
