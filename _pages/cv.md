---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in **Robitics**, University of Michigan, 2023 (expected)
  * GPA: 4.0/4.3
  * Exchange student at the University of Toronto, GPA: 3.96/4.0
  * Coursework: Mobile Robotics and Perception, Robot Modeling and Control, Machine Learning
* B.S. in **Mechanical Engineering**, National Taiwan University, 2020
  * **GPA: 4.0/4.0**
  * Coursework: Mobile Robotics, Computer Vision, Robotics System Laboratory

Skills
======
* Programming: **C/C++**, **Python**, MATLAB, LabVIEW
* Software Tools: ROS, Git, OpenCV, PyTorch, Simulink, Raspberry Pi, Arduino, Docker

Work experience
======
* Incoming Fall intern @ **Tesla** autopilot team

* Incoming Summer intern @ **Nvidia** mapping team

* Software Engineer Intern @ **Delta Research Center**, Delta Electronics (Jul. 2020 - Aug. 2020)
  * Designed a pipeline for robotic arms with a camera to track multiple faces in real time with OpenCV library
  * Implemented Haar-cascade and HOG object detection algorithm and compared their runtime and accuracy
  * Reduced tracking latency by 50% by implementing multithreading techniques and a modified PD controller

Research experience
======
* Graduate student researcher @ **Biped Robotics Laboratory**, Univeristy of Michigan
  * Worked on the localization pipeline for Cassie, the biped robot, using topometric map and lidar measurement
  * Extracted and Analyzed road and sidewalk feature from a Velodyne Lidar using PCL library in a ROS system
  * Replaced the bus stops generation process with agglomeratively hierachical clustering algorithm

* Undergraduate student researcher @ **Microrobotics Laboratory**, University of Toronto
  * Constructed an automatic pipeline to acquire 1500 measurements of magnetic fields within 30 mins for microrobots
  * Implemented interior-point algorithms in MATLAB to reduce the average magnetic field model errors by 50 %
  
Projects
======
* **SLAM and exploration of a mobile robot**, University of Michigan (Sept. 2021 - Oct. 2021)
  * Programmed a mobile robot to perform SLAM and exploration tasks (**First place** in the contest out of 24 teams)
  * Implemented Monte Carlo Localization with sensor readings from a RPLidar, wheel encoders, and a gyroscope
  * Implemented Frontier Exploration with A-star algorithm for the robot (Fully explored the maze in the competition)
  * Reduced position errors from 90 cm t0 3 cm when commanding the robot to drive a 1m square 8 times

* **Autonomous blocks stacking robotics arm**, University of Michigan (Oct. 2021 - Dec. 2021)
  * Programmed a robotics arm to autonomously identify and manipulate blocks (**First place** in the contest out of 24 teams)
  * Conducted camera intrinsic and extrinsic calibration using OpenCV PnP solver (with 4mm maximum depth error)
  * Developed an algorithm that utilizes a RGBD camera to detect blocks’ size, color, position, orientation on a board
  * Implemented Forward / Inverse Kinematics and fine-tuned a PID controller (reduced offset from 20mm to 3mm)

* Visual Odometry using KITTI dataset, University of Michigan (Oct. 2021 - Dec. 2021)
  * Extracted feature points from stereo images using two approaches: SIFT and D2-Net (a CNN-based feature extractor)
  * Estimated motion using essential matrix for monocular camera and using PnP solver for stereo camera
  * Compared error and runtime for different feature extraction model and different camera model
  
* Deep Learning for Computer Vision, University of Michigan (Oct. 2021 - Dec. 2021)
  * Trained a MiniVGG model with added batch normalization layers to predict categorized scenes with 55% accuracy
  * Implemented Pix2Pix conditional GAN model to color shoe’s images containing only the edges to full images of shoe
  * Implemented a single-stage object detector, based on YOLO v1, which achieved 12% mAP on the PASCAL VOC dataset


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
