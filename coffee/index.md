# coffee/index.md
---
layout: default
title: Coffee Logs
permalink: /coffee/
---
#Coffee Logs
Coffee, engineers' elixir.

<ul>
  {% for post in site.coffee %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
