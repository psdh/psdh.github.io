---
layout: post
title:first paper
subtitle: document document and then document some more
published: true
comments: true
---


paper link: http://hiperc.buffalostate.edu/courses/ACM612-F15/uploads/ACM612/VanRoy-Programming.pdf


* Around 30 programmign paradigms
* Solving a programming problem, requires a certain set of concepts. A language should support multiple sets of paradigms. So that programmers can use multiple things to solve a given problem
* Each programming paradigm is an approach to a programming problem, based on a mathematical principle or a coherent set of theories.
* paradigms are not islands, they are related. To see taxonomy of the relations, see the figure/graph in the paper
* **A paradigm has to be turing complete to be practical** (I don't understand)
* For a language to support a paradigm, it is not enough that libraries have been written to support it, the language kernel should support things.
* Following are properties of a paradigms (major properties)
* **Observable nondeterminism**
	** Nondeterminism is when the execution of a program is not completely determined by its specification
	** It is observable if a user can see different results from teh same set of configuration
    ** A typical effect is a race condition.
    ** It should be supported only if expressive power is required, since this could be used to simulate real world scenarios
    ** concurrent programming is much simpler with declarative concurrent paradigms where all programs are deterministic
* **Named State**
	** Didn't really understand this bit
    