## Posts:


{% for post in site.posts %}
* <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}

