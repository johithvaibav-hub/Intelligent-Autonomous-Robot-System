# Intelligent Autonomous Mobile Robot Using ROS2 and YOLOv8

## Overview

This project presents an Intelligent Autonomous Mobile Robot capable of:

- Real-time Object Detection using YOLOv8
- Obstacle Avoidance
- Autonomous Navigation
- SLAM Mapping
- IMU-based Orientation Estimation
- LiDAR-based Environment Perception

The system is developed using ROS2 running on Jetson Nano and integrates LiDAR, IMU, camera, and motor control modules.

---

## Hardware Components

- Jetson Nano
- ESP32
- LiDAR Sensor
- BNO085 IMU
- USB Camera
- L298N Motor Driver
- DC Geared Motors
- Battery Pack

---

## Software Stack

- Ubuntu 22.04
- ROS2 Humble
- Python
- OpenCV
- YOLOv8
- SLAM Toolbox
- RViz2

---

## System Architecture

Camera → YOLOv8 → Object Detection

LiDAR → SLAM Toolbox → Mapping

IMU → Orientation Estimation

ROS2 → Navigation Decision

ESP32 → Motor Control

---

## Features

### Object Detection

Detects:

- Person
- Bottle
- Chair
- Laptop
- Cell Phone
- Backpack
- Cup
- Book

using YOLOv8.

### Mapping

Creates real-time maps using LiDAR and SLAM Toolbox.

### Navigation

Avoids obstacles and moves autonomously.

### Localization

Uses IMU and LiDAR data for orientation and localization.

---

## Results

### SLAM Mapping

(Add Screenshot Here)

### Object Detection

(Add Screenshot Here)

### Robot Hardware

(Add Robot Image Here)

---

## Future Improvements

- Multi-room navigation
- Voice commands
- Dynamic path planning
- AI task execution

---

## Author

Johith Vaibav
