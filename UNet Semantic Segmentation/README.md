# Semantic Segmentation with U-Net

This repository contains implementations of the **U-Net architecture** for pixel-level semantic segmentation tasks. It demonstrates how to adapt the network depth for different dataset sizes, from single medical images to large standard datasets.

## 📂 Project Overview

| Architecture | Task | Dataset | Description |
| :--- | :--- | :--- | :--- |
| **Mini U-Net** | Brain Tumor Segmentation | Custom MRI (`my_image.jpg`) | A lightweight, 2-level U-Net optimized for small data samples. |
| **Standard U-Net** | Pet Segmentation | [Oxford-IIIT Pet](https://www.tensorflow.org/datasets/catalog/oxford_iiit_pet) | A full 4-level U-Net trained to segment pets from backgrounds. |



## 🛠️ Features
* **Architecture Implementation:** Custom Keras implementation of U-Net blocks (Encoder, Decoder, Bottleneck).
* **Loss Function:** Dice Coefficient Loss to handle class imbalance (e.g., small tumors vs. large background).
* **Data Pipeline:**
    * **Manual:** OpenCV-based loading and thresholding for custom MRI scans.
    * **Automated:** TensorFlow Datasets (TFDS) pipeline for the Oxford Pets dataset.

## 🚀 Installation & Usage

### Prerequisites
* Python 3.x
* TensorFlow 2.x
* OpenCV
* Matplotlib
* TensorFlow Datasets

```bash
pip install tensorflow opencv-python matplotlib tensorflow-datasets
```

---

## 👨‍💻 Author

**Raj Antala**
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---
