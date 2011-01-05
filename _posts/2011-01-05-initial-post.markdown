---
layout: default
title: Initial post
---

{% for post in site.posts limit:5 %}
  {{ post.url }} <strong>{{post.title}}</strong>
{% endfor %}
