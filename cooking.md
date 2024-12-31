---
layout: page
title: Cooking
description: Cooking posts and recipes
---

I'm in the arena trying stuff. Some will work, some won't. But always learning.

<div class="post-feed">
  {% if site.cooking and site.cooking.size > 0 %}
    {% for post in site.cooking %}
      <article class="timeline-entry">
        <div class="post-date">{{ post.date | date: "%B %-d, %Y" }}</div>
        <div class="post-content">
          <h4><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h4>
          <p>{{ post.description }}</p>
        </div>
      </article>
    {% endfor %}
  {% else %}
    <p>No posts found.</p>
  {% endif %}
</div>

<style>
  .timeline-entry {
    display: flex;
    margin-bottom: 1.5em;
    gap: 2em;
  }
  .post-date {
    min-width: 100px;
    color: #666;
  }
  .post-content {
    flex: 1;
  }
  .post-content h2 {
    margin: 0;
  }
  .post-content p {
    margin-top: 0.5em;
  }
</style>
