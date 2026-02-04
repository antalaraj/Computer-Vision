# Harris & FAST Corner Detection (Computer Vision Notebook)

## 📌 Overview
This repository contains an interactive **Jupyter Notebook** that demonstrates
classical feature detection techniques in Computer Vision using:

- **Harris Corner Detector**
- **FAST (Features from Accelerated Segment Test)**

The notebook explores both:
- **Single-scale detection**
- **Multi-scale detection (Image Pyramid)**

with additional analysis on:
- Rotation invariance  
- Non-Maximum Suppression (NMS)  
- Feature stability across scales  

---

## 🧠 What This Notebook Covers

### 1. Improved Harris Corner Detection
- Gradient-based corner detection
- Optimized structure tensor
- Score-based filtering
- Non-Maximum Suppression

### 2. Improved FAST Corner Detection
- Manual implementation of FAST logic
- Bright/Dark segment testing
- Score calculation
- Clustering removal using NMS

### 3. Rotation Invariance Test
- Image rotated by 45°
- Feature stability comparison
- Visual validation

### 4. Multi-Scale Feature Detection
- Image pyramid construction
- Detection at multiple resolutions
- Mapping back to original image
- Circle size encodes feature scale

---

## 🖼 Visual Output

The notebook generates rich visualizations including:

- 🔴 Red circles → Harris corners  
- 🟢 Green circles → FAST corners  
- Larger circles → Coarser-scale features  

All plots are embedded directly in the notebook.

---

## ⚙️ Requirements

Install dependencies:

```bash
pip install numpy opencv-python matplotlib scipy
````

---

## 🚀 How to Run

### Option 1: Run Locally

```bash
jupyter notebook
```

Open:

```
Harris_FAST_Corner_Detection.ipynb
```

### Option 2: Run Online

* Upload directly to **Google Colab**
* Or view interactively on GitHub

No setup required for viewing.

---

## 📂 Repository Structure

```
.
├── Harris_FAST_Corner_Detection.ipynb
├── chess-board.jpg   (optional test image)
└── README.md
```

If no image is provided, the notebook automatically generates
a synthetic chessboard for demonstration.

---

## 🎯 Key Concepts Demonstrated

* Feature detection fundamentals
* Scale-space theory
* Rotation invariance
* Non-Maximum Suppression
* Practical OpenCV + SciPy usage

---

## 👨‍💻 Author

**Raj Antala** 
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---


