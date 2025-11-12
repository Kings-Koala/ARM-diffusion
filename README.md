# ARM - Challenge Project with RL and Diffusion Policy

[![SVG Banners](https://svg-banners.vercel.app/api?type=origin&text1=ARM-diffusion%20🤖&text2=🐨%20Diffusion%20Policy%20Based%20Robot%20Manipulator%20Grasping%20System&width=800&height=200)](https://github.com/Akshay090/svg-banners)

**Alternative Languages**

-🐉 简体中文 ([readme.zh-CN.md](readme.zh-CN.md))


This project aims to accomplish the ARM Challenge by integrating reinforcement learning (RL)–based grasping decision-making with trajectory planning through the Diffusion Policy framework. The “Autonomous Robot Manipulation Challenge” (ARM Challenge) is a competition affiliated with RoboCup, designed to attract young researchers and students to tackle challenging topics in autonomous robotic manipulation. It takes the form of an educational and scientific competition, technically supported by RoboCup, MathWorks, and Universal Robots.

<div align=center>
<image src="https://github.com/catowningengineer-cell/ARM-diffusion/blob/main/images/ARM-challenge.png">
</div>

Participating teams are required to complete a “Recycling Task” in a dynamic environment — using a robotic arm to grasp and manipulate various objects such as bottles, cans, and detergent pouches, and sort them into two separate collection bins according to their categories. Grasping and manipulation are fundamental skills for most robotic applications. The competition provides a fair platform for RoboCup participants and student teams to research and demonstrate perception and control algorithms for manipulation in a simulated environment, and to transfer these algorithms to commercial robotic platforms. In 2025, a new dynamic environment is introduced — where both the positions of objects and obstacles change randomly. This makes it especially important for robotic arms to possess autonomous reasoning capabilities.


ARM - Challenge website：[ARM-Challenge](https://arm.robocup.org/)

## 1. Theoretical Basis
Before getting familiar with this project, we strongly recommend that you review relevant papers and theoretical courses in fields such as reinforcement learning and diffusion models.

### 📊 Related Work：

 - Chi, C. et al. (2025) Diffusion policy: Visuomotor policy learning via action diffusion. *The International journal of robotics research.* [Online] 44 (10–11), 1684–1704. [[paper](https://arxiv.org/pdf/2303.04137)][[code](https://github.com/real-stanford/diffusion_policy.git)]
 - Ze, Y. et al. (2024) *3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations.* [Online] [[paper](https://arxiv.org/pdf/2403.03954)][[code](https://github.com/YanjieZe/3D-Diffusion-Policy.git)]
 - Ren, A. Z. et al. (2024) *Diffusion Policy Policy Optimization.* [Online] [[paper](https://arxiv.org/pdf/2409.00588)][[code](https://github.com/irom-princeton/dppo)]
