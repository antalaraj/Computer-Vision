# Image Stitching & Panorama Creation

This project explores different techniques for creating panoramic images from overlapping photos using **classical computer vision methods and deep learning approaches**.

## 🚀 Overview

The project compares three stitching pipelines:

- **Manual Classical Pipeline** using ORB feature detection, feature matching, RANSAC homography, and perspective warping.
- **OpenCV Stitcher** using the built-in `cv2.Stitcher` for fast and optimized panorama generation.
- **Deep Learning Approach** using **LoFTR (Vision Transformer)** for robust feature matching in challenging scenes.

## 🛠 Features

- ORB feature detection and matching  
- RANSAC-based homography estimation  
- Cylindrical warping for wide panoramas  
- Seamless image blending  
- Deep learning feature matching with LoFTR  
- Automatic cropping and panorama cleanup  

## ⚙️ Requirements

Install dependencies:

```bash
pip install opencv-python opencv-contrib-python numpy matplotlib torch kornia
````

## ▶️ How to Run

1. Place overlapping images in `images/panorama_set/`
2. Run the notebook or script
3. The pipeline will generate a stitched panorama image.

## 🧠 Concepts Covered

* Feature detection and matching
* Homography estimation
* Cylindrical projection
* Image warping and blending
* Vision Transformer based matching

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj


