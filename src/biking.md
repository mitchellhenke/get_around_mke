---
layout: page
title: Biking
---

This is a page that has information about biking


<ul>
  {% for post in collections.biking.resources %}
    <li>
      <a href="{{ post.relative_url }}">{{ post.data.title }}</a>
    </li>
  {% endfor %}
</ul>
