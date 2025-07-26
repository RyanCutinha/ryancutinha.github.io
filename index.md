---
layout: default
title: TitanBot Robotics Project!
---


## Background 
I worked on a robotics project with a team that involved building a robotic machine that can navigate through mazes and perform certain tasks. I am interested in robotics, and building this robotic machine has helped to increase my knowledge of the various aspects of engineering.

## Current Design

The current design is neat and organized with zip-wries to prevent entanglement and has an open center for easy access to parts. Our machine also has a lower chassis which helps it have a lower center of mass to prevent tipping. The control hub and the expansion hub are mounted on the side of the machine so that wiring is distributed to each side. One side of the claw is opened so the linear slide doesn't need to carry a lot of weight. The camera is mounted high to see over the motor and get a better view of the signal. I have also added additional weight to the back to evenly distribute weight.

![Current Design](/assets/css/images/Current%20Design%20Picture.png){: .my-custom-image-class}

## Machine Designs

The machine that we have built is a small robotic device that can move around places autonomously and with a controller. There were several designs that we used over the course of my project, and each had its pros and cons. Each design had four wheels, a base, and an arm to pick up objects as they moved around. For most of the project, I controlled the machine via joysticks that were connected to an electronic device that sent signals to the machine. Additionally, there were several sensors that I also included so that I could code the machine and move it to several positions, which allowed me to control the machine hands-free. 

The design of the first machine is shown below. 

![First Machine Design](/assets/css/images/Machine%20Designs%20-%201.png){: .my-custom-image-class}

Some pros and cons of the first machine are shown below. 

![First Machine Table](/assets/css/images/First%20Machine%20Table.png){: .my-custom-image-class}

The design of the second machine is shown below. 

![Second Machine Design](/assets/css/images/Machine%20Design%20-%202.png){: .my-custom-image-class}

The pros of the second machine are shown below.

![Second Machine Table](/assets/css/images/Second%20Machine%20Table.png){: .my-custom-image-class}

## Software

We decided to have 2 parts in the software of our machine. The first part was designing the autonomus part of the robot, and the second was having TeleOps incorporated into the software. 

## Autonomus Software

For the autonomus path, turning the robot while it was moving would be efficient, which allowed for it to save time. In order to accomplish this, we decided to use RoadRunner, a motion planning library, into our Auto code. To make RoadRunner effective, I had to include motion sensors into the machine for it to properly function. After incorporating RoadRunner, a specific location and heading can be given, and the robot moves to that position using the motion sensors without me making complicated calculations to do so. 

## TeleOps

When driving, we noticed that some parts of the machine were moving even though I had not touched the joystick. To combat this, I included a 'dead zone' on the joystick, which is the area in which the machine does nothing. I also coded preset positions for the arm of the robot, which allowed the arm to go different heights more efficiently and accurately. While picking up certain objects, I had to reduce the speed of the robot to 40%, which allowed for more precise movements overall.


## Sensors used

While building, we used 4 drive motor encoders, 1 linear slide motor encoder, 1 InHub Gryo, 1 InHub Accelerometer, and 1 Webcam. The drive motor encoders helped the machine to move into its positions, the slide motor encoder moved the arm into position,  the InHub gryo ensures that the machine turns accurately and stays straight, the accelerometer ensured that the machine accelerated properly, and the Webcam is used to scan a signal to start moving.

Some of the sensors used are shown below. 

![Drive Motor Encoder](/assets/css/images/Drive%20Metal%20Encoder.jpg){: .my-custom-image-class}
The sensor shown above is called the Drive motor encoder. It was used to move the machine around so that we could go through the mazes. 


![Linear Slide Motor Encoder](/assets/css/images/Linear%20slide%20motor%20encoder.png){: .my-custom-image-class}
The sensor shown above is called the Linear Slide Motor Encoder. It was used to move the arm up and down so that it can pick up objects.



## About Me 

I am a rising senior at North Creek High School interested in engineering. Some of my hobbies are building, playing sports, and reading books. I enjoy spending time outdoors, especially hiking and going to parks.

![Personal Image](/assets/css/images/About%20Me%20Picture.JPG){: .my-custom-image-class}


[def]: /assets/css/images/Current%20Design%20Picture.png