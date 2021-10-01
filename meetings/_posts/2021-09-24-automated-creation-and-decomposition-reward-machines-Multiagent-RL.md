---
layout: post 
title: "Automated Creation and Decomposition of Reward Machines for Multiagent Reinforcement Learning"
---

**When**:  Friday, September 24, 2021, 3pm (CEST).

**Where**: Zoom online, check the address in the Google Calendar Event.

**Topic**: Automated Creation and Decomposition of Reward Machines for Multiagent Reinforcement Learning.

**Speaker**: [Giovanni Varricchione](https://www.uu.nl/medewerkers/GVarricchione), PhD Student at Utrecht University.

#### Abstract

Recent years saw the introduction of reward machines (RM) in reinforcement learning (RL). An RM is a Mealy machine used
to define the reward function of learning agents depending on its current state. Intuitively, a state of an RM is a
high-level representation of either the agent’s (or team’s if in a multi-agent setting) behavior so far or of the stage
of completion of a task. RMs can then be used to easily define rewards. In this talk, I will describe our novel approach
that uses RMs and planning to train teams of agents.

I will first present (Neary, Wu, Xu, Topcu in AAMAS 2021), in which a multi-agent setting is considered. To overcome
various issues of the setting, like non-stationarity, a team RM is decomposed into multiple ones, one per agent, that
are then used to train their corresponding agents. We improve on this work in two ways: (i) by automatically generating
the team and individual RMs, and (ii) by training agents using an option-based framework in conjunction with a strategy.
We generate high-level uniform strategies using MCMAS, a model checker for multi-agent systems. Given that the strategy
obtained is uniform, we can easily generate the agents’ RMs from it, and then use them to train their agents. Finally,
as strategies are specified in terms of high-level actions, we can train agents to execute them using options, a known
concept in the RL literature. Preliminary results show that the automatically generated RMs lead to similar performance
when compared to the hand-crafted ones of Neary et al., and that the main approach of Neary et al. is outperformed by
our option-based one.

This talk is based on a joint work with Natasha Alechina, Mehdi Dastani and Brian Logan.

#### Material

- [Video](https://drive.google.com/file/d/1RaT7lCtkFoNe6_pp1QAtAqF8hQKVwn-y/view?usp=sharing)