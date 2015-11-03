---
layout: post
title: "Prochain PerfUG : le 19 novembre"
description: "Comment ne plus ajouter de RAM à vos JVM sans savoir pourquoi..."
category: annonce-event
tags: []
---
{% include JB/setup %}

Les applications Java (et les autres langages de la JVM) consomment de plus en plus de mémoire, dans le même temps les algorithmes de GC (Garbage Collection) ont amélioré leur efficacité et permettent d’allouer toujours plus de mémoire. 

Malheureusement augmenter la RAM pour éviter une OutOfMemoryError sans plus d’investigation conduit souvent à masquer/repousser une fuite mémoire ou un bug applicatif et à générer une nouvelle source d’instabilité pour l’application et la JVM. 
<!-- more -->

Durant cette session nous verrons comment analyser la consommation mémoire d’une application afin de ne pas systématiquement lui accorder plus de mémoire sans savoir quel usage qui en est fait. Pour cela, nous commencerons par une rapide présentation du fonctionnement de la mémoire de la JVM puis nous verrons comment analyser la mémoire de vos applications en production. Cette deuxième partie sera faite de façon interactive sur une JVM issue d’un retour d’experience à l’aide de l’outil Eclipse Memory Analyzer. Nous terminerons avec quelques astuces pour vous aider lors de vos futures investigations.

La présentation sera assurée par Philippe Kernévez, consultant chez OCTO Technology.
Inscriptions : [PerfUG Meetup](http://www.meetup.com/fr/PerfUG/events/226508244/)
