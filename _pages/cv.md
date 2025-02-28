---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

The page shows the information about me. The pdf version is also available. You can find it [here](https://michael112233.github.io/files/michael_cv.pdf).

Education
======
* B.S. in Sun Yat-sen University, Software Engineering, *2025*(expected)
  * Average Score: 91.11/100;   GPA: 4.0/4.0; 
  
Area of Interests
======
* Distributed System 
  * protocol design and blockchain system
* Machine Learning
  * optimization theory, distributed learning, federated learning

Skills
======
* Programming
  * C++/C
  * Golang (Familiar with constructing blockchain system using Golang.)
  * Python (Familiar with the common AI package like PyTorch and TensorFlow.)
* Language
  * Chinese: Mother Tongue
  * English: Fluent
    * IELTS (Overall: 7.0)
      * **Listening**: 7.0; **Reading**: 7.5; **Writing**: 6.5; **Speaking**: 6.0
    
  
Research Experiences
======
* **Historical Information Assisted Zeroth-order Federated Optimization** *Feb 2024 - Sept 2024*
  * Gaussian smoothing is a significant optimization algorithm which can evaluate the gradients in zeroth-order settings. However, standard gaussian smoothing computes the finite differences along isotropic sampling direction, suffering from high estimation errors. 
  * We propose a **zeroth-order federated optimization assisted by historical trajectories**. When clients train the model, they can **sample the direction subspaces from a non-isotropic covariance matrix** including the historical trajectories information. Therefore, the algorithm can perform well due to mastering the objective landscape.
  * In this work, I proposed the algorithm, designed the comparison experiments to prove the effectiveness of our algorithm and wrote the paper.
  * [Click here for the code of the algorithm](https://github.com/Michael112233/Federated-Learning-ZO)
  * [Click here for the paper of the work](https://arxiv.org/abs/2409.15955)

* **A Blockchain Layer-2 Framework Ensuring Secure Sharding** *May 2024 - Sept 2024*
  * We propose a **two-layer blockchain system**, LessChain, which **decouples the functions of consensus and state storage** into different categories of shards. The consensus shards are responsible for transaction execution and validation. The storage shards handle the storage of ledgers' states. This system **supports reconfiguration of the nodes** in all the shards, so that the system can be robust to counter physical attacks.
  * In this work, I designed comparison experiments to test the performance of our system and compared our system with another existing two-layer sharding scheme like Ethereum 2.0.

* **A High-Throughput Cross-chain Scheme Based on Multi-committee** *Jan 2024 - Present*
  * We propose a secure cross-chain scheme through multi-committee with a high throughout
  * In this work, I investigated the existing cross-chain schemes, clarified these schemes, summarised the similarities of each categories, designed four comparison experiments to compare the performance of ours with the performance of these schemes and implemented our scheme and tested the performance of our scheme.
  * The paper is still in preparation.

Other Experiences
======
* Teaching Assistant(CSE312, CSE314) *Feb 2024 - Jul 2024*
  * The teaching assistant for the course on **Principles of Compilers** and **Compilers Construction Laboratory** at the School of Cyber Science and Technology, Sun Yat-sen University.
  * My responsibility is to check students' homework and assist students' to accomplish the experiments, which trains my communication skills and the ability to express my thoughts clearly.
* Reviewer of IEEE Internet of Things Journal.
  
Scholarship
======
* Excellent Student Scholarship in Sun Yat-sen University, *2022 / 2023 / 2024*

Awards
======
* Sun Yat-sen Program Designing Competition, **Second Prize**, *2022.10*
  * As the leader of our team, I organized my team well when faced with more than 12 problems with only one computer to program in the competition. Therefore, we solved as many problems as we could and won the Second Prize.
* the 1st International Meta Computing Contest, **Third Prize**, *2024.06*
  * held by IEEE International Conference on Meta Computing (ICMC) in Qingdao, China.
  * Our team introduced BlockEmulator, a tool used to simulate the blockchain system.
  * As one of the developers, I introduced the tool to the committee on behalf of our research group.

Publications
======
* <u>Chenlin Wu</u>, Xiaoyu He*, Zike Li, Zibin Zheng, "A Historical Trajectory Assisted Optimization Method for Zeroth-Order Federated Learning" (under review, Applied Soft Computing, JCR Q1)
* Huawei Huang, Miaoyong Xu, <u>Chenlin Wu</u>, Lu Zhou, Zibin Zheng*, "LessChain: A Secure Sharding Blockchain by Decoupling Consensus and Storage" (under review, Financial Cryptography and Data Security 2025, CCF-C)