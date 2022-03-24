---
layout: post
author: ilya
---
Growing a Smart Contract Language: from Safety Net to Springboard


## Abstract
The Scilla project, aimed at creating a programming language for safe and secure smart contracts, has started in late 2017 as a 100-lines-of-code prototype implemented in the Coq proof assistant. Learning
from the mistakes of Ethereum, which had pioneered the area of blockchain-based smart contracts, the aim of Scilla was to provide a smart contract language, which is expressive enough to accommodate most of the reasonable use-cases, while allowing for scalable and tractable formal verification and analysis.

Since 2019, Scilla has been powering the application layer of Zilliqa, the world's first publicly deployed sharded blockchain system. Since its public launch, hundreds of unique smart contracts implemented in
Scilla have been deployed, including custom tokens, collectibles (NFTs), auctions, multiplayer games, name registries, atomic token swaps, and many others. The design of Scilla has enabled the very first approach for efficiently sharding account-based smart contracts in a Layer-1 scalable blockchain protocol.

In my talk, I will describe the motivation, high-level design principles, and semantics of Scilla, and outline the main use cases and the tools provided by the developer community. I will also present a framework for lightweight verification of Scilla programs, and showcase its automated domain-specific analyses, aiming at proving different notions of safety and enabling sharding-based parallelism. Finally, I will outline the pragmatic pitfalls of building a new smart contract language from scratch, and present the future exciting research directions that are enabled by Scilla's take on smart contract implementation.


## Biodata
Ilya Sergey is an Associate Professor at the School of Computing of National University of Singapore, where he leads the Verified Systems Engineering lab. He also holds a joint appointment at Yale-NUS College and is a lead language designer at Zilliqa, a Singapore FinTech start-up. Ilya received his MSc from St Petersburg University and PhD from KU Leuven. Before joining NUS, he was a postdoctoral researcher at IMDEA Software Institute and a faculty at University College London. Prior to starting his academic career, he worked as a software developer at JetBrains. Ilya does research in programming language design and implementation, software verification, distributed systems, program synthesis and repair. He is a recipient of distinguished paper awards at POPL and PLDI, the 2019 Dahl-Nygaard Junior Prize, the 2021 Yale-NUS Distinguished Researcher Award, and a Google Faculty Research Award.


## Video
<iframe width="420" height="345" src=" https://www.youtube.com/embed/t1odVtEbH0A">
</iframe>
