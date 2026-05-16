# Vision-Based Pick and Place

## Overview

This project implements a vision-based pick-and-place pipeline using MATLAB and RoboDK.

A UR5e robot equipped with a camera detects colored objects, estimates their pose, and performs autonomous pick-and-place operations inside a simulated robotic workcell.

The project was developed as part of a university laboratory exercise in robotics and computer vision. :contentReference[oaicite:0]{index=0}

---

## Features

- Camera-based object detection
- Color segmentation
- Pose estimation
- Image processing pipeline
- Homography-based coordinate transformation
- RoboDK robot simulation
- Autonomous block stacking

---

## Technologies

- MATLAB
- RoboDK
- Machine Vision Toolbox
- Image Processing Toolbox

---

## System Workflow

1. Capture image from camera
2. Detect colored objects
3. Extract object position and orientation
4. Convert image coordinates to world coordinates
5. Compute grasp pose
6. Execute pick-and-place sequence in simulation

---

## Implemented Topics

### Image Processing
- Thresholding
- Blob detection
- Histogram analysis
- Morphological filtering
- Brightness adaptation

### Robotics
- Coordinate transformations
- Homography
- Pose estimation
- Pick-and-place sequencing

### Simulation
- RoboDK integration
- UR5e robot simulation
- Camera simulation
- Object manipulation

---

## Notes

This repository is based on a provided university framework and laboratory setup.

The following parts were mainly predefined:
- simulation environment,
- robot cell setup,
- general processing structure,
- base MATLAB scripts,
- RoboDK integration framework.

The image processing adaptation, threshold tuning, detection logic, pose extraction, debugging, and system adjustments were implemented and modified by myself.

The purpose of this project is to document practical experience with:
- industrial robotics workflows,
- robot vision systems,
- MATLAB-based image processing,
- simulation-driven robotics development.

---

## Related Topics

- Computer Vision
- Robotics
- Pick and Place
- Pose Estimation
- Image Processing
- RoboDK
- MATLAB

---

## Reference

THWS laboratory exercise:
"Vision-Based Pick and Place – Instruction Manual for Student Lab Exercise" :contentReference[oaicite:1]{index=1}
