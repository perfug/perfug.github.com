---
layout: post
title: "Prochain PerfUG : le 27 mars"
description: "Génération de code, moteur Catalyst… Démystifions Apache Spark !"
category: old-event
tags: []
---
{% include JB/setup %}
Apache Spark est un framework de calcul distribué écrit en Scala qui s’est largement démocratisé ces dernières années. Au cours des dernières versions, Apache Spark s’est doté d’un moteur SQL avec génération de code à la volée, qui lui permet de profiter des diverses optimisations existantes dans le domaine.
Afin de comprendre en détail le fonctionnement de ce moteur SQL, nous allons réécrire une version simplifiée mais fonctionnelle du moteur qui s’appuie sur le même principe que le moteur Catalyst utilisé par Spark : étape par étape, nous allons parser une requête SQL, calculer les plans logique et physique et comprendre en quoi la génération de code à la volée permet d’améliorer les performances lors de l'exécution.
<!-- more -->
Nous nous attarderons également sur certains aspects plus théoriques qui sont aujourd’hui exploités par la plupart des moteurs SQL, tel que le Volcano Model, les optimisations, etc.

Développeur Java de longue date, Adrien Besnard travaille aujourd'hui majoritairement en Scala et s'est spécialisé dans l'utilisation framework Apache Spark
Développeur Scala depuis plusieurs années, Marc Alonso travaille chez OCTO Technology sur des problématiques liées au traitement et au stockage de la donnée, notamment en tant qu'expert Spark.

Inscriptions : [PerfUG Meetup](https://www.meetup.com/fr-FR/PerfUG/events/254607751/)
