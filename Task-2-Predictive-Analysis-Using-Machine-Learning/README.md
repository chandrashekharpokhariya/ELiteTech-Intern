# Task 2 - Predictive Analysis Using Machine Learning

## Objective

The objective of this project is to build a machine learning classification model to predict whether a customer is likely to churn based on their demographic, service, contract, and billing information.

## Dataset

The project uses the IBM Telco Customer Churn dataset.

The dataset contains customer demographic information, services, contract details, payment methods, monthly charges, total charges, and churn status.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Steps Performed

1. Loaded and understood the dataset.
2. Cleaned the data and handled missing values.
3. Converted `TotalCharges` into numeric format.
4. Performed exploratory data analysis (EDA).
5. Encoded categorical variables.
6. Split the data into training and testing sets.
7. Scaled the features using `StandardScaler`.
8. Trained a Logistic Regression classification model.
9. Evaluated the model using accuracy, classification report, confusion matrix, and ROC-AUC.
10. Analyzed the most influential features affecting customer churn.

## Model

**Logistic Regression** was used as the machine learning classification model.

## Model Evaluation

* **Accuracy:** 80.38%
* **ROC-AUC Score:** 0.8357

### Classification Report

|        Class | Precision | Recall | F1-Score |
| -----------: | --------: | -----: | -------: |
|            0 |      0.85 |   0.89 |     0.87 |
|            1 |      0.65 |   0.57 |     0.61 |
| **Accuracy** |           |        | **0.80** |

The confusion matrix and detailed classification report are available in the Jupyter Notebook.

## Conclusion

The Logistic Regression model achieved an accuracy of **80.38%** and a ROC-AUC score of **0.8357**, indicating reasonable performance in predicting customer churn.

The analysis also identified important factors associated with customer churn, which can help businesses understand customer retention challenges and make better customer-focused decisions.

