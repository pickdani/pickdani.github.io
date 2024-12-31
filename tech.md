---
layout: page
title: Tech
description: Tech posts and articles
---

<div class="post-feed">
  {% if site.tech and site.tech.size > 0 %}
    {% for post in site.tech %}
      <article class="timeline-entry">
        <div class="post-date">{{ post.date | date: "%Y-%m-%d" }}</div>
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
