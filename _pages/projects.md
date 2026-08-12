---
permalink: /projects/
title: "Projects"
---


A collection of projects I've worked on.

{% assign project_posts = site.posts | where_exp: "post", "post.categories contains 'projects'" %}

<div class="project-grid">

{% for post in project_posts %}

<div class="project-card">

    <h2>{{ post.title }}</h2>

    {% if post.tags %}
    <p class="project-tags">{{ post.tags | join: " · " }}</p>
    {% endif %}

    <p>{{ post.description }}</p>

    <p class="project-link">
        <a href="{{ post.github }}" target="_blank" rel="noopener">
            View on GitHub →
        </a>
    </p>

</div>

{% endfor %}

</div>