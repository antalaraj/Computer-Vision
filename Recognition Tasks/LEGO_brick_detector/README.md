# LEGO Brick Detection using Template Matching (OpenCV)

This project detects specific LEGO bricks inside a cluttered image using **template matching and advanced contour filtering**.

It combines **classical computer vision techniques** with **morphological processing** to accurately detect and count objects even when multiple detections overlap.

---

## 🚀 Project Overview

The system identifies occurrences of a target LEGO brick in a pile image by:

- Matching a **template image** against the main image
- Filtering detections using a confidence threshold
- Merging overlapping detections using **morphological dilation**
- Extracting final object regions using contours

It outputs:

- Detected bounding boxes
- Total brick count
- Visualization of intermediate processing steps :contentReference[oaicite:0]{index=0}

---

## ✨ Features

- Template-based object detection  
- Confidence threshold filtering  
- Overlap removal using **morphological merging**  
- Accurate object counting  
- Visualization of:
  - Original image
  - Detection mask
  - Final output  
- Optional output image saving  

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
```

---

## 🧠 Key Concepts

* Template Matching (`cv2.matchTemplate`)
* Image Thresholding
* Morphological Operations (Dilation)
* Contour Detection
* Object Localization

---

## ⚡ Algorithm Highlights

* Uses **TM_CCOEFF_NORMED** for robust matching
* Converts detections into a **center-point mask**
* Applies **dilation to merge overlapping detections**
* Filters noise using contour area threshold
* Produces clean bounding boxes for each detected object

---

## 📊 Output Visualization

The system generates three views:

1. Original image
2. Detection mask (merged regions)
3. Final detection with bounding boxes

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

