---
title: "Kafka"
layout: archive
permalink: /categories/kafka/
author_profile: true
sidebar:
  nav: "sidebar-menu"
---

{% assign posts = site.categories['kafka'] %}
{% for post in posts %}
  {% include archive-single.html %}
{% endfor %}
