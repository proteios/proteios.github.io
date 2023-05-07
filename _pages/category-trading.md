---
title: "trading"
layout: archive
permalink: /trading
author_profile: true
sidebar:
    nav: "sidebar-category"
---
{% assign posts = site.categories.trading %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}