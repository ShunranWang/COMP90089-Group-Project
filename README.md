# COMP90089-Project-Group1
 
# Risk of Diabetic Ketoacidosis Causing Hospital Readmission

## Project Overview
This project focuses on predicting the risk of hospital readmission among patients with Diabetic Ketoacidosis (DKA). Using machine learning models, we aim to identify high-risk patients and improve ICU resource allocation.

## Files we used:
- `lightGBM_ver02.ipynb`: The notebook used grid search on LightGBM to compare combinations of different NaN Filling Methods and Class Imbalance Handling Techniques, then used metrics including Precision, Recall,	F1-Score, and	ROC-AUC to evaluate the results. After getting the ideal hyperparameters, figures of the ROC-AUC graph, calibration curve and feature importance score are drawn according to the final model for further analysis in the report.
- `LSTM_model.ipynb`: This notebook predicts hospital readmissions for DKA patients using an LSTM model. It preprocesses data by handling missing values and encoding categorical variables, and addresses class imbalance with techniques like SMOTE and Borderline-SMOTE. Hyperparameter tuning is applied, and performance is evaluated using Precision, Recall, F1-Score, and ROC-AUC, with visualizations of training loss and model performance for analysis.

