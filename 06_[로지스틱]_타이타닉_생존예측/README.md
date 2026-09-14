# Titanic Survival Classification

## Project Overview

This project builds and compares multiple machine learning classification models to predict passenger survival using the Titanic dataset.

The project focuses on constructing a reusable preprocessing and modeling pipeline and comparing baseline classification models using multiple evaluation metrics.

## Dataset

The dataset contains 1,306 passenger records with the following variables:

- `Pclass` – Passenger class
- `Age` – Passenger age
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation
- `HasCabin` – Cabin information availability
- `FamilySize` – Family size
- `Title` – Passenger title
- `Survived` – Survival status (target)

## Workflow

1. Data quality checking
2. Exploratory data analysis
3. Feature preprocessing
4. Categorical variable encoding
5. Train/test split
6. Baseline model training
7. Model performance comparison

## Models

Nine classification models are compared:

- Logistic Regression
- Ridge Classifier
- K-Nearest Neighbors
- Support Vector Classifier
- Decision Tree
- Random Forest
- XGBoost
- LightGBM
- CatBoost

## Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- PR-AUC
- Diagnostic Odds Ratio (DOR)

F1 Score is used as the primary metric for baseline model comparison.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib / Seaborn
- Jupyter Notebook

## Project Structure

```text
titanic/
├── baseline/
│   ├── logistic.pkl
│   ├── ridge.pkl
│   ├── kneighbors.pkl
│   ├── svc.pkl
│   ├── decisiontree.pkl
│   ├── randomforest.pkl
│   ├── xgb.pkl
│   ├── lgbm.pkl
│   └── catboost.pkl
├── notebooks/
└── README.md