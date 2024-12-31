---
layout: default
title: tech
description: A posts page for danielpickett.dev posts
---

<div class="tech-page">
  <h1>Tech Posts</h1>
  
  <div class="debug">
    <h2>Debug Info:</h2>
    <p>Raw tech collection size: {% raw %}{{ site.tech.size }}{% endraw %}</p>
  </div>

  <ul class="post-list">
    {% raw %}{% for post in site.tech %}{% endraw %}
      <li>
        <h3>
          <a href="{% raw %}{{ post.url }}{% endraw %}">{% raw %}{{ post.title }}{% endraw %}</a>
        </h3>
        <p>Path: {% raw %}{{ post.path }}{% endraw %}</p>
        <p>Date: {% raw %}{{ post.date | date: "%Y-%m-%d" }}{% endraw %}</p>
      </li>
    {% raw %}{% endfor %}{% endraw %}
  </ul>
</div>
