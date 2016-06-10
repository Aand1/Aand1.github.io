---
layout: post
title: Be careful with python scripts in ROS
categories: develop
tags: ROS
---

### 1.Need to use **sudo chmod +x **.py** cmd to give ROS the right to exec the script
~~~
and1@VM-Ubuntu:~$ rosrun gi5630_to_odom gi5630_to_gpfpd_ros_topic.py  
[rosrun] Couldn't find executable named gi5630_to_gpfpd_ros_topic.py below /home/and1/catkin_ws_2/src/gi5630_to_odom  
[rosrun] Found the following, but they're either not files,  
[rosrun] or not executable:  
[rosrun] /home/and1/catkin_ws_2/src/gi5630_to_odom/src/gi5630_to_gpfpd_ros_topic.py
~~~  

### 2.The head of the python script must start with **#!/usr/bin/python**
>started core service [/rosout]  
process[gpfpd_ros_topic_node-2]: started with pid [11628]  
Unable to launch [gpfpd_to_odom_node-3].   
If it is a script, you may be missing a '#!' declaration at the top.  
The traceback for the exception was written to the log file