# Medical Image Classification using Deep Learning

This project builds a **deep learning model to classify mammogram images** into three categories: **Normal, Benign, and Malignant** using **Transfer Learning with ResNet50**.

The system also uses **Grad-CAM visualization** to highlight important regions in the image that influence the model's decision.

---

## 🚀 Project Overview

This project demonstrates an **AI-based medical image analysis pipeline** that includes:

- Downloading and preparing the **MIAS mammography dataset**
- Converting images to a structured dataset
- Training a **deep learning model using transfer learning**
- Evaluating performance using **Accuracy and AUC-ROC**
- Visualizing predictions with **Grad-CAM**

The model helps understand how deep learning can assist in **breast cancer detection from medical images**. :contentReference[oaicite:0]{index=0}

---

## ✨ Features

- Automatic dataset download and preprocessing  
- Image conversion from **PGM to JPG**
- Data augmentation using **ImageDataGenerator**
- Transfer Learning with **ResNet50**
- Class imbalance handling using **class weights**
- Model evaluation with **Accuracy and AUC**
- **Grad-CAM heatmap visualization** for model interpretability

---

## 🛠 Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- ResNet50 (Transfer Learning)

---

## ⚙️ Installation

Install the required dependencies:

```bash
pip install tensorflow opencv-python numpy matplotlib
````

---

## ▶️ How to Run

1. Download and prepare the dataset automatically.
2. Train the model using the training script.
3. Test the model on a sample mammogram image.

Example test image:

```
Sample(1).jpg
```

The system will:

* Predict the class (**Normal / Benign / Malignant**)
* Display prediction confidence
* Generate a **Grad-CAM heatmap** highlighting important regions.

---

## 🧠 Concepts Covered

* Medical Image Classification
* Transfer Learning
* Data Augmentation
* Class Imbalance Handling
* Model Evaluation (AUC-ROC)
* Explainable AI (Grad-CAM)

---

## 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

