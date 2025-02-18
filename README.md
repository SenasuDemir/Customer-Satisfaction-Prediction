# Customer Satisfaction Prediction 📊

## Introduction 🤖
The goal of this project is to predict customer satisfaction levels based on various customer-related features. The target variable, `TARGET`, is a binary indicator where:
- **1** represents an unsatisfied customer
- **0** represents a satisfied customer

This dataset contains various numeric features that describe customer behavior, transactions, and interactions with the company. Using machine learning models, we aim to predict whether a customer will be satisfied or unsatisfied.

## Aim 🎯
The objectives of this project are:
- Predict the probability of a customer being unsatisfied (i.e., predict the `TARGET` value).
- Utilize machine learning classification algorithms such as Logistic Regression, Random Forest, Gradient Boosting, and others to model the data.
- Evaluate the performance of each model using metrics like accuracy, precision, recall, and F1-score.
- Handle class imbalance using techniques such as **SMOTE** to enhance prediction accuracy.

## Models Used ⚙️
### Traditional Machine Learning Models:
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **LightGBM Classifier**
- **Gradient Boosting Classifier**
- **KNeighbors Classifier**
- **Logistic Regression**
- **Naive Bayes (Gaussian and Bernoulli)**

### Deep Learning Model 🧠:
- A Deep Learning model was also tested, achieving a performance close to the top-performing traditional models.

## Results 📈
- **Best Performing Model**: Random Forest Classifier with an accuracy of **96.49%**.
- **Deep Learning Model**: Achieved an accuracy of **50.09%**.
- **Other notable models**: LightGBM (94.14%) and Decision Tree (94.35%).

## Summary 📌
Both **Random Forest** and the **Deep Learning model** demonstrated excellent predictive performance, making them well-suited for this customer satisfaction prediction task. The **Gradient Boosting** and **LightGBM** models also performed admirably. On the other hand, **Logistic Regression** and **Naive Bayes** models were less effective, showing lower accuracy.

## Kaggle Notebook 📑
You can access the full Kaggle notebook here: [Customer Satisfaction Prediction Notebook](https://www.kaggle.com/code/senasudemir/customer-satisfaction-prediction?scriptVersionId=223244013).
