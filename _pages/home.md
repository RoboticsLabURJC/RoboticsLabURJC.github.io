---
layout: splash
permalink: /
header:
  overlay_color: "#aaaaaa"
  overlay_image: /assets/images/cover/peloto_texto_urjc.png
  #actions:
  #  - label: "<i class='fas fa-github'></i> GitHub"
  #    url: "https://github.com/JdeRobot"
  #  - label: "<i class='fas fa-github'></i> Twitter"
excerpt: 
  Grupo de Robótica en la URJC desde el año 2000
feature_row:
  - image_path: /assets/images/cover/community.jpg
    alt: "People"
    title: "People"
    excerpt: "Members, students..."
    url: "/people/members"
    btn_class: "btn--primary"
    btn_label: "Learn more"

  - image_path: /assets/images/cover/activities.jpg
    alt: "Publications"
    title: "Publications"
    excerpt: "Journal papers, conference papers, book chapters...."
    url: "/activities/"
    btn_class: "btn--primary"
    btn_label: "Learn more"   

  - image_path: /assets/images/cover/projects.png
    alt: "Projects"
    title: "Projects"
    excerpt: "Competitive projects, industry projects..."
    url: "/projects/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

youTube_id: ID7qaEcIu4k

---


<figure class="third" style="text-align: center">
    <a href="https://github.com/RoboticsLabURJC" target="_blank"><img src="/assets/images/cover/github_social_button.png" style="width:200px;"></a>
    <a href="https://twitter.com/roboticslaburjc" target="_blank"><img src="/assets/images/cover/twitter_social_button.png" style="width:200px;"></a>
    <a href="https://www.youtube.com/channel/UCgmUgpircYAv_QhLQziHJOQ/videos" target="_blank"><img src="/assets/images/cover/youtube_social_button.png" style="width:200px;"></a>
</figure>

{% include feature_row %}

Robotics applications are typically distributed, made up of a collection of concurrent asynchronous components which communicate using some middleware (ROS messages, ICE, DDS...). Building robotics applications is a complex task. Integrating existing nodes or libraries, which provide already solved functionality, and using several tools may increase the software robustness and shorten the development time. JdeRobot toolkit provides several tools, libraries and reusable nodes for Robotics and Computer Vision.

| Main Features |
| :--- |
| ROS friendly (full compatible with ROS-Kinetic) |
| C++, Python, JavaScript |
| Open Source |
| Easy installation from debian, PIP and npm packages |


Our (international) community mainly works on five fields inside Robotics and Computer Vision:

