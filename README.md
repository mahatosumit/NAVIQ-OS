# NAVIQ OS 🚀

**NAVIQ OS** is a real-time, modular operating system designed for autonomous ground, aerial, and space vehicles. Built on Zephyr RTOS with ROS 2 integration, it supports hardware platforms like Raspberry Pi 5, STM32, ESP32, and Jetson Nano (companion).

## 🔧 Features
- Modular FSM-based control
- HAL for sensors like LiDAR, Load Cell, IMU
- Motor control, serial comm, SLAM-ready
- ROS 2 compatible (via Micro-ROS or native)

## 🧠 Powered By
This project is developed under [OPTINX](https://optinx.tech), a tech innovation lab.

## 📁 Structure
- `/src`: Zephyr or C++ kernel code
- `/docs`: Diagrams, architecture plans
- `/drivers`: Hardware-specific code
- `/ros2_interfaces`: ROS message files

## 📜 License
Apache 2.0
