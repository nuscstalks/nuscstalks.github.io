---
layout: post
author: umang
---
The Tree Clock Data Structure

## Abstract
Many applications in distributed and concurrent computing crucially rely on logical timestamping. This involves assigning timestamps to different events in the execution of a system so that the ordering induced on the assigned timestamps is isomorphic to the underlying causal ordering on events in the execution. In other words, the timestamps of two events can be used to infer the causal ordering between them. The most popular data structure used in timestamping (i.e., assigning timestamps to all events) is the vector clock data structure, which stores an integer for each node/thread in a flat array. The two basic updates on vector clocks, namely join and copy, perform exactly k integer operations, where k is the number of threads/processes. In applications where timestamps need to be computed at every event, such vector clock updates can be a computational bottleneck, especially when k is large.

In this talk, I will describe tree clocks, a new data structure that replaces vector clocks for computing causal orderings in program executions. Joining and copying tree clocks takes time that is roughly proportional to the number of entries being modified, and hence the two operations do not suffer the a-priori Θ(k) cost per application. I will then discuss an optimality result in the context of an application of my interest, namely data race detection. In shared memory multi-threaded programs synchronising over locks, the happens-before (HB) partial order on events in an execution is a classic partial order used to infer the presence of data races dynamically. For computing the HB partial order, tree clocks are optimal, in the sense that no other data structure can lead to smaller asymptotic running time. Finally, for the practically inclined, I will present empirical evidence that this data structure can significantly speed up applications such as data race detection, and for the theoretically inclined, I will discuss some future extensions and applications.

This is joint work with Andreas Pavlogiannis and Hunkar Can Tunc from Aarhus University, and Mahesh Viswanathan from University of Illinois at Urbana Champaign, and won a best paper award at ASPLOS'22. 

## Biodata
Umang Mathur is an Assistant Professor at the National University of Singapore; he received his PhD from the University of Illinois at Urbana Champaign and was an NTT Research Fellow at the Simons Institute for the Theory of Computing at Berkeley. His research broadly centres on developing techniques inspired from formal methods and logic for answering design, analysis and implementation questions in programming languages, software engineering and systems. He was a recipient of a Google PhD Fellowship, an ACM SIGSOFT Distinguished Paper Award at ESEC/FSE'18. Best Paper Award at ASPLOS'22 and was invited as a Young Researcher at the 8th Heidelberg Laureate Forum.

Umang is nervous about this talk, especially given the previous excellent colloquium by Seth Gilbert that has implicitly set very high expectations.
