---
layout: post
title: ROS topic name in code different with rostopic list tool 
categories: develop
tags: 
---

####1."gpfpd" topic name in the ros topic publisher
>pub = rospy.Publisher("gpfpd", gpfpd, queue_size=10)  


####2.when use the rostopic tool to list the topic,it becomes "/gpfpd"
>rostopic list  
>and1@VM-Ubuntu:~$ rostopic list
**_/gpfpd_**
/rosout
/rosout_agg
