---
layout: post
author: roland
---
Constraint Solving–Revisiting Optimal Arc Consistency

## Abstract
This talk will revisit algorithms for local consistency, in particular, the most well-known one being Arc Consistency (AC). A classic important result is the AC3.1/AC2001 algorithm for arc consistency.  Prior to this work, the practical algorithm was AC3 but this was known not to be theoretically optimal. On the other hand, it was well known that there were optimal algorithms such as AC4 but it was simply not efficient in practice.  This was for some time, a separation between time complexity versus practical efficiency. The AC3.1/AC2001 algorithm was the first work which showed that it was possible to be: 
(i)	theoretically optimal; (ii) practically efficient and more than AC3.
Arc consistency is only for binary constraints. Since then most consistency algorithms have been on its generalization to non-binary constraints, Generalised Arc Consistency (GAC). Recently it has been shown that non-binary constraints can be practically encoded to binary constraints. We will briefly see some recent binary encodings and how it is possible to come a full circle, from binary constraints to non-binary constraints and back to binary again. New encodings such as BE and BCT show that binary propagators can outperform existing state-of-art GAC.The mechanisms we propose are rather intuitive, but through either combinatorial preprocessing, or careful analysis, we show that they are able to provide strong fairness guarantees, as well as high social welfare.
Based on joint works with Nawal Benabbou, Mithun Chakraborty, Ayumi Igarashi, Justin Payan and Vignesh Viswanathan. 

## Biodata
Roland Yap is an associate professor in the School of Computing, National University of Singapore. He obtained his PhD from Monash University, Australia. His research interests are in Artificial Intelligence, Big Data, Constraints, Programming Languages, Security. He is well known for his work on Constraint Logic Programming and the CLP(R) programming language which is one of the first programming languages where constraints are first class. CLP(R) has led to many developments in Constraint Programming (CP) and Logic Programming. 

