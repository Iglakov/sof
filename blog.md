---
layout: default
title: Блог
description: Список новостей
image: contact-bg.jpg
permalink: /blog/
---

## Список постов:
{% for post in site.posts %}
  * [{{ post.title }} - {{ post.description }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
