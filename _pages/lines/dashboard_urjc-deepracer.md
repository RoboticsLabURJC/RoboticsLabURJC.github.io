---
permalink: /lines/urjc-deepracer
title: ""
subtitle: "URJC-DeepRacer: Sim2Real platform "


layout: single

classes: wide
---

<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">        
        <a href="http://www.urjc.es">
            <img style="max-width: 60%; height: auto; margin-bottom: 10px;" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/2560px-URJC_logo.svg.png" alt="">                    
        </a>
    </div>
    <div style="width: 33%; float: left; margin-bottom: 20px; text-align: center;">      
        <a href="https://roboticslaburjc.github.io/">
        <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://pbs.twimg.com/profile_images/1709157413134188544/MHuOqgeK_400x400.jpg" alt="">        
        </a>
    </div>
    <div style="width: 33%; float: left; margin-bottom: 20px; text-align: center;">      
        <a href="https://jderobot.github.io/">
        <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" alt="">        
        </a>
    </div>
</div>



<p style="text-align: center; font-weight: bold; font-size: 20px"><font size="15">URJC DeepRacer</font></p>

## Summary

<div style="display: flex; align-items: center; gap: 20px; flex-wrap: wrap;">

  <div style="flex: 55%; min-width: 300px;">
    <p align="justify">
      URJC-deepracer is an advanced sim2real platform designed to bridge the gap between virtual training environments and physical autonomous driving deployment. Built upon the high-fidelity physics of the CARLA simulator and the AWS DeepRacer, this ecosystem provides a seamless pipeline for developing and testing reinforcement learning models. By leveraging CARLA’s realistic environmental rendering and AWS DeepRacer’s competitive racing logic, the platform allows researchers to refine complex driving behaviors in simulation before transferring them to a physical vehicle, ensuring higher reliability and performance in real-world scenarios.
    </p>
    <p align="justify">
     To enhance its physical capabilities, the hardware platform has been upgraded with a Raspberry Pi processing unit and a Google Coral accelerator, enabling high-speed edge AI inference with minimal latency. This hardware integration allows the vehicle to process deep learning models locally and efficiently. Furthermore, URJC-deepracer introduces a hybrid control scheme that includes the ability to operate the car manually using a standard RC remote control. This feature is essential for manual data collection, safety interventions, and fine-tuning control algorithms, making it a versatile and robust tool for both academic research and competitive autonomous racing.
    </p>
  </div>

  <div style="flex: 40%; text-align: center;">
    <img src="/assets/images/lines/uws/aws_vs_urjc.png" alt="URJC DeepRacer" style="width: 100%; height: auto; border-radius: 8px;">
  </div>

</div>

## Semi-structured, OffRoad and Racing environments


The URJC-deepracer platform demonstrates exceptional versatility by operating across a wide range of environments, a capability made possible through the development of customized worlds within the CARLA simulator. By leveraging these tailored virtual environments, the sim2real pipeline can accurately recreate semi-structured scenarios, such as complex road networks and adverse weather conditions, allowing for high-stakes training without physical risk. This flexibility extends to off-road terrains, where the system’s robust hardware and inference capabilities are tested against the unpredictability of natural dirt paths and gravel. Finally, the platform excels in racing contexts, utilizing controlled laboratory settings to bridge the gap between simulation and reality, ensuring that reinforcement learning models achieve maximum precision and speed in competitive autonomous driving.

<div style="display: flex; justify-content: space-between; gap: 15px; flex-wrap: wrap; margin-top: 20px;">

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/assets/images/lines/uws/semi-structured.jpg" alt="Semi-structured" 
         style="width: 100%; height: 400px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9em; color: #666; margin-top: 8px;">Semi-structured</p>
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/assets/images/lines/uws/offroad.png" alt="Off-road" 
         style="width: 100%; height: 400px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9em; color: #666; margin-top: 8px;">Off-road</p>
  </div>

  <div style="flex: 1; min-width: 300px; text-align: center;">
    <img src="/assets/images/lines/uws/racing.png" alt="Racing" 
         style="width: 100%; height: 400px; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
    <p style="font-size: 0.9em; color: #666; margin-top: 8px;">Racing</p>
  </div>

</div>

## Videos

<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <div style="width: 70%; text-align: center; padding: 10px;">    
      <h2>URJC DeepRacer: Simulation and Real environments</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/xh-FRzT9Ohg?si=9GKtXVo0QiCVHR7X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>  
  </div>

</div>


<div style="display: flex; justify-content: space-around; align-items: flex-start;">
  <div style="width: 70%; text-align: center; padding: 10px;">    
      <h2>URJC DeepRacer controlled by RC (Radio Control) transmitter.</h2>
<iframe width="560" height="315" src="https://www.youtube.com/embed/LwTNduZmzoM?si=02TEy5SkxYn2hgma" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

</div>