<style type="text/css">
.mytable{text-align: center}
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{font-family:Arial, sans-serif;font-size:14px;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg th{font-family:Arial, sans-serif;font-size:14px;font-weight:normal;padding:10px 5px;border-style:solid;border-width:1px;overflow:hidden;word-break:normal;border-color:black;}
.tg .tg-lboi{border-color:inherit;text-align:left;vertical-align:middle;}
.tg .tg-kmbl{font-weight:bold;background-color:#c0c0c0;color:#000000;border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top;}
</style>

<div class="mytable">
<table class="tg">
  <tr>
    <th class="tg-kmbl"><a href="http://jderobot.org/Projects#Robot_Programming_Tools">Development Areas</a></th>
    <th class="tg-kmbl"><a href="http://jderobot.org/Projects#Robot_Programming_Tools">Products</a></th>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="2"><a href="https://jderobot.github.io/projects/robotics_education">Robotics Education and Games</a></td>
    <td class="tg-0pky"><a href="https://jderobot.github.io/RoboticsAcademy/">Robotics-Academy</a> for engineering students</td>
  </tr>
  <tr>
    <td class="tg-0pky">Kibotics online platform for children learning robotics</td>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="3"><a href="https://jderobot.github.io/projects/deep_learning">MachineLearning</a> in Robotics</td>
    <td class="tg-0pky"><a href="https://jderobot.github.io/DetectionStudio">DetectionStudio </a>tool for evaluation of visual detection networks</td>
  </tr>
     <tr>
    <td class="tg-0pky"><a href="https://jderobot.github.io/BehaviorStudio">BehaviorStudio </a>tool for evaluation of control networks</td>
   </tr>
  <tr>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/ObjectDetector">ObjectDetector </a>see deep learning networks in action</td>
  </tr>
   <tr>
    <td class="tg-lboi" rowspan="3"><a href="https://jderobot.github.io/projects/robots_programming_tools">Robot Programming Tools</a></td>
    <td class="tg-0pky"><a href="https://jderobot.github.io/VisualCircuit/">VisualCircuit</a> visual robot programming using connected blocks and wires</td>
  </tr>
  <tr>
    <td class="tg-lboi"><a href="https://jderobot.github.io/VisualStates">VisualStates</a> tool for robot programming with automata</td>
  </tr>
  <tr>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/WebSim2D">WebSim2D </a>robot simulator with web technologies</td>
  </tr>
  <tr>
    <td class="tg-lboi" rowspan="2">FPGAs in Robotics</td>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/neuralFPGA">neuralFPGA </a>running deeplearning networks on FPGAs</td>
  </tr>
  <tr>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/FPGA-robotics">FPGA-robotics </a>designing robot intelligence with IceStudio blocks</td>
  </tr>
 
  <tr>
    <td class="tg-lboi" rowspan="2"><a href="https://jderobot.github.io/projects/visual_slam/visual_slam">SLAM</a>, visual localization</td>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/SDslam">SDslam </a>visual SLAM algorithm</td>
  </tr>
  <tr>
    <td class="tg-0pky"><a href="https://github.com/JdeRobot/slam-TestBed">slam-testbed </a>tool for evaluation of SLAM algorithms<br></td>
  </tr>
  </table>

</div>

We are registered as **non-profit organization** in Spain Ref.#615800.

## News

* (2021/02/15) JdeRobot-base and JdeRobot-assets are now deprecated. Our toolkit is now fully ROS-based!.
* (2021/02/01) [*RoboticsAcademy 2.3.2*](https://jderobot.github.io/RoboticsAcademy) released. It includes four web based exercises, solve them from your browser :-)
* (2020/12/22) [*VisualCircuit*](https://jderobot.github.io/VisualCircuit/) tool has born, it is ready to use. Program your robot application using blocks and wires, as in electronic circuits.
* *JdeRobot has been accepted as a mentoring organization for Google Summer of Code 2020*, several students will be funded by Google to work in open projects of our organizaton. Check the [proposed ideas list](https://jderobot.github.io/activities/gsoc/2020) and our candidate selection process.
<!-- * The last stable release, JdeRobot-5.7.0, has been released as debian package (2020/02/14): full compatible with ROS Melodic. -->
<!-- * All our web pages are finally being migrated to GitHub Pages: nice, under version control and convenient. -->
<!-- * JdeRobot was accepted as a mentoring organization for Google Summer of Code 2019, several students will be funded by Google to work in open projects of our organizaton. Check the [proposed ideas list](https://jderobot.github.io/activities/gsoc/2019) and our candidate selection process. --> 
<!--  * The last stable release, [JdeRobot/base 5.6.7](https://github.com/JdeRobot/base/wiki/JdeRobot-5.6.7) has been released (2019/03/12): full compatible with ROS Kinetic. -->
<!-- * 3rd edition of [Program-A-Robot Challenge](https://jderobot.github.io/activities/competitions/2018) was celebrated inside the [International Conference on Intelligent Robots and Systems (IROS 2018)](https://www.iros2018.org/competitions) (2018/10/03). Watch the [summary video](https://www.youtube.com/watch?v=VFBL6zuXqgo): a drone (cat) searches and pursues a moving target (mouse). -->

<div align="center">
<a class="twitter-timeline" data-lang="es" data-width="800" data-height="700" href="https://twitter.com/RoboticsLabURJC?ref_src=twsrc%5Etfw">Tweets by RoboticsLabURJC</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</div>


<figure class="half">
    <a href="/assets/images/cover/projects.png"><iframe src="https://www.youtube.com/embed/gDP9nWCL0Vg"></iframe></a>
    <a href="/assets/images/cover/activities.jpg"><iframe src="https://www.youtube.com/embed/1iYlJLJkESU"></iframe></a>
<!--    <figcaption>Last two videos from YouTube channel.</figcaption> -->
</figure>


<figure class="third">
    <a href="https://urjc.es" target="_blank"><img src="/assets/images/cover/logoURJC.jpg" style="width:400px;"></a>
    <a href="https://www.urjc.es/universidad/facultades/escuela-tecnica-superior-de-ingenieria-de-las-telecomunicaciones/content/89-etsit-escuela-tecnica-superior-de-ingenieria-de-telecomunicacion" target="_blank"><img src="/assets/images/cover/etsit-urjc.jpg" style="width:200px;"></a>
</figure>
