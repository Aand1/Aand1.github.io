---
layout: post
title: Frame id and Topic in ROS
categories: develop
tags:
---

1.Frame is a subset of a tf tree.[tf](http://wiki.ros.org/tf) is a package that lets the user keep track of multiple coordinate frames over time. tf maintains the relationship between coordinate frames in a tree structure buffered in time, and lets the user transform points, vectors, etc between any two coordinate frames at any desired point in time.  
2.[Topics](http://wiki.ros.org/Topics) are named buses over which nodes exchange messages;

A screenshot in Rviz shows the the same name map but with different meaning.

![_config.yml]({{ site.baseurl }}/images/frame id--topic--rviz.jpg)

And it's my first blog building by jekyll.
