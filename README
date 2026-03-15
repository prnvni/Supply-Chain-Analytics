# Late Delivery Risk Prediction

A machine learning project that predicts whether an order will be delivered late, 
achieving **ROC-AUC of 0.74** on 180,000+ logistics records.

## Problem
Late deliveries hurt customer satisfaction and operational efficiency. 
This project identifies high-risk deliveries before they happen, giving 
supply chain teams actionable intelligence to intervene early.

## Results
- ROC-AUC: 0.74
- High precision in identifying high-risk orders
- Key finding: shipping mode and order region are the strongest predictors 
  of late delivery, not product category

## Dataset
180,000+ historical orders from Kaggle, including order type, shipping mode, 
region, scheduled shipment days, and product category.

## Methodology
1. Exploratory data analysis to identify high-risk patterns across categories and regions
2. Feature engineering and one-hot encoding of categorical variables
3. Class imbalance handling
4. Random Forest classifier (depth-controlled to reduce overfitting)
5. Evaluation via ROC-AUC, precision-recall, F1-score, and confusion matrix

## Key Insights
- Certain product categories consistently show higher late delivery risk
- Shipping mode and region drive delays more than product type
- Delivery risk is largely systematic, not random — making it predictable

## Tech Stack
Python · pandas · NumPy · scikit-learn · matplotlib
