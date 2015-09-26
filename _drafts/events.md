---
layout: page
title: Events
permalink: /events/
order: 10
---

<ul>
  {% for post in site.events %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
