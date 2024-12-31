---
layout: tags
title: tech
description: A posts page for danielpickett.dev posts
---

<h2>Debug Info:</h2>
<p>Number of tech posts: {{ site.tech.size }}</p>

<ul>
  {% for post in site.tech %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      ({{ post.path }})
    </li>
  {% endfor %}
</ul>
