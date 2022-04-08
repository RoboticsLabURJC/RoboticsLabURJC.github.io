---
permalink: /people/students
title: "STUDENTS"

youtubeId1: xg40zN9tJqw

sidebar:
  nav: "docs"
  
toc: true
toc_label: "Students"
toc_icon: "cog"

projects:


---



&nbsp;
## Oferta de TFG y TFM para alumnos de URJC

Los interesados podéis contactar con el mentor correspondiente para ampliar información, enviar vuestro CV y listado de notas.

### 1.- Realidad virtual en web y distribuida con [Networked-Aframe](https://github.com/networked-aframe)

En los últimos años la tecnología realidad virtual (VR) está aportando aplicaciones inmersivas útiles en entretenimiento (como videojuegos), en entrenamiento de profesionales (médicos, militares, pilotos) e incluso en educación. FaceBook también está apostando fuerte con escenarios virtuales en su metaverso. Además de emplearse con gafas de realidad virtual (Oculus Rift, HTC Vivo o Valve Index), también está madurando la tecnología para usarlo en navegadores web. En esa dirección [AFrame](https://aframe.io/) se está extendiendo como estandard de facto para combinar web con gafas de realidad virtual.

En el grupo ya tenemos experiencia manejando AFrame con varios TFGs, por ejemplo programando un simulador robótico con ello (Álvaro, David, [Natalia](https://gsyc.urjc.es/jmplaza/students/tfg-kibotics-motor_fisicas-natalia_monforte-2020.pdf)). Ahora queremos explorar el uso distribuido de AFrame con varios usuarios simultáneos, cada uno desde su ordenador accediendo a misma escena *distribuida*, dentro de la cual incluso pueden interactuar. Algo parecido a la tecnología [Mozilla Hubs](https://hubs.mozilla.com/). Aprenderás tecnología puntera de VR y reforzarás tu conocimiento web.

- **Orientado a** Alumnos de titulaciones de telecomunicación o informática URJC (GISAM, GITT, GIT, GST), preferibles conocimientos de tecnologías web de frontend (HTML, JavaScript, CSS)
- **Mentor:** José María Cañas (josemaria.plaza AT urjc.es)

<figure class="half">
    <a href=""><iframe src="https://www.youtube.com/embed/4BezsGTTrXs"></iframe></a>
    <a href=""><iframe src="https://www.youtube.com/embed/8mtK8DVkDZo"></iframe></a>
</figure>

{% include youtubePlayer.html id=page.youtubeId1 %}

### 2.- Programación de aplicaciones robóticas reactivas con la herramienta visual [VisualCircuit](https://jderobot.github.io/VisualCircuit/)

La manera habitual de programar aplicaciones robóticas es escribir su código fuente en un lenguaje de alto nivel como C++ o Python. Por ejemplo como un bucle infinito que en cada iteración comprueba valores de los sensores, toma alguna decisión y envía comandos a los actuadores del robot. En el entorno ROS las aplicaciones son varios nodos ejecutando concurrentemente e intercambiando mensajes entre sí (*topics*). Una manera alternativa es diseñar la aplicación robótica como si fuera un circuito, con entradas, salidas y bloques internos conectados entre sí mediante "cables", como si fueran componentes electrónicos. Las entradas del circuito global se conectan a los sensores y las salidas a los actuadores del robot. Esta filosofía se usa mucho en Computación Reconfigurable (FPGAs). 

Con la financiación de Googe (GSoC-2020) en la asociación JdeRobot crearon la herramienta gráfica [VisualCircuit](https://jderobot.github.io/VisualCircuit/) para facilitar la creación de aplicaciones robóticas siguiendo esta filosofía. Cada bloque es un proceso de Python, iterativo, y los cables entre bloques se implementan con memoria compartida. Varias aplicaciones se desarrollaron con ROS1 y con visión para validar su funcionamiento. Este trabajo fue seleccionado en [ROS World 2020](https://www.youtube.com/watch?v=FDi2-TTH9z0) como charla relámpago. En GSoC-2021 se construyó el servidor web [visualcircuit.org](https://visualcircuit.org/) para ofrecer esa misma funcionalidad desde el browser, sin necesidad de instalar nada. Este trabajo también fue seleccionado dentro de la [ROS World 2021](https://www.youtube.com/watch?v=FDi2-TTH9z0).

Se ofrece un TFG sobre la creación usando VisualCircuit de varias aplicaciones robóticas reactivas con robots variados (un drone, un TurtleBot2, un coche autónomo). También se abordará la extensión de la herramienta para soportar robots con drivers en ROS2. Es recomendable manejar GitHub e inglés escrito con cierta soltura, interactuarás con el equipo internacional de desarrolladores de esta herramienta.

- **Orientado a** Alumnos del Grado de Ingeniería en Robótica Software 
- **Mentor:** José María Cañas (josemaria.plaza AT urjc.es)


<p class="aligncenter">
<img src="/assets/images/community/VisualCircuit.png"> 
</p>

<figure class="half">
    <a href=""><iframe src="https://www.youtube.com/embed/WMRDqv3TYB0"></iframe></a>
    <a href=""><iframe src="https://www.youtube.com/embed/k0KEFBCWEQc"></iframe></a>
</figure>


### 3.- Integración de ejercicios de programación pura en [Unibotics](https://unibotics.org/)

En la actualidad, tanto en carreras técnicas como en algunas no consideradas técnicas, adquirir competencias de programación se está convirtiendo en algo obligatorio. Es por ello por lo que muchas instituciones trabajan para ofrecer a los estudiantes recursos para apoyarlos durante las asignaturas de introducción a la programación. Para facilitar este apoyo, es necesario facilitar las herramientas apropiadas para que la asignatura pueda transcurrir con éxito, facilitando estas plataformas apoyo tanto a los docentes como a los estudiantes.

[Unibotics](https://unibotics.org/) es una plataforma Web que inicialmente fue concebida para la enseñanza de la programación de robots. En dicha plataforma y para cada ejercicio disponible, se ofrecen una serie de evaluadores (de estilo, de funcionalidad, etc...) que permiten a los estudiantes obtener una retroalimentación automática sobre el código que escriben. Además, en la propia plataforma los estudiantes disponen de un historial con sus calificaciones, pudiendo ser conscientes en todo momento de su evolución. 

El objetivo de este TFG es implementar ejercicios de programación pura que no requieren de un simulador robótico, si no que directamente el usuario podrá escribir su código en la plataforma Web y obtener el resultado de la ejecución directamente a través de la plataforma. De esta manera, además de tener acceso a herramientas de autoevaluación, no sería tampoco necesario que tuvieran que instalar ningún tipo de herramienta.

- **Orientado a** Alumnos de titulaciones de telecomunicación o informática URJC (GISAM, GITT, GIT, GST), preferibles conocimientos de tecnologías web de frontend (HTML, JavaScript, CSS)
- **Mentor:** David Roldán Álvarez (david.roldan AT urjc.es)


&nbsp;
## Current Students

### Current PhD students
<!--  - [Francisco Rivas](https://github.com/RoboticsLabURJC/2017-phd-francisco-rivas), DeepLearning -->
  - [Nuria Oyaga](https://roboticslaburjc.github.io/2022-phd-nuria-oyaga), Machine Learning in Robotics
  - Pedro Cuenca, DeepLearning in image enhancement
  - [Sergio Paniego](https://github.com/RoboticsLabURJC/2019-phd-sergio-paniego), Machine Learning in Robotics
  - [Rubén Lucas](https://github.com/RoboticsLabURJC/2020-phd-ruben-lucas), Machine Learning in Robotics
<!---  - [Luis Caiza](https://github.com/RoboticsLabURJC/2018-phd-luis-caiza), vision in drones -->
  - [Pedro Fernández](https://github.com/RoboticsLabURJC/2018-phd-pedro-fernandez), Reinforcement Learning in Robotics
<!--  - [Alberto Martín](https://roboticslaburjc.github.io/2019-phd-alberto-martin), Reinforcement Learning -->


### Current Master students
<!---  - José Miguel Zamora, Machine Learning in Robotics -->
  - [Antonio Triguero](https://roboticslaburjc.github.io/2020-tfm-antonio-triguero), Machine Learning in Robotics
  - [Pablo Asensio](https://roboticslaburjc.github.io/2020-tfm-pablo-asensio), RoboticsAcademy: Visual 3D odometry exercise
  - [David Valladares](https://roboticslaburjc.github.io/2020-tfm-david-valladares), RoboticsAcademy: Vision based exercises
<!---  - Álvaro Paniagua, robotics education with Kibotics, data design -->
<!---  - Mikel Díez, visual perception on an autonomous boat  -->
<!---  - [Francisco J. Palacios](https://roboticslaburjc.github.io/2018-tfm-Francisco-Palacios), SDSLAMmobile: visualSLAM in Android for Augmented Reality applications. -->




### Current Grad students
  - [David Tapiador](https://roboticslaburjc.github.io/2022-tfg-david-tapiador), VisualCircuit for robotics applications
  - [Raúl Fernández](https://github.com/RoboticsLabURJC/2022-tfg-raul-fernandez) (co-advised with Daniel Palacios -URJC-), Unibotics
  - [Felicidad Abad](https://roboticslaburjc.github.io/2021-tfg-felicidad-abad/), Unibotics, automatic testing, vision based exercises
  - [Carlos Caminero](https://roboticslaburjc.github.io/2021-tfg-carlos-caminero), Unibotics, ROS2, BehaviorTrees, TurtleBot2
  - [Daniel Hervás](https://roboticslaburjc.github.io/2021-tfg-daniel-hervas), Unibotics, robot programming games
  - [Álvaro Martín](https://roboticslaburjc.github.io/2020-tfg-alvaro-martin) (co-advised with Inmaculada Mora -URJC-), Predicting images, learning time sequences
<!---  - [Rodrigo Pacheco](https://github.com/RoboticsLabURJC/2018-tfg-rodrigo-pacheco), Tello drones support in Kibotics -->
<!---  - [Sergio Lorenzo](https://github.com/RoboticsLabURJC/2018-tfg-sergio-lorenzo), VisualCircuit robot programming tool in Python -->
  - [Eva García](https://github.com/RoboticsLabURJC/2017-tfg-eva_garcia), mBot robot programming in Python, PyBoKids
  - [Richard Nicklas](https://roboticslaburjc.github.io/2017-tfg-richard-nicklas) (co-advised with Felipe Machado -URJC-), computer vision algorithms on FPGAs




&nbsp;
## Previous students

### 2022
  - [Claudia Álvarez](https://roboticslaburjc.github.io/2021-tfg-claudia-alvarez/logbook/) (grad) [(pdf)](https://gsyc.urjc.es/jmplaza/students/tfg-Robotics_Academy-claudia_alvarez-2022.pdf), Unibotics analytics, based on Elasticsearch and DASH
  - [Pedro Arias](https://github.com/RoboticsLabURJC/2021-tfm-pedro-arias) (master, co-advised with David Martín -UC3M-) [(pdf)](https://gsyc.urjc.es/jmplaza/students/tfm-drones-followperson-pedro_arias-2022.pdf), DroneWrapper, follow person application with real drones, simulated drones and DeepLearning perception
  - [Vladislav Kravchenko](https://github.com/vladkrav/AmigoBot) (master, co-advised with Manuel Ocaña -UAH-) [(pdf)](https://gsyc.urjc.es/jmplaza/students/tfm-academy-vladislav_kravchenko-2022.pdf), RoboticsAcademy laser mapping and laser localization exercises

### 2021
  - [Marta Quintana](https://roboticslaburjc.github.io/2020-tfg-marta-quintana) (grad), robotics education with Kibotics
  - [Ana Cuevas](https://github.com/RoboticsLabURJC/2019-tfg-ana-cuevas) (grad), computer vision exercises in JdeRobot's RoboticsAcademy

### 2020
  - [Daniel Pulido](https://github.com/RoboticsLabURJC/2020-tfg-daniel-pulido) (grad), robotics education with Kibotics
  - [David Pascual](https://roboticslaburjc.github.io/2017-tfm-david-pascual/) (master), Convolutional Pose Machines
  - [Nuria Oyaga](https://roboticslaburjc.github.io/2017-tfm-nuria-oyaga/logbook/) (master), Predicting images, learning time sequences
  - [Javier Martínez](https://roboticslaburjc.github.io/2018-tfm-javier-martinez) (master), VisualSLAM including IMU information
  - [Francisco Pérez](https://roboticslaburjc.github.io/2017-tfm-francisco-perez) (master), DeepLearning in autonomous vision based navigation of real robots
  - [Ignacio Arranz](https://roboticslaburjc.github.io/2019-tfm-ignacio-arranz) (master), Deep Reinforcement Learning for autonomous robot navigation
  - [Aitor Martínez](https://roboticslaburjc.github.io/2019-tfm-aitor-martinez) (master), Visual navigation of a Tello drone
  - [David Valladares](https://roboticslaburjc.github.io/2019-tfg-david-valladares) (grad), robotics education with Kibotics
  - [Natalia Monforte](https://roboticslaburjc.github.io/2019-tfg-natalia-monforte) (grad), robotics education with Kibotics
  - [Jorge Cruz](https://github.com/RoboticsLabURJC/2019-tfg-jorge-cruz) (grad), PiBot visual behaviors in Kibotics
  - [Nacho Condés](https://roboticslaburjc.github.io/2019-tfm-nacho_condes/) (master), DeepLearning perception for a social autonomous robot
  - [Ángel Perea](https://roboticslaburjc.github.io/2019-tfg-angel-perea/) (grad), analytics in a robotics education online platform
  - [Omar Garrido](https://roboticslaburjc.github.io/2019-tfm-omar-garrido) (master), SDLAM+: VisualSLAM algorithm with RGBD sensors
  - [Pablo Moreno](https://roboticslaburjc.github.io/2019-tfm-pablo-moreno/) (master), automatic competitions in a robotics education online platform
  - [Eldon Caldwell](https://gsyc.urjc.es/jmplaza/students/phd-eldon_caldwell-2020.pdf) (PhD), Social assistive robotics for speech language therapy
  - [Eloy Navarro](https://github.com/RoboticsLabURJC/2018-tfg-eloy-navarro) (grad), drone stabilization with an FPGA ground station	 
  - [Pedro Arias](https://github.com/RoboticsLabURJC/2019-tfg-pedro-arias) (grad), ROSpilot project with drones
  - [Carlos Awadallah](https://gsyc.urjc.es/jmplaza/students/tfm-academy-carlos_awadallah-2020.pdf) (master), Robotics Academy

### 2019
  - [Rubén Álvarez](https://roboticslaburjc.github.io/2019-tfg-ruben-alvarez) (grad), WebSim robot simulator.
  - [Elías Barcia](https://roboticslaburjc.github.io/2017-tfm-elias-barcia) (master), visual SLAM, slam-testbed tool
  - [Alexandre Rodríguez](https://roboticslaburjc.github.io/2017-tfm-alexandre-rodriguez) (master), Visual multiobject tracker with DeepLearning
  - [Jéssica Fernández](https://roboticslaburjc.github.io/2018-tfm-Jessica-Fernandez) (master), DeepLearning for visual detection and tracking
  - [Vanessa Fernández](https://roboticslaburjc.github.io/2017-tfm-vanessa-fernandez) (master), DeepLearning for learning a visual controller
  - [Ignacio Malo](http://roboticslaburjc.github.io/2016-tfg-Ignacio-Malo) (grad), robotic arm exercise in RoboticsAcademy


### 2018
  - [Vanessa Fernández](http://roboticslaburjc.github.io/2016-tfg-vanessa-fernandez), new exercises at RoboticsAcademy


