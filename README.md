# Class Imbalance and Model Evaluation

## Project Overview
This project focuses on addressing class imbalance in the APS Failure dataset using various techniques including SMOTE, Random Forests, and XGBoost. The analysis includes comprehensive data preparation, feature selection, and model evaluation using multiple metrics.

## Key Components
- **Data Preprocessing**:
 - Handling missing values using data imputation techniques
 - Feature selection using coefficient of variation (CV)
 - Correlation analysis and visualization
 - Class imbalance analysis and mitigation

- **Model Implementation**:
 - Random Forest Classification (with and without class imbalance compensation)
 - XGBoost with L1-penalized logistic regression
 - SMOTE for handling imbalanced data

## Technical Details
### Data Analysis
- Feature selection using CV (Coefficient of Variation)
- Visualization using scatter plots and box plots
- Correlation matrix analysis
- Class distribution analysis

### Models & Evaluation
- **Random Forest**:
 - Out of Bag error estimation
 - Class imbalance compensation analysis
 
- **XGBoost**:
 - L1-penalized logistic regression at nodes
 - Cross-validation for hyperparameter tuning
 
- **Evaluation Metrics**:
 - Confusion Matrix
 - ROC Curves
 - AUC Scores
 - Misclassification rates

## Technologies Used
- Python
- Scikit-learn
- XGBoost
- Pandas
- Matplotlib/Seaborn
- imbalanced-learn (for SMOTE)

## Dataset
The APS Failure dataset from UCI Machine Learning Repository:
- 60,000 training samples
- 171 features (all numeric)
- Binary classification problem
- Significant class imbalance (1,000 positive cases)
- [Link to dataset](https://archive.ics.uci.edu/ml/datasets/APS+Failure+at+Scania+Trucks)

## Results
- Comparative analysis of models with/without class imbalance handling
- Impact of SMOTE on model performance
- Cross-validation error analysis
- Feature importance insights

This project was completed as part of USC's DSCI 552 course under the guidance of Professor Mohammad Reza Rajati.
