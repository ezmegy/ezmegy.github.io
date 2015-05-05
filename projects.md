---
layout: page
title: Projects
permalink: /projects/
---

A list of current projects

iOS:
<ul>
  {% for post in site.ios %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>