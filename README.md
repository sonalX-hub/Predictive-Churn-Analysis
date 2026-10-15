# Predictive Churn Analysis

## Project Objective
The objective of this project is to predict customer churn using machine learning and identify customers who may be at risk of leaving a service.

## Dataset
The dataset contains 800 customer records and 18 features, including:
- Age and tenure
- Monthly and total charges
- Support tickets and late payments
- Region, subscription type, contract type, and payment method

## Model
A machine learning classification model was developed to predict customer churn.

## Model Evaluation
The model was evaluated using the following metrics:

| Metric | Score |
|---|---:|
| Accuracy | 63.75% |
| Precision | 57.63% |
| Recall | 50.75% |
| F1 Score | 53.97% |
| ROC-AUC | 67.85% |

## Project Files
- `Predictive_Churn_Analysis.ipynb` — Project notebook
- `customer_churn_model_v2(1).csv` — Dataset
- `customer_churn_predictions(1).csv` — Customer churn predictions
- `churn_model.pkl` — Trained model
- `churn_scaler.pkl` — Feature scaler
- `confusion_matrix.png` — Confusion matrix
- `roc_curve.png` — ROC curve

## Conclusion
The model demonstrates the ability to identify potential customer churn, although its predictive performance can be improved through further experimentation and model tuning.e
