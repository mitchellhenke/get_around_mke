---
layout: page
title: Your Life
---

<ul>
  {% for post in collections.your_life.resources %}
    <li>
      <a href="{{ post.relative_url }}">{{ post.data.title }}</a>
    </li>
  {% endfor %}
</ul>
