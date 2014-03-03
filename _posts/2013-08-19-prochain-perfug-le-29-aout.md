---
layout: post
title: "Prochain PerfUG : le 29 août"
description: "Perfs système pour les nuls"
category: old-event
tags: []
---
{% include JB/setup %}

L'avènement récent du Cloud (public et privé) et historiquement les guerres de chapelles avec les équipes infra engendrent un manque de visibilité pour les équipes projet sur les infras utilisées.
Mais quand on veut faire de la perf avec une appli, mieux vaut savoir de quoi l'infra, qui supporte l'appli, est capable.
<!-- more -->
Ces informations primaires peuvent conduire à réviser ses choix d'architecture technique, ses stratégies applicatives, son capacity planning.

A travers quelques outils ultra-simples, nous allons discerner les performances brutes de notre système (cpu, mémoire, i/o) et voir les leviers dont on dispose pour améliorer les choses.

* requêtes http : apachebench et wrk
* i/o disques : bonnie++ et iozone et sysbench
* ram : bandwidth et sysbench
* cpu : openssl et sysbench
* mysql : sysbench

Enfin, nous terminerons par un pot offert par OCTO Technology.
 
Animateur: Ludovic Piot (OCTO Technology)

Infos et inscription sur [Eventbrite](http://www.eventbrite.fr/event/7954561307)