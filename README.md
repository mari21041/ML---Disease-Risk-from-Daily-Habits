
# Disease Risk from Daily Habits 🧠💊

# 🧠 Disease Risk from Daily Habits: Machine Learning Project

This project uses machine learning to analyze lifestyle and biometric data to predict disease risk based on daily habits. The goal is to empower individuals with insights about their health and promote preventive healthcare through intelligent data analysis.

---

## 📌 Project Summary

We use a labeled dataset containing demographic, lifestyle, physiological, and psychological features to build a classification model that predicts whether an individual is **healthy** or **diseased**. This project demonstrates the power of using machine learning in healthcare and diagnosis prevention.

---

## 📊 Dataset Overview

Data source: https://www.kaggle.com/datasets/mahdimashayekhi/disease-risk-from-daily-habits

The dataset consists of **100,000 entries** and **48 features**, including:


### 📥 Input Features:
- **Demographics:** `age`, `gender`
- **Biometrics:** `height`, `weight`, `bmi`, `waist_size`, `blood_pressure`, `heart_rate`, `cholesterol`, `glucose`, `insulin`
- **Lifestyle Habits:** `sleep_hours`, `sleep_quality`, `work_hours`, `physical_activity`, `daily_steps`, `diet_type`, `exercise_type`
- **Consumption Metrics:** `calorie_intake`, `sugar_intake`, `alcohol_consumption`, `smoking_level`, `water_intake`, `caffeine_intake`
- **Behavioral Factors:** `screen_time`, `stress_level`, `mental_health_score`, `mental_health_support`
- **Other Factors:** `job_type`, `device_usage`, `healthcare_access`, `sunlight_exposure`, `meals_per_day`, `family_history`, `pet_owner`, `environmental_risk_score`, `daily_supplement_dosage`


### 🎯 Target Feature:
- `target`: Categorical (`healthy` or `diseased`)

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Dropping irrelevant columns
   - Handling missing values (e.g., `device_usage`)
   - Feature scaling
   - One-hot encoding categorical features

2. **Exploratory Data Analysis (EDA)**
   - Box plots
   - Chi-square test
   - Two samples T-test
   

3. **Modeling**
   - Binary classification using:
     - Logistic Regression
     - Decision Tree
     - Random Forest

4. **Optimization**
   - Balancing data: 
      - Overfitting 
      - Underfitting 
      - SMOTE
   - VIF (Variance Inflation Factor)   

5. **Evaluation**
   - Accuracy, Precision, MAE, MRSE 
   

## 📌  Requirements

- Python 
- pandas, numpy, scikit-learn
- matplotlib, seaborn
- sklearn, imblearn
- scipy.stats
- statsmodels (VIF)
  

## ✅  Future Enhancements:

- Fine-tunning of features for a more accurate model
- Multiclass classification (e.g., predict specific diseases)
- Real-time health monitoring from wearable data
- Personalized health advice with explainable AI


## ✅  Link:

- **Presentation:** https://docs.google.com/presentation/d/1Mr0Iakry8YThLcSKHXwYkBc6evT3Mu9iT_GRbbOuapM/edit?slide=id.g924297ca04_0_1464#slide=id.g924297ca04_0_1464

Data source: https://www.kaggle.com/datasets/mahdimashayekhi/disease-risk-from-daily-habits

