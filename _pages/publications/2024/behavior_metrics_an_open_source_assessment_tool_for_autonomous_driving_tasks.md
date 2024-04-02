---
permalink: /publications/2024/behavior_metrics_an_open_source_assessment_tool_for_autonomous_driving_tasks
title: "Behavior Metrics: An open-source assessment tool for autonomous driving tasks"


layout: single

classes: wide
---


<p style="text-align: center; font-weight: bold;">Software X, 2024</p>

<p style="text-align: center"><a href="https://sergiopaniego.github.io/">Sergio Paniego<sup>1,2</sup></a>, <a href="http://rocapal.org">Roberto Calvo-Palomino<sup>1,2</sup></a>, <a href="https://gsyc.urjc.es/jmplaza/">JoseMaria Cañas<sup>1,2</sup></a></p>
<div class="container" style="overflow: hidden;">
    <p style="text-align: center; width: 50%; float: left;">1: <a href="https://www.urjc.es/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/1280px-URJC_logo.svg.png" width="40%" height="40%" alt="URJC"/></a></p>
    <p style="text-align: center; width: 50%; float: left;">2: <a href="https://jderobot.github.io/"><img src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" width="20%" height="20%" alt="JdeRobot"/></a></p>
</div>
<p style="text-align: center;">This work was partially supported by <a href="https://summerofcode.withgoogle.com/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/GSoC-logo-horizontal.svg/2560px-GSoC-logo-horizontal.svg.png" width="30%" height="30%" alt="GSoC"/></a></p>
<p style="text-align: center">DOI: <a href="https://doi.org/10.1016/j.softx.2024.101702">10.1016/j.softx.2024.101702</a></p>


## Abstract

The development and validation of autonomous driving solutions require testing broadly in simulation. Addressing this requirement, we present Behavior Metrics (BM) for the quantitative and qualitative assessment and comparison of solutions for the main autonomous driving tasks. This software provides two evaluation pipelines, one with a graphical user interface used for qualitative assessment and the other headless for massive and unattended tests and benchmarks. It generates a series of quantitative metrics complementary to the simulator’s, including fine-grained metrics for each particular driving task (lane following, driving in traffic, route navigation, etc.). It provides a deeper and broader understanding of the solutions’ performance and allows their comparison and improvement. It uses and supports state-of-the-art open software such as the reference CARLA simulator, the ROS robotics middleware, PyTorch, and TensorFlow deep learning frameworks. BehaviorMetrics is available open-source for the community.

## Materials

<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://doi.org/10.1016/j.softx.2024.101702">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper (journal)">
            <p>Paper (journal)</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://www.softxjournal.com/action/showPdf?pii=S2352-7110%2824%2900073-6">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper (PDF)">
            <p>Paper (PDF)</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://github.com/JdeRobot/BehaviorMetrics">
            <img style="max-width: 30%; height: auto;" src="https://static-00.iconduck.com/assets.00/comparison-icon-512x512-vl4u7s2n.png" alt="Open source code">
            <p>Open source code</p>
        </a>
    </div>
</div>

## Citation

``` 
@article{PANIEGO2024101702,
    title = {Behavior metrics: An open-source assessment tool for autonomous driving tasks},
    journal = {SoftwareX},
    volume = {26},
    pages = {101702},
    year = {2024},
    issn = {2352-7110},
    doi = {https://doi.org/10.1016/j.softx.2024.101702},
    url = {https://www.sciencedirect.com/science/article/pii/S2352711024000736},
    author = {Sergio Paniego and Roberto Calvo-Palomino and JoséMaría Cañas},
    keywords = {Evaluation tool, Autonomous driving, Imitation learning},
    abstract = {The development and validation of autonomous driving solutions require testing broadly in simulation. Addressing this requirement, we present Behavior Metrics (BM) for the quantitative and qualitative assessment and comparison of solutions for the main autonomous driving tasks. This software provides two evaluation pipelines, one with a graphical user interface used for qualitative assessment and the other headless for massive and unattended tests and benchmarks. It generates a series of quantitative metrics complementary to the simulator’s, including fine-grained metrics for each particular driving task (lane following, driving in traffic, route navigation, etc.). It provides a deeper and broader understanding of the solutions’ performance and allows their comparison and improvement. It uses and supports state-of-the-art open software such as the reference CARLA simulator, the ROS robotics middleware, PyTorch, and TensorFlow deep learning frameworks. BehaviorMetrics is available open-source for the community.}
}
``` 



