# Rock vs Mine Prediction using Machine Learning

## Project Overview
This project is a Machine Learning classification system that predicts whether an underwater object is a **Rock** or a **Mine** using sonar signal data.

The model is trained on the famous Sonar dataset, where each object is represented by 60 numerical sonar readings.

---

## Problem Statement
Underwater mines are dangerous for naval operations and marine transportation. Sonar systems send sound waves underwater and analyze the reflected signals to identify objects.

This project uses Machine Learning to classify:
- **R** → Rock
- **M** → Mine

based on sonar frequency data.

---

## Dataset Information
- Dataset: Sonar Dataset
- Total Features: 60
- Target Classes:
  - `R` → Rock
  - `M` → Mine

Each row contains sonar signal measurements reflected from an object.

---

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Machine Learning Workflow

### 1. Data Collection
Load the sonar dataset using pandas.

### 2. Data Preprocessing
- Handle missing values
- Label encoding
- Feature scaling using `StandardScaler`

### 3. Train-Test Split
Split the dataset into training and testing sets.

### 4. Model Training
Train the model using:
- Logistic Regression

### 5. Model Evaluation
Evaluate the model using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 6. Prediction System
Provide sonar input data to predict:
- Rock
or
- Mine

---
