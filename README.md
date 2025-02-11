# Churn Prediction Application

This project is a machine learning application built to predict customer churn for banks. It uses several machine learning models to analyze customer data and predict which customers are likely to churn, along with a web interface to display churn probabilities and generate personalized emails for each customer. 

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

---

## Overview

This project leverages various machine learning models, such as XGBoost, Random Forest, Decision Trees, Naive Bayes, Logistic Regression, and Support Vector Classification, to predict customer churn. The web app provides a user-friendly interface displaying customer churn probabilities and generates a custom email for each customer using Llama3.

---

## Dataset

The application uses a dataset with customer information to train and test models. The data includes various customer attributes such as age, gender, tenure, product details, and account balance.

- **Source**: [Churn Dataset](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers)

---

## Technologies Used

- **Python**: Pandas, Scikit-Learn, XGBoost
- **Machine Learning Models**: Random Forest, Decision Tree, XGBoost, Naive Bayes, Logistic Regression, Support Vector Classification
- **Replit & Streamlit**: For building the web application
- **Llama3**: To generate customized emails for customers based on churn predictions
- **Matplotlib & Seaborn**: For data visualization

---

## Usage

1. **Data Preparation**: Load and preprocess the dataset to handle missing values, split data, and visualize trends.
2. **Model Training**: Train various models and save the best-performing model (XGBoost) for the final application.
3. **Web App**: Open the app in a browser to view churn predictions and email summaries for customers.
4. **Email Generation**: Llama3 is used to generate personalized emails for each customer, explaining the churn analysis and offering solutions.

---

## Results

The project successfully predicts customer churn and offers additional functionality:
- Improved recall on XGBoost model.
- Real-time churn predictions displayed on a web dashboard.
- Automated email generation explaining the results.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
