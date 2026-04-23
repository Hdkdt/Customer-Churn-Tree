# Customer Churn Prediction with Tree-Based Models

Portfolio-style machine learning project focused on predicting telecom customer churn using tree-based classifiers.

## Project Summary
This repository analyzes customer churn patterns and builds multiple supervised learning models to classify whether a telecom customer is likely to leave the service. The workflow combines data cleaning, exploratory data analysis, feature engineering, hyperparameter tuning, model evaluation, and interpretation.

## Main Objectives
- understand the main churn drivers
- segment customers by tenure behavior
- compare tree-based classifiers on the same classification task
- evaluate model quality using precision, recall, F1-score, and confusion matrices
- interpret feature importance for business insights

## Models
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

## Tech Stack
- Python
- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Repository Structure
```text
telco-churn-tree-models/
├── data/
│   └── README.md
├── images/
├── notebooks/
│   └── customer-churn-tree-models.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

## Dataset
Place the dataset file below inside the `data/` folder before running the notebook:

`Telco-Customer-Churn.csv`

Expected path from the notebook:
```python
../data/Telco-Customer-Churn.csv
```

## Skills Demonstrated
- data cleaning and preprocessing
- exploratory data analysis
- categorical encoding
- customer segmentation with cohort features
- model training and hyperparameter tuning
- supervised learning for churn prediction
- model comparison and interpretation

## Notes
This repository was cleaned and structured as a portfolio project. It is intended to be easy to read for recruiters, hiring managers, and collaborators.
