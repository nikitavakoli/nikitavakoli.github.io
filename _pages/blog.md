---
layout: archive
permalink: /blog/
title: "Blog"
author_profile: true
---

{% for post in site.posts %}
 {% if post.tags contains 'blog post' %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}
