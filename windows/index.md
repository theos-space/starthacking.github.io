---
layout: page
title: Windows
---

# Getting Started with [x]

TODO: there's quite a bit of stuff you need to set up to start
doing dev on Windows.

{% for post in site.posts %}
    {% if post.categories contains 'windows' %}
* [{{ post.title }}]({{ post.url }})
    {% endif %}
{% endfor %}
