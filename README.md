# Advertising Click Prediction

Machine Learning project for predicting user advertisement click behavior using feature selection and Support Vector Machine (SVM).

## Project Overview

Digital advertising is widely used to reach potential customers, but not every user who views an advertisement will interact with it. This project aims to identify the factors that influence advertisement click behavior and build a binary classification model capable of predicting whether a user will click an advertisement.

## Dataset

Dataset: Advertisement Click on Ad Dataset

Number of observations: 1,000

Target Variable:
- Clicked on Ad
  - 1 = User clicked the advertisement
  - 0 = User did not click the advertisement

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Statistical Analysis
4. Feature Selection
5. Data Preprocessing
6. Candidate Model Development
7. Hyperparameter Tuning
8. Model Evaluation
9. Feature Importance Analysis

## Selected Features

The final model uses four numerical features:

- Daily Internet Usage
- Daily Time Spent on Site
- Area Income
- Age

## Candidate Models

The following machine learning algorithms were evaluated:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- XGBoost

## Final Model

Support Vector Machine (SVM)

Best Hyperparameters:

```python
kernel='rbf'
C=10
gamma=1
```

## Model Performance

| Metric | Score (%) |
|----------|----------:|
| Accuracy | 97.00 |
| Precision | 97.00 |
| Recall | 97.00 |
| F1-Score | 97.00 |
| ROC AUC | 98.94 |

## Key Findings

- Daily Internet Usage is one of the strongest predictors of advertisement click behavior.
- Daily Time Spent on Site also has a significant influence on user engagement.
- Area Income and Age contribute meaningfully to click prediction.
- Numerical features provide substantially more predictive power than categorical features.

## Repository Structure

```
advertising-click-prediction/
│
├── Advertising_Click_Prediction.ipynb
├── advertising.csv
├── figures/
├── report/
│   └── Final_Report.pdf
├── README.md
└── requirements.txt
```

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn

## Author

Philipus Dima Wira Pratomo
