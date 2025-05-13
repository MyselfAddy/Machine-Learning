# Customer Churn Analysis and Prediction


This project focuses on analyzing customer data from a telecom company to predict churn using machine learning techniques. Customer churn represents the phenomenon of customers discontinuing services, which significantly impacts business revenue. The objective is to develop predictive models that assist in identifying potential churners, enabling companies to take proactive retention measures.


## Objective
Analyze telecom customer data to identify patterns influencing churn.

Develop machine learning models to predict customer churn.

Provide data-driven insights for business strategy improvements.


## Dataset Description
The dataset includes customer information such as demographics, subscribed services, billing details, and churn status.

| Feature             | Description                                   |
| ------------------- | --------------------------------------------- |
| CustomerID          | Unique customer identifier                    |
| Gender              | Customer gender                               |
| SeniorCitizen       | Indicates if the customer is a senior citizen |
| Tenure              | Number of months with the company             |
| Contract            | Type of subscription contract                 |
| MonthlyCharges      | Monthly billing amount                        |
| PaymentMethod       | Method used for payment                       |
| Churn               | Target variable (Yes/No)                      |
| Additional features | Service usage and demographic details         |



## Tools and Technologies Used
Python (Pandas, NumPy, Scikit-learn)

Google Collab

Data Visualization (Matplotlib, Seaborn)

Machine Learning Algorithms: Logistic Regression, Decision Tree, Random Forest, XGBoost



## Methodology
Data Preprocessing
Handling missing values and outliers.

Encoding categorical variables.

Feature scaling and normalization.

Dropping irrelevant columns (e.g., CustomerID).

Data distribution analysis.

Visualization of churn patterns.

Correlation heatmaps and feature relationships.

## Model Building

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

## Model Evaluation
Metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC.

Confusion Matrix and ROC Curve analysis.

## Result Interpretation
Identification of significant factors contributing to churn.

## Comparative analysis of model performances.

| Model               | Accuracy | Class 1 Recall | Class 1 Precision | F1 (Class 1) | ROC-AUC |
|---------------------|----------|----------------|-------------------|--------------|---------|
| Logistic Regression | 0.791    | 0.49           | 0.63              | 0.55         | 0.818   |
| Decision Tree       | 0.717    | 0.41           | 0.45              | 0.43         | 0.631   |
| Random Forest       | 0.752    | 0.44           | 0.53              | 0.48         | 0.761   |
| Gradient Boosting   | 0.785    | 0.48           | 0.61              | 0.54         | 0.825   |



## Key Insights
Month-to-month contract customers are more prone to churn.

Higher monthly charges correlate with increased churn probability.

Longer-tenured customers exhibit better retention.

Specific payment methods show a higher churn tendency.
