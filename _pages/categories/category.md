---
title: "Category"
layout: archive
permalink: categories
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.html %} 
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}