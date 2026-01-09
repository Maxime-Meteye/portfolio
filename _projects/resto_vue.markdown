---
objective: ["Apprentissage de l'utilisation du framework VueJs"] 
description: "Recréation du site web d'un restaurant fictif avec framework VueJs"
full_description: "Création d'un site web pour un restaurant fictif avec accès admin, affichage d'informations extraites d'une base de données MariaDB."
result: "Site web fonctionnel, utilisation du framework VueJs"
work-date: "05/2025"
permalink: /projects/:name/
layout: page
title: "Le gout du Quebec, version VueJs"
---

{{page.work-date}}

## Objectifs

{% for obj in page.objective %}

{{obj}}

{% endfor %}

### Description

{{page.full_description}}

### Résultats

{{page.result}}

{% if page.link %}

<a href="{{page.link}}" target="_blank">Lien vers le site du projet</a>

{% endif %}

<a href="/projects/">Retour à la liste des projets</a>
