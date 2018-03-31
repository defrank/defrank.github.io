---
title: "Blog"
layout: default
---

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})
{% endfor %}

## Categories

{% include categories.html %}
