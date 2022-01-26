# Third_assignment_RT1

Introduction
================================

Development of a software architecture for the control of a mobile robot. General idea to control a mobile robot in the gazebo area by different methods. The following ways to do this are divided into three parts:

1. Use the coordinates entered by the user 
2. Driving robots with keyboards
3. Drive robots through user, avoid going against obstacles
Developed code written in ros area in python language, it is possible to develop similar codes with the same concept in C++ language.

Materials and Methods
=========================

To make the following codes work on your system, you need to install the slam_gmapping package form: https://github.com/CarmineD8/slam_gmapping .You have to use the version adapted for your type of ros there are two types: 1.Kinetic and 2.Noetic in my case the second was used. The package can be downloaded from the following repository or by using fork directly in your ros workspace.

Actionlib stack was used in the developed code. Therefore you have to install actionlib in your repository, in case of lack of installation you can receive errors of type lack of attribution in the SimpleActionCliente or any type of attribution error on actionlib stack. For actionlib installation package to have more information can be found on: http://wiki.ros.org/actionlib.

Installing and running
----------------------
Once it was ready all the following cases you can download or fork, the repository in your workspace. At this stage to start the simulation you have to do:
1.Use:
$catkin_make
```
To compile the new packages installed on workspace, remember to use catkin_make in the workspace root file
