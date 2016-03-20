---
title: Opening page
layout: default
---

# Hello world

This is a test of gh-pages.

## Posts

{% for post in site.posts %}
* {{ post.date | date_to_string }} -- [{{ post.title}}]({{ site.url }}{{ post.url }})
{% endfor %}

## Pages
{% for page in site.pages %}
* [{{ page.title }}]({{ site.url }}{{page.url}})
{% endfor %}
