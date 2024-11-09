---
layout: page
title: Blog
permalink: /Blog/
---

Mục này sẽ trình bày về các project

{% if site.show_excerpts %}
   {% include home.html %}
{% else %}
   {% include archive.html title="Blog" %}
{% endif %}
