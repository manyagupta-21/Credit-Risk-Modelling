# Credit Risk Modelling

## Overview
Built a classification system to predict credit default using financial and behavioural data.  
Focus on handling class imbalance and improving model performance in a risk-sensitive setting.

---

## Dataset
- Source: UCI – Default of Credit Card Clients  
- Size: 30,000 observations  
- Target: Default (binary)

---

## Key Challenges
- Severe class imbalance  
- Trade-off between interpretability and performance  

---

## Methodology
- EDA and feature analysis  
- Data preprocessing and scaling  
- Imbalance handling: SMOTE, over/under-sampling  

### Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- AdaBoost  
- XGBoost  

---

## Results
- Best model: Ensemble methods (RF / XGBoost)  
- **ROC-AUC:** 0.778  
- **F1 Score:** 0.53  

---

## Key Insights
- Payment history is the strongest predictor  
- Handling imbalance significantly improves performance  
- Ensemble models capture non-linear patterns effectively  
- Minimizing false negatives is critical in credit risk  

---

## Tech Stack
Python, pandas, numpy, scikit-learn, imbalanced-learn  

---
