---
title: Hello World
layout: base.html
---

Hello Eleventy!

{% for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url }})
{% endfor %}