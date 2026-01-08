---
layout: page
title: Projets
permalink: /projects/
---


{% for project in site.projects %} {{".test"}}

## {{ project.name }}
### Objectifs :
    {% for objective in project.objective %}
- {{ objective }}
    {% endfor %}
### Description :
{{ project.description }}
### Résultat :
{{ project.result }}
{% endfor %}