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

## Installation

1. Clone the repository:
    ```bash
   git clone https://github.com/chyash1110/customer_churn_prediction.git
   cd customer_churn_prediction
    ```

## Usage

1. Run the Flask application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/`.

3. Use the web interface to fill details for Churn prediction.

## Model Training

To retrain the model, run the Jupyter notebook `telco-customer-churn-prediction.ipynb` which contains the steps for data preprocessing, feature extraction, and model training.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request.

## Output

![Screenshot 2024-07-05 210256](https://github.com/chyash1110/customer_churn_prediction/assets/118417410/51f10ad3-a957-44b9-a9cd-5c415dda11a6)
![Screenshot 2024-07-05 210356](https://github.com/chyash1110/customer_churn_prediction/assets/118417410/dbf80058-be82-4be9-8e37-e602bf2d46c3)


