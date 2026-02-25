# Classification Model Comparison Study

## Overview
This project evaluates and compares multiple classical machine learning classification algorithms on a structured dataset. The goal was to benchmark model performance based on accuracy and computational efficiency to determine the most effective approach.

---

## Models Implemented

- Decision Tree
- Naïve Bayes (Gaussian & Multinomial)
- Support Vector Machine (Linear & RBF)
- k-Nearest Neighbors (k-NN)
- Bagging
- Random Forest
- AdaBoost
- XGBoost

---

## Performance Comparison

| Model | Accuracy |
|--------|----------|
| Decision Tree | 87.1% |
| Gaussian NB | 55.1% |
| Multinomial NB | 82.8% |
| SVM (Linear) | 93.5% |
| SVM (RBF) | 97.6% |
| k-NN | 97.2% |
| Random Forest | 96.6% |
| XGBoost | **97.8%** |

---

## Key Insights

- XGBoost achieved the highest accuracy (97.8%).
- SVM with RBF kernel performed strongly among non-ensemble models.
- Ensemble methods significantly improved performance.
- Naïve Bayes was computationally efficient but lower in accuracy.

---

## Technologies Used

- Python
- Scikit-Learn
- XGBoost
- NumPy
- Matplotlib

---

## How to Run

1. Install dependencies:
  pip install scikit-learn xgboost numpy matplotlib

2. Run each notebook:
- Decision Tree Classifier.ipynb
- Support Vector Machine (SVM).ipynb
- Ensemble Methods.ipynb
