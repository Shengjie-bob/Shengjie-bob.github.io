---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Learning to Control for Capturing the Space Target 
======
<figure class="half">
    <img src="/images/capture1.gif" width="300">
    <img src="/images/capture1.gif" width="300">
</figure>	
* Time : Sept. 2021 - Present
* Developed a hierachical decoupling optimization algorithm to realize 6D-pose multi-target trajectory planning for the free-floating space robot.
* In order to reduce the complexity of exploration, the whole system consists of two layers : the high-level policy completes the collision-free trajectory planning of the end-effector pose; the low-level policy divides the pose reaching problem into two sub-problems (position and orientation). 
* Thanks to introducing the expert policy and hindlight experice replay, the policies reach the optimal quickly optimized by reinforcement learning.
* Our approach generalizes to capture a target satellite under different poses, despite being trained without the gripper.


Development of a Miniature Quadruped Robotic Rat Capable of Multi-Modal Motions
======
<figure class="half">
    <img src="/images/rat1.gif" width="300">
    <img src="/images/rat2.gif" width="300">
  	<img src="/images/rat3.gif" width="300">
  	<img src="/images/rat5.gif" width="300">
</figure>
* Time : Mar. 2018 - Present
* Developed a miniature rat-inspired robot integrated with $12$ actuated DOFs and a size of $202\times55\times75 mm^3$ . The morphology and weight of the robotic rat is the same as a mature rat. The mechanical structure of the robotic rat makes full use of the connecting rod mechanism to transfer the movement. 
* Designed an optimal Central Pattern Generator (CPG) network through Particle Swarm Optimization (PSO) algorithm which guaranteed adjustable frequency and amplitude to determine gait pattern and stride frequency. This method solves how to choose the optimal parameters of the CPG network based on Kimura model.
* Designed a hierarchical multi-modal locomotion controller for a rat-inspired quadruped robot based on optimization with bionic constraints. Consisting of three layers, our method can execute multiple modes including crouch-standing action, walking forward, turning around, crawling and recovery from a fall.
* Compared with the quadruped robots in similar size, the motion performance of our robot has some certain advantages. The maximum speed of the robotic rat reaches 15 cm/s, and the radius of turning is less than 6 cm. Except for them, it can carry loads that are 60% of its weight. 


Multi-Target Trajectory Planning Strategy of a 6-DoF Free-Floating Space Robot
======
<figure class="half">
    <img src="/images/horizon.gif" width="300">
    <img src="/images/vertical.gif" width="300">
</figure>	
* Time : Sept. 2019 - Mar. 2021
* Developed an identification algorithm of the target position and estimated the relative pose between the space robot and target satellite using visual simultaneous localization and mapping (SLAM).
* Designed a robust multi-target capture strategy of a 6-DoF free-floating space robot within a large initial space; Proposed the Action Ensembles based on Poisson distribution (AEP) method to improve the Proximal Policy Optimization (PPO) algorithm, boosting the terminal capture precision under a certain low threshold of error.
* Evaluated our approach on three tasks: grasping objects in the case of different masses of the base satellite, external disturbances at joints, and even single joint failure, without any further fine-tuning.


End-To-End Trajectory Planning for a  6-DoF Free-floating Space Robot 
======
<figure class="half">
    <img src="/images/end2end1.png" width="300">
    <img src="/images/end2end2.png" width="300">
</figure>
* Time : Sept. 2020 - Present
* Designed an end-to-end planning system of perception, planning and control, which is divided into three layers of convolution network and three layers of perceptron network in policy layer, and velocity tracking PD controller in driver layer.
* Implemented a deep reinforcement learning algorithm based on maximum entropy for the learning of parameters in the network, and had better performance comparing with other baseline algorithms.
* Evaluated the kinematic and dynamic characteristics of the trained strategy,and carried out antidisturbance experiments to test its robustness.


A Passively-Stable Four-legged Robot Capable of Leaping Obstacle 
======
* Time : Oct. 2017 – Oct. 2018
* Outstanding course design thesis in Beijing Institute of Technology  
* Designed a special foot structure, which is composed of three semicircular arcs of carbon fiber. 
* Designed an ejection mechanism based on spring energy storage, in which the energy of spring is stored by rack and pinion mechanism.
* Developed a control system using WiFi communication, integrated PID control based on position tracking, and realized the modes including walking, turning and leaping obstacle.
