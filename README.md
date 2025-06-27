<h1 align="center">🩺 Diabetes Prediction using K-Nearest Neighbors (KNN)</h1>

<p align="center">
  A simple machine learning project that predicts whether a person is diabetic or not based on health data using the K-Nearest Neighbors algorithm.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat-square&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4C8CBF?style=flat-square&logo=seaborn&logoColor=white"/>
</p>

---

## 📌 About the Project

This project uses the **K-Nearest Neighbors (KNN)** algorithm to predict whether a patient is likely to have diabetes or not. The model is trained on real medical data such as glucose level, blood pressure, BMI, and age.  
KNN is a simple, non-parametric algorithm that classifies data points based on their similarity to other points (neighbors).

---

## 🧠 How KNN Works

KNN works by:
1. Choosing a number `K`.
2. Measuring distance between the new data point and all training points.
3. Picking the K closest neighbors.
4. Making a prediction based on the majority class of those neighbors.

---

## 📊 Dataset Used

- **Dataset**: Pima Indians Diabetes Dataset
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
- **Target**: Outcome (1 = Diabetic, 0 = Not Diabetic)

---

## 🚀 What This Project Does

- Loads and explores diabetes dataset  
- Cleans and preprocesses data  
- Splits data into training and testing sets  
- Trains a KNN classifier  
- Evaluates model using accuracy score and confusion matrix  
- Visualizes results using Seaborn & Matplotlib
