---
layout: archive
permalink: /blog/
title: "Personal Blog"
author_profile: true
---
Blogs about all things school, applications, & tech

{% for post in site.posts %}
 {% if post.tags contains 'blog post' %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}
