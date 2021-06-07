---
title: Deep reinforcement learning of skills using intrinsic motivation
layout: default
---
### Introduction
In reinforcement learning, an agent learns by trials and errors to maximize the expectation of rewards received while acting in his environment. Despite the recent advances in deep reinforcement learning (DRL), there are several scientific barriers: when the rewards are sparse, the agent never finds the reward and has an erratic behavior; what it learnt while solving a task is almost useless for solving another task; when the sequence of actions that leads to the optimal reward is very long, it hardly adapts the first actions of the sequence (_credit assignment issue_).

### Current works

In the first part of the projet, we review how intrinsic motivation-based approaches currently tackle these issues an exhibit their limitations [1]. We then highlight the perspectives of the domain [1]. In the second part, we investigate how skill-based intrinsic motivations can tackle these issues by introducing two models: ELSIM [4] and DisTop [5]. Both learn intrinsic skills that can be hierarchically used in an end-to-end way to explore and solve a task. In particular, skills are learnt with purely intrinsic rewards and extrinsic reward are only used to choose which skills to improve.

Our main results are as follow:
1. ELSIM [4] continually expands a tree of skills in the direction of the feedbacks of the environments. We show that skills learnt this way can both learn a task and be used later for another correlated task. 
2. DisTop [5] builds a topological representation of its environment and learns skills that maximize the entropy of the states in its representation. It manages both to learn a task and learn very diverse skills. By combining the two, we show it efficiently explores when rewards are sparse in the environment.


### Papers

[5] Aubret, A., Matignon, L., Hassas, S.: DisTop: Discovering a Topological representation to learn diverse and rewarding skills. Under review.

[4] Arthur Aubret, Laëtitia Matignon, Salima Hassas: ELSIM: End-to-End Learning of Reusable Skills Through Intrinsic Motivation. ECML/PKDD (2) 2020: 541-556

[3] Aubret, A., Matignon, L., Hassas, S.: ELSIM: End-to-end learning of reusable skills
through intrinsic motivation. ICML 2020 Workshop LifelongML

[2] Aubret, A., Matignon, L., Hassas, S.: A survey on intrinsic motivation in reinforcement learning. arXiv
preprint arXiv:1908.06976 (2019)

[1] Aubret, A., Matignon, L., Hassas, S.: Étude de la motivation intrinsèque en apprentissage par renforce-
ment (JFPDA 2019).




### Project participants

Name : AUBRET Arthur  
Co-director : MATIGNON Laetitia  
Director : HASSAS Salima  


### Contact

LIRIS  
Building Nautibus  
Université Claude Bernard Lyon 1  
43 Boulevard du 11 Novembre 1918  
69622 Villeurbanne Cedex  
arthur.aubret@univ-lyon1.fr  
