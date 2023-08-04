---
layout: archive
title: " "
permalink: /software/
author_profile: true
---

{% include base_path %}

DSAC (Distributional Soft Actor-Critic)
======
<p style="text-align: justify;">I proposed an RL algorithm, named DSAC, to tackle the overestimation problem encountered by most model-free off-policy RL algorithms. It achieves state-of-the-art (SOTA) performance in most MuJoCo benchmarks, surpassing other model-free RL baselines such as SAC, TD3, PPO. </p>
<li><b>Paper</b>: <b>J. Duan</b>, Y. Guan, S. E. Li, Y. Ren, Q. Sun, and B. Cheng, <a href="https://ieeexplore.ieee.org/abstract/document/9448360">“Distributional Soft Actor-Critic: Off-Policy Reinforcement Learning for Addressing Value Estimation Errors,”</a> IEEE Transactions on Neural Networks and Learning Systems, pp. 1–15, 2021.‌&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://arxiv.org/abs/2001.02811">Download</a></li>
<li><b>Github</b>: <a href="https://github.com/Jingliang-Duan/Distributional-Soft-Actor-Critic-2.0">https://github.com/Jingliang-Duan/Distributional-Soft-Actor-Critic-2.0</a></li>

<br>

GOPS (General Optimal control Problems Solver)
======
<p style="text-align: justify;">I am currently serving as the co-leader in developing GOPS. Solving optimal control problems serves as basic demands of industrial control tasks. Existing methods like model predictive control often suffer from heavy online computational burdens. Reinforcement learning (RL) has shown great promise in computer and board games but has yet to be widely adopted in industrial applications due to lacking accessible and high-accuracy solvers. Therefore, <a href="http://www.idlab-tsinghua.com/">“Intelligent Driving Lab (iDLab)”</a> at Tsinghua University has developed GOPS, an easy-to-use RL solver package that aims to build real-time and high-performance controllers in industrial fields. GOPS is built with a highly modular structure that retains a flexible framework for secondary development. Considering the diversity of industrial control tasks, GOPS also includes a conversion tool that allows for the use of Matlab/Simulink to support environment construction, controller design, and performance validation. To handle large-scale control problems, GOPS can automatically create various serial and parallel trainers by flexibly combining embedded buffers and samplers. It offers a variety of common approximate functions for policy and value functions, including polynomial, multilayer perceptron, convolutional neural network, etc. Additionally, constrained and robust training algorithms for special industrial control systems with state constraints and model uncertainties are also integrated into GOPS.</p>
<li><b>GOPS Open Source Website</b>: <a href="https://gops.readthedocs.io/">https://gops.readthedocs.io/</a></li>
<li><b>Github</b>: <a href="https://github.com/Intelligent-Driving-Laboratory/GOPS">https://github.com/Intelligent-Driving-Laboratory/GOPS</a></li>
<iframe class="image middle" src="benchmark_run2.html" width="100%" height="600px"></iframe>




									



  

