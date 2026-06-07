# Yoga Pose Recognition Using Deep Learning

## Project Overview

This project develops an automated yoga pose recognition system using deep learning techniques. The objective is to classify yoga poses from images and compare the performance of a Custom CNN, MobileNetV2, and ResNet50.

The project is implemented using TensorFlow and Keras and includes explainable AI techniques such as Grad-CAM and SHAP for model interpretation.

---

## Dataset

**Dataset:** 47 Yoga Pose Detection Dataset

Dataset Link:
https://www.kaggle.com/datasets/gendubali/47-yoga-pose-detection

### Dataset Statistics

* Number of Classes: 47
* Total Images: 59759
* Image Type: RGB Images (.jpg, .png)
* Input Size: 224 × 224 × 3

---

## Methodology

1. Dataset Collection
2. Data Preprocessing
3. Image Resizing and Normalization
4. Data Augmentation
5. Train / Validation / Test Split
6. Custom CNN Development
7. MobileNetV2 Transfer Learning
8. ResNet50 Transfer Learning
9. Model Training
10. Model Evaluation
11. Performance Comparison

---

## Models Used

### Custom CNN

A custom Convolutional Neural Network developed as a baseline model.

### MobileNetV2

A lightweight transfer learning model initialized with ImageNet weights.

### ResNet50

A deep residual network utilizing transfer learning for improved classification performance.

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## Explainable AI

The project includes:

* Grad-CAM Visualizations
* SHAP Explanations

These techniques help understand how the models make predictions.

---

## Results

| Model       | Accuracy |
| ----------- | -------- |
| Custom CNN  | 64.31%   |
| MobileNetV2 | 94.65%   |
| ResNet50    | 95.40%   |

ResNet50 achieved the highest classification accuracy and overall performance.

---

## Repository Structure

```text
proposal/
notebooks/
figures/
outputs/
requirements.txt
README.md
```

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Kaggle Notebook

https://www.kaggle.com/code/anishkhobragadee/notebookml2

---

## Author

Anish Dadaji Khobragade

Master of Science in Data Science

University of Europe for Applied Sciences
