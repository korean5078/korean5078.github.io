---
title: "Java"
layout: archive
permalink: /java/
author_profile: true
sidebar_main: true
sidebar:
    nav: "docs"
---

{% assign posts = site.categories.Java %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}