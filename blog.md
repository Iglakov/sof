---
layout: default
title: Блог
description: Список новостей
image: contact-bg.jpg
permalink: /blog/
---

## Список постов:
{% for post in site.posts %}
  ** [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) **
  {{ post.excerpt }}
  
  
{% endfor %}
