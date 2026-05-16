---
layout: default
title: Home
---

# Welcome to My Portfolio

Hello! I'm a passionate developer dedicated to creating elegant solutions to complex problems. This is my digital home where I showcase my work, skills, and projects.

## Featured Projects

Check back soon for featured project highlights!

## Latest Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date_to_string }}
{% endfor %}

---

*Feel free to explore my portfolio and don't hesitate to reach out if you'd like to collaborate!*
