# 🦾 RTAB-Map Onboard COBRA
![ROS 2](https://img.shields.io/badge/ROS2-Humble-blue?logo=ros)
![Python](https://img.shields.io/badge/Python-3.10-yellow?logo=python)
![C++](https://img.shields.io/badge/C++-17-lightgrey?logo=cplusplus)
![Jetson Orin NX](https://img.shields.io/badge/Jetson-Orin%20NX-green?logo=nvidia)
![SLAM](https://img.shields.io/badge/RTAB--Map-SLAM-orange?logo=mapbox)

---

## 📘 Overview
This project implements **RTAB-Map SLAM** on the **COBRA (Crater Observing Bio-inspired Rolling Articulator)** robot using **ROS 2 Humble**, **Jetson Orin NX**, and **RGB-D cameras**.  
The goal is to achieve **real-time onboard mapping and localization** while validating system accuracy against **OptiTrack ground truth** in a laboratory environment.

---

## 🎯 Objectives
- Integrate RTAB-Map with COBRA’s onboard sensors for real-time SLAM.  
- Benchmark odometry accuracy against OptiTrack reference data.  
- Analyze sparse point cloud limitations in low-texture environments.  
- Propose sensor fusion improvements for enhanced mapping robustness.

---

## 🧩 System Architecture
