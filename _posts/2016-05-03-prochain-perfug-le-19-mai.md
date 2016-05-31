---
layout: post
title: "Prochain PerfUG : le 19 mai"
description: "OutOfMemoryException : Quel est le coût des objets en Java ?"
category: old-event
tags: []
---
{% include JB/setup %}

A Ullink, nos Heaps sont habituellement plutôt large (jusqu'à 32 Go) et nous gérons un large volume de données. Mais nous avons observé que la majorité de l'espace occupé dans la Heap ne l'est pas par les données business mais par les structures ! 
<!-- more -->

Dans cette présentation il sera montré quel est le coût des objets, quels sont les suspects idéals dans nos structures de données habituelles (Lists, Maps, Strings) et ce que nous pouvons faire pour réduire l'empreinte mémoire.

[Jean-Philippe BEMPEL](https://twitter.com/jpbempel) travaille chez [Ullink](http://www.ullink.com/) en tant qu'architecte performance sur des applications de trading requérant une très faible latence. De l'optimisation du code java jusqu'au réglage très fin du système d'exploitation et du matériel, toute la chaîne d’exécution de l'application est pris en compte pour grappiller des micro-secondes sur le traitement des ordres.
Inscriptions : [PerfUG Meetup](http://www.meetup.com/fr-FR/PerfUG/events/230809462/)
