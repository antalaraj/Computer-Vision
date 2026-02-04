# Real-Time Face & Eye Detection using OpenCV

## 📌 Project Overview

This project demonstrates a **real-time face and eye detection system** using OpenCV and Haar Cascade classifiers.
The system captures live video from a webcam, detects human faces, and then detects eyes within each face region.

It is a classic **computer vision application** used in:

* Face recognition systems
* Biometric authentication
* Surveillance systems
* Human-computer interaction

---

## 🚀 Features

* Real-time webcam processing
* Face detection using Haar Cascades
* Eye detection inside face regions
* Histogram equalization for better accuracy
* Live bounding boxes for visualization
* Keyboard-controlled exit (`q` key)

---

## 🛠️ Technologies Used

* **Python 3**
* **OpenCV (cv2)**
* Haar Cascade Classifiers

---

## 📂 Project Structure

```
real_time_face_eye_detection.ipynb
README.md
```

---

## ⚙️ Installation

Install required dependency:

```bash
pip install opencv-python
```

---

## ▶️ How to Run

### Option 1: Run as Jupyter Notebook

Open the notebook and run all cells.

### Option 2 (Recommended): Run as Python Script

For best real-time performance:

```bash
python real_time_face_eye_detection.py
```

---

## 🧠 How It Works

1. Webcam captures frames continuously
2. Frame converted to grayscale
3. Histogram equalization improves contrast
4. Haar cascade detects faces
5. ROI (Region of Interest) used to detect eyes
6. Bounding boxes drawn on detected regions
7. Output shown in real-time window

---

## 📸 Sample Output

* Blue rectangle → Face
* Green rectangle → Eyes

(Real-time output shown on webcam window)

---

## ❗ Important Notes

* Press **`Q`** to exit the camera window
* Must run in **GUI-enabled environment**
* Will not work inside headless notebooks or remote servers

---

## 🎓 Learning Outcomes

After completing this project, you understand:

* Real-time video processing
* Haar Cascade detection
* ROI-based detection
* OpenCV GUI handling
* Webcam integration

---

## 👨‍💻 Author

**Raj Antala** 
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---
