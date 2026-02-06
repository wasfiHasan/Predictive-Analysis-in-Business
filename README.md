# Calories Burned Prediction – MIS444 Project

## Project Overview

This project focuses on building and evaluating machine learning models to predict **Calories Burned** based on various physiological and activity-related features. The objective is to apply end-to-end data analytics and machine learning techniques, including data preprocessing, feature selection, model optimization, and performance evaluation.

The project was developed as part of the **MIS444** course to demonstrate practical understanding of predictive modeling and performance interpretation.


## Dataset

* **Target Variable:** `Calories_Burned`
* **Features:** Multiple numerical and categorical variables related to physical activity and personal attributes
* **Preprocessing Steps:**

  * Handling categorical variables using label encoding
  * Feature scaling using StandardScaler
  * Train–test data splitting


## Project Workflow

The notebook follows a structured machine learning pipeline:

1. **Data Loading**

   * Importing and inspecting the dataset

2. **Exploratory Data Analysis (EDA)**

   * Understanding data distributions
   * Identifying relationships between variables
   * Visual analysis using Matplotlib and Seaborn

3. **Preprocessing**

   * Encoding categorical features
   * Feature scaling
   * Preparing data for modeling

4. **Feature Selection**

   * Recursive Feature Elimination (RFE)
   * Model-based feature importance using Random Forest

5. **Model Development**
   The following regression models were implemented and compared:

   * Linear Regression
   * Decision Tree Regressor
   * Random Forest Regressor
   * Support Vector Regressor (SVR)
   * XGBoost Regressor

6. **Model Optimization**

   * Hyperparameter tuning using `RandomizedSearchCV`
   * Cross-validation for performance robustness

7. **Performance Measurement**
   Models were evaluated using:

   * Mean Squared Error (MSE)
   * Mean Absolute Error (MAE)
   * R-squared (R²)

8. **Performance Interpretation**

   * Comparison of model accuracy
   * Interpretation of feature importance
   * Selection of the best-performing model

## Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * pandas, numpy
  * matplotlib, seaborn
  * scikit-learn
  * xgboost

