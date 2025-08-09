---
layout: default
title: TitanBot Robotics Project!
nav_order: 4
permalink: /pages/sensors
---

## Sensors Used

While building, we used 4 drive motor encoders, 1 linear slide motor encoder, 1 InHub Gryo, 1 InHub Accelerometer, and 1 Webcam. The drive motor encoders helped the machine to move into its positions, the slide motor encoder moved the arm into position,  the InHub gryo ensures that the machine turns accurately and stays straight, the accelerometer ensured that the machine accelerated properly, and the Webcam is used to scan a signal to start moving.

For our camera detection, we learned how to detect the signal cone using our webcam. We started off using TensorFlow as this was the most common method for sensing the cone. We learned after League 1 that there were too many factors that affected this like brightness and intensity of light. We then learned from online videos about April Tags. April Tags are simple black-and-white images that look like QR codes. After implementing this we noticed that this was much easier for our robot to sense as outside factors had nearly no effect on the webcam sensing the signal cone.

<p class="center-text">Some of the sensors used are shown below.</p> 

![Drive Motor Encoder](/assets/css/images/Drive%20Metal%20Encoder.jpg){: .my-custom-image-class}
<p class="center-text">The sensor shown above is called the Drive motor encoder. It was used to move the machine around so that we could go through the mazes.</p> 


![Linear Slide Motor Encoder](/assets/css/images/Linear%20slide%20motor%20encoder.png){: .my-custom-image-class}
<p class="center-text">The sensor shown above is called the Linear Slide Motor Encoder. It was used to move the arm up and down so that it can pick up objects.</p>

