---
layout: archive
permalink: /tutorials/
title: "Projects & Tutorials"
tags: "project"
author_profile: true
---
{% for post in site.posts %}
 {% if post.tags contains 'project' %}
  {% include archive-single.html %}
 {% endif %}
{% endfor %}
