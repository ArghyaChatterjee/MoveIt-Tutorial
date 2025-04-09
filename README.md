# MoveIt Tutorial
MoveIt tutorial for manipulation with generic robots.

- MoveIt Setup Assistant Tutorial [[website]](https://docs.ros.org/en/kinetic/api/moveit_tutorials/html/doc/setup_assistant/setup_assistant_tutorial.html)

# Requirements
MoveIt2 was tested on Ubuntu 22.04, Nvidia Driver 535, Cuda 12.4, Python 3.10, Isaac Sim 4.5 and ROS2 Humble.

# Installation
First, install ROS2 Humble desktop version.
```bash
sudo apt install ros2-humble-desktop
```
Clone this repo:
```
git clone https://github.com/ArghyaChatterjee/MoveIt-Tutorial.git
```
Navigate to the repo directory and build the workspace.
```
cd MoveIt-Tutorial/moveit2_UR5
colcon build
```
Install the necessary binary files for the MoveIt package:
```bash
sudo apt install ros-humble-ros2-control ros-humble-ros2-controllers ros-humble-gripper-controllers ros-humble-moveit
```
Launch MoveIt Setup Assistant:
```bash
source install/setup.bash
ros2 launch moveit_setup_assistant setup_assistant.launch.py
```
Launch UR5 Model inside Isaac Sim:

# Resources
- How to Use MoveIt with Isaac Sim: A Step-by-Step Guide [[video]](https://www.youtube.com/watch?v=pGje2slp6-s) 
- ROS2 humble tutorial, using ROS2 with your custom Robot [[video]](https://www.youtube.com/watch?v=EosEikbZhiM)
- How to Control ANY Robot in ROS2 with MoveIt2 & Gazebo [[video]](https://www.youtube.com/watch?v=45PGFt9C-B8)
- Simulation took Control of my Robot Arm (NVIDIA Isaac Sim) [[video]](https://www.youtube.com/watch?v=Eb2zuQxOBlY)
- MoveIt2 and ROS2 Control: How to Configure & Fix Motion Planning Issues with Setup Assistant [[video]](https://www.youtube.com/watch?v=nZqTdzGAfYs)
- Roboage [[youtube channel]](https://www.youtube.com/@roboage1027)
