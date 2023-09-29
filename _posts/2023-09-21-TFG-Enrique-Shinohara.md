---
title: "TFM: Autonomous driving in traffic using end-to-end deep learning"
categories:
  - TFM
tags:
  - tfm
  - IA
  - autonomous driving
  - tutor:sergiopaniego 
  - tutor:jmplaza
---


Enrique Shinohara  has successfully presented her final master's project named **"Conducción autónoma en tráfico usando aprendizaje profundo extremo a extremo"**.


| Information and Resources  | |
| :--- |
| Work |  [PDF](https://github.com/RoboticsLabURJC/2022-tfm-enrique-shinohara/blob/main/final/TFM_final.pdf)| 
| Slides | [PDF](https://github.com/RoboticsLabURJC/2022-tfm-enrique-shinohara/blob/main/final/TFM_presentacion_FINAL_v5.0.pptx) |
| Git Repository | [Link](https://github.com/RoboticsLabURJC/2022-tfm-enrique-shinohara)|
| Tutor | JoseMaria Cañas Plaza and Sergio Paniego |


<div style="text-align: justify"> 


In this project an end-to-end vision-based deep learning approach for an autonomous car
to drive in traffic is presented. In this context the car should both keep the lane and also
keep a safety distance with the front vehicle, if any. The imitation learning approach has
been followed, creating a supervised dataset with the autopilot of CARLA simulator in
different traffic conditions which include front vehicles. A variant of the PilotNet model
has been developed, with additional dropout and the previous speed as input, and it has
been (re)trained with such in-traffic dataset. The experimental results show that the model
successfully drives the car in traffic conditions without losing performance in free road
conditions. It also keeps safety distance with the front cars and even properly generalizes
to several types of front vehicles.

<br>
<br>

A plugin for measuring the distance to the front vehicle has been created and added to
Behavior Metrics, an open-source autonomous driving assessment tool.

</div>
<br>
<br>

**Video:**
<br>

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/mVSfxQeWwrQ/0.jpg)](https://www.youtube.com/watch?v=mVSfxQeWwrQ)

