# coffee/index.md
---
layout: home
title: Coffee Logs
---

coffee, engineers elixir.

<ul>
  {% for post in site.coffee %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
