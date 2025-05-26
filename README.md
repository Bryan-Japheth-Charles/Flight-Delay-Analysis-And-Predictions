# ✈ Flight Delay Prediction and Classification Project

This project explores the causes and patterns of flight delays using exploratory data analysis (EDA), interactive Tableau dashboards, and machine learning models. The goal is to predict the arrival delay duration (`arr_delay`) and classify whether a flight was significantly delayed (`arr_del15`), using various linear and non-linear models.

---

## 📊 Exploratory Data Analysis (EDA)

Comprehensive EDA was conducted to understand the distribution and relationships between key features such as:

- Flight carrier
- Airport
- Monthly and seasonal delay trends
- Delay causes (weather, carrier, NAS, etc.)

---

## 📈 Interactive Dashboards (Tableau)

Created insightful visualizations across three key categories:

- **Seasonal and Monthly Analysis**  
  Trends in delays over different months and seasons.

- **Airport Analysis**  
  Delay statistics for different airports.

- **Carrier Analysis**  
  Performance of individual carriers in terms of delay frequency and severity.

---

## 🔁 Regression Models (Predicting `arr_delay`)

### Linear Models
- Linear Regression
- Lasso Regression (L1 regularization)
- Ridge Regression (L2 regularization)

### Non-Linear Models
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN) Regressor

---

## 🔀 Classification Models (Predicting `arr_del15`)

`arr_del15` was converted into a binary target:  
- `0` for flights delayed ≤ 15 minutes  
- `1` for flights delayed > 15 minutes

Models used:  
- Logistic Regression  
- Random Forest Classifier  
- Decision Tree Classifier  

---

## ✅ Model Evaluation and Validation

Applied multiple validation and evaluation techniques to ensure performance and prevent overfitting:

- Cross-Validation (CV)  
- R² Score (for regression)  
- Root Mean Squared Error (RMSE)  
- F1 Score (for classification)  
- Confusion Matrix  
- Precision & Recall Scores  

---

## ⚠ Limitations

Due to limited hardware specifications, I was unable to implement grid search or random search for hyperparameter tuning. I also could not experiment with more computationally intensive models such as XGBoost, SVM, or neural networks. Future work will explore these techniques on higher-spec hardware.

---

