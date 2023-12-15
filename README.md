# Robotic Exploration with Jetson Nano
## Overview
This project focuses on using the Jetson Nano for robotic exploration, leveraging a camera and a distance sensor. The goal is to help students understand how robot sensors capture information from the world and how AI models like MobileNet and DepthNet can process this data into meaningful perception.

![DepthNet Processing](depthnet.jpg)
![Distance Sensor Plot](2D_plot.png)

## Components
![Jetbot with CSI Camera and VL53L1X Distance Sensor](jetbot.jpg)

* Jetson Nano
* Jetbot
* CSI Camera
* VL53L1X Distance Sensor


## Objectives
Understand how robots can navigate and analyze environments.
Learn to integrate hardware components (camera and distance sensor) with the Jetson Nano.
Apply AI models for data interpretation and environmental perception.

## Setup and Configuration
Hardware Setup:
Assemble the Jetbot with the Jetson Nano.
Connect the VL53L1X distance sensor and the camera to the Jetson Nano.

Software Requirements:
Python libraries: smbus2, VL53L1X, cv2, ipywidgets, traitlets, jetbot, jetson_inference, jetson_utils, numpy, matplotlib.

Sensor Calibration:
Use the VL53L1X Sensor Calibration Test.ipynb notebook to calibrate the distance sensor.

## Activity Description
The robot will move forward and spin to capture a series of images and distances from its environment.
The distances will generate a 2D polar grid of readings.
Images will be processed through DepthNet and MobileNet models to create depth maps and identify objects.
The robotic_exploration_camera_distance_data_analysis.ipynb notebook contains the code for this investigation.

## Educational Insights
Explore how robots can operate in environments unsuitable for humans.
Analyze how different sensors provide varied types of data.
Understand the application of AI in interpreting sensor data.

## Additional Resources
[PowerPoint Presentation](Robotic Exploration - Distance and Analysis - Public.pptx): Provides a detailed overview of the project, its objectives, and the technology used.
Contributing
Your contributions to improve or extend this educational activity are welcome. Please follow the standard GitHub pull request process.

