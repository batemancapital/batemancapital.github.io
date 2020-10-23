---
layout: posts
---

## Posts

{% for post in site.categories.posts %}
 * <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
{% endfor %}
