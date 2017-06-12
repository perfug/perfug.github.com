---
layout: post
title: "Prochain PerfUG : le 21 juin"
description: "Java at speed: getting the most out of modern hardware by Gil Tene"
category: annonce-event
tags: []
---
{% include JB/setup %}

Getting the most of your Java applications can be an interesting challenge. Understanding some of the optimizations that the latest crop of JVMs are able to apply when running on the latest servers may help with that. This talk will discuss some of those features and optimizations.

<!-- more -->

Along with discussing some JIT compiler capabilities & issues around the black art of micro-bechmarking, we will take a look at the evolution of Inte-based server platforms, quickly traversing through features that were introduced across the past few years, from Nehalem [55xx], through Broadwell [E-26xx v4] and beyond. We'll highlight the some of the coolest capabilities, discuss new sets of instructions (like AVX2, AVX512, BMI2, TSX, HLE), pipeline improvements, and core counts and topologies. We will then demonstrate some examples of JVM JITs using these capabilities where available, as they adapt the code they generate to the specific processor types they run on.

If you like to geek out to the sound of mechanical sympathy discussions, this is the talk for you.

[Gil Tene](https://twitter.com/giltene) is CTO and co-founder of Azul Systems. He has been involved with virtual machine and runtime technologies for the past 25 years. His pet focus areas include system responsiveness and latency behavior. Gil is a frequent speaker at technology conferences worldwide, and an official JavaOne Rock Star. He pioneered the Continuously Concurrent Compacting Collector (C4) that powers Azul's continuously reactive Java platforms. In past lives, he also designed and built operating systems,network switches, firewalls, and laser based mosquito interception systems.

Inscriptions : [PerfUG Meetup](https://www.meetup.com/fr-FR/PerfUG/events/240733470/)
