Sawyer Robot
==============

This repository contains metapackages and files for installation/use of the Sawyer Robot (to be used with sawyer_gail repository).

Installation
------------
Create a catkin workspace

```
$ mkdir -p ~/sawyer_ws/src/    
$ cd ~/sawyer_ws/
$ catkin_make
```
Setup sawyer_robot package:

```
$ cd ~/sawyer_ws/src
$ wstool init .
$ git https://github.com/nav74neet/sawyer_robot.git
$ wstool merge sawyer_robot/sawyer_robot.rosinstall
$ wstool update
```
