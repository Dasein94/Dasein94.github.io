---
permalink: /projects/
title: "Projects"
---


A collection of analytical and computational projects I've worked on.

{% assign project_posts = site.posts | where_exp: "post", "post.categories contains 'projects'" %}

{% for post in project_posts %}

## {{ post.title }}

{% if post.tags %}
**{{ post.tags | join: " · " }}**
{% endif %}

{{ post.excerpt | strip_html | truncate: 180 }}

[View project →]({{ post.url | relative_url }})

---

{% endfor %}