# Shape Detection using Hu Moments (OpenCV)

This project implements **shape detection and classification** using **Hu Moments and contour matching** in OpenCV.

It identifies basic geometric shapes such as:

- Circle  
- Square  
- Triangle  

using a **mathematical comparison approach** instead of machine learning.

---

## 🚀 Project Overview

The system detects shapes from an image by:

1. Preprocessing the image (grayscale, blur, threshold)
2. Extracting contours
3. Comparing each contour with **reference shapes**
4. Classifying shapes using **Hu Moments (cv2.matchShapes)**

This approach is **lightweight, fast, and explainable**, making it ideal for understanding classical computer vision.

---

## ✨ Features

- Detects multiple shapes in a single image  
- Uses **Hu Moments for shape similarity**  
- Generates **reference contours dynamically**  
- Handles noise using thresholding and filtering  
- Displays labeled shapes with similarity score  

---

## ⚙️ Technologies Used

- Python  
- OpenCV  
- NumPy  
- Matplotlib  

---

## 🛠 Installation

Install required dependencies:

```bash
pip install opencv-python numpy matplotlib
````

---

## 🧠 Key Concepts

* Contour Detection
* Hu Moments
* Shape Matching (`cv2.matchShapes`)
* Image Thresholding
* Object Localization

---

## ⚡ Algorithm Highlights

* Uses **Gaussian Blur** to reduce noise
* Applies **Binary Thresholding** for segmentation
* Filters small contours using area threshold
* Uses **CONTOURS_MATCH_I1** for precise matching
* Calculates shape center using image moments

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

