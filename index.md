---
title: Opening page
layout: post
---

# Hello world

This is a test of gh-pages.

## Posts

{% for post in site.posts %}
* {{ post.date | date_to_string }} -- [{{ post.title}}]({{ post.url }})
{% endfor %}

