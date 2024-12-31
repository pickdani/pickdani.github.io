---
layout: tags
title: Tech
description: Tech posts and articles
---

<div class="post-feed">
  {% if site.tech.size > 0 %}
    {% for post in site.tech %}
    <article class="post">
      <div class="post-inside">
        {% if post.feature_image %}
        <a class="post-thumbnail" href="{{ post.url | relative_url }}">
          <img src="{{ post.feature_image | relative_url }}" alt="{{ post.title }}">
        </a>
        {% endif %}
        <header class="post-header">
          <h2 class="post-title"><a href="{{ post.url | relative_url }}" rel="bookmark">{{ post.title }}</a></h2>
        </header>
        <div class="post-content">
          <p>{{ post.description }}</p>
        </div>
        <footer class="post-meta">
          <time class="published" datetime="{{ post.date | date: '%Y-%m-%d' }}">{{ post.date | date: "%B %-d, %Y" }}</time>
        </footer>
      </div>
    </article>
    {% endfor %}
  {% else %}
    <p>No posts found.</p>
  {% endif %}
</div>
