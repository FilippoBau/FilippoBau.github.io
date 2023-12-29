---
layout: default
title: Your Website - Welcome
---

# Welcome to My Website

Hello, I'm Filippo, and this is my personal. I share my ideas, thoughts, and projects here.

## Latest Blog Posts

{% for post in site.posts %}

- [{{ post.title }}]({{ site.url }}{{ site.baseurl }}{{ post.url }})
  {% endfor %}

Want to read more? [Visit the Blog](./myblog.html)
