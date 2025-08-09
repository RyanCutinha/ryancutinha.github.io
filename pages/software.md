---
layout: default
title: TitanBot Robotics Project!
nav_order: 3
permalink: /pages/software
---

## Software

We decided to have 2 parts in the software of our machine. The first part was designing the autonomus part of the robot, and the second was having TeleOps incorporated into the software. 

## Autonomus Software

For the autonomus path, turning the robot while it was moving would be efficient, which allowed for it to save time. In order to accomplish this, we decided to use RoadRunner, a motion planning library, into our Auto code. To make RoadRunner effective, I had to include motion sensors into the machine for it to properly function. After incorporating RoadRunner, a specific location and heading can be given, and the robot moves to that position using the motion sensors without me making complicated calculations to do so. Overall, through the implementation of RoadRunner, we developed better testing habits where we videotaped our robot to notice potential flaws instead of retaining problems in our minds before refining it. We also learned concepts like what spline movements were and different uses for sensors in the control hub.

## TeleOps

When driving, we noticed that some parts of the machine were moving even though I had not touched the joystick. To combat this, I included a 'dead zone' on the joystick, which is the area in which the machine does nothing. I also coded preset positions for the arm of the robot, which allowed the arm to go different heights more efficiently and accurately. While picking up certain objects, I had to reduce the speed of the robot to 40%, which allowed for more precise movements overall. Previously, a toggleable button inverted driver controls so the front of the robot became the back. This made it easier for our drivers to comprehend the direction they were facing and needed to move as we used to pick cones from one side of the robot and place them from the other.

