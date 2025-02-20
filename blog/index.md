---
layout: default
title: Blog
nav_order: 2
---

# Posts

## this a test heading

{% for post in site.posts %}
  * [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}