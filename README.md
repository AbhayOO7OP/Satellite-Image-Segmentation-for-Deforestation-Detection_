## 🌍 Satellite Image Segmentation for Deforestation Detection
## 📌 Overview
This project focuses on deforestation detection using satellite image segmentation techniques. It employs K-Means, Mean Shift, and Hierarchical Clustering to segment images and identify deforested areas. The results contribute to environmental conservation by providing insights for decision-makers and researchers.

## 🏆 Key Features
📡 Satellite Image Segmentation to monitor forest loss
🏗 Clustering Algorithms (K-Means, Mean Shift, Hierarchical)
📊 Performance Evaluation using Intersection over Union (IoU)
🌲 Real-World Dataset (2013-2024, Chandrapur region)
🛠 Python & OpenCV-based Implementation

## 🛠 Methodology
The project applies three clustering techniques:

## 1️⃣ K-Means Clustering
Groups pixels based on color similarity
Identifies deforested areas using pixel intensity analysis

## 2️⃣ Mean Shift Clustering
Detects spatially cohesive clusters
Assumes lower green intensity represents deforestation

## 3️⃣ Hierarchical Clustering
Constructs a tree-like structure for segmentation
Effective for small-scale deforestation analysis

## 📊 Results
K-Means: Detected 183.5 sq. meters deforested in 2023

Mean Shift: Identified 258.25 sq. meters

Hierarchical Clustering: Found minor deforestation changes

## 🚀 Installation & Usage
Prerequisites
Python 3.x
Jupyter Notebook
OpenCV, NumPy, Matplotlib, Scikit-Learn

## 📜 Conclusion
This project provides an automated approach for detecting deforestation using unsupervised clustering techniques. The results help track forest loss over time and contribute to environmental conservation efforts.
