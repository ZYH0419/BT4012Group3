**Fraud Detection Modelling Project**
A comparative study of supervised, unsupervised and rule-based approaches on a single-transaction fraud dataset

**Project Overview**
This project explores multiple machine learning and analytical approaches to detect fraudulent bank transactions.
The dataset contains single, isolated transactions per user with a fraud rate of ~5%, and the goal was to evaluate whether any modelling technique could meaningfully distinguish fraud from non-fraud.

**Models Implemented**
Supervised Learning： 
1. Logistic Regression
2. Random Forest
3. XGBoost
4. LightGBM

Feature Engineering Experiments:
1. Risk-encoded categorical variables
2. Aggregated & deviation features
3. TF-IDF on transaction descriptions
4. Creation of interaction terms
5. Combined all engineered features
   
Unsupervised Learning:
1. Isolation Forest

Rule-Based System:
1. Weighted heuristic scoring using engineered features
