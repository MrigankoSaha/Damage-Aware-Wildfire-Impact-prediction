# 🔥 Wildfire Structural Damage Prediction

This project builds a machine learning pipeline to predict **structural damage categories** (e.g., No Damage, Minor, Moderate, Major, Destroyed) caused by wildfires. By integrating **post-incident structural data** with **real-time environmental features** such as NDVI, temperature, humidity, and wind speed, this project offers an interpretable and actionable framework for disaster risk management.

---

## 📊 Overview

- **Goal:** Predict the extent of damage to structures impacted by wildfires using supervised classification.
- **Approach:** Enrich CAL FIRE inspection data with weather and vegetation indices via APIs, build and evaluate ML models (Random Forest, XGBoost, Naive Bayes).
- **Outcome:** Achieved macro F1-score of **0.48** and ROC-AUC of **0.78** with Random Forest.  
- **Bonus:** Released a fully enriched dataset with over 100,000 real-world records.

---

## 🧰 Tools & Technologies

- **Languages:** Python (pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, shap)
- **APIs Used:**  
  - [Open-Meteo API](https://open-meteo.com/) – Historical weather data  
  - [Google Earth Engine (MODIS)](https://developers.google.com/earth-engine) – NDVI extraction  
- **ML Models:** Random Forest, XGBoost, Naive Bayes  
- **Other:** SMOTE (imbalanced-learn), SHAP, GridSearchCV, ROC curves, SHAP plots

---

## Business Impact
- **Insurance: 15–25% more accurate risk pricing
- **Emergency Response: Better prioritization of high-risk zones
- **Urban Planning: Improved zoning and vegetation management
- **Real Estate: Risk-adjusted valuation for fire-prone areas

