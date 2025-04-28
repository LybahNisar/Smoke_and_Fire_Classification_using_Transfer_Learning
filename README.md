# Smoke and Fire Classification using Transfer Learning

This project focuses on classifying images into two categories: **Smoke** and **Fire**, using deep learning and transfer learning techniques. We use EfficientNetB0 as a pre-trained model, perform fine-tuning, and visualize performance through evaluation metrics and graphs.

## 🧠 Project Highlights

- **Problem**: Binary classification of images into "Smoke" or "Fire"
- **Dataset**: Custom dataset organized into train/test folders
- **Preprocessing**:
  - Image resizing to 224x224
  - Normalization
  - Label encoding
- **Visualization**:
  - Class distribution
  - Sample images

## 📦 Techniques Used

- Transfer Learning with **EfficientNetB0**
- Feature Extraction and Fine Tuning
- Partial Layer Freezing
- Data Augmentation (optional)
- Model Evaluation: Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- Deployment Phase: Prediction on unseen images

---

## 🛠 Libraries and Frameworks

- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- OpenCV

---


## 📊 Key Features
- Train a deep learning model using EfficientNetB0.

- Fine-tune pre-trained models on a custom Smoke/Fire dataset.

- Evaluate performance using:

- Accuracy

- Precision

- Recall

- Confusion Matrix

- Classification Report

---
## 📈 Model Performance

Metric	Value
Test Accuracy           	~76.0%
Precision (Fire)         	1.0000
Recall (Fire)            	0.5200
Precision (Smoke)       	0.6757
Recall (Smoke)	          1.0000
----
## 📸 Sample Outputs
- Training and Validation Accuracy/Loss Curves

- Confusion Matrix Visualization

- Classification Report

- Predictions on Unseen Images
