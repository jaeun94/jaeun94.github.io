---
title: "Retrospect"
layout: archive
permalink: /categories/retrospect/
author_profile: true
sidebar:
  nav: "sidebar-menu"
---

{% assign posts = site.categories['retrospect'] %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
