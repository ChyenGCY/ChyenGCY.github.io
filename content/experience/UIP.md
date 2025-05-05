---
title: 'Motion capture for rehabilitation'
date: 2024-08-26T17:38:13-04:00
draft: true
jobTitle: "Motion capture for rehabilitation"
company: "Brain-robot Rehabilitation Lab"
location: "Shenzhen, China"
duration: "April 2022 – May 2024"
companyLogo: "images/experience/mmzlab.png"
---

## UWB-IMU Fusion Motion Capture System for Rehabilitation  
**Southern University of Science and Technology – Shenzhen, China**  
**Undergraduate Innovation Project**  
*Skills: Sensor Fusion, Embedded Systems, Deep Learning, Human Pose Estimation*

### Introduction
As motion capture technology expands in medical applications, this project proposes a cost-effective and portable system for full-body motion tracking using **IMU and UWB fusion**. The goal is to support continuous rehabilitation assessment with high precision across diverse environments, overcoming the cost and complexity of commercial systems.

### Key Contributions
- 🧠 Designed a **wearable sensor network** combining **Ultra-Wideband (UWB)** and **Inertial Measurement Units (IMUs)** with **long battery life** and **anti-magnetic interference**.  
- 📡 Developed a **communication protocol** using UWB for real-time, multi-node IMU data transmission.  
- 🔧 Implemented a **sensor fusion pipeline** using **Kalman filtering** and **complementary filters** for accurate positioning and orientation.  
- 🕺 Built a **pose estimation pipeline** using an **RNN neural network** trained on the **DIP-IMU dataset** and fine-tuned with simulated noise.  
- 💡 Introduced **LOS/NLOS classification** to improve UWB accuracy in obstructed environments.  
- 🧪 Achieved **3D pose estimation** with RMSE of **4.6 cm** in position and outperformed baseline models in accuracy.

### Outcome
The project completed two design iterations:
1. **System prototype** with real-time visualization and OpenSim integration.
2. **Sensor fusion and neural network-based pose estimation**, achieving **state-of-the-art accuracy** on benchmark datasets.

The system shows strong potential for at-home rehabilitation and scalable healthcare technology.

### Future Work
- Improve **NLOS signal classification** for enhanced UWB accuracy.  
- Collect **real-world UWB-IMU datasets** for further training and validation.  
- Optimize the neural network architecture for real-time inference.

[**Read more →**](projects/uwb-imu-rehab-motion-capture.md)