---
layout: archive
permalink: /blog/
title: "Personal Blog"
author_profile: true
---
{% for post in site.posts %}
 {% if post.tags contains 'blog post' %}
  {{ post.title }}
 {% endif %}
{% endfor %}
