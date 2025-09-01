# rainfall-prediction-ml
Final project for a Machine Learning course. Predicting rainfall in Melbourne using Random Forest and Logistic Regression with scikit-learn pipelines and GridSearchCV.
# Rainfall Prediction Classifier 🌧️

This repository contains my **final project** from the Machine Learning course.  
The goal was to build and evaluate a classifier to predict whether it will rain today in Melbourne, Australia, using historical weather data.

## Project Overview
- **Dataset:** Weather observations from the Australian Bureau of Meteorology (subset: Melbourne, MelbourneAirport, Watsonia).
- **Target:** `RainToday` (Yes/No).
- **Techniques:**
  - Data preprocessing with `scikit-learn` Pipelines.
  - Handling categorical and numerical variables (One-Hot Encoding + Scaling).
  - Model training with **Random Forest** and **Logistic Regression**.
  - Hyperparameter optimization with **GridSearchCV**.
  - Model evaluation using Accuracy, Balanced Accuracy, Confusion Matrix, Precision, Recall, and Feature Importances.

## Results
- **Random Forest Classifier**
  - Accuracy: ~84%
  - Recall (Rain): ~49%
- **Logistic Regression**
  - Accuracy: ~83%
  - Recall (Rain): ~51%
- **Most important feature:** `Sunshine`

## Key Learnings
- How to design and use machine learning pipelines.
- Importance of hyperparameter tuning and validation.
- Trade-offs between model types (Random Forest vs Logistic Regression).
- Handling imbalanced datasets with balanced accuracy and decision thresholds.

---

📌 File included:
- `FinalProject_AUSWeather.ipynb` → full notebook with preprocessing, training, evaluation, and conclusions.
