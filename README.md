# Olive Kit Description

This package contains ROS-related information about individual olive kit such as olive OWL, olive ANT.

It has .urdf definitions, meshes, collision info etc.

## Usage

```
sudo apt install ros-humble-xacro
sudo apt install ros-humble-joint-state-publisher-gui

git clone https://gitlab.com/oliverobotics/hardware/descriptions/olv_kit_descriptions.git

colcon build

source install/setup.bash
```

### OWL
```
ros2 launch olv_kit_descriptions visualize_olive_owl.launch.py
```

### ANT
```
ros2 launch olv_kit_descriptions visualize_olive_ant.launch.py

```
