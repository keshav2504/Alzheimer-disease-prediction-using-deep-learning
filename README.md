# 🧠 Alzheimer Disease Prediction using Deep Learning

An AI-powered medical imaging project for detecting Alzheimer’s Disease from brain MRI scans using Deep Learning techniques such as Custom CNN and VGG16 Transfer Learning.

## 📌 Project Overview

Alzheimer’s Disease is a progressive neurological disorder that affects memory, thinking ability, and daily activities. Early diagnosis plays an important role in improving treatment and patient care.

This project uses MRI brain scan images and Deep Learning models to classify patients into:

- Non-Demented
- Demented

Two deep learning approaches were implemented and compared:

- Custom CNN Model
- VGG16 Transfer Learning Model

The VGG16 model achieved significantly better performance than the custom CNN model.

# 🎯 Objectives

- Develop a Deep Learning model for Alzheimer’s disease detection.
- Compare Custom CNN and VGG16 architectures.
- Improve classification accuracy using transfer learning.
- Assist healthcare professionals with automated diagnosis.
- Reduce human error in MRI interpretation.

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Streamlit
- Jupyter Notebook

# 📂 Dataset Information

The dataset contains MRI brain scan images categorized into:

| Class | Number of Images |
|------|------------------|
| Non-Demented | 3200 |
| Demented | 2240 |

# 🔄 Data Preprocessing

The following preprocessing steps were applied:

- Image resizing to `224x224`
- RGB conversion
- Normalization
- Data augmentation
- Train-test split (70%-30%)
- Label encoding
# 🏗️ Model Architectures

## 1️⃣ Custom CNN Model

### Features
- Conv2D Layers
- MaxPooling Layers
- Dropout Regularization
- Dense Layers
- RMSprop Optimizer

### Performance
- Training Accuracy: **67.8%**
- Validation Accuracy: **52.17%**

## 2️⃣ VGG16 Transfer Learning Model

### Features
- Pretrained VGG16 Architecture
- Transfer Learning
- Fine-tuned Dense Layers
- Label Smoothing
- RMSprop Optimizer

### Performance
- Training Accuracy: **96.6%**
- Validation Accuracy: **85.17%**

✅ VGG16 outperformed the Custom CNN model and showed better generalization.

# 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1 Score
- Accuracy & Loss Curves

# 🔁 Project Workflow
Load Dataset
      ↓
Data Preprocessing
      ↓
Data Augmentation
      ↓
Train CNN / VGG16 Models
      ↓
Model Evaluation
      ↓
Prediction
     ↓
Frontend Deployment

💻 Frontend
A simple frontend interface was developed using Streamlit where users can:

Upload MRI images
Predict Alzheimer’s status
View prediction results instantly


📈 Results
Model	Accuracy
Custom CNN	52%
VGG16	85%

✅ VGG16 was selected as the final model due to its superior accuracy and stability.



<img width="701" height="712" alt="image" src="https://github.com/user-attachments/assets/5ae022c3-ab63-45e8-b300-c76a411a5a54" />

<img width="708" height="268" alt="image" src="https://github.com/user-attachments/assets/b604fc6c-3da4-458e-97d4-eca53fa81de9" />


