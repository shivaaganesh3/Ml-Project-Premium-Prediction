# 🩺 Health Insurance Premium Prediction System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)

A machine learning system that predicts health insurance premiums using demographic, medical, and lifestyle factors. Built with industry-standard ML engineering practices and deployed via Streamlit Cloud for real-time accessibility.

**🔗 Live Demo:** [https://ml-project-premium-healthcare-prediction.streamlit.app/](https://ml-project-premium-healthcare-prediction.streamlit.app/)

---

## 📝 Project Summary

This end-to-end ML project was developed for Shield Insurance to automate premium estimation and improve underwriting efficiency. It predicts health insurance costs based on inputs like age, BMI, smoking habits, and genetic risk. Tailored models were created for different age groups and integrated into a user-friendly Streamlit web application.

---

## 🚀 Features

- **Personalized Premium Estimation:** Tailored cost predictions based on individual health and lifestyle profiles  
- **Age-Segmented Models:** Separate models for young adults (18–25) and general population (26+) to improve accuracy  
- **Genetic Risk Integration:** Additional risk factor to enhance precision in premium prediction  
- **Streamlit Web App:** Deployed interface for real-time interaction and user-friendly predictions  
- **Comprehensive Feature Analysis:** Model explains key variables affecting premiums  

---

## 📂 Dataset

- **Source:** Simulated insurance dataset modeled after real-world distributions  
- **Features:** Age, Gender, BMI, Children, Smoking Status, Region, Genetic Risk  
- **Size:** ~1,338 records × 7+ features  
- **Preprocessing:** Missing value handling, categorical encoding, outlier detection  

---

## 🛠 Tech Stack

**Core ML & Data Tools**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%230077B5.svg?style=flat&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white)

**Web Interface**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white)

---

## ⚙️ Methodology

### 🔄 Data Preprocessing
- One-hot encoding for categorical variables (`pd.get_dummies`)
- Standardization using `StandardScaler`
- Outlier treatment using IQR method
- Feature engineering for medical history and synthetic genetic risk

### 🤖 Model Development
- Trained multiple models: Linear Regression, Ridge, Lasso, XGBoost  
- Built age-specific models for better accuracy  
- Feature selection via correlation analysis and VIF  
- Hyperparameter tuning using `RandomizedSearchCV`  
- Cross-validation with 5-fold CV for robust performance  


---

## 📊 Model Performance

| Model Variant | Target Group | Avg. Error Margin | Accuracy Notes |
|---------------|--------------|-------------------|----------------|
| Young Adults Model | Age 18–25 | < 15% | Reduced variance due to tailored features |
| General Population | Age 26+ | ~10% | Balanced performance across regions |
| Genetic Risk Model | All | Improved accuracy | Captured chronic illness risk factors |

---


