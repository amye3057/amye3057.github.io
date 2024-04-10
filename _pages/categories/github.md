---
title: "Github"
layout: archive
permalink: /categories/github/
author_profile: true
sidebar_main: false
sidebar:
  nav: "docs"
---

{% assign posts = site.categories.github %}
깃허브에 대해서 알아보자.
{% for post in posts %} {% include archive-single.github type=page.entries_layout %} {% endfor %}
