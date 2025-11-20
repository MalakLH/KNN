# Heart Failure Prediction using K-Nearest Neighbors (KNN)

## Project Overview

This project implements a K-Nearest Neighbors (KNN) classifier to predict heart failure outcomes using the Heart Failure Clinical Records dataset from Kaggle. The goal is to build an accurate predictive model by applying various data preprocessing and model optimization techniques.

## Dataset

The dataset used is the **Heart Failure Clinical Records Dataset** from Kaggle, containing medical records with various clinical features that may indicate heart failure.

## Techniques Implemented

### Data Preprocessing
- **Encoding Data**: Converted categorical variables into numerical format
- **Standardization**: Applied feature scaling using StandardScaler to normalize features

### Model Optimization
- **Grid Search**: Used for hyperparameter tuning to find optimal KNN parameters
- **Cross-Validation**: Implemented k-fold cross-validation to ensure model robustness
- **Hyperparameter Tuning**: Optimized number of neighbors, distance metrics, and weight functions

### Model Evaluation
- **Confusion Matrix**: Generated to visualize and verify model performance
- **Multiple Metrics**: Evaluated using accuracy, precision, recall, and F1-score
