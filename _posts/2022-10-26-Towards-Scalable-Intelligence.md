---
layout: post
author: david
---
Towards Scalable Intelligence

## Abstract
Despite the monumental progress in AI, current AI agents are confined to narrow tasks in tightly controlled environments. In the near future, we will have wearable AI assistants in smart glasses or intelligent robots, providing a variety of services at homes, in workplaces, or on the road. AI and robot agents must contend with the vast uncertainty and variability of natural human environments and scale up the ability to reason, learn, and act. In the first part of this talk, we will briefly review Partially Observable Markov Decision Process (POMDP) as a principled general model for reasoning under uncertainty and then present our work on scaling up POMDP planning. POMDP planning is computationally intractable; it is also “useless” in practice according to folklore. On the contrary, our DESPOT algorithm achieves near real-time performance on complex POMDP planning tasks in dynamic environments, such as autonomous vehicles navigating among many pedestrians. The ability to reason is, however, not enough for intelligent agents; they must first acquire the model for reasoning. In the second half of the talk, we will discuss the Differentiable Algorithm Network (DAN), a compositional architecture for robot learning. A DAN is composed of neural network modules, each encoding a differentiable reasoning or planning algorithm along with an associated model; it is trained "end-to-end" from data. DAN offers many benefits, particularly, robustness in learned models and compositionality that reduces data requirements and scales up learning.

## Biodata
David Hsu is Provost’s Chair Professor in the Department of Computer Science, the director of Smart Systems Institute, and also the founding director of NUS Artificial Intelligence Laboratory (NUSAiL). He received BSc in computer science & mathematics from the University of British Columbia, Canada, and PhD in computer science from Stanford University, USA. He is an IEEE Fellow with interests in robotics, AI, and computational biology; his works currently are about robot planning and learning under uncertainty and human-robot collaboration and won multiple international awards, including, recently, Test of Time Award at Robotics: Science & Systems (RSS), 2021.

Lee Wee Sun is a professor in the Department of Computer Science, National University of Singapore. He obtained his B.Eng from the University of Queensland in 1992 and his Ph.D from the Australian National University in 1996. He has been a research fellow at the Australian Defence Force Academy, a fellow of the Singapore-MIT Alliance, and a visiting scientist at MIT. His research interests include machine learning, planning under uncertainty, and approximate inference; his works have won multiple awards and competitions, including the IJCAI-JAIR Best Paper Prize 2022 and the Test of Time Award at Robotics: Science and Systems (RSS) 2021.