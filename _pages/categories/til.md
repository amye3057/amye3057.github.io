---
title: "TIL"
layout: archive
permalink: /categories/til/
author_profile: true
sidebar_main: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.html %}
Today I Learned
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
