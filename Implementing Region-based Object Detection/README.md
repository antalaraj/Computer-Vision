# Faster R-CNN Object Detection Pipeline

This project demonstrates how to perform **real-time object detection on an image using a pre-trained Faster R-CNN model with a ResNet50 backbone** from TensorFlow Hub. The system detects objects, draws bounding boxes with confidence scores, and saves the final visualized output. 

---

# 📌 Project Overview

Object detection is a key task in **Computer Vision** that involves identifying and locating objects within an image.

This project uses a **production-grade Faster R-CNN model** trained on the **COCO dataset** to automatically detect objects in an image and visualize the results. 

The pipeline includes:

* Image preprocessing
* Running inference using Faster R-CNN
* Bounding box extraction
* Confidence score filtering
* Visualization and saving results

---

# 🚀 Features

* Pre-trained **Faster R-CNN (ResNet50 backbone)**
* Automatic **Region Proposal Network (RPN)**
* Built-in **Non-Maximum Suppression (NMS)**
* Confidence score filtering
* Bounding box visualization
* Saves final detection result image

The system automatically scans the image and highlights detected objects with bounding boxes and confidence percentages.

---

# 🖼 Example Output

The model detects objects and draws bounding boxes with confidence scores.

Example detection result:

* Green boxes represent detected objects
* Percentage indicates prediction confidence
* The output image is automatically saved after detection

*(Example shown in the project output image where multiple objects are detected and labeled.)*

---

# ⚙️ Requirements

Install required dependencies:

```bash
pip install tensorflow tensorflow_hub opencv-python numpy matplotlib
```

---

# 📂 Project Structure

```
Faster-RCNN-Object-Detection
│
├── detect.ipynb
├── object.jpg
├── real_detection_output.jpg
└── README.md
```

---

# ▶️ How to Run

1. Place an image named **`object.jpg`** in the project directory.

2. Run the script:

```bash
python detect.ipynb
```

3. The program will:

* Load the pre-trained Faster R-CNN model
* Scan the image for objects
* Draw bounding boxes with confidence scores
* Save the final output as:

```
real_detection_output.jpg
```

---

# 🔍 How It Works

### 1. Model Loading

The script loads a **Faster R-CNN ResNet50 model from TensorFlow Hub**, trained on the COCO dataset. 

### 2. Image Preprocessing

* Image is read using OpenCV
* Converted from **BGR → RGB**
* Converted to TensorFlow tensor format

### 3. Object Detection

The image is passed through the model which automatically performs:

* Region Proposal Network (RPN)
* ROI Align
* Non-Maximum Suppression (NMS)

### 4. Visualization

* Bounding boxes are drawn around detected objects
* Confidence scores are displayed
* Final result is saved as an image

---

# 🛠 Technologies Used

* Python
* TensorFlow
* TensorFlow Hub
* OpenCV
* NumPy
* Matplotlib

---

# 🎯 Learning Outcomes

This project demonstrates important **Deep Learning and Computer Vision concepts**:

* Object Detection using Faster R-CNN
* Region Proposal Networks (RPN)
* Bounding box extraction
* Confidence threshold filtering
* Visualization of detection results
* Using pre-trained models from TensorFlow Hub

---

# 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj


---