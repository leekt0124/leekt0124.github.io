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
* B.S. in Mechanical Engineering, National Taiwan University, 2020
  * GPA: 4.0/4.0
  * Coursework: Mobile Robotics, Computer Vision, Robotics System Laboratory
* M.S. in Robitics, University of Michigan, 2023 (expected)
  * GPA: 4.0/4.3
  * Exchange student at the University of Toronto, GPA: 3.96/4.0
  * Coursework: Mobile Robotics and Perception, Robot Modeling and Control, Machine Learning

Work experience
======
* Incoming Fall intern @ Tesla autopilot team

* Incoming Summer intern @ Nvidia mapping team

* Software Engineer Intern @ Delta Research Center, Delta Electronics (Jul. 2020 - Aug. 2020)
  * Designed a pipeline for robotic arms with a camera to track multiple faces in real time with OpenCV library
  * Implemented Haar-cascade and HOG object detection algorithm and compared their runtime and accuracy
  * Reduced tracking latency by 50% by implementing multithreading techniques and a modified PD controller

Research experience
======
* Graduate student researcher @ Biped Robotics Laboratory, Univeristy of Michigan
  * Worked on the localization pipeline for Cassie, the biped robot, using topometric map and lidar measurement
  * Extracted and Analyzed road and sidewalk feature from a Velodyne Lidar using PCL library in a ROS system
  * Replaced the bus stops generation process with agglomeratively hierachical clustering algorithm

* Undergraduate student researcher @ Microrobotics Laboratory, University of Toronto
  * Constructed an automatic pipeline to acquire 1500 measurements of magnetic fields within 30 mins for microrobots
  * Implemented interior-point algorithms in MATLAB to reduce the average magnetic field model errors by 50 %
  
Skills
======
* Programming: C/C++, Python, MATLAB, LabVIEW
* Software Tools: ROS, Git, OpenCV, PyTorch, Simulink, Raspberry Pi, Arduino, Docker

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
