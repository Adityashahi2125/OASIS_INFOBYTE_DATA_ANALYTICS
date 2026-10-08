# OASIS INFOBYTE — Data Analytics Internship

## Level 2 — Task 2: Wine Quality Prediction

### Objective
Predict whether a wine is high quality (`quality >= 7`) from physicochemical measurements.

### Models
- Logistic Regression
- Random Forest

### Evaluation
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix
- Model comparison
- Feature importance

### Dataset
UCI Wine Quality — Red Wine. The notebook downloads `winequality-red.csv` automatically.

### Important
The original `quality` score is excluded from model features after creating the binary target to prevent target leakage.
