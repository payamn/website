---
layout:     project
title:     "Recognizing and Tracking High-Level, Human-Meaningful Navigation Features of Occupancy Grid Maps"
date:       2020-01-01
code: https://github.com/AutonomyLab/following-ahead
doc: https://ieeexplore.ieee.org/abstract/document/9108678
demo: bPgnD9fb8zI
best:       true
image_small: /files/projects_files/2020-01-01-Recognizing-and-Tracking.png
short:  "Built an occupancy grid map during online and at the same time use a neural network (Based on ResNet34 and YOLOv2) to detect, locate and say the target classes around the robot. Tools: Pytorch, ROS, Stage, Python, OpenCV"

---
This paper describes a system whereby a robot detects and tracks human-meaningful navigational cues as it navigates in an indoor environment. It is intended as the sensor front-end for a mobile robot system that can communicate its navigational context with human users. From simulated LiDAR scan data we construct a set of 2D occupancy grid bitmaps, then hand-label these with human-scale navigational features such as closed doors, open corridors and intersections. We train a Convolutional Neural Network (CNN) to recognize these features on input bitmaps. In our demonstration system, these features are detected at every time step then passed to a tracking module that does frame-to-frame data association to improve detection accuracy and identify stable unique features. We evaluate the system in both simulation and the real world. We compare the performance of using input occupancy grids obtained directly from LiDAR data, or incrementally constructed with SLAM, and their combination.
