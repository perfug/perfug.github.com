---
layout: post
title: "CR du PerfUG 26 : High Performance Images"
description: ""
category: compte-rendu
tags: []
---
{% include JB/setup %}

Retrouvez les présentations du PerfUG 26 par Gareth Hughes et Tobias Baldauf.

 - Measuring Front-end Performance: What, When and How?
 - High Performance Images

<!-- more -->

## Measuring Front-end Performance: What, When and How?  

by: [Gareth Hughes](https://uk.linkedin.com/pub/gareth-hughes/17/743/2ab), Web Performance Enterprise Architect at Akamai Technologies 

Les slides sont disponibles ici : http://fr.slideshare.net/GarethHughes3/measuring-frontend-performance-what-when-and-how  
Quelques outils utiles cités pendant la présentation :
  
  - WebPageTest : http://www.webpagetest.org (Open source : https://github.com/WPO-Foundation/webpagetest)
  - Site Speed : https://www.sitespeed.io/
  - PerfBar : http://wpotools.github.io/perfBar/
  
<iframe src="//fr.slideshare.net/slideshow/embed_code/key/rkPdLlNzgAtjAG" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe>


## High Performance Images

by: [Tobias Baldauf](http://who.tobias.is/), Senior Web Performance Solutions Architect at [Akamai](http://www.akamai.com/)

Les slides sont disponibles ici : https://speakerdeck.com/tbaldauf/high-performance-images-paris-perfug-meetup-20151102  
Quelques outils utiles pour optimiser vos images JPEG :

  - CPJPEG DSSIM : https://github.com/technopagan/cjpeg-dssim (calcule l'index de dissimilarité DSSIM en utilisant différents algorithmes de compression afin de choisir le meilleur
  - Adept JPG Compressor : https://github.com/technopagan/adept-jpg-compressor
  - MSS Saliency : https://github.com/technopagan/mss-saliency (implémente l'algorithme de Maximum Symmetric Surround Saliency)
  - ZorroSVG : http://quasimondo.com/ZorroSVG/ (transforme les images PNG transparante et lourde en un SVG qui aura les mêmes propriétés de transparences mais une taille bien plus faible)

Et le dernier standard, [JPEG XT](http://www.jpeg.org/jpegxt/index.html), backward compatible que seul Safari supporte malheureusement. 

<script async class="speakerdeck-embed" data-id="a8052743f8434848ab1c943aba41ce68" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>