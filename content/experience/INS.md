---
title: 'A Portable Inertial Navigation System for Total Hip Arthroplasty Targeting Direct Anterior Approach'
date: 2024-08-26T17:35:30-04:00
draft: true
jobTitle: "Inertial navigation system for surgeries"
company: "Brain-robot Rehabilitation Lab"
location: "Shenzhen, China"
duration: "Feb 2022 – Oct 2023"
---

This paper presents a novel inertial measurement unit (IMU)-based navigation system designed to enhance the precision of total hip arthroplasty (THA) surgeries, specifically targeting the Direct Anterior Approach (DAA).

## Key Features and Innovations

  * **DAA-Targeted Design:** The system is tailored to meet the unique requirements of DAA surgeries, which have gained popularity due to their potential for faster patient recovery.
  * **Accurate Acetabular Prosthesis Placement:** The system aims to improve the accuracy of acetabular prosthesis placement, which is crucial for the success of THA surgeries.
  * **Cost-Effective and Portable:** Compared to conventional technologies like computed tomography (CT), this system offers a more cost-effective and portable solution.
  * **Comprehensive Hardware and Software Design:** The system includes two sensor modules (on-body and on-handle), along with integrated circuitry, housing, data transmission capabilities, and visualization software.
  * **High Accuracy and Reliability:** The system has demonstrated high accuracy (RMSE of 1.24° for radiographic anteversion and 1.89° for radiographic inclination) and reliability in experimental evaluations.
  * **Negligible Sensor Drift:** The system exhibits minimal sensor drift, measured to be less than 0.13°/min, ensuring consistent and stable measurements during surgery.

## Potential Impact

This innovative system has the potential to significantly improve the precision and efficiency of THA surgeries, leading to better patient outcomes. Its portability, cost-effectiveness, and accuracy make it a promising alternative to traditional navigation technologies.

## System Architecture

The architecture of the proposed system, as shown in Fig. 1(c), is principally divided into two core components: the body module and the on-handle module.

*Fig. 1: Overall scheme of THA surgeries via DAA. (c) Utilization of our system with the location of the sensor in the plastic model.*

The body module precisely tracks the patient's body rotation, while the on-handle module measures the rotation of the cup impact handle. The system incorporates a single-axis gyroscope and a nine-axis IMU to measure pelvic rotation and track the motion of the cup impact handle.

## Hardware System

The hardware design of the proposed system involves two integral modules: an on-body module and an on-handle module. Both modules share common features including power modules, a microcontroller unit (MCU), and a sensor module.

*Fig. 3: Proposed navigation system architecture and system usage. (a) PCB board of the on-handle module and the 3-D housing model. (c) PCB board of the on-body module and the 3-D housing model.*

The on-body module uses the WitMotion HWT101, focusing on Z-axis rotation. The on-handle module uses the HWT905 nine-axis IMU sensor to accurately measure pitch and yaw angles.

## Software System

The inertial-based measuring system comprises two sensor modules, a lower machine for data processing, and a visual feedback module. The system includes a self-designed Wi-Fi charging base and a Unity program for real-time visualization of the RI, RA angles, and pelvic rotation.

## Experimental Design and Data Analysis

The experimental design aimed to validate the system at both the sensor and system levels through two sets of experiments: sensor validation and model simulation.

*Fig. 5: Schematics of the experimental design and data analysis flow. (a) Experimental protocol of sensor validation. (b) Experimental protocol of model simulation.*

For sensor validation, the fundamental properties of the sensors were assessed, including their static and dynamic accuracy, stability, and drift. For model simulation, a plastic model and an operational handle were used to simulate a realistic surgical environment for system-level validation.

## Model Simulation Setup

A plastic model was mounted on a horizontal plane, and a socket joint was attached to the hip joint. The system modules were attached to the model pelvis and the cup impact handle. The experiment involved controlled movements of the handle and rotations of the model pelvis.

*Fig. 6: Experimental scene with the pelvis model and our sensor unit under OMC environment.*