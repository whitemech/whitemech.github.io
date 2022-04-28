---
layout: post 
title: "Structure and Hierarchy in Reinforcement Learning"
---

**When**:  Thursday, April 28, 2022, 12pm (CEST).

**Where**: Zoom online, check the address in the Google Calendar Event.

**Topic**: Structure and Hierarchy in Reinforcement Learning

**Speaker**: [Prof. Anders Jonsson](https://www.upf.edu/web/anders-jonsson), associate professor in the Department of Information and Communication Technology, Pompeu Fabra University.

#### Abstract

Hierarchical reinforcement learning (HRL) decomposes a task into simpler subtasks that can be independently solved, making it possible to solve complex sparse reward tasks more efficiently. In this talk I will present two recent papers that both introduce novel approaches for HRL.
The first paper assumes that the state space is partitioned, and defines subtasks for moving between the partitions. We represent value functions on several levels of abstraction, and use the compositionality of subtasks to estimate the optimal values of the states in each partition. The policy is implicitly defined on these optimal value estimates, rather than being decomposed among the subtasks. As a consequence, our approach can learn the globally optimal policy, and does not suffer from non-stationarities induced by high-level decisions.
In the second paper, we introduce a formalism for hierarchically composing reward machines (RMs), i.e. finite state machines with edges labeled by propositional logic formulas over high-level events that capture subgoals. We adapt HRL algorithms to Hierarchical RMs (HRMs) by defining each RM in the hierarchy as a subtask, and describe a curriculum-based method to induce an HRM for each task. A multi-level HRM can be learned more efficiently than a flat HRM since the size of each machine is much smaller.

Guillermo Infante, Anders Jonsson, Vicenç Gómez (2022).
Globally Optimal Hierarchical Reinforcement Learning for Linearly-Solvable Markov Decision Processes.
Proceedings of the AAAI Conference on Artificial Intelligence (AAAI).

Daniel Furelos-Blanco, Mark Law, Anders Jonsson, Krysia Broda, Alessandra Russo (2022).
Hierarchies of Reward Machines.
The Multi-disciplinary Conference on Reinforcement Learning and Decision Making (RLDM). 

#### Short Bio

Anders Jonsson is an associate professor in the Department of Information and Communication Technology working in automated planning and reinforcement learning. He received his Ph.D. in computer science in 2005 from the University of Massachusetts Amherst. His research interests involve sequential decision problems in which one or several agents have to make repeated decisions about what to do. Specifically, he is currently working on sequential decision problems involving multiple agents, hierarchical representations of problems, combining the strengths of reinforcement learning and planning, finding and exploiting structure in sequential decision problems, and analyzing the computational complexity of different classes of problems.


#### Material

- [Video (restricted access)](https://uniroma1.zoom.us/rec/share/Yni1vuOlwGpF6UR8f1KthWIOhOCjkabX1EmiIx8jhxjNR927buKHzAVzvXKXBKwj.j82_DZyDniMTLAr_?startTime=1651140505000)