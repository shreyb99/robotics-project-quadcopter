# Robotics Project Quadcopter
This project was developed during the course 'Robotics and Automation', titled as Unmanned Aerial Exploration System (UAVs). Aim of the project was to develop an simulation of 
an UAV as it passes through obstacles and barriers over land autonomusly. It uses ROS Kinetic Version 1.2 and developed on Ubuntu 16.04. 

This simulation showcases Self-Flying of the drone, the ability of a drone to perform aerial maneuvers without human control. In this we are using mapping in which the drone moves around with 
and sees if any object is present. It then uses localization to identify the position of the drone. Next comes the path planning which determines its navigational path. 
The results are made using mapping and localisation technique called SLAM (Simultaneous Localization and Mapping).

<img src=https://github.com/shreyb99/robotics-project-quadcopter/blob/main/Pictures/5.png width=600>

<img src=https://github.com/shreyb99/robotics-project-quadcopter/blob/main/Pictures/1.png width=600>

# Future Work
Since our implementation only covers 2D space (drone performs mapping and localization at a specified height only, does not take in height as parameter), a lot of focus of future
 works will be on making working 3D SLAM implementation. Also, with the use of cameras and Artificial Intelligence & Computer Vision algorithms, the navigational path and mapping could be improved significantly.
 
 This project is under development.
