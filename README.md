# Real-Time Headcount Tracking System

[![OpenCV](https://img.shields.io/badge/OpenCV-5.0-green)](https://opencv.org/)
[![YOLOv10](https://img.shields.io/badge/YOLO-v10-blue)](https://github.com/ultralytics/ultralytics)
[![Python](https://img.shields.io/badge/Python-3.11%2B-yellow)](https://www.python.org/)

A computer vision system for real-time people counting and movement analysis using webcam/IP cameras.

![System Demo](image.png)

## Features

- 👥 Real-time person detection using YOLOv10
- 📈 Dynamic headcount tracking with entry/exit direction
- 🖥️ Interactive OpenCV-based visualization
- 📊 Movement trend analysis (Entering/Exiting)
- 🎥 Multi-camera support (Webcam/IP/HDMI)
- 🚨 Visual alerts for crowd density changes

## Installation

### Prerequisites
- Python 3.11+
- Webcam/IP Camera
- NVIDIA GPU (Recommended for better performance)

# Clone repository
git clone https://github.com/SahilPatil-codes/Real-Time-Headcount-Tracking-System.git

graph TD
    A[Video Input] --> B[Frame Capture]
    B --> C[YOLOv10 Inference]
    C --> D[Person Detection]
    D --> E[Movement Analysis]
    E --> F[Visualization]
    F --> G[Display Output]

