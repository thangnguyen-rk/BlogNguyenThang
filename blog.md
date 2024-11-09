---
layout: post
title: Blog
permalink: /blog/
---

<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

