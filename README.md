# Heart Disease Classification using Statistical Learning

## Overview

This project investigates heart disease classification using multinomial and binary logistic regression models in R.  
The workflow includes data preprocessing, missing-value imputation, exploratory data analysis, statistical modelling, cross-validation, and model selection techniques applied to a clinical dataset.

The primary objective is to identify the most informative clinical predictors associated with heart disease severity while evaluating predictive performance through rigorous statistical validation.

---

## Objectives

- Multiclass heart disease classification
- Binary heart disease prediction
- Statistical feature analysis
- Missing-value handling and preprocessing
- LOOCV performance evaluation
- AIC-based model selection
- Clinical interpretability of predictors

---

## Dataset

The project uses a clinical heart disease dataset containing demographic, physiological, and diagnostic variables, including:

- Age
- Sex
- Chest pain type
- Cholesterol
- Resting blood pressure
- Exercise-induced angina
- ECG measurements
- Heart disease severity classes

---

## Methodology

### Data Preprocessing

- Conversion of categorical variables into factors
- Dummy encoding of binary predictors
- Handling physiologically implausible values
- Median and mode imputation for missing values

### Exploratory Data Analysis

The project includes:
- Distribution analysis
- Boxplots
- Categorical association plots
- Statistical comparison tests

### Statistical Models

#### Multinomial Logistic Regression
Used to predict five heart disease severity classes.

#### Binary Logistic Regression
Used to predict the presence/absence of heart disease.

### Model Validation

- Leave-One-Out Cross Validation (LOOCV)
- Accuracy evaluation
- Misclassification error analysis
- Stepwise AIC model selection

---

## Main Findings

- Exercise-induced angina strongly correlates with heart disease
- Chest pain type is highly predictive
- Some predictors show strong statistical significance across disease classes
- Binary classification performs substantially better than multiclass classification
- Stepwise AIC improves model parsimony with negligible predictive loss

---

## Technologies Used

- R
- RMarkdown
- nnet
- MASS
- ggplot2
- Statistical Learning
- Logistic Regression
- Cross Validation

---

## Repository Structure

```text
.
├── ProjectWork_Pazienza.Rmd
├── ProjectWork_Pazienza.pdf
├── figures/
├── data/
├── results/
└── README.md
```

---

## Results

| Model | Accuracy |
|---|---|
| Multinomial Logistic Regression | 64.13% |
| Binary Logistic Regression | 84.24% |

LOOCV evaluation highlights the increased difficulty of multiclass heart disease prediction compared to binary classification.

---

## Author

Lorenzo Pazienza  
BSc in Management and Artificial Intelligence — LUISS Guido Carli