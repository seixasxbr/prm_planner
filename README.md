# prm_planner
Package developed for ROS Noetic that implements PRM as a global planner in plugin form.<br />

**Author: [Mateus Seixas](https://github.com/seixasxbr)<br />
Affiliation: [BIR - Brazilian Institute of Robotics](https://github.com/Brazilian-Institute-of-Robotics)<br />
Maintainer: Mateus Seixas, mateus_seixas@hotmail.com.br**

## Dependencies:<br />
sudo apt install ros-noetic-tf2-bullet<br />
sudo apt install ros-noetic-ompl<br />
sudo apt install ros-noetic-ompl-dbgsym

## How to Set PRM as Global Planner 

Change move_base parameter **base_global_planner** to **PRM**.
It can be done in the launch file:
<param name="base_global_planner" value="PRM" />
