# Heart Attack Prediction Model

## Overview

This project focuses on predicting the likelihood of a heart attack based on various health-related features. We utilized a logistic regression model and employed the Synthetic Minority Over-sampling Technique (SMOTE) to handle class imbalance. Additionally, outliers were removed to enhance model performance.

## Contents

1. [Dataset](#dataset)
2. [Data Preprocessing](#data-preprocessing)
3. [Modeling](#modeling)
4. [Evaluation](#evaluation)
5. [Dependencies](#dependencies)
6. [Usage](#usage)
7. [License](#license)

## Dataset

The dataset used for this project contains information related to heart health, including features such as age, gender, chest pain type, blood pressure, cholesterol level, and more.

## Data Preprocessing

- **Handling Null Values:** No null values were present in the dataset.
- **Outlier Removal:** Outliers were identified and removed to improve model robustness.
- **SMOTE Technique:** Synthetic Minority Over-sampling Technique was applied to address class imbalance in the target variable.

## Modeling

Logistic Regression was chosen as the predictive model due to its effectiveness in binary classification problems. The SMOTE technique was implemented to handle the imbalanced nature of the target variable.

## Evaluation

The model's performance was evaluated using standard classification metrics, including accuracy, precision, recall, and F1-score. Confusion matrix and ROC curve analysis were also utilized to assess the model's effectiveness.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Imbalanced-learn (for SMOTE)

Install the dependencies using:

```bash
pip install numpy pandas scikit-learn seaborn matplotlib imbalanced-learn


# heartattackfile_2
