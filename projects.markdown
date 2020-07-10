---
layout: page
title: Projects
permalink: /projects/
---

<ul>
  {% for project in site.data.projects %}
    <li><span>{{ project.name }}</span> &raquo; <a href="https://github.com/{{ post.url }}">{{ project.name }}</a></li>
  {% endfor %}
</ul>
