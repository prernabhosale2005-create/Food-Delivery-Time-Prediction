 # Food Delivery Time Prediction using Machine Learning

## Project Overview

This project applies supervised machine learning techniques to analyze food delivery data and predict delivery outcomes.

Two machine learning problems are implemented:

1. **Regression** – Predict the delivery time in minutes.
2. **Classification** – Predict whether the delivery speed is Fast or Slow.

## Objectives

* Perform data preprocessing and cleaning.
* Explore the dataset using exploratory data analysis (EDA).
* Analyze relationships between delivery-related features.
* Build a Linear Regression model to predict delivery time.
* Build a Logistic Regression model to classify delivery speed.
* Evaluate both models using appropriate performance metrics.
* Visualize the classification results using a confusion matrix.

## Machine Learning Models

### 1. Linear Regression

**Problem type:** Regression

**Target variable:** `Delivery_Time_min`

Evaluation metrics:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### 2. Logistic Regression

**Problem type:** Classification

**Target variable:** `Delivery_Speed`

Classes:

* Fast
* Slow

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Workflow

```text
Data Collection
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Selection
       ↓
Data Preprocessing
       ↓
Train-Test Split
       ↓
Feature Scaling
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Results & Visualization
```

## Project Structure

```text
Food-Delivery-ML-Project/
│
├── Food_Delivery_Time_Prediction.ipynb
├── classification_predictions.csv
├── model_comparison.csv
└── README.md
```

## Results

The final model performance is reported in the Jupyter Notebook using the evaluation metrics appropriate for each machine learning task.

## Conclusion

The project demonstrates how supervised machine learning can be applied to food delivery data for both numerical prediction and categorical classification. Regression is used to estimate delivery time, while classification is used to categorize delivery speed.

## Future Scope

* Test additional regression and classification algorithms.
* Perform hyperparameter tuning.
* Use cross-validation for more reliable evaluation.
* Compare ensemble models such as Random Forest and Gradient Boosting.
* Deploy the trained model as a web application or API.
