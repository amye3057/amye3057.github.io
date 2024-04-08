---
title: "programming"
layout: archive
permalink: /categories/programming/
author_profile: true
sidebar_main: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.programming %}
programming
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
