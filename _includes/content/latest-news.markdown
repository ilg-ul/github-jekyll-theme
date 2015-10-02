#### [Latest News]({{ site.baseurl }}/blog/)

{% for post in site.posts limit:{{site.latest-news-pages}} %}* [{{ post.title }}]({{ post.url }})
{% endfor %}
