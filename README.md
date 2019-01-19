# motoman_apps [![Build Status](https://travis-ci.org/ntl-ros-pkg/motoman_apps.svg?branch=master)](https://travis-ci.org/ntl-ros-pkg/motoman_apps)

## Installation
### 1. Clone this repository.
```bash
$ cd <catkin_ws>/src
$ git clone https://github.com/ntl-ros-pkg/motoman_apps.git
```

### 2. Run install script
```bash
$ cd <catkin_ws>/src/motoman_apps
$ sh install.sh
```

## Applications
### Moveit
#### SIA5
```bash
$ roslaunch motoman_moveit_apps sia5_with_dhand_moveit_gazebo_autorun.launch
```

#### MotoMINI
```bash
$ roslaunch motoman_moveit_apps motomini_with_gripper_moveit_gazebo_autorun.launch
```

### Mathworks Demo
```bash
$ roslaunch motoman_mathworks_apps motomini_picking_demo_gazebo_autorun.launch
```
