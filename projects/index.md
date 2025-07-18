# projects/index.md
---
layout: home
title: Projects
---

All the tinkerings and fried boards go here.
<ul>
  {% for post in site.projects %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
