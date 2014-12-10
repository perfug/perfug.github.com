---
layout: post
title: "Prochain PerfUG : le 17 décembre"
description: "PerfUG : Phaser and StampedLock Concurrency Synchronizers"
category: annonce-event
tags: []
---
{% include JB/setup %}

The Phaser is a Java 7 synchronizer used to coordinate repeated tasks between several threads.  It is very flexible and the interface is easier to use than the older constructs such as CountDownLatch.
<!-- more -->

The StampedLock is a Java 8 optimistic lock mechanism, which allows us to get much better throughput on the reading and even on the writing.



In Java 7, the Phaser was introduced to give us a more flexible form of CountDownLatch and CyclicBarrier.

In this presentation, we will show examples of how Phaser can be used to communicate between threads and how it simplifies your code. A new construct that is available in Java 8 is the StampedLock. This new type of locking mechanism allows readers to access state concurrently, much like the ReadWriteLock. However, it is much more efficient for readers, since you can do so in a more optimistic fashion. In this presentation, we will show how to use it and what some of the common coding patterns are that we can use.



Heinz Kabutz is the author of the Java Specialists Newsletter, where he researches Java constructs.  He regularly investigates techniques for writing better, faster concurrent Java code.  He has also published courses on Java and specifically on concurrency.

Cette session sera suivie d'un pot dans les locaux d'Octo, puis d'un restaurant aux frais des convives (une invitation Meetup pour le restaurant suivra).

Inscriptions : [PerfUG Meetup](http://www.meetup.com/PerfUG/events/219040577/).



 

