---
title: Home
layout: index
---

{% for posts in site.posts limit: 5 %}
  <div class="card">
    <div class="card-title">
      {{ post.title }}
    </div>
    <div class="card-content">
      {{ post.excerpt }}
    </div>
  </div>
{% endfor %}
