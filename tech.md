---
layout: tags
title: tech
description: A posts page for danielpickett.dev posts
---

<ul>
  {% for post in site.tech %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
