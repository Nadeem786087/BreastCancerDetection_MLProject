# Breast Cancer Tumor Classification using Machine Learning

A comprehensive machine learning workflow for classifying breast cancer tumors as malignant or benign using the Wisconsin Breast Cancer Dataset.

## Project Overview

This project demonstrates a complete machine learning pipeline for medical diagnosis, including data preprocessing, exploratory data analysis, model training, hyperparameter optimization, and performance evaluation.

## Key Results

- **Test Accuracy**: 97.37%
- **Test AUC-ROC**: 0.9962
- **Best Model**: Random Forest with optimized hyperparameters
- **Dataset**: Wisconsin Breast Cancer Dataset (569 samples, 30 features)

## Model Performance

### Confusion Matrix (Test Set)
- True Negatives (Benign): 72
- False Positives: 0
- False Negatives: 3  
- True Positives (Malignant): 39

### Key Metrics
- **Accuracy**: 97.37%
- **Precision**: 100% (for malignant class)
- **Recall**: 92.86% (for malignant class)
- **AUC-ROC**: 0.9962

## Technical Implementation

### Algorithms Evaluated
- Logistic Regression
- Decision Trees
- Random Forest (Best Performer)
- Hyperparameter tuning with GridSearchCV

### Feature Analysis
Top 5 most important features identified:
1. Worst Radius
2. Worst Concave Points  
3. Mean Perimeter
4. Worst Area
5. Mean Concave Points

### Data Preprocessing
- Train-test split with stratification
- Feature scaling with StandardScaler
- Comprehensive EDA with correlation analysis
- UMAP visualization for data structure

