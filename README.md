# 🩺 Health Insurance Premium Prediction System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/downloads/)

A machine learning system that predicts health insurance premiums using demographic, medical, and lifestyle factors. Developed with best practices in ML engineering and designed for portfolio presentation.

**Live Demo:** [https://ml-project-premium-healthcare-prediction.streamlit.app/](https://ml-project-premium-healthcare-prediction.streamlit.app/)

## 🚀 Features

- **Personalized Premium Estimation:** Get tailored insurance cost predictions based on your specific profile  
- **Age-Segmented Models:** Specialized predictive models for young adults (18–25) and older populations (26+)  
- **Genetic Risk Integration:** Enhanced models that incorporate genetic risk factors for more precise predictions  
- **User-Friendly Interface:** Intuitive Streamlit web application for easy interaction  
- **Comprehensive Feature Analysis:** Evaluation of multiple factors that influence insurance costs  


## 🛠 Tech Stack

**Core ML**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%230077B5.svg?style=flat&logo=xgboost&logoColor=white)

**Web Interface**  
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=Streamlit&logoColor=white)

**Data Processing**  
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white)

# Methodology
**Data Preprocessing**
- Categorical variable encoding
- Feature scaling using StandardScaler
- Handling missing values and outliers
- Feature engineering for medical history and risk scoring

**Model Development**
- Separate models for different age groups to improve prediction accuracy
- Feature selection based on correlation analysis and VIF (Variance Inflation Factor)
- Cross-validation to ensure model robustness
- Hyperparameter tuning using GridSearchCV

**Evaluation Metrics**
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared score
- Percentage difference between predicted and actual premiums

**Model Performance**
- The system employs specialized models:
- Young Adults Model (18–25): Achieved average prediction accuracy with error margins below 15%
- General Population Model (26+): Demonstrated strong performance with error margins typically around 10%
- Enhanced Models with Genetic Risk: Further improved prediction accuracy by incorporating genetic risk factors

