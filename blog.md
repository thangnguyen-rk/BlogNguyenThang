---
layout: post
title: Blog
permalink: /_blog/
---

<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

