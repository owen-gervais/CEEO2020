# ROS2 and Gazebo Integration with Onshape-to-Robot Generated sdfs

Utilizing the built LEGO SPIKE Prime Models, I used the Onshape-to-Robot plugin to export Robotic Assemblies to sdf's and imports
and into Gazebo for simulation.

## Installation of ROS2

This the step by step process of installing the required componnents to run this simulation. 
Running on an Ubuntu 20.04 LTS system, you can follow this [ROS2](https://index.ros.org/doc/ros2/Installation/Foxy/Linux-Install-Debians/) install tutorial in order to install everything you need.

If you run into the need to run python3-rosdep, You may need to install the rosdep package with the terminal command below

```bash
sudo apt-get install python3-rosdep
```

## Installation of Gazebo 11

In order to run this simulation, you need to have a standalone install of [Gazebo 11](http://gazebosim.org/tutorials?tut=install_ubuntu).
All new versions of ROS1 and ROS2, i.e. Noetic and Foxy currently, target Gazebo 11. 

## Installlation of gazebo_ros Package

