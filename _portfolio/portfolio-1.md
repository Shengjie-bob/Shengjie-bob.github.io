---
title: "A Multi-Target Trajectory Planning Strategy of a 6-DoF Free-Floating Space Robot based on Reinforcement Learning"
excerpt: "Video submitted at IEEE IROS, 2021<br/><iframe src='/images/spacerobot_v3_cut.mp4' scrolling='no' border='0' frameborder='no' framespacing='0' allowfullscreen='true'> </iframe>"
collection: portfolio

---
{% include base_path %}

<iframe src='/images/spacerobot_v3_cut.mp4' scrolling='no' border='0' frameborder='no' framespacing='0' allowfullscreen='true'> 
</iframe>

Main Work
======
* We constructed a multi-layer perceptron network to parameterize our planning strategy, which was optimized by PPO algorithm to realize trajectory planning for multi-target;
* We used some meth- ods to improve the PPO algorithm on precision and stability of reaching multiple targets. In particular, we introduced an Action Ensembles Based on Poisson Distribution (AEP) method, which makes the policy approximate the optimal policy efficiently;
* We conducted a trajectory tracking task in which the end-effctor follows a specific trajectory. Furthermore, we also carried out extensive evaluations under the conditions of external disturbances at joints, different masses of the base satellite, and single joint failure, without any further training. The results suggest that our strategy has the significant adaptability and anti-disturbance capacity.
