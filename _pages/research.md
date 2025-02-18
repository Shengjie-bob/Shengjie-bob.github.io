---
layout: archive
title: "Research"
permalink: /research/
author_profile: true

---

{% include base_path %}

Learning to Control for Capturing the Space Target 
======
* **Time : Sept. 2021 - Present**
* **Tsinghua Navigation and Control Lab (as researcher, advisor: prof. Tao Zhang)**
* **Team members: Shengjie Wang, Yuxue Cao, Xiang Zheng**
<details>
<summary>Abstract</summary>
<pre>
* Developed a hierachical decoupling optimization algorithm to realize 6D-pose multi-target trajectory planning for the free-floating space robot.
* In order to reduce the complexity of exploration, the whole system consists of two layers : the high-level policy completes the collision-free trajectory planning of the end-effector pose; the low-level policy divides the pose reaching problem into two sub-problems (position and orientation). 
* Thanks to introducing the expert policy and hindlight experice replay, the policies reach the optimal quickly optimized by reinforcement learning.
* Our approach generalizes to capture a target satellite under different poses, despite being trained without the gripper.
</pre>
</details>
<figure class="half">
    <img src="/images/capture3.gif" width="200">
    <img src="/images/capture4.gif" width="200">
</figure>	




Development of a Miniature Quadruped Robotic Rat Capable of Multi-Modal Motions
======
* **Time : Mar. 2018 - Present**
* **Beijing Advanced Innovation Center for Intelligent Robots and Systems (BAICIRS) (as researcher, advisor: prof. Qing Shi)**
* **Team members: Shengjie Wang, Junhui Gao, Yuxuan Wang, Fansheng Meng, Yi Hao**
<details>
<summary>Abstract</summary>
<pre>
* Developed a miniature rat-inspired robot integrated with $12$ actuated DOFs and a size of $202\times55\times75 mm^3$ . The morphology and weight of the robotic rat is the same as a mature rat. The mechanical structure of the robotic rat makes full use of the connecting rod mechanism to transfer the movement. 
* Designed an optimal Central Pattern Generator (CPG) network through Particle Swarm Optimization (PSO) algorithm which guaranteed adjustable frequency and amplitude to determine gait pattern and stride frequency. This method solves how to choose the optimal parameters of the CPG network based on Kimura model.
* Designed a hierarchical multi-modal locomotion controller for a rat-inspired quadruped robot based on optimization with bionic constraints. Consisting of three layers, our method can execute multiple modes including crouch-standing action, walking forward, turning around, crawling and recovery from a fall.
* Compared with the quadruped robots in similar size, the motion performance of our robot has some certain advantages. The maximum speed of the robotic rat reaches 15 cm/s, and the radius of turning is less than 6 cm. Except for them, it can carry loads that are 60% of its weight. 
</pre>
</details>
<figure class="half">
  	<img src="/images/rat3.gif" width="200">
  	<img src="/images/rat5.gif" width="200">
</figure>



Multi-Target Trajectory Planning Strategy of a 6-DoF Free-Floating Space Robot
======
* **Time : Sept. 2019 - Mar. 2021**
* **Tsinghua Navigation and Control Lab (as researcher, advisor: prof. Tao Zhang)**
* **Team members: Shengjie Wang, Yuxue Cao, Xiang Zheng**
<details>
<summary>Abstract</summary>
<pre>
* Developed an identification algorithm of the target position and estimated the relative pose between the space robot and target satellite using visual simultaneous localization and mapping (SLAM).
* Designed a robust multi-target capture strategy of a 6-DoF free-floating space robot within a large initial space; Proposed the Action Ensembles based on Poisson distribution (AEP) method to improve the Proximal Policy Optimization (PPO) algorithm, boosting the terminal capture precision under a certain low threshold of error.
* Evaluated our approach on three tasks: grasping objects in the case of different masses of the base satellite, external disturbances at joints, and even single joint failure, without any further fine-tuning.
</pre>
</details>
<figure class="half">
    <img src="/images/horizon.gif" width="200">
    <img src="/images/vertical.gif" width="200">
</figure>	

An End-To-End Trajectory Planning for a  6-DoF Free-floating Space Robot 
======
* **Time : Sept. 2020 - Present**
* **Tsinghua Navigation and Control Lab (as researcher, advisor: prof. Tao Zhang)**
* **Team members: Shengjie Wang, Yuxue Cao, Xiang Zheng**
<details>
<summary>Abstract</summary>
<pre>
* Designed an end-to-end planning system of perception, planning and control, which is divided into three layers of convolution network and three layers of perceptron network in policy layer, and velocity tracking PD controller in driver layer.
* Implemented a deep reinforcement learning algorithm based on maximum entropy for the learning of parameters in the network, and had better performance comparing with other baseline algorithms.
* Evaluated the kinematic and dynamic characteristics of the trained strategy and carried out antidisturbance experiments to test its robustness.
</pre>
</details>
<figure class="half">
    <img src="/images/end2end1.png" width="200">
    <img src="/images/end2end2.png" width="200">
</figure>


