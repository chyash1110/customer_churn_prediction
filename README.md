# Telco Customer Churn Prediction

This repository contains a project aimed at predicting customer churn for a telecommunications company. The project uses machine learning techniques to analyze customer data and identify those who are likely to leave the company.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)

## Introduction

Customer churn is a critical issue for telecom companies, as acquiring new customers is often more expensive than retaining existing ones. This project uses machine learning to predict whether a customer will churn based on various features.

## Dataset

The dataset used in this project is the Telco Customer Churn dataset, which includes information about customer demographics, services, and account information. The dataset contains 7043 entries and 21 columns.

## Libraries Used

The following libraries are used in this project:

- numpy
- pandas
- matplotlib
- seaborn
- plotly
- scikit-learn
- imbalanced-learn

## Data Preprocessing

Data preprocessing steps include:

1. Loading the dataset.
2. Cleaning the data by replacing missing values and converting data types.
3. Encoding categorical variables.
4. Handling class imbalance using the SMOTE technique.

## Model Training

The RandomForestClassifier from scikit-learn is used for training the model. The training steps include:

1. Splitting the data into training and test sets.
2. Applying SMOTE to handle class imbalance.
3. Training the model on the resampled data.

## Evaluation

The model's performance is evaluated using classification metrics such as precision, recall, and F1-score. The results show an accuracy of 77%, with precision and recall varying between the classes.

## Conclusion

This project demonstrates the application of machine learning techniques to predict customer churn in the telecom industry. The model can help the company identify customers at risk of churning and take proactive measures to retain them.

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/chyash1110/customer_churn_prediction.git
cd customer_churn_prediction
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn imbalanced-learn
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook telco-customer-churn-prediction.ipynb
```

4. Run the notebook cells to execute the code.
