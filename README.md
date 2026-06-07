# AI-Based Coconut Harvesting Machine

## Overview

An AI-powered coconut harvesting system that automatically detects mature coconuts using Computer Vision and triggers a harvesting mechanism through an ESP8266-controlled robotic platform.

## Features

- Real-time coconut detection using TensorFlow Lite
- ESP32-CAM live video streaming
- MediaPipe Object Detection
- Automatic harvesting mechanism
- Dual servo control
- Motorized movement
- IoT dashboard control using KiwisIoT
- Relay-based cutting mechanism

## Hardware Used

- ESP8266 NodeMCU
- ESP32-CAM
- Servo Motors
- L298N Motor Driver
- Relay Module
- DC Motors
- Battery Pack

## Software Used

- Arduino IDE
- Python
- OpenCV
- MediaPipe
- TensorFlow Lite

## Working Principle

1. ESP32-CAM streams live video.
2. Python model detects mature coconuts.
3. Detection signal sent to ESP8266 via HTTP.
4. ESP8266 stops movement.
5. Servo positions harvesting arm.
6. Relay activates cutting mechanism.
7. Harvesting operation completes automatically.

## Results

Successfully detected mature coconuts and triggered automatic harvesting action.

## Future Improvements

- Depth estimation
- Autonomous navigation
- Edge AI deployment on ESP32
- Multiple fruit detection
