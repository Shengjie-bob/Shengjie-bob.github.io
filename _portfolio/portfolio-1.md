---
title: "A Multi-Target Trajectory Planning Strategy of a 6-DoF Free-Floating Space Robot based on Reinforcement Learning"
excerpt: "Video submitted at **IEEE IROS**, 2021"
collection: portfolio

---
{% include base_path %}

<iframe height=720 width=1280 src='/images/spacerobot_v3_cut.mp4' allowfullscreen='true'> </iframe>

**Tips**：If you see a small figure in the center of the above screen, click it and then you will see the video.

Abstract
======
With the development of space technology, space robots have played an important role in detecting and recycling space junk. However, due to the modeling error and the non-holonomic constraint, it is challenging to perform tasks with model-based methods. Model-free reinforcement learning methods are promising in tackling space capture missions. Nevertheless, current research results mostly focus on the single- target environment. In this paper, we proposed a multi-target trajectory planning strategy of a 6-DoF free-floating space robot optimized by the Proximal Policy Optimization (PPO) algorithm. Besides, we adopted some augmentation techniques to improve the PPO algorithm on precision and stability of reaching multiple targets. In particular, we introduced an Action Ensembles Based on Poisson Distribution (AEP) method, which facilitates the policy to efficiently approximate the optimal policy. Our method can be easily extended to realize the end-effector trajectory tracking. We evaluated our approach on four tasks: circle trajectory tracking, external disturbances at joints, different masses of the base, and even single joint failure, without any further fine-tuning. The results suggeest that the planning strategy has comparably high adaptability and anti- inference capacity.

