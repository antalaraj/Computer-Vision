# Real-Time Object Detection with YOLOv8

This repository hosts an automated computer vision pipeline for **Real-Time Object Detection**. It leverages the state-of-the-art **YOLOv8 (You Only Look Once)** architecture to identify and localize objects in video streams with high speed and accuracy.

## 📂 Project Overview

The project is designed to take raw video footage as input and generate an annotated output video with bounding boxes around detected objects (e.g., people, cars, signs).

| Component | Specification |
| :--- | :--- |
| **Model** | Ultralytics YOLOv8 Nano (`yolov8n.pt`) |
| **Task** | Object Detection & Localization |
| **Input** | MP4 Video File |
| **Output** | Annotated MP4 Video |



## 🛠️ Features
* **High-Speed Inference:** Uses the "Nano" version of YOLOv8, optimized for real-time performance on standard hardware (CPUs/GPUs).
* **Automated Pipeline:** Handles video loading, frame-by-frame processing, annotation, and video encoding automatically.
* **Robust Annotation:** Draws clear bounding boxes with class labels and confidence scores.

## 🚀 Installation & Usage

### Prerequisites
* Python 3.x
* Ultralytics
* OpenCV

```bash
pip install ultralytics opencv-python
