# Toxicity Prediction using Machine Learning

## Overview

This project predicts whether a chemical compound is **Toxic or Non-Toxic** using machine learning techniques.

The dataset contains **molecular descriptors** used as features.

## Steps Performed

1. Exploratory Data Analysis (EDA)
2. Data Cleaning
3. Target Encoding
4. Feature Reduction
   - Variance Threshold
   - Random Forest Feature Selection
5. Model Training using Random Forest
6. Model Evaluation using **Stratified 5-Fold Cross Validation**

## Model Used

Random Forest Classifier (Ensemble Model)

## Evaluation

Evaluation was done using:

- Cross Validation Accuracy
- Classification Report
- Confusion Matrix

## Libraries Used

- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Hyperparameter Tuning

Grid Search was used to optimize the Random Forest model.

Parameters tuned:

- n_estimators
- max_depth
- min_samples_split
- min_samples_leaf

This improved the model performance and reduced overfitting.

## How to Run

```bash
git clone <repo link>
cd toxicity-prediction
jupyter notebook
