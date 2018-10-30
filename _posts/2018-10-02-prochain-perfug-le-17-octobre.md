---
layout: post
title: "Prochain PerfUG : le 17 octobre"
description: "Comprendre les GC sur la JVM : Mode Avancé !"
category: old-event
tags: []
---
{% include JB/setup %}
Depuis quelques années, le monde du GC sur la JVM évolue : G1 est par défaut sur le JDK9, Shenandoah est mis à disposition par Red Hat, un nouveau GC entre dans l'OpenJDK depuis le JDK 11: ZGC et Azul C4 est toujours là.
Comme les GC "classiques" sont plutôt bien compris maintenant, cette présentation s'attardera sur les arcanes des plus récents. Nous allons expliquer le concurrent marking (tri-color marking), les specificités de G1, la Load Value Barrier de C4, les Brooks pointers de Shenandoah et le multi-mapping de ZGC.

<!-- more -->
Développeur passionné par les performances, les runtimes (JVM, CLR) et adepte de Mechanical Sympathy, Jean-Philippe Bempel a plus de 8 ans d'expérience dans les systèmes de trading low latency. Maintenant il apporte son expertise sur la JVM chez Criteo afin d'optimiser les jobs Map/Reduce & Spark.

Inscriptions : [PerfUG Meetup](https://www.meetup.com/fr-FR/PerfUG/events/244682807/)
