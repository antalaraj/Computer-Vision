# Face Detection & Recognition Pipeline (Computer Vision Mini Project)

## 📌 Project Overview
This project demonstrates a complete **face detection and recognition pipeline** using classical computer vision techniques implemented in a **Jupyter Notebook (.ipynb)**.

The system captures images from a webcam, preprocesses them, performs face segmentation, extracts features using **ORB**, matches features between two images, and applies **Non-Maximum Suppression (NMS)** for final detection.

---

## 🔧 Technologies Used
- Python 3.x  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

## 🧠 Pipeline Workflow

1. Image Acquisition (Webcam)
2. Preprocessing (Grayscale, Blur, Histogram Equalization)
3. Face Segmentation (Haar Cascade + Contours)
4. Feature Extraction (ORB)
5. Feature Matching (Brute Force Matcher)
6. Classification (Area-based)
7. Non-Maximum Suppression (NMS)

---

## 🚀 How to Run (Jupyter)

### 1. Install Dependencies
```bash
pip install opencv-python numpy matplotlib jupyter
````

### 2. Launch Notebook

```bash
jupyter notebook
```

### 3. Open File

Open:

```
face-detection-pipeline.ipynb
```

Then run all cells **top to bottom**.

> Make sure your webcam is connected.

---

## 📂 Generated Output Files

| File               | Description                  |
| ------------------ | ---------------------------- |
| acquired_image.jpg | Captured webcam image        |
| preprocessed.jpg   | Preprocessed grayscale image |
| segmented.jpg      | Face segmentation result     |
| image2.jpg         | Second image for matching    |
| NMS Output         | Final detection window       |

---

## 🖼 Results Included

The notebook visualizes:

* Face segmentation
* ORB feature keypoints
* Feature matching between two images
* Final NMS bounding box

All results are displayed inline in the notebook.

---

## 🧪 Algorithms Used

### Haar Cascade

For initial face detection.

### ORB (Oriented FAST and Rotated BRIEF)

For feature extraction and matching.

### Non-Maximum Suppression

For removing overlapping bounding boxes.

---

## 📈 Learning Outcomes

* Real-time CV pipeline in Jupyter
* Feature-based face recognition
* Practical OpenCV experience
* Understanding detection vs recognition

---

## ⚠ Limitations

* Only frontal faces
* Sensitive to lighting
* Not robust for large datasets

---

## 🔮 Future Enhancements

* Use deep learning models (YOLO / MTCNN)
* Add CNN embeddings (FaceNet)
* Build recognition database
* Convert to web app

---

## 📜 License

For academic and educational purposes only.

---

## 👨‍💻 Author

**Raj Antala**
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---
