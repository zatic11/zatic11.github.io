---
layout: page
title: Projects
permalink: /projects/
---
# Project Logs
All the tinkering and fried boards go here.

{% assign pojects_posts = site.projects | sort: 'date' | reverse %}
<ul>
  {% for post in projects_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

