# 🛣️ Highway Congestion & Speed Analytics

A robust, classical Computer Vision pipeline designed to analyze highway traffic congestion, track vehicle speeds in km/h, and detect stopped vehicles—built entirely without the use of heavy Deep Learning models.

This project demonstrates a strong foundational understanding of computer vision mathematics, object tracking, and spatial transformation.

## ✨ Key Features
* **Centroid Tracking Mechanism:** Assigns unique IDs to moving vehicles across consecutive frames, logging their historical trajectory and filtering out micro-jitter.
* **Mathematical Speed Calculation:** Calculates true real-world speed (km/h) using displacement calculus over a smoothed 15-frame window.
* **Perspective Transformation (Homography):** Converts 2D camera angles into a Top-Down "Bird's Eye" view to calculate mathematically accurate real-world distances, eliminating perspective distortion.
* **Advanced Background Subtraction (MOG2):** Isolates moving objects using strict shadow rejection (thresholding) and morphological filtering (Opening/Closing) to prevent overlapping bounding boxes.
* **Real-Time Congestion Detection:** Automatically flags and highlights vehicles whose smoothed trajectory drops below 3.0 km/h as "STOPPED".

## 🧠 Technical Architecture

To accurately measure speed from a 2D video, the pipeline translates pixel movement into physical meters. 

1. **Object Detection:** The `MOG2` subtractor separates foreground vehicles from the static highway background. Shadows are aggressively filtered out.
2. **Bird's Eye View Warp:** A predefined trapezoidal Region of Interest (ROI) on the road is warped into a perfect 2D rectangle. 
3. **Tracking & Calculus:** The system tracks the centroid $(x, y)$ of a vehicle. The distance formula is applied to the warped coordinates to find displacement over time ($\Delta d / \Delta t$).

## ⚙️ Installation & Setup

### Requirements
* Python 3.8+
* OpenCV (`opencv-python`)

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj
