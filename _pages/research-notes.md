---
permalink: /research-notes/
title: "Research notes"
---

A collection of research questions, ideas, and topics I'm exploring.

{% assign research_posts = site.posts | where_exp: "post", "post.categories contains 'research'" %}

<div class="project-grid">

{% for post in research_posts %}

<div class="project-card">

    <h2>{{ post.title }}</h2>

    {% if post.tags %}
    <p class="project-tags">{{ post.tags | join: " · " }}</p>
    {% endif %}

    <p>{{ post.description }}</p>

    <p class="project-link">
        <a href="{{ post.url | relative_url }}">
            Read note →
        </a>
    </p>

</div>

{% endfor %}

</div>