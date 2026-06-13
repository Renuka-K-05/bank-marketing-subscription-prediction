# bank-marketing-subscription-prediction
End-to-end machine learning project for predicting customer term-deposit subscriptions using data preprocessing, feature engineering, SMOTE, and multiple classification models.

## Overview

This project focuses on predicting whether a customer will subscribe to a term deposit using the Bank Marketing Dataset. The workflow includes data preprocessing, exploratory data analysis, feature engineering, handling class imbalance, and training multiple machine learning classification models.

The objective is to analyze customer and campaign-related information and build predictive models that can help improve marketing decision-making.

---

## Dataset
Source: Kaggle Bank Marketing Dataset
Dataset Link: https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset
The project uses the Bank Marketing Dataset, which contains information collected from direct marketing campaigns conducted by a banking institution.

Target Variable:

* **y**

  * yes → Customer subscribed to a term deposit
  * no → Customer did not subscribe

Features include:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan Status
* Personal Loan Status
* Contact Type
* Campaign Information
* Previous Campaign Outcomes

---

## Project Workflow

### 1. Data Preprocessing

* Data cleaning and preparation
* Handling missing and unknown values
* Outlier treatment using IQR
* Feature transformation
* Creation of new features

### 2. Exploratory Data Analysis

* Customer demographic analysis
* Campaign performance analysis
* Distribution analysis
* Correlation analysis
* Data visualization

### 3. Feature Engineering

* Creation of derived features
* Feature selection using SelectKBest
* Feature scaling using StandardScaler

### 4. Class Imbalance Handling

* Applied SMOTE (Synthetic Minority Oversampling Technique) to balance the target classes.

### 5. Model Training and Evaluation

The following machine learning algorithms were implemented and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree Classifier
* Random Forest Classifier
* Gaussian Naive Bayes

### 6. Model Validation

* Train-Test Split
* Stratified K-Fold Cross Validation
* ROC-AUC Analysis
* Performance Comparison

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Imbalanced-Learn (SMOTE)
* Jupyter Notebook

---

## Project Structure

```text
├── 01_Data_Preprocessing.ipynb
├── 02_Exploratory_Data_Analysis.ipynb
├── 03_Model_Training_and_Evaluation.ipynb
├── README.md
└── requirements.txt
```

---

## Key Learning Outcomes

* Data preprocessing techniques
* Feature engineering methods
* Handling imbalanced datasets
* Machine learning model development
* Cross-validation strategies
* Model evaluation using multiple metrics

---

## Future Improvements

* Hyperparameter optimization for all models
* Ensemble learning approaches
* Model deployment using Flask or Streamlit
* Interactive dashboard development

---

## Author

Renuka Kommoju

B.Tech Computer Science and Engineering
