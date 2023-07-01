---
layout: default
title: Posts
---

<h1>{{ page.title }}</h1>

<ul>
  {% for post in site.collection_name %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>