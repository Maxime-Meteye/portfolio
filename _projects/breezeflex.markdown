---
objective: ["Apprentissage de Sass/Scss", "Gagner en compétence avec CSS"] 
description: "Création d'un framework CSS"
full_description: "Création d'un framework css, permettant de positionner des éléments sur une page web avec un systeme de division en 12 colones, systeme de theme qui permet de styliser rapidement de nombreux éléments d'une page web, créations de checkbox style interrupteur etc."
result: "Projet techniquement fonctionnel, gains de compétences en Sass et CSS, mais framework difficilement utilisable."
work-date: "10/2025"
permalink: /projects/:name/
layout: page
title: "Breezeflex"
link: "https://maxime-meteye.github.io/breezeFlex/"
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
