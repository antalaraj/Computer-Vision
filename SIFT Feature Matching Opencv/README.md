# 🔍 SIFT Feature Matching using OpenCV

This project demonstrates how to detect and match visual features between two images using the **SIFT (Scale-Invariant Feature Transform)** algorithm and **Brute-Force Matching with Lowe’s Ratio Test**.

The implementation is provided in a **Jupyter Notebook**, making it easy to understand, visualize, and experiment with.

---

## 📌 Project Highlights
- Detects robust keypoints using SIFT
- Matches features using k-Nearest Neighbors
- Filters false matches using Lowe’s Ratio Test
- Visualizes strong correspondences between images
- Fully documented and interview-ready

---

## 🧠 Concepts Covered
- Feature Detection & Description  
- Scale & Rotation Invariance  
- Distance Metrics (Euclidean)  
- kNN Matching  
- Lowe’s Ratio Test  
- Computer Vision with OpenCV  

---

## 🛠️ Tech Stack
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## ▶️ How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/your-username/sift-feature-matching-opencv.git
cd sift-feature-matching-opencv
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the notebook

```bash
jupyter notebook
```

Open:

```
notebook/SIFT_Feature_Matching.ipynb
```

---

## 📊 Output

The notebook displays matched keypoints between two images.

Only strong matches are kept using **Lowe’s Ratio Test (threshold = 0.75)**, ensuring higher accuracy and fewer false matches.

---

## 🚀 Use Cases

* Object recognition
* Image similarity detection
* Panorama stitching
* Visual search systems
* Feature-based tracking

---

## 🔮 Future Improvements

* Add ORB for faster real-time matching
* Apply Homography to localize object in scene
* Implement real-time webcam matching
* Compare performance between SIFT and ORB

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---


