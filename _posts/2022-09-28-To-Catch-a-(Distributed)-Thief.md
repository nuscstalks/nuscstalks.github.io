---
layout: post
author: seth
---
To Catch a (Distributed) Thief

## Abstract
Over the last several years we have seen a boom in the development of new Byzantine agreement protocols, in large part driven by the excitement over blockchains and cryptocurrencies. Unfortunately, Byzantine agreement protocols have some inherent limitations: 
(a) they are very expensive, particularly in terms of bandwidth; 
(b) correctness tends to depend on strong assumptions, such as unreliable network behavior; 
(c) and it is impossible to ensure correct operation when more than 1/3 of the processing power in the system is controlled by a single malicious party. These problems are fundamentally intertwined with the problem of Byzantine fault tolerance.
What if, instead of preventing bad behavior by a malicious attacker, we guarantee "accountability," i.e., we can provide irrefutable evidence of the bad behavior and the identity of the perpetrator of those illegal actions? Much in the way we prevent crime in the real world, we can prevent bad behavior in a distributed system: either the protocol succeeds, or alternatively we record sufficient information to catch the criminal and take remedial actions. (Accountability has been increasingly discussed as a desirable property in blockchains like Ethereum to slash stake of cheating users.) The problem is to avoid suspecting correct peers while provably identifying cheating ones.
In this talk, we give an overview of accountability in distributed systems, with a focus on decision problems like consensus. We begin with Polygraph, the first (provably) accountable consensus protocol, and then describe the ABC transformation for making every consensus protocol accountable. Finally, we talk about the underlying theory of accountability and the necessary and sufficient conditions for achieving accountability.
This talk covers joint work by Pierre Civit, Vincent Gramoli, Rachid Guerraoui, Jovan Komatovic, Zarko Milosevic, and Adi Serendinschi, and appeared at ICDCS 2021, IPDPS 2022, and ICDCS 2022.

## Biodata
Seth Gilbert is an Associate Professor at the National University of Singapore. He received his PhD from MIT, and spent several years as a postdoc at EPFL. His work includes research on backoff protocols, dynamic graph algorithms, wireless networks, robust scheduling, and the occasional blockchain. In fact, Seth’s research focuses on algorithmic issues of robustness and scalability, wherever they may arise.
