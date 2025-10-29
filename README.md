# Churn Prediction Using Machine Learning

This project predicts customer churn using structured service usage data. The goal is to identify customers likely to discontinue their subscription based on behavioral and account features.  
It uses preprocessing pipelines with scaling and one-hot encoding, followed by a Logistic Regression model to maximize ROC-AUC performance.

---

## Features
- Data preprocessing with `ColumnTransformer` (scaling + encoding)
- Model training and validation split for fair evaluation
- ROC-AUC used as the key performance metric
- Pipeline integration for reproducibility
- Final predictions formatted for automated evaluation (`prediction_df`)

---

## Model Used
- Logistic Regression (baseline and final model)

---

## Results
- Best Validation ROC-AUC ≈ **0.75** (96th percentile score in the competition)
- Produced submission-ready predictions with columns:
  - `CustomerID`
  - `predicted_probability`

---

## 📁 Repository Structure
```
ChurnPrediction.ipynb        # Jupyter notebook with complete pipeline
data/                        # (optional) Folder for train/test CSVs
README.md                    # Project documentation
```
## Author
**Eshaan James**  
Machine Learning & Data Science Enthusiast  
📬 Connect on [LinkedIn](https://www.linkedin.com/in/eshaan-r-james/)
