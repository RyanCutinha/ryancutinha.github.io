---
layout: default
title: Ryan's Passion Project!
---

# About Me 

I am a rising senior at North Creek High School interested in engineering. I built this robot as a passion project so that I could better understand the aspects of engineering, especially in robotics, and how I could use my interests in the real world. 

# Machine Designs

The machine that I have built is a small robotic device that can move around places autnomously and with a controller. There were several designs that I used at several stages, and each had its pros and cons. Each design had four wheels, a base and a arm to pick up objects as they moved around. For most of the project, I controlled the machine via joysticks that were connected to a electronic device that sent signals to the machine. Additionaly, there were several sensors that I also included so that I could code the machine and move it to several positions, which allowed me to control the machine hands-free. 

# Current Design

The current design is neat and organized with zip-wries to prevent entanglement and has an open center for easy access to parts. My machine also has a lower chassis which helps it have a lower center of mass to prevent tipping. The control hub and the expansion hub are mounted on the side of the machine so that wiring is distributed to each side. One side of the claw is opened so the linear slide doesn't need to carry a lot of weight. The camera is mounted high to see over the motor and get a better view of the signal. I have also added additional weight to the back to evenly distribute weight. 

# Software

I decided to have 2 parts in the software of my machine. The first part was designing the autonomus part of the robot, and the second was having TeleOps incorporated into the software. 

# Autonomus Software

For the autonomus path, turning the robot while it was moving would be efficient, which allowed for it to save time. In order to accomplish this, I decided to use RoadRunner, a motion planning library, into our Auto code. To make RoadRunner effective, I had to include motion sensors into the machine for it to properly function. After incorporating RoadRunner, a specific location and heading can be given, and the robot moves to that position using the motion sensors without me making complicated calculations to do so. 

# TeleOps

When driving, I noticed that some parts of the machine were moving even though I had not touched the joystick. To combat this, I included a 'dead zone' on the joystick, which is the area in which the machine does nothing. I also coded preset positions for the arm of the robot, which allowed the arm to go different heights more efficiently and accurately. While picking up certain objects, I had to reduce the speed of the robot to 40%, which allowed for more precise movements overall. 

# Sensors used

While building, I used 4 drive motor encoders, 1 linear slide motor encoder, 1 InHub Gryo, 1 InHub Accelerometer, and 1 Webcam. The drive motor encoders helped the machine to move into its positions, the slide motor encoder moved the arm into position,  the InHub gryo ensures that the machine turns accurately and stays straight, the accelerometer ensured that the machine accelerated properly, and the Webcam is used to scan a signal to start moving. 

