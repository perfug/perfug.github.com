---
layout: post
title: "Prochain PerfUG : le 16 mai"
description: "Traitement d’image sur GPU en C#"
category: old-event
tags: []
---
{% include JB/setup %}
Le traitement d’image représente une partie coûteuse de nombreuses applications logicielles, du Backend Web au Machine Learning. Il est donc souvent nécessaire d’optimiser cette partie du code.
<!-- more -->

Parallélisable, le traitement d’image bénéficie largement des capacités de bande passante mémoire et de calcul des cartes graphiques.

Dans cette présentation nous verrons comment accélérer une librairie de traitement d’image écrite en C# (AForge). Nous commencerons par faire du code multithread CPU, puis nous porterons ce code sur GPU et nous descendrons de plus en plus bas dans la stack logicielle pour arriver à un niveau de performance satisfaisant.

Pour le portage GPU, nous utiliserons l’Hybridizer, le compilateur que nous développons chez Altimesh.

Regis Portales est ingénieur de recherche chez Altimesh. Diplômé de l’Ecole Polytechnique en 2010, il y a étudié les mathématiques pures et appliquées, telles que la topologie ou la mécanique des fluides numérique. Il a travaillé trois ans chez Microsoft avant de rejoindre Altimesh. Regis est particulièrement concentré sur l’intégration de LLVM IR dans l’Hybridizer, et sur le développement de Hybridizer Essentials.

Altimesh is a software company specialized in accelerator programming. The solutions developed have different application fields such as quantitative finance, oil and gas and other linear algebra users. Software solutions are built on research on manycore architectures programming which prove to provide much higher computing capabilities than regular CPUs on compute-intensive algorithms. The latest solution provided by Altimesh is the Hybridizer, a productivity tool that helps dot net users enabling GPU technologies in their environment. Hybridizer seamlessly integrates accelerated code within managed solutions.

Inscriptions : [PerfUG Meetup](https://www.meetup.com/fr-FR/PerfUG/events/244682774/)
