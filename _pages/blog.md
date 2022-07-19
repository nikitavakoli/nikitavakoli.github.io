---
layout: archive
permalink: /blog/
title: "Blog"
author_profile: false
---

{% for post in site.posts %}
 {% if post.tags contains 'blog post' %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}
