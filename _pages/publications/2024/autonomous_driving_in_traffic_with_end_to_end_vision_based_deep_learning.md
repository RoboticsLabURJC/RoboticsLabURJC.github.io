---
permalink: /publications/2024/autonomous_driving_in_traffic_with_end_to_end_vision_based_deep_learning
title: "Autonomous Driving in Traffic with End-to-End Vision-based Deep Learning"


layout: single

classes: wide
---

<p style="text-align: center; font-weight: bold;">Neurocomputing, 2024</p>

<p style="text-align: center"><a href="https://sergiopaniego.github.io/">Sergio Paniego<sup>1,2</sup></a>, <a href="">Enrique Shinohara<sup>1,2</sup></a>, <a href="https://gsyc.urjc.es/jmplaza/">JoseMaria Cañas<sup>1,2</sup></a></p>
<div class="container" style="overflow: hidden;">
    <p style="text-align: center; width: 50%; float: left;">1: <a href="https://www.urjc.es/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/1280px-URJC_logo.svg.png" width="40%" height="40%" alt="URJC"/></a></p>
    <p style="text-align: center; width: 50%; float: left;">2: <a href="https://jderobot.github.io/"><img src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" width="20%" height="20%" alt="JdeRobot"/></a></p>
</div>
<p style="text-align: center">DOI: <a href=""></a></p>


## Abstract

This paper presents a shallow end-to-end vision-based deep learning approach for autonomous vehicle driving in traffic scenarios. The primary objectives include lane keeping and maintaining a safe distance from preceding vehicles. This study leverages an imitation learning approach, creating a supervised dataset for robot control from expert agent demonstrations using the state-of-the-art Carla simulator in different traffic conditions. This dataset encompasses three different versions complementary to each other and we have made it publicly available along with the rest of the materials. The PilotNet neural model is utilized in two variants: the first one with complementary outputs for brake and throttle control commands along with dropout; the second one incorporates these improvements and adds the vehicle speed. Both models have been trained with the aforementioned dataset. The experimental results demonstrate that the models, despite their simplicity and shallow architecture, including only small-scale changes, successfully drive in traffic conditions without sacrificing performance in free-road environments, broadening their area of application widely. Additionally, the second model adeptly maintains a safe distance from leading cars and exhibits satisfactory generalization capabilities to diverse vehicle types. A new evaluation metric to measure the distance to the front vehicle has been created and added to Behavior Metrics; an open-source autonomous driving assessment tool built on CARLA that performs experimental validations of autonomous driving solutions.

## Videos

<div style="display: flex;justify-content: space-around;margin-bottom: 20px;">
    <div style="width: 45%;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/mVSfxQeWwrQ" frameborder="0" allowfullscreen></iframe>
    </div>
    <div style="width: 45%;">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/TxYeBWp0XN8" frameborder="0" allowfullscreen></iframe>
    </div>
</div>


## Materials



<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper">
            <p>Paper</p>
        </a>
    </div>
    <div style="width: 33%; float: left; margin-bottom: 20px; text-align: center;">
        <a href="https://huggingface.co/datasets/YujiroS/traffic-6">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://static.thenounproject.com/png/2200230-200.png" alt="Dataset">
            <p>Dataset</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://github.com/RoboticsLabURJC/2022-tfm-enrique-shinohara">
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
        <a href="https://huggingface.co/YujiroS/subjective_vision_pilotnet">
            <img style="max-width: 15%; height: auto;" src="https://cdn-icons-png.flaticon.com/512/6461/6461819.png" alt="Models' weights">
            <p>Models' weights</p>
        </a>
    </div>
</div>


## Citation

``` 
@article{Paniego20242,
    title = {Autonomous Driving in Traffic with End-to-End Vision-based Deep Learning},
    journal = {Neurocomputing},
    author = {Sergio Paniego and Enrique Shinohara and JoséMaría Cañas},
    abstract = {This paper presents a shallow end-to-end vision-based deep learning approach for autonomous vehicle driving in traffic scenarios. The primary objectives include lane keeping and maintaining a safe distance from preceding vehicles. This study leverages an imitation learning approach, creating a supervised dataset for robot control from expert agent demonstrations using the state-of-the-art Carla simulator in different traffic conditions. This dataset encompasses three different versions complementary to each other and we have made it publicly available along with the rest of the materials. The PilotNet neural model is utilized in two variants: the first one with complementary outputs for brake and throttle control commands along with dropout; the second one incorporates these improvements and adds the vehicle speed. Both models have been trained with the aforementioned dataset. The experimental results demonstrate that the models, despite their simplicity and shallow architecture, including only small-scale changes, successfully drive in traffic conditions without sacrificing performance in free-road environments, broadening their area of application widely. Additionally, the second model adeptly maintains a safe distance from leading cars and exhibits satisfactory generalization capabilities to diverse vehicle types. A new evaluation metric to measure the distance to the front vehicle has been created and added to Behavior Metrics; an open-source autonomous driving assessment tool built on CARLA that performs experimental validations of autonomous driving solutions.}
}
``` 



