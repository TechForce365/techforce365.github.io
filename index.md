---
layout: default
title: Tech Force 365
---

## Welcome to Tech Force 365 

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View all updates &rarr;]({{ "/updates/" | relative_url }})
