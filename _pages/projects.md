---
permalink: /projects/
title: "Projects"
---


A collection of projects I've worked on.

{% assign project_posts = site.posts | where_exp: "post", "post.categories contains 'projects'" %}

{% for post in project_posts %}

## {{ post.title }}

{% if post.tags %}
**{{ post.tags | join: " · " }}**
{% endif %}

{{ post.description }}

[View on GitHub →]({{ post.github }})

---

{% endfor %}