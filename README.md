# Food Delivery Time Prediction Using Supervised Learning

## 1. Problem Statement

Food delivery time is an important factor in customer satisfaction and efficient delivery operations. The delivery time can be affected by various factors such as distance, preparation time, traffic conditions, weather, vehicle type, and other delivery-related attributes.

The objective of this project is to analyze a publicly available food delivery dataset using statistical analysis and supervised machine learning techniques.

This project addresses two related problems:

* **Regression:** Predict the estimated food delivery time in minutes.
* **Classification:** Classify the delivery as **Fast** or **Slow** based on the available delivery information.

The project demonstrates the application of data preprocessing, exploratory data analysis, statistical concepts, supervised learning, and model evaluation using Python.

---

## 2. Dataset Description

### Dataset Source

The project uses a **secondary dataset** obtained from Kaggle, a publicly available platform for datasets and data science resources.

Source: Kaggle 
Dataset: Food Delivery Time Prediction
Number of Observations: 5,000

### Dataset Information

| Property               | Description                   |
| ---------------------- | ----------------------------- |
| Dataset                | Food Delivery Time Prediction |
| Number of observations | 5,000                         |
| Data type              | Secondary data                |
| Programming language   | Python                        |
| Learning type          | Supervised Learning           |
| Regression target      | `Delivery_Time_min`           |
| Classification target  | `Delivery_Speed`              |
| Classification classes | Fast, Slow                    |

The dataset contains information related to food delivery and the factors that may influence delivery time and delivery speed.

### Target Variables

#### Regression Target

`Delivery_Time_min`

This target represents the estimated delivery time in minutes.

#### Classification Target

`Delivery_Speed`

This target categorizes deliveries into:

* **Fast**
* **Slow**

---

## 3. Data Preprocessing

The dataset was inspected and prepared before applying machine learning algorithms.

The preprocessing steps included:

* Loading the dataset using Pandas.
* Checking the number of rows and columns.
* Inspecting data types.
* Checking for missing values.
* Identifying numerical and categorical variables.
* Handling categorical variables using appropriate encoding techniques.
* Separating features and target variables.
* Splitting the data into training and testing sets.
* Applying feature scaling to numerical variables where required.
* Checking the processed dataset before model training.

These preprocessing steps help ensure that the dataset is in a suitable format for machine learning.

---

## 4. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the structure and characteristics of the dataset.

The analysis included:

### Statistical Analysis

* Mean
* Median
* Standard deviation
* Minimum and maximum values
* Quartiles
* Frequency distributions

### Visualizations

The project uses suitable visualizations such as:

* Histograms
* Box plots
* Count plots
* Distribution plots
* Correlation analysis
* Confusion matrix

EDA was used to identify patterns, distributions, relationships between variables, and possible unusual observations before building the models.

---

## 5. Model Building

Since this is a supervised learning project, two models were developed for two different prediction tasks.

### 5.1 Linear Regression

**Problem type:** Regression

**Target variable:** `Delivery_Time_min`

Linear Regression was used to predict the numerical delivery time in minutes.

The model was trained using the training dataset and evaluated on previously unseen test data.

---

### 5.2 Logistic Regression

**Problem type:** Classification

**Target variable:** `Delivery_Speed`

Logistic Regression was used to classify deliveries into two categories:

* Fast
* Slow

The classification model was trained using the processed training data and evaluated using the test dataset.

---

## 6. Model Evaluation

Different evaluation measures were used according to the type of machine learning problem.

### Regression Evaluation

The Linear Regression model was evaluated using:

* **Mean Absolute Error (MAE)** – measures the average absolute difference between actual and predicted delivery time.
* **Mean Squared Error (MSE)** – measures the average squared prediction error.
* **Root Mean Squared Error (RMSE)** – represents the prediction error in the same unit as delivery time.
* **R² Score** – indicates how well the model explains the variation in the target variable.

### Classification Evaluation

The Logistic Regression model was evaluated using:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **Confusion Matrix**

The confusion matrix was used to examine correct and incorrect predictions for the Fast and Slow classes.

---

## 7. Interpretation

The regression model provides predicted delivery times based on the available features in the dataset.

The classification model predicts whether a delivery belongs to the Fast or Slow category.

The evaluation metrics provide different perspectives on model performance. For classification, accuracy indicates the overall proportion of correct predictions, while precision, recall, and F1-score provide additional information about the quality of classification.

The confusion matrix provides a visual representation of actual versus predicted delivery categories.

The detailed numerical results and visualizations are available in the Jupyter Notebook.

---

## 8. Conclusion

This project demonstrates the application of supervised learning to a food delivery dataset using Python.

The project followed the complete machine learning workflow:

**Data → Preprocessing → EDA → Feature Preparation → Model Building → Evaluation → Interpretation**

Two supervised learning approaches were implemented:

1. **Linear Regression** for predicting delivery time.
2. **Logistic Regression** for classifying delivery speed.

The project helped demonstrate how statistical analysis and machine learning techniques can be applied to a real-world dataset to obtain meaningful predictions.

### Limitations

Some limitations of the project include:

* The results depend on the quality and representativeness of the available dataset.
* Only selected supervised learning algorithms were implemented.
* Model performance may be improved through hyperparameter tuning and additional feature engineering.
* The dataset represents historical/secondary data and may not capture all real-world factors affecting delivery time.

---

## 9. Future Scope

The project can be extended by:

* Comparing additional regression algorithms.
* Comparing additional classification algorithms.
* Applying cross-validation.
* Performing hyperparameter tuning.
* Performing additional feature engineering.
* Using ensemble learning methods such as Random Forest and Gradient Boosting.
* Deploying the final model as a web application or API.

---

## 10. Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

---

## 11. Project Structure

```text
Food-Delivery-Time-Prediction/
│
├── Food_Delivery_Time_Prediction.ipynb
├── Food_Delivery_Time_Prediction.csv
├── classification_predictions.csv
├── model_comparison.csv
└── README.md
```

---

## 12. Author

**Prerna Bhosale**
BSc Information Technology
