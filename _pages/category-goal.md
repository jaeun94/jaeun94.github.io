---
title: "Goal"
layout: archive
permalink: /categories/goal/
author_profile: true
sidebar:
  nav: "sidebar-menu"
---

{% assign posts = site.categories['goal'] %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
