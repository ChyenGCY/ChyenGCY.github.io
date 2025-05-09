---
title: 'Movement analysis using IMU sensors'
date: 2024-08-26T17:40:42-04:00
draft: true
jobTitle: "Movement analysis using IMU sensors"
company: "Intelligent Heart Technology Lab (I-HeaL)"
location: "Stockholm, Sweden"
duration: "Oct 2023 – Jan 2024"
companyLogo: "images/experience/KTH_logo_RGB_bla.png"
---

## IMU-Based Gait Analysis and Cardiac Synchrony  
**KTH Royal Institute of Technology – Stockholm, Sweden**  
**Research Project in Wearable Sensing and Biomechanics**  
*Skills: Sensor Fusion, Kalman Filter, Orientation Estimation, Gait Analysis*

### Introduction
Wearable sensors, especially inertial measurement units (IMUs), are widely used in rehabilitation for continuous motion and physiology monitoring. This project investigates how synchronized walking affects gait parameters and their potential relationship with cardiac cycles using a **single IMU** mounted at the pelvis, representing the center of mass (CoM).

### Key Contributions
- 🧭 Developed a **Kalman filter-based method** for orientation estimation using **Euler ZYX** angles.  
- 🧠 Derived **sensor orientation** and reconstructed **3D CoM trajectory** from accelerometer and gyroscope data.  
- 👣 Extracted **gait parameters** including:
  - Step count  
  - Cadence  
  - Average step time  
  - Step length  
- 📉 Evaluated the **displacement estimation error** using RMSE:
  - **X axis:** 0.117 m  
  - **Y axis:** 0.0064 m  
  - **Z axis:** 0.0026 m  

### Outcome
Successfully built a low-cost, single-sensor method for human gait analysis that can estimate CoM displacement and core gait metrics. This lays the foundation for real-world application in cardiac-gait synchrony studies and mobile health monitoring.

### Future Work
- Integrate and test the algorithm with **real IMU hardware**  
- Improve documentation and publish implementation details

[**Read more →**](projects/imu-gait-cardiac-synchrony.md)
