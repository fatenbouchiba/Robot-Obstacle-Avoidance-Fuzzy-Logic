# Autonomous Robot Control using Fuzzy Logic and LiDAR

## Project Overview
This project focuses on developing an autonomous robot control system using fuzzy logic and a LiDAR sensor for obstacle avoidance. The robot uses fuzzy logic to control its speed and steering based on real-time LiDAR data, ensuring efficient navigation and obstacle detection.

## Description
The robot, *AUIOT Autocar Prime X*, is equipped with a LiDAR sensor to map the environment and avoid obstacles. The fuzzy logic system processes the sensor data to adjust the robot's speed and steering angle, allowing for safe and smooth navigation. The robot's decision-making is based on the degree of steering (left, right, or straight) and the distance from obstacles.

## Components Used
- **LiDAR Sensor**: For obstacle detection and mapping.
- **Fuzzy Logic**: For controlling the robot's speed and steering based on environmental data.
- **AUIOT Autocar Prime X**: The robot platform used for testing the algorithm.

## How it Works
1. **LiDAR Mapping**: The LiDAR sensor scans the surroundings and detects obstacles.
2. **Fuzzy Logic Inference**: The data from the LiDAR is used to calculate the necessary actions using a fuzzy logic system.
3. **Steering & Speed Control**: Based on the inference, the robot adjusts its steering (left, right, or straight) and speed (slow or fast).

## Features
- Real-time obstacle detection and avoidance.
- Speed and steering control using fuzzy logic.
- Simple and effective decision-making algorithm based on sensor input.

## Demo
Watch the demo video of the robot in action:

![Robot Image](demo_image.jpg)  
[Demo Video](demo_video.mp4)

## Requirements
To run the project, make sure to install the following dependencies:

```bash
pip install -r requirements.txt
