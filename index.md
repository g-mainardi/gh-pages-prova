---
layout: default
title: Home
---

# Benvenuti!

Questo è il nostro sito creato con Jekyll su GitHub Pages.

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
