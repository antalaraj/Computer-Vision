# CNN Padding and Stride Impact Visualizer

A deep learning experiment that demonstrates how **padding (`valid`, `same`) and stride (`1`, `2`) affect Convolutional Neural Networks (CNNs)** in terms of **feature map size, parameter count, training time, and accuracy** using the **MNIST dataset**.

This project also provides **visualization of feature maps** to understand how convolution operations process image data.

---

# 📌 Project Overview

Convolutional Neural Networks rely heavily on **hyperparameters such as padding and stride**, which influence:

* Output feature map dimensions
* Number of model parameters
* Training speed
* Model accuracy

This project runs multiple CNN configurations and compares their results using **performance metrics and visualizations**.

The experiment evaluates four configurations:

| Configuration | Padding | Stride |
| ------------- | ------- | ------ |
| Valid         | valid   | 1      |
| Same          | same    | 1      |
| Valid         | valid   | 2      |
| Same          | same    | 2      |

---

# 🚀 Features

* CNN experiment on **MNIST dataset**
* Comparison of **4 CNN architectures**
* Automatic **performance summary table**
* Visualization of **feature maps**
* Training time and accuracy analysis
* Clean **Matplotlib visualization dashboard**

---

# 📊 Experiment Results

Example output from the experiment:

| Config           | Output Dim | Params | Time (s) | Accuracy |
| ---------------- | ---------- | ------ | -------- | -------- |
| Valid | Stride 1 | 26x26      | 54410  | 4.14     | 0.9611   |
| Same | Stride 1  | 28x28      | 63050  | 4.22     | 0.9649   |
| Valid | Stride 2 | 13x13      | 11850  | 3.57     | 0.9381   |
| Same | Stride 2  | 14x14      | 16010  | 3.71     | 0.9410   |

### 🔎 Key Observations

* **Same padding preserves spatial dimensions**
* **Stride 2 reduces feature map size**
* Lower stride generally improves **accuracy**
* Higher stride reduces **parameters and training time**

---

# 🖼 Visualization

The project generates a **Matplotlib dashboard** showing:

* Original MNIST digit
* Feature map activations from CNN filters
* Differences caused by padding and stride

This helps visualize **how CNN filters detect patterns in images**.

---

# 📂 Project Structure

```
CNN-Padding-Stride-Visualizer
│
├── cnn_experiment.ipynb
└── README.md
```

---

# ⚙️ Installation

Install the required dependencies:

```bash
pip install tensorflow numpy matplotlib pandas
```

---

# ▶️ How to Run

1. Open the notebook:

```
cnn_experiment.ipynb
```

2. Run all cells.

The notebook will:

1. Load the **MNIST dataset**
2. Train CNN models with different configurations
3. Print a **performance comparison table**
4. Display a **visualization dashboard**

---

# 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib

---

# 🎯 Learning Outcomes

This project helps understand:

* CNN architecture design
* Impact of **stride and padding**
* Feature map visualization
* Model performance comparison
* Practical experimentation with deep learning

---

# 👨‍💻 Author

Raj Antala  
🎓 PGDM Student in AI and Data Science  
🏫 Adani Institute of Digital Technology Management (AIDTM)  
📍 Gandhinagar, India  
📧 antalaraj214@gmail.com  
🔗 www.linkedin.com/in/antalaraj

---