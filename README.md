# Potato Disease Detection Using CNN

## Overview

Potato Disease Detection is a deep learning-based computer vision project that identifies diseases in potato leaves using Convolutional Neural Networks (CNNs). The system classifies potato leaf images into different disease categories and helps in early detection of crop diseases to improve agricultural productivity.

This project uses image processing and machine learning techniques to automatically detect whether a potato leaf is healthy or infected.

---

# Features

* Automatic potato leaf disease detection
* CNN-based image classification
* Image preprocessing and augmentation
* Model training and evaluation
* Disease prediction from uploaded images
* User-friendly implementation
* High accuracy disease classification
* Easy to extend for more crop diseases

---

# Problem Statement

Potato crops are highly affected by diseases such as:

* Early Blight
* Late Blight
* Healthy Leaves

Manual disease detection requires agricultural experts and can be time-consuming. This project automates the detection process using Artificial Intelligence and Deep Learning.

---

# Objectives

* Detect potato leaf diseases automatically
* Reduce dependency on manual inspection
* Improve crop monitoring efficiency
* Provide fast and accurate predictions
* Apply CNN in real-world agriculture problems

---

# Dataset

The dataset contains images of potato leaves categorized into:

1. Potato___Early_blight
2. Potato___Late_blight
3. Potato___healthy

## Dataset Structure

```bash
Potato-Disease-Detection/
│
├── training/
│   ├── Potato___Early_blight/
│   ├── Potato___Late_blight/
│   └── Potato___healthy/
│
├── validation/
│   ├── Potato___Early_blight/
│   ├── Potato___Late_blight/
│   └── Potato___healthy/
```

Dataset Source:

* PlantVillage Dataset

---

# Technologies Used

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| TensorFlow       | Deep Learning Framework |
| Keras            | CNN Model Building      |
| OpenCV           | Image Processing        |
| NumPy            | Numerical Operations    |
| Matplotlib       | Visualization           |
| Jupyter Notebook | Development Environment |

---

# System Architecture

```text
Input Image
     ↓
Image Preprocessing
     ↓
CNN Model
     ↓
Feature Extraction
     ↓
Classification Layer
     ↓
Disease Prediction
```

---

# CNN Model Workflow

1. Image Collection
2. Data Preprocessing
3. Data Augmentation
4. CNN Model Creation
5. Model Training
6. Validation
7. Testing
8. Prediction Generation

---

# Image Preprocessing

The following preprocessing techniques are applied:

* Image resizing
* Normalization
* Noise reduction
* Data augmentation
* Label encoding

---

# Data Augmentation

Data augmentation improves model performance by generating modified versions of images.

Techniques used:

* Rotation
* Zoom
* Horizontal Flip
* Vertical Flip
* Rescaling

---

# Model Architecture

The CNN model includes:

* Convolution Layers
* ReLU Activation
* Max Pooling Layers
* Flatten Layer
* Dense Layers
* Dropout Layer
* Softmax Output Layer

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/potato-disease-detection.git
```

## Navigate to Project

```bash
cd potato-disease-detection
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

Create a `requirements.txt` file with:

```txt
tensorflow
keras
numpy
opencv-python
matplotlib
scikit-learn
jupyter
pandas
```

---

# How to Run

## Run Training File

```bash
python train.py
```

## Run Prediction

```bash
python predict.py
```

---

# Sample Prediction Flow

```text
Upload Potato Leaf Image
        ↓
Preprocessing
        ↓
CNN Model Prediction
        ↓
Display Disease Name
```

---

# Output Classes

| Class        | Description                            |
| ------------ | -------------------------------------- |
| Early Blight | Fungal disease affecting potato leaves |
| Late Blight  | Serious disease causing leaf decay     |
| Healthy      | Healthy potato leaf                    |

---

# Model Evaluation Metrics

The following metrics are used:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

# Expected Results

* Accurate disease classification
* Faster prediction time
* Improved crop disease management
* Reduced manual effort

---

# Advantages

* Fast disease detection
* High accuracy
* Low manual effort
* Easy deployment
* Useful for smart agriculture

---

# Limitations

* Requires quality images
* Performance depends on dataset size
* Limited to trained diseases only

---

# Future Enhancements

* Mobile application integration
* Real-time disease detection
* Multi-crop disease detection
* IoT-based smart farming integration
* Cloud deployment
* Web-based interface

---

# Applications

* Smart Agriculture
* Crop Monitoring
* Precision Farming
* Agricultural Research
* Disease Surveillance Systems

---

# Screenshots

## Training Accuracy

Add screenshots here:

```bash
screenshots/training_accuracy.png
```

## Prediction Output

```bash
screenshots/prediction_output.png
```

---

# Folder Structure

```bash
Potato-Disease-Detection/
│
├── dataset/
├── training/
├── validation/
├── models/
├── screenshots/
├── train.py
├── predict.py
├── requirements.txt
├── README.md
└── notebook.ipynb
```

---

# Research & Concepts Used

* Deep Learning
* Convolutional Neural Networks
* Computer Vision
* Image Classification
* Artificial Intelligence
* Data Augmentation

---

# Learning Outcomes

Through this project, the following concepts were learned:

* CNN architecture design
* Deep learning model training
* Image preprocessing techniques
* Dataset handling
* Model evaluation
* Computer vision applications

---

# Reviewer Checklist

This project includes:

* Problem statement
* Clear objectives
* Dataset explanation
* CNN implementation
* Training workflow
* Prediction system
* Evaluation metrics
* Proper documentation
* Future scope
* Real-world application
* Folder structure
* Installation steps
* Requirements file
* Clean code structure

---

# Conclusion

The Potato Disease Detection project demonstrates how Deep Learning and CNNs can be used in agriculture to automatically detect plant diseases. The system helps farmers and researchers by providing quick and accurate disease identification, reducing crop damage and improving productivity.

---

# Contributors

* Anushka Chauhan
* Team Members

---

# License

This project is for educational and research purposes.

---

# Contact

For queries or collaboration:

* GitHub: [https://github.com/anushkachauhan234](https://github.com/anushkachauhan234)

---

# Star the Repository

If you found this project useful, give it a star on GitHub.
