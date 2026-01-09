---
objective: ["Apprentissage de l'utilisation des canvas","Création d'un moteur graphique", "Approche de la programmation orientée objet", "Recherche d'optimisation","Gagner en aisance avec Javascript"] 
description: "Création d'un Game of life, avec moteur de jeu maison utilisant la technologie des canvas"
full_description: "Création d'un Game of life, avec moteur de jeu indépendant fait maison. Le moteur de jeu est optimisé pour la gestion d'affichage pixel par pixel. Utilisation de la méthode 'double buffering' pour optimiser la fréquence d'affichage"
result: "Projet fonctionnel et publique, objectifs accomplis."
work-date: "04/2025"
permalink: /:name/
layout: page
title: "Game of life"
link: "https://maxime-meteye.github.io/game-of-life/"
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
