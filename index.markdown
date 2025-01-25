---
layout: home
title: Welcome to My Blog
---

# Welcome to My Blog

Hi! I'm Artem Bogdanov. This is my personal blog where I write about AI, computer stuff and everything.

## Recent Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) ({{ post.date | date: "%B %d, %Y" }})
{% endfor %}

[View all posts](/blog)