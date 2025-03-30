# food-calorie-estimator
AI-Powered Food Classification and Calorie Estimation using Food-101 Dataset

# 
Abdallah Waked
INFO-6147 Deep Learning with PyTorch
Dr. Mohammed Yousefhussien

## 🔥 Project Overview
This project aims to classify food images and estimate their caloric value using deep learning. We use the Food-101 dataset to train a ResNet18-based model and link the predictions to a nutritional database for calorie estimation.

---

## 📂 Dataset
- **Food-101 Dataset:** 101 food categories with 1000 images per class.
- Preprocessing: Resizing to 224x224, normalization, data augmentation.
- Splits: 70% Training, 15% Validation, 15% Test.

---

## 🧠 Model Architecture
- **Base Model:** Pre-trained ResNet18
- Modifications:
  - Final layer adjusted to 101 classes
  - Regularization: Dropout, EarlyStopping
- Loss Function: CrossEntropy
- Optimizer: Adam

---

## 📊 Evaluation Results
- Final Test Accuracy: XX%
- Precision, Recall, F1-Score provided in the report
- Confusion Matrix & GradCAM visualizations

---

## 🍽️ Calorie Estimation
Each classified food item is matched with an average caloric value stored in a JSON file.

Example Output:
## Installation
### Environment
1- craete a new env named 'food-calorie-estimator'
'''bash
python -m venv food-calorie-estimator
.\food-calorie-estimator\Scripts\activate

'''
2- Activate the env

### Install the required packages

