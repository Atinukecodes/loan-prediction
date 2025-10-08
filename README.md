Binary Classification Model Comparison

Overview

This project presents a comparative analysis of five machine learning models—Logistic Regression, Support Vector Machine (SVM), Random Forest, XGBoost, and LightGBM—applied to a binary classification task. The goal is to identify the most effective model for deployment based on performance metrics and visual evaluation.

Models Evaluated

Logistic Regression

Support Vector Machine (SVM)

Random Forest

XGBoost

LightGBM

Evaluation Metrics

Each model was assessed using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Confusion Matrix

ROC Curve

 Key Findings
 
LightGBM achieved the highest overall performance with an AUC of 0.999,minimal false predictions, and excellent precision-recall balance.

XGBoost closely followed, also delivering near-perfect classification.

Random Forest showed strong results with high accuracy and low error rates.

SVM and Logistic Regression performed well but had higher false positive rates.

Recommendation
Based on the analysis, LightGBM is recommended for deployment due to its superior accuracy, efficiency, and reliability.

Structure

├── data/                 # Dataset files
├── notebooks/            # Jupyter notebooks with model training and evaluation
├── images/               # ROC curves and confusion matrices
├── README.md             # Project overview and summary


Getting Started

To run the notebooks:

Clone the repository

Install dependencies from requirements.txt

Launch the Jupyter notebook and follow the workflow

 Requirements
 
Python 3.12+

scikit-learn

xgboost

lightgbm

matplotlib

seaborn

pandas

numpy

Contact
For questions or collaboration, feel free to reach out!
