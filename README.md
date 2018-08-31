[![DOI](https://zenodo.org/badge/22321/prajankya/Lidar-Robot.svg)](https://zenodo.org/badge/latestdoi/22321/prajankya/Lidar-Robot) [![GPL Licence](https://badges.frapsoft.com/os/gpl/gpl.svg?v=103)](https://opensource.org/licenses/GPL-3.0/)  [![Prajankya](https://img.shields.io/badge/Developer-Prajankya-blue.svg)](https://github.com/prajankya)


## Unmanned Mapping Vehicle Using L.O.A.M. in Real-time
 L.O.A.M. - Lidar Odometry and Mapping in Real-time

This project is about an Unmanned Mobile Robot using L.O.A.M. (Lidar, Odometry And Mapping) in Real-time.

## Abstract
The robot uses a Laser distance sensor(Lidar) which gives distance to the first obstacle in its line-of-sight and the sensor. Making this sensor rotate gives us distance of all the obstacles from the sensor, which in fact is the map of the surrounding. This sensor, with other sensors like odometry and IMU(Inertial measurement Unit), mounted on a mobile moving base and complex algorithms driving the robot autonomously help make a to-scale map of the surrounding.

## Basic contruction
The Bot uses ROS(Robot Operating System) at its core running on a compact mobile CPU. It uses IMU(Inertial measurement Unit) for its orientation feedback. The base comprise of a square frame with four omni wheel on its corners driven by high torque BLDC motors. The Bot works on 24v DC and have internal power distribution and conversion unit. The bot first takes in the lidar input, and process that into a map fusing together with  odometry input and IMU input. The Odometry sensor is a “Castor Feedback sensor” which consist of two rotary encoders, one reading the angle or rotation, and other the length in that direction. This type of feedback can be universally used for any type of terrain robots with very good accuracy. This bot can be controlled from a remote computer, on which we can even see the 3D Model and see the model within the map in Real time. The GUI remote can be used to save the map or load the map in the system. Taking all the properties in consideration,  Lidar Robot with L.O.A.M. is a very robust platform with variety of robotics applications.


## How to Install
rosdep install --from-paths /opt/ros/jade --ignore-src

rosdep install --from-paths Lidar-Robot/src --ignore-src

6th sem, 2017 Batch  
Department of Automation and Robotics.  
B. V. Bhoomaraddi College of Engineering and Technology, Hubli  

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)

[![forthebadge](http://forthebadge.com/images/badges/powered-by-electricity.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
