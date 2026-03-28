# Face Detection using Haar Cascade (Optimized)

This project implements **face detection using OpenCV's Haar Cascade classifier** with improved parameter tuning for better accuracy in real-world group images.

The system is optimized to detect faces even in **challenging conditions such as shadows, background faces, and varying lighting**.

---

## 🚀 Project Overview

This project demonstrates a **classical computer vision approach** to detect human faces in an image using:

- Haar Cascade Classifier
- Image preprocessing techniques
- Parameter tuning for balanced detection

The goal is to achieve **high accuracy while minimizing false positives**.

---

## ✨ Features

- Face detection using **Haar Cascade**
- Improved detection using **histogram equalization**
- Optimized parameters for better results
- Works well for **group photos**
- Draws bounding boxes around detected faces
- Simple and fast implementation

---

## ⚙️ Technologies Used

- Python
- OpenCV
- NumPy

---


## 🧠 Key Concepts

* Haar Cascade Classifier
* Image preprocessing (Grayscale + Histogram Equalization)
* Feature-based face detection
* Parameter tuning (`scaleFactor`, `minNeighbors`)

---

## ⚡ Optimization Used

The model uses a **balanced configuration**:

* `scaleFactor = 1.05` → More accurate scanning
* `minNeighbors = 6` → Reduces false positives
* Histogram Equalization → Improves detection in low-light areas

---

## 👨‍💻 Author

Raj Antala
PGDM Student – AI & Data Science
Adani Institute of Digital Technology Management (AIDTM)
Gandhinagar, India


