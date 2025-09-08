# ❤️ Heart Disease Prediction

## 📌 Overview
This project predicts the likelihood of **heart disease** in patients using machine learning.  
It is based on the **UCI Heart Disease Dataset (1988)**, which has been widely used for medical research.  

The dataset originally contains **76 attributes**, but most research and this project use the **14 most relevant features**.  
The target variable indicates:
- `0` → No Heart Disease
- `1` → Heart Disease Present

---

## 📊 Dataset
- Source: UCI Machine Learning Repository  
- Databases: Cleveland, Hungary, Switzerland, Long Beach V  
- Attributes: 14 selected clinical features (age, sex, chest pain type, blood pressure, cholesterol, etc.)  
- Target: Binary classification (0 = healthy, 1 = heart disease)

---

## ⚙️ Features Used
Some of the key attributes include:
- **age** → Age of patient  
- **sex** → Gender (1 = male, 0 = female)  
- **cp** → Chest pain type  
- **trestbps** → Resting blood pressure  
- **chol** → Serum cholesterol (mg/dl)  
- **fbs** → Fasting blood sugar > 120 mg/dl  
- **restecg** → Resting electrocardiographic results  
- **thalach** → Maximum heart rate achieved  
- **exang** → Exercise-induced angina  
- **oldpeak** → ST depression induced by exercise  
- **slope** → Slope of peak exercise ST segment  
- **ca** → Number of major vessels colored by fluoroscopy  
- **thal** → Thalassemia  
- **target** → 0 (no disease) / 1 (disease)  

---

## 🚀 Tech Stack
- **Python**  
- **NumPy, Pandas** (data processing)  
- **Matplotlib, Seaborn** (visualization)  
- **Scikit-learn** (ML models: Logistic Regression, Random Forest, SVM, etc.)  
- **Jupyter Notebook** for experimentation  

---

## 📈 Model Training
- Preprocessing: Handling missing values, feature scaling, and encoding categorical variables.  
- Models Implemented:
  - Logistic Regression  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - K-Nearest Neighbors (KNN)  
- Evaluation: Accuracy  

---
