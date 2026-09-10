---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

Below are selected projects and demos that illustrate my work in autonomy, robotics, and perception. Each section includes a short technical summary and a link to a demo video or CAD model.

---

## Project ARES — Autonomous Docking & Safety-Critical GNC

**Demo:** [![Project ARES](https://img.youtube.com/vi/rvvRkMmm3tA/0.jpg)](https://youtu.be/rvvRkMmm3tA)

**Overview:**  
Autonomous 6-DOF docking system designed to explore robust proximity operations and safety-critical guidance, navigation, and control.

**Technical Summary:**  
- Implemented a Lyapunov-based safety layer to enforce stability constraints during approach.  
- Evaluated robustness via Monte Carlo trials under sensor noise, drift, and actuator uncertainty.  
- Focused on maintaining convergence and safety under perception uncertainty and stochastic disturbances.

**Keywords:** docking, GNC, Lyapunov safety, robustness, proximity operations.

---

## TurtleBot3 Navigation — SLAM + AMCL + Nav2

**Demo:** [YouTube](https://youtu.be/gd0OGeUqW24)

**Overview:**  
Full-stack navigation pipeline on a TurtleBot3 platform in dynamic indoor environments.

**Technical Summary:**  
- Used SLAM and AMCL for localization and mapping.  
- Integrated Nav2 for path planning and obstacle avoidance.  
- Achieved high success rates in environments with moving obstacles and partial occlusions.

**Keywords:** SLAM, AMCL, Nav2, mobile robotics, navigation.

---

## Dense 3D Perception Pipeline

**Demo:** [YouTube](https://youtu.be/SDDUo-M2lAQ)

**Overview:**  
Dense 3D perception system using stereo depth and point clouds for environment understanding.

**Technical Summary:**  
- Built stereo-based depth estimation and point cloud generation.  
- Processed 3D data for obstacle representation and scene understanding.  
- Designed the pipeline to support downstream planning and control modules.

**Keywords:** stereo vision, depth estimation, point clouds, 3D perception.

---

## Multi-Sensor Fusion & Tracking (EKF + JPDA/MHT)

**Demo:** [YouTube](https://youtu.be/WRZVafBsNlI)

**Overview:**  
Multi-target tracking and sensor fusion pipeline for cluttered environments.

**Technical Summary:**  
- Implemented EKF-based fusion across multiple sensors.  
- Used JPDA/MHT-style logic for data association and track management.  
- Focused on track consistency and robustness under clutter and partial observations.

**Keywords:** sensor fusion, EKF, tracking, JPDA, MHT.

---

## Julia CV — Multi-Camera Computer Vision Workflow (NSF I-Corps)

**Demo:** [YouTube](https://youtu.be/DRghkLMc4aI)

**Overview:**  
NSF-backed computer vision workflow platform with multi-camera support for real-world inspection and analysis.

**Technical Summary:**  
- Developed multi-camera capture and processing pipelines.  
- Integrated CV models for detection and analysis across multiple viewpoints.  
- Focused on deployable, maintainable workflows for applied computer vision.

**Keywords:** computer vision, multi-camera, NSF I-Corps, workflow automation.

---

## Vanguard Node — Robotic Arm & Fixture CAD

**Model:** [Onshape CAD](https://cad.onshape.com/documents/29647b7642c6a92852f9c141/w/e913651535f8bf12c2ff7bff/e/1da40a6cccc6e58797d24128)

**Overview:**  
Mechanical design and CAD for a robotic arm fixture and node used in autonomous manipulation and testing.

**Technical Summary:**  
- Designed mechanical fixtures and arm interfaces in Onshape.  
- Considered workspace, reachability, and mounting constraints.  
- Supported integration with control and perception stacks for manipulation tasks.

**Keywords:** CAD, robotic arm, mechanical design, fixtures.

---

## Embedded ML & Real-Time Inference Demo

**Demo:** [YouTube](https://youtu.be/UvIVTmqDgEk)

**Overview:**  
Embedded ML deployment for real-time inference in a robotics context.

**Technical Summary:**  
- Deployed ML models using TensorRT or similar acceleration frameworks.  
- Optimized inference latency for real-time control and perception loops.  
- Demonstrated end-to-end integration from model to embedded deployment.

**Keywords:** embedded ML, TensorRT, real-time inference, robotics.

---

If you’d like a detailed CV or additional technical documentation, please reach out via the contact information on the home page.
