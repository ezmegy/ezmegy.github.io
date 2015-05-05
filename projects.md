---
layout: page
title: Projects
permalink: /projects/
---

A list of current projects

iOS:
<ul>
  {% for page in site.ios %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>