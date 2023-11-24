---
permalink: /publications/2023/model_optimization_in_deep_learning_based_robot_control_for_autonomous_driving
title: "Model Optimization in Deep Learning based Robot Control for Autonomous Driving"
subtitle: "Model Optimization in Deep Learning based Robot Control for Autonomous Driving"


layout: single

classes: wide
---
<p style="text-align: center">IEEE Robotics and Automation Letters (RA-L), 2023</p>

<p style="text-align: center">Sergio Paniego<sup>1,3</sup>, Nikhil Paliwal<sup>2,3</sup>, JoseMaria Cañas<sup>1,3</sup></p>
<div class="container" style="overflow: hidden;">
    <p style="text-align: center; width: 33%; float: left;">1: <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/1280px-URJC_logo.svg.png" width="40%" height="40%"/></p>
    <p style="text-align: center; width: 33%; float: left;">2: <img src="https://www.se.cs.uni-saarland.de/projects/BrainsOnCode/images/uds_logo.png" width="40%" height="40%"/></p>
    <p style="text-align: center; width: 33%; float: left;">3: <img src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" width="20%" height="20%"/></p>
</div>
<p style="text-align: center;">This work was partially supported by <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/GSoC-logo-horizontal.svg/2560px-GSoC-logo-horizontal.svg.png" width="30%" height="30%"/> </p>


## Abstract

Deep Learning (DL) has been successfully used in robotics for perception tasks and end-to-end robot control. In the context of autonomous driving, this work explores and compares a variety of alternatives for model optimization to solve the visual lane-follow application in urban scenarios with an imitation learning approach. 
The optimization techniques include quantization, pruning, fine-tuning (retraining), and clustering, covering all the options available at the most common DL frameworks. TensorRT optimization for specific cutting-edge hardware devices has been also explored. 
For the comparison, offline metrics such as mean squared error and inference time are used. In addition, the optimized models have been evaluated in an online fashion using the autonomous driving state-of-the-art simulator CARLA and an assessment tool called Behavior Metrics, which provides holistic quantitative fine-grain data about robot performance. Typically the performance of robot applications depends both on the quality of the control decisions and also on their frequency. The studied optimized models significantly increase inference frequency without losing decision quality. The impact of each optimization alone has also been measured. This speed-up allows us to successfully run DL robot-control applications even in limited computing hardware. All the work presented here is open-source, including models, weights, assessment tool, and dataset, for easy replication and extension.

## Materials

<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Descripción de la imagen 1">
        <p><a href="https://ieeexplore.ieee.org/document/10328061">Paper</a></p>
    </div>
    <div style="width: 33%; float: left; margin-bottom: 20px; text-align: center;">
        <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://static.thenounproject.com/png/2200230-200.png" alt="Descripción de la imagen 1">
        <p><a href="https://huggingface.co/datasets/sergiopaniego/CarlaFollowLanePreviousV">Dataset</a></p>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://static.thenounproject.com/png/1448954-200.png" alt="Descripción de la imagen 1">
        <p><a href="https://github.com/JdeRobot/DeepLearningStudio">Code</a></p>
    </div>
</div>
<div class="container" style="overflow: hidden;">
    <div style="width: 50%; float: left;margin-bottom: 20px; text-align: center;">
        <img style="max-width: 15%; height: auto;" src="https://static-00.iconduck.com/assets.00/comparison-icon-512x512-vl4u7s2n.png" alt="Descripción de la imagen 1">
        <p><a href="https://github.com/JdeRobot/BehaviorMetrics">Paper</a></p>
    </div>
    <div style="width: 50%; float: left; margin-bottom: 20px; text-align: center;">
        <img style="max-width: 15%; height: auto;" src="https://cdn-icons-png.flaticon.com/512/6461/6461819.png" alt="Descripción de la imagen 1">
        <p><a href="https://huggingface.co/sergiopaniego/OptimizedPilotNet">Dataset</a></p>
    </div>
</div>

## Citation

``` 
@article{Paniego2023,
    author={Paniego, Sergio and Paliwal, Nikhil and Cañas, JoséMaría},
    journal={IEEE Robotics and Automation Letters}, 
    title={Model Optimization in Deep Learning based Robot Control for Autonomous Driving}, 
    year={2023},
    volume={},
    number={},
    pages={1-8},
    doi={10.1109/LRA.2023.3336244}
}
``` 



