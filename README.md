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
#### MotoMINI
```bash
$ roslaunch motoman_moveit_apps motomini_with_gripper_moveit_gazebo_autorun.launch
```

[![motomini_gripper_gazebo_moveit](.images/motomini_gripper_gazebo_moveit.jpg)](https://youtu.be/l5X38tWWEHU)

#### SIA5
```bash
$ roslaunch motoman_moveit_apps sia5_with_dhand_moveit_gazebo_autorun.launch
```
![sia5_dhand_gazebo_moveit](.images/sia5_dhand_gazebo_moveit.png)

### MotoMINI Mathworks Demo
#### Function Options
##### With gazebo grasp fix plugin
```bash
$ roslaunch motoman_mathworks_apps motomini_picking_demo_gazebo_autorun.launch load_grasp_fix:=true
```

#### Object Options
##### With coke ball
```bash
$ roslaunch motoman_mathworks_apps motomini_picking_demo_gazebo_autorun.launch
```

![motomini_mathworks_demo](.images/motomini_gazebo_mathworks.png)

##### With parts
```bash
$ roslaunch motoman_mathworks_apps motomini_picking_demo_gazebo_autorun.launch world:=motomini_with_table_parts
```

![motomini_mathworks_demo_parts](.images/motomini_gazebo_mathworks_parts.png)

##### With coke cans
```bash
$ roslaunch motoman_mathworks_apps motomini_picking_demo_gazebo_autorun.launch world:=motomini_with_table_coke
```

