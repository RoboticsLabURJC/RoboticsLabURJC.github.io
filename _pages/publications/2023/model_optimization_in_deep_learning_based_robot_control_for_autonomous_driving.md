---
permalink: /publications/2023/model_optimization_in_deep_learning_based_robot_control_for_autonomous_driving
title: "Model Optimization in Deep Learning based Robot Control for Autonomous Driving"


layout: single

classes: wide
---


<p style="text-align: center">Sergio Paniego<sup>1</sup>, Nikhil Paliwal<sup>2</sup>, JoseMaria Cañas<sup>1</sup></p>
<p style="text-align: center">[1]: Universidad Rey Juan Carlos, Spain</p>
<p style="text-align: center">[2]: Saarland University, Germany</p>



## Abstract

Deep Learning (DL) has been successfully used in robotics for perception tasks and end-to-end robot control. In the context of autonomous driving, this work explores and compares a variety of alternatives for model optimization to solve the visual lane-follow application in urban scenarios with an imitation learning approach. 
The optimization techniques include quantization, pruning, fine-tuning (retraining), and clustering, covering all the options available at the most common DL frameworks. TensorRT optimization for specific cutting-edge hardware devices has been also explored. 
For the comparison, offline metrics such as mean squared error and inference time are used. In addition, the optimized models have been evaluated in an online fashion using the autonomous driving state-of-the-art simulator CARLA and an assessment tool called Behavior Metrics, which provides holistic quantitative fine-grain data about robot performance. Typically the performance of robot applications depends both on the quality of the control decisions and also on their frequency. The studied optimized models significantly increase inference frequency without losing decision quality. The impact of each optimization alone has also been measured. This speed-up allows us to successfully run DL robot-control applications even in limited computing hardware. All the work presented here is open-source, including models, weights, assessment tool, and dataset, for easy replication and extension.

## Materials

- <img src="https://static.thenounproject.com/png/2200230-200.png" width="5%" height="5%"/> Dataset: [https://huggingface.co/datasets/sergiopaniego/CarlaFollowLanePreviousV](https://huggingface.co/datasets/sergiopaniego/CarlaFollowLanePreviousV)
- <img src="https://static.thenounproject.com/png/1448954-200.png" width="5%" height="5%"/> Code (model architecture and training scripts):[https://github.com/JdeRobot/DeepLearningStudio](https://github.com/JdeRobot/DeepLearningStudio)
- <img src="https://static-00.iconduck.com/assets.00/comparison-icon-512x512-vl4u7s2n.png" width="5%" height="5%"/> Comparison software tool with simulator: [https://github.com/JdeRobot/BehaviorMetrics](https://github.com/JdeRobot/BehaviorMetrics)
- <img src="https://cdn-icons-png.flaticon.com/512/6461/6461819.png" width="5%" height="5%"/> Models' weights: [https://huggingface.co/sergiopaniego/OptimizedPilotNet](https://huggingface.co/sergiopaniego/OptimizedPilotNet)





