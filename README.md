# Titanic Data Analysis and Binary Logistic Regression

## Project Overview

This project focuses on two main tasks:  
**Exploratory Data Analysis (EDA):** Analyzing the Titanic dataset to gain insights into passenger demographics and survival rates.  
**Binary Logistic Regression for Classification:** Building a logistic regression model to predict passenger survival.

## Dataset

**Source:** The Titanic dataset is loaded from \[this link\](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv).  
**Description:** The dataset includes details of passengers such as age, class, gender, and survival status.

## Project 1: Exploratory Data Analysis (EDA)

**Objective:** Understand the data distribution, handle missing values, and visualize key relationships.  
**Steps Involved:**  
    - Load and explore the Titanic dataset.  
    - Handle missing values in the dataset (fill `Age` and drop `Cabin` and `Embarked` columns).  
    - Visualize:  
        * Distribution of passenger classes.  
        * Survival rates by passenger class and gender.  
        * Age distribution of passengers.

## Project 2: Binary Logistic Regression for Classification

**Objective:** Predict whether a passenger survived using logistic regression.  
**Steps Involved:**  
    - Preprocess the data (convert `Sex` to binary and select key features).  
    - Split the dataset into training and testing sets.  
    - Train a Logistic Regression model on the training data.  
    - Evaluate the model's performance using accuracy, confusion matrix, and classification report.

## Tools and Libraries

**Languages:** Python  
**Libraries:**  
    - Pandas for data manipulation  
    - Seaborn and Matplotlib for data visualization  
    - Scikit-learn for model training and evaluation

## Results

**Exploratory Data Analysis:** Provided insights into survival rates based on class, gender, and age.  
**Model Performance:**  
    - Accuracy: \* \0.8100558659217877  
    - Confusion Matrix: \* \[[92 13]
                             [21 53]]  
    - Detailed precision, recall, and F1-score in the classification report.
                precision    recall  f1-score   support

           0       0.81      0.88      0.84       105
           1       0.80      0.72      0.76        74

    accuracy                           0.81       179
   macro avg       0.81      0.80      0.80       179
weighted avg       0.81      0.81      0.81       179

## Conclusion

This project demonstrates both data analysis and machine learning, providing a comprehensive approach to predictive analytics.

## References

* Dataset: [Titanic Dataset on GitHub\](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
