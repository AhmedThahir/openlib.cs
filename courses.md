---
layout: page
title: "Courses"
permalink: "/courses/"
---

<ul>
  {% for course in site.courses %}
    <li>
      <a href="{{ course.url | relative_url }}">{{ course.code }} : {{ course.title }}</a>
    </li>
  {% endfor %}
</ul>