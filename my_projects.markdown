---
layout: page
title: Projets
permalink: /projects/
---

<section class="project-list">

{% for project in site.projects %}

<article class="project-card">

    <h2>{{ project.title }}</h2>
    <div>
        <h3>Objectifs :</h3>
        <ul>
            {% for objective in project.objective %}
            <li>{{ objective }}</li>
            {% endfor %}
        </ul>
    </div>
    <div>
        <h4> Description : </h4>
        <p>{{ project.description }}</p>
    </div>
    <div>
        <h5>Résultat :</h5>
        <p>{{ project.result }}</p>
    </div>
    <a href=".{{ project.url }}">En savoir plus</a>
</article>

{% endfor %}
</section>