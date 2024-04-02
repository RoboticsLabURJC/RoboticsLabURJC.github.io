---
permalink: /publications/2021/robust_real_time_traffic_surveillance_with_deep_learning
title: "Robust Real-Time Traffic Surveillance with Deep Learning"
subtitle: "Robust Real-Time Traffic Surveillance with Deep Learning"


layout: single

classes: wide
---
<p style="text-align: center; font-weight: bold;">Computational Intelligence and Neuroscience, 2021</p>

<p style="text-align: center"><a href="">Jessica Fernández<sup>1,2</sup></a>, <a href="https://gsyc.urjc.es/jmplaza/">JoseMaria Cañas<sup>1,2</sup></a>, <a href="">Vanessa Fernández<sup>1,2</sup></a>, <a href="https://sergiopaniego.github.io/">Sergio Paniego<sup>1,2</sup></a></p>
<div class="container" style="overflow: hidden;">
    <p style="text-align: center; width: 50%; float: left;">1: <a href="https://www.urjc.es/"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/URJC_logo.svg/1280px-URJC_logo.svg.png" width="40%" height="40%" alt="URJC"/></a></p>
    <p style="text-align: center; width: 50%; float: left;">2: <a href="https://jderobot.github.io/"><img src="https://avatars.githubusercontent.com/u/10959337?s=280&v=4" width="20%" height="20%" alt="JdeRobot"/></a></p>
</div>
<p style="text-align: center">DOI: <a href="https://doi.org/10.1155/2021/4632353">10.1155/2021/4632353</a></p>


## Abstract

Real-time vehicle monitoring in highways, roads, and streets may provide useful data both for infrastructure planning and for traffic management in general. Even though it is a classic research area in computer vision, advances in neural networks for object detection and classification, especially in the last years, made this area even more appealing due to the effectiveness of these methods. This study presents TrafficSensor, a system that employs deep learning techniques for automatic vehicle tracking and classification on highways using a calibrated and fixed camera. A new traffic image dataset was created to train the models, which includes real traffic images in poor lightning or weather conditions and low-resolution images. The proposed system consists mainly of two modules, first one responsible of vehicle detection and classification and a second one for vehicle tracking. For the first module, several neural models were tested and objectively compared, and finally, the YOLOv3 and YOLOv4-based network trained on the new traffic dataset were selected. The second module combines a simple spatial association algorithm with a more sophisticated KLT (Kanade–Lucas–Tomasi) tracker to follow the vehicles on the road. Several experiments have been conducted on challenging traffic videos in order to validate the system with real data. Experimental results show that the proposed system is able to successfully detect, track, and classify vehicles traveling on a highway on real time.

## Videos

<div style="display: flex;justify-content: space-around;margin-bottom: 20px;">
    <div style="width: 45%;">
      <h2>High Quality Video</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/xDzGYq1Kl-8" frameborder="0" allowfullscreen></iframe>
    </div>
    <div style="width: 45%;">
      <h2>Low Quality and Unfavorable Weather Conditions Video</h2>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/SKO2n4zFbnU" frameborder="0" allowfullscreen></iframe>
    </div>
</div>

## Materials

<div class="container" style="overflow: hidden;">
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://www.hindawi.com/journals/cin/2021/4632353/">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper (journal)">
            <p>Paper (journal)</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://downloads.hindawi.com/journals/cin/2021/4632353.pdf?_gl=1*91gypa*_ga*MTk0NDMwNDEyOC4xNzEyMDY3Mzg3*_ga_NF5QFMJT5V*MTcxMjA2NzM4Ni4xLjEuMTcxMjA2NzYyMi42MC4wLjA.&_ga=2.61784492.1842624577.1712067387-1944304128.1712067387">
            <img style="max-width: 30%; height: auto; margin-bottom: 10px;" src="https://cdn-icons-png.flaticon.com/512/3731/3731553.png" alt="Paper (PDF)">
            <p>Paper (PDF)</p>
        </a>
    </div>
    <div style="width: 33%; float: left;margin-bottom: 20px; text-align: center;">
        <a href="https://github.com/JdeRobot/smart-traffic-sensor">
            <img style="max-width: 30%; height: auto;" src="https://static-00.iconduck.com/assets.00/comparison-icon-512x512-vl4u7s2n.png" alt="Open source code">
            <p>Open source code</p>
        </a>
    </div>
</div>

## Citation

``` 
@article{cazorla2021robust,
  title={Robust Real-Time Traffic Surveillance with Deep Learning},
  author={Fernández, Jessica and Cañas, José M. and Fernández, Vanessa and Paniego, Sergio},
  journal={Computational Intelligence and Neuroscience},
  editor={Cazorla, Miguel},
  volume={2021},
  pages={4632353},
  year={2021},
  publisher={Hindawi},
  doi={10.1155/2021/4632353},
  url={https://doi.org/10.1155/2021/4632353},
  ISSN={1687-5265},
  abstract={Real-time vehicle monitoring in highways, roads, and streets may provide useful data both for infrastructure planning and for traffic management in general. Even though it is a classic research area in computer vision, advances in neural networks for object detection and classification, especially in the last years, made this area even more appealing due to the effectiveness of these methods. This study presents TrafficSensor, a system that employs deep learning techniques for automatic vehicle tracking and classification on highways using a calibrated and fixed camera. A new traffic image dataset was created to train the models, which includes real traffic images in poor lightning or weather conditions and low-resolution images. The proposed system consists mainly of two modules, first one responsible of vehicle detection and classification and a second one for vehicle tracking. For the first module, several neural models were tested and objectively compared, and finally, the YOLOv3 and YOLOv4-based network trained on the new traffic dataset were selected. The second module combines a simple spatial association algorithm with a more sophisticated KLT (Kanade–Lucas–Tomasi) tracker to follow the vehicles on the road. Several experiments have been conducted on challenging traffic videos in order to validate the system with real data. Experimental results show that the proposed system is able to successfully detect, track, and classify vehicles traveling on a highway on real time.},
  date={2021-12-27}
}
``` 



