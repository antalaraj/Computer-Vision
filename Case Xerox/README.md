# OCR Compression Analysis with OpenCV

This project demonstrates how **image compression affects Optical Character Recognition (OCR)** performance using classical computer vision techniques in Python. It includes multiple experiments to analyze character extraction, reconstruction, compression quality, and safe compression decisions for text-heavy documents. 

---

## 📌 Objectives

The main goals of this project are:

* Extract characters from a document image.
* Group visually similar characters.
* Reconstruct the document using prototypes.
* Analyze the effect of **JPEG compression** on OCR.
* Measure quality using **PSNR** and **SSIM**.
* Compare **lossy vs lossless** compression.
* Build a rule-based OCR and evaluate accuracy.
* Decide whether a document should be compressed safely.

---

## 🛠️ Technologies Used

* Python 3
* OpenCV
* NumPy
* Matplotlib
* scikit-image

---

## 📂 Input

The system works on a grayscale scanned document:

```
document.png
```

---

## 🔍 Task Breakdown

### Task 1 – Character Extraction & Reconstruction

* Convert image to binary.
* Detect connected components.
* Resize each character to 20×20.
* Group similar symbols using MSE.
* Reconstruct full image from prototypes.

Result: ~26 unique symbol groups detected.

---

### Task 2 – Compression Quality Analysis

Images are compressed at different JPEG qualities:

| Quality | PSNR  | SSIM  |
| ------- | ----- | ----- |
| 90      | 45.15 | 0.995 |
| 70      | 38.54 | 0.973 |
| 50      | 37.53 | 0.957 |
| 30      | 36.67 | 0.942 |

Also visualized:

* Edge maps using Canny detection.
* Structural degradation with lower quality.

---

### Task 3 – Lossy vs Lossless Comparison

* Save document as:

  * `doc_lossless.png`
  * `doc_lossy.jpg`
* Perform pixel-wise difference.
* Detect corruption regions.

---

### Task 4 – Rule-Based OCR System

A simple OCR classifier based on:

* Vertical strokes
* Horizontal strokes
* Hole detection

Accuracy:

| Image Type | Accuracy |
| ---------- | -------- |
| Original   | 92%      |
| Compressed | 92%      |

---

### Task 5 – Safe Compression Decision System

Uses three metrics:

* Shannon Entropy
* Edge Density
* Connected Components

Final output example:

```
Entropy: 0.45  
Edge Density: 0.061  
Connected Components: 239  
Final Decision: NO COMPRESSION  
Reason: Critical document (forms / fine lines)
```

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install opencv-python numpy matplotlib scikit-image
```

2. Place your document image:

```bash
document.png
```

3. Run the notebook or script step by step.

---

## 📊 Key Learnings

* JPEG compression degrades fine text edges.
* OCR accuracy drops mainly due to shape distortion.
* Lossless compression is preferred for:

  * Scanned forms
  * Legal documents
  * Printed text
* Edge density is a strong indicator of OCR risk.

---

## 🎯 Use Cases

* OCR preprocessing pipelines
* Document digitization systems
* Compression-aware scanners
* Computer vision coursework
* Research on image quality metrics

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

Passionate about Computer Vision and Intelligent Systems

---


