---
layout: page
---

# Recent writing

{% for page in site.pages %}
  {% if page.title == "Blogs" %}
{{ page.content }}
  {% endif %}
{% endfor %}

{% comment %}

# Recent comments

{% for page in site.pages %}
  {% if page.title == "Comments" %}
{{ page.content }}
  {% endif %}
{% endfor %}

{% endcomment %}
