---
layout: default
title: ~
---

```
$ whoami
james-bullock
```

```
$ cat about.txt
Sr. Machine Learning Engineer @ Boise Cascade
Manufacturing lifer · Data scientist · Cyber engineer
Anomaly detection · Agentic AI · SDR · Edge ML
```

```
$ ls posts/
```
{% for post in site.posts limit:5 %}
[{{ post.date | date: "%Y-%m-%d" }} {{ post.title }}]({{ post.url }})
{% endfor %}

```
$ _
```
