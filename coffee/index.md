---
layout: page
title: Coffee Logs
permalink: /coffee/
---
Coffee, engineers' elixir.

{% assign coffee_posts = site.coffee | sort: 'date' | reverse %}
<ul>
  {% for post in coffee_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
