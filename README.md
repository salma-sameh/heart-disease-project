# Heart Disease Prediction

This project focuses on predicting the likelihood of heart disease using machine learning techniques. The notebook explores various models, evaluates their performance, and selects the best model for heart disease classification.

## Project Overview

The dataset contains health-related features relevant to predicting heart disease. By analyzing these features, machine learning algorithms can assist in determining whether an individual is at risk.

## Notebook Structure

1. *Importing Libraries*:
The notebook utilizes the following Python libraries:
 -numpy, pandas: For data manipulation
 -seaborn, matplotlib: For data visualization
 -scikit-learn: For model building, evaluation, and feature selection

2. *Loading the Data*:
-The dataset is loaded into a pandas DataFrame for exploration and preprocessing.

3. *Data Preprocessing*:
-Handling missing values and removing duplicates
-Scaling numerical features to improve model performance

4. *Feature Selection*:
-Recursive Feature Elimination (RFE) and Recursive Feature Elimination with Cross-Validation (RFECV) are applied to identify the most important features.

5. *Model Training*:
The notebook applies various machine learning models:
-Logistic Regression
-Support Vector Machine (SVM)
-Naive Bayes Classifier
-Random Forest Classifier

Each model is trained to predict the likelihood of heart disease.

6. *Model Evaluation*:
   The performance of each model is evaluated using metrics such as:
-Accuracy Score
-Confusion Matrix
-Classification Report

## Results
The project achieves high accuracy in predicting heart disease risk. Each model's precision, recall, and F1-score are evaluated to determine the best-performing model.
