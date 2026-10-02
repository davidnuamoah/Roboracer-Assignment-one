AME RoboRacer ROS 2 Foundation Assignment

## 1. Student Identification
* **Full Name:** David Afranie Nuamoah
* **Student ID:** 19001858

## 2. Environment Specifications
* **Operating System:** Ubuntu 24.04 LTS
* **ROS 2 Distribution:** ROS 2 Jazzy (or Humble)

## 3. How to Run

```bash
cd ~/ros2_ws
colcon build --symlink-install --packages-select roboracer_safety_controller
source install/setup.bash
ros2 launch roboracer_safety_controller safety_demo.launch.py
