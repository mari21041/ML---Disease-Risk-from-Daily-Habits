
# Disease Risk from Daily Habits 🧠💊

# 🧠 Disease Risk from Daily Habits: Machine Learning Project

This project uses machine learning to analyze lifestyle and biometric data to predict disease risk based on daily habits. The goal is to empower individuals with insights about their health and promote preventive healthcare through intelligent data analysis.

---

## 📌 Project Summary

We use a labeled dataset containing biometric, lifestyle, environmental, and behavioral features to build a classification model that predicts whether an individual is **healthy** or at **health risk**. This project demonstrates the power of machine learning in healthcare informatics and preventive diagnostics.

---

## 📊 Dataset Overview

Data source: https://www.kaggle.com/datasets/mahdimashayekhi/disease-risk-from-daily-habits

The dataset consists of **17,577 entries** and **39 features**, including:


### 📥 Input Features:
- **Demographics:** `age`, `gender`
- **Biometrics:** `height`, `weight`, `bmi`, `waist_size`, `blood_pressure`, `heart_rate`, `cholesterol`, `glucose`, `insulin`
- **Lifestyle Habits:** `sleep_hours`, `sleep_quality`, `work_hours`, `physical_activity`, `daily_steps`, `diet_type`, `exercise_type`
- **Consumption Metrics:** `calorie_intake`, `sugar_intake`, `alcohol_consumption`, `smoking_level`, `water_intake`, `caffeine_intake`
- **Behavioral Factors:** `screen_time`, `stress_level`, `mental_health_score`, `mental_health_support`
- **Other Factors:** `job_type`, `device_usage`, `healthcare_access`, `sunlight_exposure`, `meals_per_day`, `family_history`, `pet_owner`, `environmental_risk_score`, `daily_supplement_dosage`


### 🎯 Target Feature:
- `target`: Categorical (`healthy` or `at-risk`)

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Handling missing values (e.g., `device_usage`)
   - Feature scaling
   - One-hot encoding categorical features

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Distribution plots
   - Feature importance ranking

3. **Modeling**
   - Binary classification using:
     - Logistic Regression
     - Random Forest
     - XGBoost
     - Support Vector Machine (SVM)
   - Hyperparameter tuning via GridSearchCV

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve & AUC Score


## 🗃️ Repository Structure

Disease-Risk-from-Daily-Habits/
├── data/
│ └── Clean_data.csv
├── notebooks/
│ └── --.ipynb
├── models/
│ └── ----
├── main.py
└── README.md
\


## 📌  Requirements

- Python 3.8+
- pandas, numpy, scikit-learn
- xgboost, matplotlib, seaborn, graphviz
  

## ✅  Future Enhancements:

- Multiclass classification (e.g., predict specific diseases)
- Real-time health monitoring from wearable data
- Personalized health advice with explainable AI


## ✅  Link:

- **Trello:** https://trello.com/b/pm17khhl/machine-learning

- **Presentation:** https://docs.google.com/presentation/d/1Mr0Iakry8YThLcSKHXwYkBc6evT3Mu9iT_GRbbOuapM/edit?slide=id.g373d7af2684_0_2&pli=1#slide=id.g373d7af2684_0_2

