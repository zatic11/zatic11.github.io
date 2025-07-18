---
layout: page
title: Project Diary
permalink: /projects/
---
All the tinkering and fried boards go here.

{% assign projects_posts = site.projects | sort: 'date' | reverse %}
<ul>
  {% for post in projects_posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

