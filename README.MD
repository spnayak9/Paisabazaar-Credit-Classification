# Paisabazaar Credit Classification

## Project Summary

This project focused on credit classification using the Paisabazaar dataset. After loading and cleaning the data, including handling categorical features and class imbalance with SMOTE, several models were trained: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. Exploratory analysis revealed key features like credit history and outstanding debt influence credit scores. Random Forest and a tuned Decision Tree model showed superior performance with high F1-scores. Feature importance analysis highlighted crucial factors. The project successfully built effective models for credit score prediction, with potential for further improvement using advanced techniques.

## Problem Statement

The problem is to accurately classify the creditworthiness of individuals using the Paisabazaar dataset. This involves building a model that can predict whether a customer's credit score is Poor, Standard, or Good, to help in making informed lending decisions and managing credit risk effectively.

## Approach

1. **Data Loading and Exploration:** Loaded the dataset and performed initial checks for missing values and duplicates.
2. **Data Cleaning and Preprocessing:** Handled categorical features using one-hot encoding and addressed class imbalance using SMOTE. Scaled numerical features.
3. **Model Training:** Trained several classification models: Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.
4. **Model Evaluation:** Evaluated models using classification reports and confusion matrices.
5. **Hyperparameter Tuning:** Tuned the Decision Tree model using RandomizedSearchCV to improve performance.
6. **Feature Importance Analysis:** Analyzed feature importances from the best-performing model.
7. **Cross-Validation and Learning Curve:** Performed cross-validation and plotted the learning curve for the best model.
8. **Baseline Model Comparison:** Trained and evaluated a baseline model for performance comparison.

## Findings

* The dataset exhibited class imbalance in the target variable 'Credit_Score'.
* Exploratory data analysis revealed relationships between credit score and features like Annual Income, Outstanding Debt, and Credit History Age.
* The Random Forest and tuned Decision Tree models significantly outperformed the baseline and other models.
* Feature importance analysis indicated that 'Credit Mix' and 'Outstanding Debt' were among the most influential features.

## Conclusion and Summary

This project successfully built and evaluated several models for credit classification. The tuned Decision Tree and Random Forest models achieved high F1-scores, demonstrating their effectiveness in predicting creditworthiness. The analysis provided insights into key factors influencing credit scores. Future work could involve exploring more advanced models and feature engineering techniques to potentially further improve model performance.