---
layout: post
author: jelani
---
Private Frequency Estimation via Projective Geometry

## Abstract
We propose a new algorithm Projective Geometry Response (PGR) for locally differentially private (LDP) frequency estimation. For a universe size of k and with n users, our ε-LDP algorithm has communication cost ⌈log2k⌉ bits in the private coin setting and εlog2e+O(1) in the public coin setting, and has computation cost O(n+kexp(ε)logk) for the server to approximately reconstruct the frequency histogram, while achieving optimal privacy/utility tradeoff, including optimality of the leading constant factor. Our empirical evaluation shows a speedup of over 50x over PI-RAPPOR (Feldman and Talwar; 2021), while using approximately 75x less memory for practically relevant parameter settings. In addition, the running time of our algorithm is within an order of magnitude of Hadamard Response (Acharya, Sun, and Zhang; 2019) and Recursive Hadamard Response (Chen, Kairouz, and Ozgur; 2020) which have significantly worse reconstruction error. Our new algorithm is based on using Projective Planes over a finite field to define a small collection of sets that are close to being pairwise independent and a dynamic programming algorithm for approximate histogram reconstruction on the server side.  We also give an extension of PGR, which we call Hybrid Projective Geometry Response, that allows trading off computation time with utility smoothly. 
 
Joint work with Vitaly Feldman (Apple), Huy Le Nguyen (Northeastern), and Kunal Talwar (Apple). 

## Biodata
Jelani Nelson is a Professor in the Department of Electrical Engineering and Computer Sciences at UC Berkeley, and also a part-time Research Scientist at Google. His research interests include sketching and streaming algorithms, random projections and their applications to randomized linear algebra and compressed sensing, and differential privacy. He is a recipient of the Presidential Early Career Award for Scientists and Engineers, a Sloan Research Fellowship, and Best Paper Awards at PODS 2010 and 2022. He is also Founder and President of AddisCoder, Inc., which has provided free algorithms training to over 500 Ethiopian high school students since 2011, and he recently co-launched a similar "JamCoders" program in Kingston, Jamaica in Summer 2022.
