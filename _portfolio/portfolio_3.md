---
title: "Collision-Free Trajectory Planning for a 6-DoF Free Floating Space Robot via Hierachical Decoupling Optimization"
excerpt: "**Recent research in 29th, Apri, 2021.**"
collection: portfolio

---

{% include base_path %}

<iframe height=720 width=1280 src='/images/capture_cut.mp4' allowfullscreen='true'> </iframe>

**Tips**：If you see a small figure in the center of the above screen, click it and then you will see the video.

we developed a hierachical decoupling optimization algorithm to realize 6D-pose multi-target trajectory planning for the free-floating space robot.

Abstract
======
The free-floating space robot plays an improtant role in recycling space junk and reparing satellite . Because of the coupling between the base and robot, there is a dynamic singularity problem in trajectory planning. Many researches focus on parameterizing the trajectory and proposing optimization-based algorithms to control the space robot. However, the previous solutions will be faild when the target to be captured has some movement. So these methods need recalculte a complete trajectory involving new pose of the target. In this paper, we developed a hierachical decoupling optimization algorithm to realize 6D-pose multi-target trajectory planning for the free-floating space robot. In order to reduce the complexity of exploration,  the whole system consists of two layers : the high-level policy completes the collision-free trajectory planning of the end-effector pose; the low-level policy divides the pose reaching problem into two sub-problems (postion and orientation). Thanks to introducing the expert policy and hindlight experice replay, the policies reach the optimal quickly optimized by reinforcement learning. The results illustrate that the proposed alogrithm shows high environmental adaptability and anti-disturbance capacity. Furthermore, our approach generalizes to capture a target satellite under different poses, despite being trained without the gripper. 


