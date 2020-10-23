---
layout: posts
---

### Miscellaneous

{% for misc in site.categories.misc %}
 * <a href="{{ site.baseurl }}{{ misc.url }}">{{ misc.title }}</a>
{% endfor %}
