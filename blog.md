---
layout: default
title: Блог
description: Список новостей
image: contact-bg.jpg
permalink: /blog/
---
{% for post in site.posts %}

  # [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
  {{ post.description }}.
  
{% endfor %}
