---
layout: Home
permalink: /
---

<h1>Welcome to My Website</h1>
<p>This is the homepage of my amazing Jekyll site!</p>

<h2>Recent Blog Posts</h2>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
