---
layout: post
title: Blog
permalink: /blog/
---

<h1>Blog Posts</h1>
<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
