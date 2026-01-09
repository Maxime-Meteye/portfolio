---
objective: ["Travail avec le local storage","Gains de compétence avec la programmation récursive","Créer un projet fonctionnel fait pour téléphone"] 
description: "Création d'un Pomodoro"
full_description: "Création d'un pomodoro, avec le framework VueJs, Pinia"
result: "Site fonctionnel avec gestion du local storage, Travail récurisif sur un arbre de tache à l'architecture inconnu, projet présentable sur mobile"
work-date: "10/2025"
permalink: /projects/:name/
layout: page
title: "Pomodoro"
link: "https://maxime-meteye.github.io/pomodoro/"
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
