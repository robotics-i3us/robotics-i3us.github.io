![logo](images/logo.png)

Entre las diversas líneas de investigación en Ingeniería Informática que apoya el [Instituto Universitario de Investigación en Ingeniería Informática de la Universidad de Sevilla](https://i3us.us.es/) (I3US), cabe destacar aquellas relacionadas con la Robótica, la Inteligencia Artificial y la Automatización. Con el fin de fomentar y apoyar la investigación en estas líneas, el I3US dispone de material e infraestructuras de robótica que pone al servicio de sus investigadores. Asimismo, la [siguiente página en Github](https://github.com/robotics-i3us) contiene repositorios de software libre creados y mantenidos por miembros del I3US para promover la colaboración y facilitar el uso compartido del material.

En esta página se detalla el material disponible.

- [RS-Lidar-16](#rs-lidar-16)
- [Plataforma TurtleBot II](#plataforma-turtlebot-ii)
  * [Base Kobuki](#base-kobuki)
  * [Lidar 2D Sick TIM551-205001](#lidar-2d-sick-tim551-205001)
  * [Lidar 2D RPLIDAR A3](#lidar-2d-rplidar-a3)
  * [Intel RealSense Depth Camera D435](#intel-realsense-depth-camera-d435)
  * [Nvidia Jetson AGX Xavier Developer Kit 32 GB](#nvidia-jetson-agx-xavier-developer-kit-32-gb)
  * [NUC i5, 8Gb RAM, 1Tb HD](#nuc-i5-8gb-ram-1tb-hd)
  * [Monitor, teclado y ratón](#monitor-teclado-y-ratón)
- [Plataforma XL-GEN](#plataforma-xl-gen)

Dicho material ha sido adquirido con fondos FEDER Convocatoria Adquisición Equipamiento Científico-Técnico Infraestructuras: FEDER / Ministerio de Ciencia e Innovación y Universidades - Agencia Estatal de Investigación EQC2019 - 6325.

## RS-Lidar-16

![rslidar](images/rslidar16.jpeg)

Sensor LiDAR con campo de visión de 360 grados (horizontal) y 30 grados (vertical), 150 metros de alcance y precisión de 2cm. Las aplicaciones principales del RS-LiDAR-16 son la conducción autónoma, la percepción del entorno de robots y el mapeo de UAV.

* [Página web del producto](https://www.roscomponents.com/es/lidar-escaner-laser/251-rs-lidar-16.html)
* [Paquete oficial para ROS](https://github.com/RoboSense-LiDAR/rslidar_sdk)  

## Plataforma TurtleBot II

![turtlebot](images/turtlebot.jpeg)

La plataforma [TurtleBot II](https://www.turtlebot.com/turtlebot2/) es una plataforma de bajo coste para la experimentación en robótica móvil. El I3US dispone de seis kits TurtleBot II. En [este repositorio](https://github.com/robotics-i3us/turtle-i3us) se puede encontrar un paquete de ROS conteniendo todos los drivers, dependencias e instrucciones necesarias para la puesta en servicio de los TurtleBot adquiridos por el I3US.

* [Página web del producto](https://www.turtlebot.com/turtlebot2/)
* [Paquete oficial de ROS](http://wiki.ros.org/turtlebot)
* [Paquete ROS del TurtleBot-I3US](https://github.com/robotics-i3us/turtle-i3us)

Cada uno de los seis kits cuenta con los siguientes componentes:

### Base Kobuki

Kobuki es una base móvil de bajo coste diseñada para la educación y la investigación en robótica. Las baterias a bordo proporcionan alimentación para un ordenador externo, así como para sensores y actuadores adicionales. La odometría de alta precisión, asistida por un giroscopio calibrado en fábrica, permite una navegación precisa.

* [Página web del producto](https://www.roscomponents.com/en/mobile-robots/97-kobuki.html)
* [Paquete oficial para ROS](https://github.com/yujinrobot/kobuki)

### Lidar 2D Sick TIM551-205001

Sensor LiDAR 2D con un campo de visión de 270 grados horizontal, 8 metros de alcance y resolución angular de 1 grado. Conexión Ethernet.

* [Página web del producto](https://www.sick.com/es/es/soluciones-de-medicion-y-deteccion/sensores-2d-lidar/tim5xx/tim551-2050001/p/p343045)
* [Paquete oficial para ROS](https://github.com/SICKAG/sick_scan)


### Lidar 2D RPLIDAR A3

Sensor LiDAR 2D con un campo de visión de 360 grados horizontal, 25 metros de alcance y resolución angular de 0.225 grados. Conexión USB.

* [Página web del producto](https://www.slamtec.com/en/Lidar/A3)
* [Paquete oficial para ROS](https://github.com/slamtec/rplidar_ros)

### Intel RealSense Depth Camera D435

Cámara de profundidad estereoscópica con aplicaciones en la robótica, realidad aumentada y virtual. Alcance de 10 metros. Conexión USB.

* [Página web del producto](https://www.intelrealsense.com/depth-camera-d435/)
* [Paquete oficial para ROS](https://github.com/IntelRealSense/realsense-ros)

### NUC i5, 8Gb RAM, 1Tb HD

La CPU a bordo del TurtleBot es un Intel NUC i5 con 8 Gb de RAM y 1 Tb de disco duro con conexión Wi-Fi y Ethernet, puertos USB 2.0 y 3.0, y salida HDMI. 

### Nvidia Jetson AGX Xavier Developer Kit 32 GB

*Sección en desarrollo*

El kit Nvidia Jetson AGX Xavier permite manejar algoritmos de odometría visual, fusión de sensores, localización y cartografía digital, detección de obstáculos y planificación de rutas para robots de nueva generación. Cuenta con un rendimiento GPU de 32 TeraOPS (TOPS) de cálculo máximo y 750 Gbps de E/S de alta velocidad en un formato reducido de 100x87 mm.

* [Página web del producto](https://www.nvidia.com/es-es/autonomous-machines/embedded-systems/jetson-agx-xavier/)

### Monitor, teclado y ratón 

Para facilitar el desarrollo de software y la preparación de experimentos, cada kit TurtleBot del I3US viene acompañado por un monitor, un teclado y un ratón, para que el usuario se pueda conectar con comodidad a la CPU a bordo o al kit Nvidia Jetson Xavier.  


## Plataforma XL-GEN

*Sección en desarrollo*

