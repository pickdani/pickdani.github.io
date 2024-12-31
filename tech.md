---
layout: page
title: Tech
description: Tech posts and articles
---

<div class="post-feed">
  {% if site.tech and site.tech.size > 0 %}
    {% for post in site.tech %}
      <article>
        <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        <p>{{ post.description }}</p>
      </article>
    {% endfor %}
  {% else %}
    <p>No posts found.</p>
  {% endif %}
</div>
