# Facial Recognition System with Emotion Detection

This project implements a **Face Recognition and Emotion Detection System** using Deep Learning and Computer Vision.  
It detects faces in images, recognizes known individuals, and estimates **happiness levels** using emotion analysis.

---

## 🚀 Project Overview

The system performs the following tasks:

- Detect faces using **OpenCV DNN Face Detector**
- Extract facial embeddings using a **custom FaceNet-style model**
- Compare faces using **cosine distance**
- Recognize known individuals from a database
- Analyze facial emotions using **DeepFace**

The model can also process **group photos**, detect multiple faces, and display identity with emotion scores.

---

## ✨ Features

- Face detection using **OpenCV Deep Learning model**
- Face embeddings using **FaceNet-style CNN**
- **Multi-face recognition** in group photos
- **Emotion detection (Happiness score)**
- Automatic bounding boxes and labels on detected faces
- Visualization using **Matplotlib**

---

## 🛠 Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib
- DeepFace
- Scikit-learn

---

## ⚙️ Installation

Install the required dependencies:

```bash
pip install tensorflow opencv-python numpy matplotlib scikit-learn deepface
````

---

## ▶️ How to Run

1. Place your test image in the project folder.

Example:

```
group_photo.jpg
```

2. Run the script:

```bash
python main.py
```

3. The system will:

* Detect all faces in the image
* Recognize registered users
* Display bounding boxes with identity and happiness score

---

## 🧠 Concepts Covered

* Face Detection
* Face Recognition
* Siamese Networks
* Face Embeddings
* Cosine Similarity
* Emotion Detection

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

