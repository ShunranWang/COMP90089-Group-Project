# COMP90089-Project-Group1
 
# Risk of Diabetic Ketoacidosis Causing Hospital Readmission

## Project Overview
This project focuses on predicting the risk of hospital readmission among patients with Diabetic Ketoacidosis (DKA). Using machine learning models, we aim to identify high-risk patients and improve ICU resource allocation.

## Files we used:
In the data folder:
- `DKA_patients.csv`: This file contains the collected dataset of the cohort of DKA patients, which is used for analysis and modelling in this project. 
- `query_data.ipynb`This notebook documents the entire process of querying and extracting data from the MIMIC-IV database to build the DKA patient cohort. It includes detailed steps and SQL queries used to retrieve relevant patient information, ensuring reproducibility and transparency in data collection.

------

- `lightGBM_ver02.ipynb`: The notebook used grid search on LightGBM to compare combinations of different NaN Filling Methods and Class Imbalance Handling Techniques, then used metrics including Precision, Recall,	F1-Score, and	ROC-AUC to evaluate the results. After getting the ideal hyperparameters, figures of the ROC-AUC graph, calibration curve and feature importance score are drawn according to the final model for further analysis in the report.
- `LSTM_model.ipynb`: This notebook predicts hospital readmissions for DKA patients using an LSTM model. It preprocesses data by handling missing values and encoding categorical variables, and addresses class imbalance with techniques like SMOTE and Borderline-SMOTE. Hyperparameter tuning is applied, and performance is evaluated using Precision, Recall, F1-Score, and ROC-AUC, with visualizations of training loss and model performance for analysis.
- `SVM_model.ipynb`: This notebook aims to predict hospital readmissions for DKA patients utilizing an SVM model. The data preprocessing steps include handling missing values, encoding categorical features, and addressing class imbalance through SMOTE. Hyperparameter tuning is conducted with both GridSearchCV and RandomizedSearchCV. Model performance is assessed using metrics like Precision, Recall, F1-Score, and ROC-AUC, along with visual representations such as confusion matrix and ROC curve to facilitate analysis.
- `eda&randomForest.ipynb`: In this notebook, we did exploratory data analysis (EDA), including displaying feature distributions and correlation with the readmission label. It then trains and optimizes a Random Forest model through grid search, evaluating its performance with classification metrics and ROC-AUC curves. The feature important scores offered insights into which variables most significantly impacted model predictions.

