# Face Detection Comparison: Haar Cascade vs MediaPipe

This project compares **classical computer vision** and **modern deep learning** approaches for face detection using:

- **Haar Cascade (OpenCV)**
- **MediaPipe Face Detection (Google)**

The system processes a video and generates a **side-by-side comparison output**, showing detection results, speed (FPS), and face count for both methods.

---

## 🚀 Project Overview

The goal of this project is to analyze:

- Detection accuracy
- Speed (FPS)
- Performance in real-world scenarios

It creates a **split-screen video** where:

- Left side → Haar Cascade  
- Right side → MediaPipe (Deep Learning)  

Each frame includes:

- Bounding boxes
- FPS (processing speed)
- Number of faces detected

---

## ✨ Features

- Real-time **video processing**
- Side-by-side comparison of two detection methods
- FPS calculation for performance analysis
- Face count tracking
- Automatic output video generation
- Works on **any input video**

---

## ⚙️ Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy

---

## 🛠 Installation

Install required dependencies:

```bash
pip install opencv-python mediapipe numpy
```

---

## 🧠 Key Concepts

* Face Detection
* Haar Cascade Classifier
* Deep Learning-based Detection (MediaPipe)
* Real-time Video Processing
* Performance Benchmarking (FPS)

---

## 📊 Comparison Summary

| Feature                | Haar Cascade             | MediaPipe     |
| ---------------------- | ------------------------ | ------------- |
| Type                   | Classical                | Deep Learning |
| Speed                  | Very Fast                | Fast          |
| Accuracy               | Moderate                 | High          |
| Robustness             | Low (lighting sensitive) | High          |
| Real-world Performance | Limited                  | Strong        |

---

## 👨‍💻 Author

Raj Antala
PGDM Student – AI & Data Science
Adani Institute of Digital Technology Management (AIDTM)
Gandhinagar, India

```
