# 🚀 Jet Image Classification using CNN

A deep learning-based approach for classifying high-energy physics jet images 
using Convolutional Neural Networks.

---

## 📌 Project Overview

In high-energy particle collisions, jets deposit energy in calorimeters.
These energy deposits can be represented as 2D images.

This project uses CNNs to:
- Automatically extract spatial features
- Classify jets into binary categories
- Analyze model performance using physics-aware metrics

---

## 🧠 Methodology

1. Data Normalization
2. CNN Feature Extraction
3. Binary Cross Entropy Loss
4. Adam Optimization
5. Regularization (Dropout + L2)
6. Evaluation Metrics (Accuracy, Precision, Recall, F1)

---

## 📊 Model Architecture

Conv → ReLU → MaxPool  
Conv → ReLU → MaxPool  
Fully Connected → Sigmoid  

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/jet-image-classification-cnn.git
cd jet-image-classification-cnn
pip install -r requirements.txt
