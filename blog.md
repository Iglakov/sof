---
layout: default
title: Новостной блог
description: Последние события
image: news-bg.jpg
permalink: /news/
---

{% for post in site.posts %}
  <div class="post-preview">
    <a href="{{ site.baseurl }}{{ post.url }}">
      <h2 class="post-title">
        {{ post.title }}
      </h2>
      <h3 class="post-subtitle">
        {{ post.description }}
      </h3>
    </a>
    <p class="post-meta">Опубликовано {{ post.date | date: "%Y-%m-%d" }}</p>
  </div>
  <hr>
{% endfor %}
