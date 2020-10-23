---
layout: posts
---

## Weekly

Subscribe weekly newsletter at [here](https://forms.gle/FnsAFYvk1s4XsqL88).

{% for post in site.categories.weekly %}
 * <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} - {{ post.date | date: "%Y-%m-%d" }}</a>
{% endfor %}
