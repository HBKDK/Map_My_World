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
<pre><code>$ git clone https://github.com/HBKDK/Map_My_World
</code></pre>

2. clone nodes
<pre><code>$ cd ~/Map_My_World/catkin_ws/src
$ git clone https://github.com/introlab/rtabmap_ros.git
$ git clone https://github.com/ros-teleop/teleop_twist_keyboard
$ git clone -b indigo-devel --single -branch https://github.com/ros-planning/navigation
</code></pre>

3. build
<pre><code>$ cd ~/home_service_robot/catkin_ws
$ catkin_make
</code></pre>

4. run
<pre><code>$ cd Map_My_World/catkin_ws  
$ source devel devel/setup.bash
$ roslaunch my_rtabmap mapping.launch</pre></code>
3. open other terminal
<pre><code>rosrun teleop_twist_keyboard teleop_twist_keyboard.py</pre></code>
4. Ok! Finish the ready for localization  
Give the command using telop package  
