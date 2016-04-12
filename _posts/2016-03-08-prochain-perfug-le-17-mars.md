---
layout: post
title: "Prochain PerfUG : le 17 mars"
description: "Working with the Type Safe Scalding API"
category: old-event
tags: []
---
{% include JB/setup %}

Scalding is a go-to choice for developing MapReduce jobs and the new(ish) Type Safe API promises to make jobs ever more safer, without adding any additional testing overhead (and, of course, you all test your jobs). Even nicer, it promises to add performance optimizations for free! Actually, it's not that easy and one has to analyze what's under the hood. 
<!-- more -->

In the process of rolling out the Type Safe API of Scalding at Criteo we encountered a number of pitfalls made more difficult to overcome by the lack of documentation and examples. During this talk we'll present a down and dirty look at how we can optimize any job from the source code and the generated counters.

Those tips and tricks will be useful for any Hadoop development, actionable straight after the talk!

[Sofian Djamaa](https://twitter.com/sdjamaa) is a passionate programmer fond of solving head-scratching problems in challenging environments such as big data architectures, low latency systems and complex algorithmic situations (machine learning, optimizations). At [Criteo](http://www.criteo.com/), Sofian is the chief sponsor of Scalding, Summingbird and other data processing frameworks.
Inscriptions : [PerfUG Meetup](http://www.meetup.com/fr-FR/PerfUG/events/229433413)
