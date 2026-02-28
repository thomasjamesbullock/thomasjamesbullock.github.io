---
layout: default
title: /blog
permalink: /blog
---

## Blog

```
$ ls -lt posts/
```
{% for post in site.posts %}
[{{ post.date | date: "%Y-%m-%d" }} {{ post.title }}]({{ post.url }})
{% endfor %}

```
$ _
```
