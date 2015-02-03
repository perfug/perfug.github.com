---
layout: post
title: "Prochain PerfUG : le 17 décembre"
description: "PerfUG : Phaser and StampedLock Concurrency Synchronizers"
category: old-event
tags: []
---
{% include JB/setup %}

Phaser est une barrière de synchronisation Java 7 utilisée pour orchestrer, entre plusieurs threads, un lot de tâches répétitives. Le système offre une interface plus simple à utiliser que son prédécesseur CountDownLatch.
<!-- more -->

StampedLock est un mécanisme de verrou apparu en Java 8 qui peut s'apparenter à un ReadWriteLock avec de meilleures performances et un système de lecture optimiste inédit.

 

Avec Java 7, l'introduction de l'API Phaser offrait un usage plus flexible des existants CountDownLatch et CyclicBarrier.

Au cours de cette présentation, nous vous exposerons un certain nombre d'exemples d'utilisation de Phaser dans la communication entre Threads et en quoi cela pourra vous simplifier le code ! En Java 8, nous pouvons profiter de la nouvelle construction StampedLock. Ce nouveau type de verrou permet l'accès concurrent à plusieurs lecteurs de manière plus efficiente qu'un ReadWriteLock grâce à son "mode" optimiste. A travers la présentation, nous vous montrerons comment l'utiliser et dans quels patterns communs ces constructions peuvent s'inscrire.

 

Heinz Kabutz est auteur du Java Specialists Newsletter où il expose ses recherches autour de nouvelles constructions Java. Il étudie régulièrement les techniques d'écriture de code Java optimisé pour la concurrence et de meilleure qualité. Il publie également des cours Java, plus particulièrement dans le domaine de la programmation concurrente.


Cette session sera suivie d'un pot dans les locaux d'Octo, puis d'un restaurant aux frais des convives (une invitation Meetup pour le restaurant suivra).

Inscriptions : [PerfUG Meetup](http://www.meetup.com/PerfUG/events/219040577/).


 

