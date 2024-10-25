# Botzo Documentation

Welcome to the **Botzo Project** documentation. This project aims to develop an autonomous quadruped robot designed for navigating complex terrains, collecting data and samples, and interacting with its environment. Botzo combines a sleek, modern design with practical functionality to achieve this purpose.

---

## **Project Overview**

The Botzo robot is designed with practicality, focusing on autonomous mobility and environmental interaction. Our team is actively working through multiple development phases, each dedicated to a specific aspect of Botzo’s design, hardware, and software.


## **Goals**

### Phase 1: Proposal and Circuit Design ✅

In this initial phase, we researched and selected essential components, considering:
- **Processing**: Jetson/Pi4 options
- **Actuators**: Torque capacity
- **Power Supply**: Battery requirements and converters
- **Sensors**: For environmental awareness
- **Other Components**

With a projected runtime of ~18 minutes under max load, actual tests suggest closer to ~30 minutes of operation. For more details, refer to the [Canva Board Proposal](https://www.canva.com/design/DAGQqN2k1i4/RCJst_pNSHRcbE02HOKgEw/edit?utm_content=DAGQqN2k1i4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton).


![basic_circuit](https://github.com/botzo-team/our_images_and_videos/blob/main/basic_circuit_scketch.png)

![full_circuit](https://github.com/botzo-team/our_images_and_videos/blob/main/full_circuit_scketch.png)

### Phase 2: Leg Design 🔜

Key steps include:
1. Fusion 360 Design
2. Integration of shock-absorbing dampers
3. Addition of ball bearings
4. Servo testing
5. Inverse Kinematics
6. Design of a testing rig for movement evaluation

Our leg design is inspired by a servo quadruped, focusing on optimized torque distribution and stability. More information can be found in the [Hackaday project reference](https://hackaday.io/project/171456-diy-hobby-servos-quadruped-robot/details).


![Leg Design Placeholder](https://github.com/botzo-team/our_images_and_videos/blob/main/leg_design.png)

### Phase 3: Whole Body Design

Development of a complete body framework.


### Phase 4: Inverse Kinematics

Software development of IK in 3DoF for one leg: [repo](https://github.com/botzo-team/botzo_IK)
Software development of Rotation matrices and transormations for body: [repo]()

#### future devellop

in C++ with parallelization support.

---

## **Upcoming Phases**

### Phase 5: IMU Readings Integration
Using an Inertial Measurement Unit (IMU) to provide stability data. [repo](https://github.com/botzo-team/IMU_readings)


### Phase 7: Interpolation and Trajectory Planning & Trot Gait
In this phase, the trajectory planning and a trot gait algorithm will be implemented for movement efficiency.

### Phase 8: Wireless Controller Integration

Developing wireless control capabilities.

### Phase 9: Computer Vision Algorithm

Implementing CV algorithms for object and terrain recognition.

### Phase 10: Real-time Simulation Environment

Building a real-time simulation platform for virtual testing.

### Phase 11: IMU Stabilization Algorithm
A stabilization algorithm to maintain balance.

### Phase 12: Reinforcement Learning
Applying reinforcement learning techniques for adaptive behavior.

### Phase 13: LiDAR Camera Integration
Adding depth perception with LiDAR.

### Phase 14: Robotic Arm
Designing and integrating a robotic arm for interaction.

### Phase 15: Botzo App Control Center
Creating a mobile app for Botzo's centralized control.

---

## **Improvements and Iterative Phases**

Throughout each phase, improvements will be documented and considered for additional development. For example, Phase 7’s trot gait could be optimized with faster algorithms to enhance Botzo's speed and fluidity in movement.

---

For more details, visit the project’s shared [Google Drive folder](https://drive.google.com/drive/folders/0AJJugXqFgaoEUk9PVA).

---

This document serves as an ongoing reference for Botzo’s design and development stages. Contributions and improvements are welcome.