Development of a Detection and Pose Estimation System for Free-floating Space Robots Based on Deep Learning
======
* **Time : Mar. 2019 – Present**
* **Tsinghua Navigation and Control Lab (as researcher, advisor: prof. Tao Zhang)**
* **Team members: Shaopeng Li, Shengjie Wang, Wenxuan Fan**
<details>
<summary>Abstract</summary>
<pre>
* Proposed a dataset construction system of spatial target perception tasks based on virtual environments, constructs dataset of spatial target feature detection and pose estimation suitable for this research task.
* Designed a method based on the Mask R-CNN to the feature detection of spatial non-cooperative target, which can complete the features’ pixel-level segmentation at the same time of detection.
* Designed a supervised learning method to estimate the pose of target satellite, and a semi-supervised learning method, which uses pose data for supervised learning and the reconstruction error between images to learn the relationship and internal relationship between images, so as to enhance the universality of the algorithm.
</pre>
</details>
<figure class="half">
    <img src="/images/pose.png" width="200">
    <img src="/images/detect.png" width="200">
</figure>

Real-Time Mask Face Detection On the CPU Platform  
======
* **Time : Mar. 2020 – Jun. 2020**
* **Course Project (Teacher: Prof. Changshui Zhang)**
* **Team members: Shengjie Wang**
<details>
<summary>Abstract</summary>
<pre>
* Designed two fast mask face detection methods based on the MobileNetV2-SSD model and the YOLOv3-tiny model.
* Evaluated two methods on accuracy and detecting speed, and studied the effects of network super parameters, data enhancement, optimizer, number of anchor boxes, NMS type and picture size on the performance of the model.
* Considering the robustness of algorithm, we introduced some noises on images to enhance data and achieve the accuracy-robustness balance. 
</pre>
</details>
* [code](https://github.com/Shengjie-bob/Face_Mask_Detection)
<figure class="center">
    <img src="/images/mask_detect.png" width="200">
</figure>


An Effective Rain Prediction Method based on Seq2Seq Model with Attention Mechanism
======
* **Time : Mar. 2020 – Jun. 2020**
* **Course Project (Teacher: Prof. Changshui Zhang)**
* **Team members: Shengjie Wang, Yuguang Dong**
<details>
<summary>Abstract</summary>
<pre>
* Designed a rain prediction method based on Seq2Seq model with attention mechanism 
* Designed other machine learning methods to predict the volume of rain, such as SVR, MLP, LSTM and XGBoost.
* Evaluated our method on the testing dataset and visualized the attention map to illustrate the different importance of various factors.
</pre>
</details>
* [code](https://github.com/Shengjie-bob/Rainfall_Prediction)
<figure class="center">
    <img src="/images/rain_predict.png" width="200">
</figure>

An Intelligent Player in 1v1 Holden Game based on Deep Q-learning
======
* **Time : Oct. 2019 – Mar. 2020**
* **Personal Business**
* **Team members: Shengjie Wang, Tianyu Wang**
<details>
<summary>Abstract</summary>
<pre>
* Developed a platform based on python for 1V1 holdem game.
* Designed an agent based on Double Deep Q-learning to compete another agent based on Monte Carlo method. 
* Testified our method on the environment where the opponent knows the fully observation, and results show the winning percentage of our method is approximately the opponent. 
</pre>
</details>
* [code](https://github.com/Shengjie-bob/Holdem_DQN)


A Passively-Stable Four-legged Robot Capable of Leaping Obstacle 
======
* **Time : Oct. 2017 – Oct. 2018**
* **Beijing Advanced Innovation Center for Intelligent Robots and Systems (BAICIRS) (as researcher, advisor: prof. Qing Shi)**
* **Outstanding course design thesis in Beijing Institute of Technology**
* **Team members: Shengjie Wang, Haoxiang Qi, Cheng Chen**
<details>
<summary>Abstract</summary>
<pre>
* Designed a special foot structure, which is composed of three semicircular arcs of carbon fiber. 
* Designed an ejection mechanism based on spring energy storage, in which the energy of spring is stored by rack and pinion mechanism.
* Developed a control system using WiFi communication, integrated PID control based on position tracking, and realized the modes including walking, turning and leaping obstacle.
</pre>
</details>
<figure class="half">
    <img src="/images/multi_feet.gif" width="200">
    <img src="/images/multi_feet2.gif" width="200">
</figure>	


A Two-wheel Robot with Adjustable Wheelbase Used for Pipeline Detection
======
* **Time : Sept. 2016 – Sept. 2017**
* **Beijing Advanced Innovation Center for Intelligent Robots and Systems (BAICIRS) (as researcher, advisor: prof. Qing Shi)**
* **Outstanding course design thesis in Beijing Institute of Technology**
* **Team members: Shengjie Wang, Zhihong Xia, Daotong Zhang**
<details>
<summary>Abstract</summary>
<pre>
* Designed a two-wheel robot, and implemented a method of changing the wheelbase based on rack and pinion mechanism. 
* Developed a control system based on WiFi communication, integrated the function of remote image transmission, and testified some experiments in narrow pipelines.
</pre>
</details>
<figure class="half">
    <img src="/images/piperobot.gif" width="200">
    <img src="/images/piperobot2.png" width="200">
</figure>	
