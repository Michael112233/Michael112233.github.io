---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

The page shows the brief information about me. Details can be checked [here](https://michael112233.github.io/files/michael_cv.pdf)

Education
======
* B.S. in Sun Yat-sen University, Software Engineering, 2025(expected)
  * Current GPA: 91/100
  
Skills
======
* Programming
  * C++/C
  * Golang(familiar with achieving blockchain using golang)
  * Python(familiar with the common AI package like pytorch and tensorflow)
* Language
  * Chinese: Mother Tongue
  * English: Fluent
    * IELTS (Overall: 7.0)
      * **Listening**: 7.0; **Reading**: 7.5; **Writing**: 6.5; **Speaking**: 6.0
    
  
Research Experience
======
* **Historical Information Assisted Zeroth-order Federated Optimization** 
  * Gaussian smoothing is a significant optimization algorithm which can evaluate the gradients in zeroth-order settings. However, standard gaussian smoothing computes the finite differences along isotropic sampling direction, suffering from high estimation errors. 
  * We propose a zeroth-order federated optimization assisted by historical trajectories. When the clients train the model, they can sample the direction subspaces from a non-isotropic covariance matrix including the historical trajectories information. Therefore, the algorithm can perform well due to mastering the objective landscape.
  * In this work, I am responsible for proposing the algorithm, designing the comparison experiments and writing the paper.
  * [Click here for the code of the algorithm](https://github.com/Michael112233/Federated-Learning-ZO)
  * [Click here for the paper of the work](https://michael112233.github.io/publications/Historical_trajectory_assisted_zeroth_order_federated_optimization_2024_IoT_J__ 01.pdf)

* **A Blockchain Layer 2 Framework Ensuring Secure Sharding** May 2024 - Aug 2024
  * Sharding is a promising technique in blockchain, while how to guarantee the security in shards is a serious problem.
  * We propose a two-layer system LessChain, which decouples the functions of consensus and storage into different categories of shards. The consensus shards are responsible for transaction execution and validation. The storage shards handle the storage of ledgers' states. This system can reconfig the nodes in all the shards, so that the system can be robust to counter physical attacks.
  * In this work, I am responsible for designing comparison experiments to test the performance of our system and compare our system with other existing two-layer sharding schemes.

Other Experience
======
* Teaching Assistant(CSE312, CSE314) Feb 2024 - Jul 2024
  * The teaching assistant for the course on **Principles of Compilers** and **Compilers Construction Laboratory** at the School of Cyber Science and Technology, Sun Yat-sen University.
  * my duty is to check students' homework and assist students' to accomplish the experiments, which trains my communication skills and the ability to express my thoughts clearly.
  
Area of Interests
======
* Distributed System 
* Distributed Learning
* Machine Learning
  
Scholarship
======
* Excellent Student Scholarship in Sun Yat-sen University, 2022-2024

Paper
======
* Chenlin Wu, Xiaoyu He*, Zike Li, Zibin Zheng, "A Historical Trajectory Assisted Optimization Method for Zeroth-Order Federated Learning" (Under review, IEEE IoT Journal, CCF-C)
* Huawei Huang, Miaoyong Xu, Chenlin Wu, Lu Zhou, Zibin Zheng*, "LessChain: A Secure Sharding Blockchain by Decoupling Consensus and Storage" (Under review)