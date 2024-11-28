# A Unified Interaction Control Framework for Safe Robotic Ultrasound Scanning with Human-Intention-Aware Compliance

The paper is submitted to IROS 2024.

The source code will be released after the publication of the paper.

[[arXiv of previous work](https://arxiv.org/abs/2403.12676)]


## Video

<p align="center">
<iframe width="800" height="450" src="https://yanseim.github.io/assets/videos/iros2024_long.mp4" title="iros24 video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen> </iframe>
</p>


## Abstract

The ultrasound scanning robot commonly works in an environment where human-robot interactions frequently arise. Most control methods for ultrasound scanning only consider one specific interaction situation, or use hard switching between different controllers for different situations, which reduces safety and efficiency. In this paper, we propose a unified interaction control framework for ultrasound scanning robots capable of handling all common interactions, distinguishing both human-intended and unintended types, and adapting with
appropriate compliance. Specifically, the robot suspends or modulates its ongoing main task if the interaction is intended, e.g., when the doctor grasps the robot to lead the end effector actively. Furthermore, it can identify unintended interactions and avoid potential collision in the null space beforehand. Even if the collision has happened, it can become compliant with the collision in the null space and try to reduce its impact on the main task (where the scan is ongoing) kinematically and dynamically. The multiple situations are integrated into a unified controller with a smooth transition to deal with the interactions by exhibiting human-intention-aware compliance. Experimental results demonstrate the framework’s ability to cope with all common interactions including intended intervention and unintended collision in a collaborative carotid artery ultrasound scanning task.

## Contact

If you have any question, feel free to contact the authors: Xiangjie Yan, <yanxj20@mails.tsinghua.edu.cn>.

My Homepage is at [yanseim.github.io](https://yanseim.github.io).
