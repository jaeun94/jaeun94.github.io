---
title: "Linux"
layout: archive
permalink: /categories/linux/
author_profile: true
sidebar:
  nav: "sidebar-menu"
---

{% assign posts = site.categories['linux'] %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
