---
permalink: /publications/2024/enhancing_end_to_end_control_in_autonomous_driving_through_kinematic_infused_and_visual_memory_imitation_learning
title: "Enhancing End-to-End Control in Autonomous Driving through Kinematic-Infused and Visual Memory Imitation Learning"

layout: single

classes: wide
---

<p style="text-align: center; font-weight: bold;">Neurocomputing, 2024</p>

<p style="text-align: center"><a href="https://sergiopaniego.github.io/">Sergio Paniego<sup>1,2</sup></a>, <a href="http://rocapal.org">Roberto Calvo-Palomino<sup>1,2</sup></a>, <a href="https://gsyc.urjc.es/jmplaza/">JoseMaria Cañas<sup>1,2</sup></a></p>
<div class="container" style="overflow: hidden;">
    <p style="text-align: center; width: 50%; float: left;">1: <a href="https://www.urjc.es/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/1280px-URJC_logo.svg.png" width="40%" height="40%" alt="URJC"/></a></p>
    <p style="text-align: center; width: 50%; float: left;">2: <a href="https://jderobot.github.io/"><img src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" width="20%" height="20%" alt="JdeRobot"/></a></p>
</div>
<p style="text-align: center">DOI: <a href="https://doi.org/10.1016/j.neucom.2024.128161">10.1016/j.neucom.2024.128161</a></p>


## Abstract

This paper presents an exploration, study, and comparison of various alternatives to enhance the capabilities of an end-to-end control system for autonomous driving based on imitation learning by adding visual memory and kinematic input data to the deep learning architectures that govern the vehicle. The experimental comparison relies on fundamental error metrics (MAE, MSE) during the offline assessment, supplemented by several external complementary fine-grain metrics based on the behavior of the ego vehicle at several urban test scenarios in the CARLA reference simulator in the online evaluation. Our study focuses on a lane-following application using different urban scenario layouts and visual bird-eye-view input. The memory addition involves architectural modifications and different sensory input types. The kinematic data integration is managed with a modified input. The experiments encompass both typical driving scenarios and extreme never-seen conditions. Additionally, we conduct an ablation study examining various memory lengths and densities. We prove experimentally that incorporating visual memory capabilities and kinematic input data makes the driving system more robust and able to handle a wider range of challenging situations, including those not encountered during training, in terms of reduction of collisions and speed self-regulation, resulting in a 75% enhancement. All the work we present here, including model architectures, trained model weights, comparison tool, and the dataset, is open-source, facilitating replication and extension of our findings.

## Materials

<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://doi.org/10.1016/j.neucom.2024.128161">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper">
            <p>Paper</p>
        </a>
    </div>
    <div style="width: 33%; float: left; margin-bottom: 20px; text-align: center;">
        <a href="https://huggingface.co/datasets/sergiopaniego/CarlaFollowLanePreviousV">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://static.thenounproject.com/png/2200230-200.png" alt="Dataset">
            <p>Dataset</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://github.com/JdeRobot/DeepLearningStudio">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://static.thenounproject.com/png/1448954-200.png" alt="Code">
            <p>Code</p>
        </a>
    </div>
</div>
<div class="container" style="overflow: hidden;">
    <div style="width: 50%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://github.com/JdeRobot/BehaviorMetrics">
            <img style="max-width: 15%; height: auto;" src="https://static-00.iconduck.com/assets.00/comparison-icon-512x512-vl4u7s2n.png" alt="Comparison software tool with simulator">
            <p>Comparison software tool with simulator</p>
        </a>
    </div>
    <div style="width: 50%; float: left; margin-bottom: 20px; text-align: center;">
        <a href="https://huggingface.co/sergiopaniego/MemoryPilotNet">
            <img style="max-width: 15%; height: auto;" src="https://cdn-icons-png.flaticon.com/512/6461/6461819.png" alt="Models' weights">
            <p>Models' weights</p>
        </a>
    </div>
</div>


## Citation

``` 
@article{PANIEGO2024128161,
    title = {Enhancing end-to-end control in autonomous driving through kinematic-infused and visual memory imitation learning},
    journal = {Neurocomputing},
    volume = {600},
    pages = {128161},
    year = {2024},
    issn = {0925-2312},
    doi = {https://doi.org/10.1016/j.neucom.2024.128161},
    url = {https://www.sciencedirect.com/science/article/pii/S0925231224009329},
    author = {Sergio Paniego and Roberto Calvo-Palomino and JoséMaría Cañas},
    keywords = {End-to-end autonomous driving, Imitation learning, Deep learning, Lane-following},
    abstract = {This paper presents an exploration, study, and comparison of various alternatives to enhance the capabilities of an end-to-end control system for autonomous driving based on imitation learning by adding visual memory and kinematic input data to the deep learning architectures that govern the vehicle. The experimental comparison relies on fundamental error metrics (MAE, MSE) during the offline assessment, supplemented by several external complementary fine-grain metrics based on the behavior of the ego vehicle at several urban test scenarios in the CARLA reference simulator in the online evaluation. Our study focuses on a lane-following application using different urban scenario layouts and visual bird-eye-view input. The memory addition involves architectural modifications and different sensory input types. The kinematic data integration is managed with a modified input. The experiments encompass both typical driving scenarios and extreme never-seen conditions. Additionally, we conduct an ablation study examining various memory lengths and densities. We prove experimentally that incorporating visual memory capabilities and kinematic input data makes the driving system more robust and able to handle a wider range of challenging situations, including those not encountered during training, in terms of reduction of collisions and speed self-regulation, resulting in a 75% enhancement. All the work we present here, including model architectures, trained model weights, comparison tool, and the dataset, is open-source, facilitating replication and extension of our findings.}
}
``` 
