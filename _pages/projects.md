---
layout: archive
permalink: /projects/
title: "Data Project Posts"
tags: "data project"
author_profile: true
---

{% for post in site.posts %}
 {% if post.tags contains 'data project' %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}
