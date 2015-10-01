---
layout: default
permalink: /blog/
title: GNU ARM Eclipse News
author: Liviu Ionescu

---

{% for post in site.posts %}
### [{{ post.title }}]({{ site.baseurl }}/{{ post.url }})

_{{ post.date | date: "%b %-d, %Y" }}._ &nbsp;&nbsp;{{ post.excerpt | replace:'<p>','' | replace:'</p>','' }}
***
{% endfor %}
