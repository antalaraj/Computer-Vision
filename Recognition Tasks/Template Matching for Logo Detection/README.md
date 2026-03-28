# Logo Detection using SIFT & RANSAC (OpenCV)

This project detects a specific logo inside a larger image using **feature-based matching** with **SIFT (Scale-Invariant Feature Transform)** and **RANSAC-based homography estimation**.

It is robust to **scale, rotation, and perspective changes**, making it far more reliable than basic template matching.

---

## 🚀 Project Overview

The system identifies a logo in a target image by:

- Automatically **cropping the template** to remove background noise
- Extracting keypoints using **SIFT**
- Matching features using **FLANN matcher**
- Filtering matches using **Lowe’s Ratio Test**
- Estimating transformation using **RANSAC**
- Drawing the detected logo region using **perspective transformation**

---

## ✨ Features

- Automatic template cropping (removes background)  
- Robust feature detection using **SIFT**  
- Fast matching using **FLANN-based matcher**  
- Outlier removal using **RANSAC**  
- Accurate detection under:
  - Rotation  
  - Scale changes  
  - Perspective distortion  
- Visual bounding box around detected logo  

---

## ⚙️ Technologies Used

- Python  
- OpenCV  
- NumPy  
- Matplotlib  

---

## 🛠 Installation

Install dependencies:

```bash
pip install opencv-python opencv-contrib-python numpy matplotlib
```

---

## 🧠 Key Concepts

* Feature Detection (SIFT)
* Feature Matching (FLANN)
* Lowe’s Ratio Test
* Homography Estimation
* RANSAC (Outlier Rejection)
* Perspective Transformation

---

## ⚡ Algorithm Highlights

* Uses **SIFT descriptors** for scale and rotation invariance
* Applies **ratio test (0.7)** for reliable matching
* Uses **RANSAC** to eliminate incorrect matches
* Detects logo even under **geometric transformations**

---

## 👨‍💻 Author

Raj Antala
PGDM Student – AI & Data Science
Adani Institute of Digital Technology Management (AIDTM)
Gandhinagar, India


