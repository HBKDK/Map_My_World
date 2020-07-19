# Map_My_World
Udacity Robotics Software Engineer Course

## Program Overview
In this program, a mobile robot inside a map in Gazebo created map with ROS rtabmap package.
You can move the mobile robot using Tele-Operation.

## Requirements
* Gazebo any version later than v7.0.0
* ROS Kinetic : Link <http://wiki.ros.org/ROS/Installation>
* C++11 Compiler (gcc/g++)
* GNU make

## Setup and Running
1. github clone
<pre><code>git clone https://github.com/HBKDK/Map_My_World
</code></pre>
2. run
<pre><code>$ cd Map_My_World/catkin_ws  
$ source devel devel/setup.bash
$ roslaunch my_rtabmap mapping.launch</pre></code>
4. open other terminal
<pre><code>rosrun teleop_twist_keyboard teleop_twist_keyboard.py</pre></code>
5. Ok! Finish the ready for localization  
Give the command using telop package  
