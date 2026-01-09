---
objective: ["Apprentissage des langages du front sans framework","Création d'un back-end avec gestion administrateur", "Gestion de base de données"] 
description: "Création d'un site web pour un restaurant fictif"
full_description: "Création d'un site web pour un restaurant fictif avec accès admin, affichage d'informations extraites d'une base de données MariaDB."
result: "Site web fonctionnel et apprentissage des bases de l'html, css, js et php"
work-date: "04/2025"
permalink: /projects/:name/
layout: page
title: "Le gout du Quebec"
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
