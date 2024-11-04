# Stacking_Technique
Implementation of a stacking ensemble model for binary classification, using Random Forest, Gradient Boosting, and Decision Tree as base models with Logistic Regression as the meta-model.

---

# Stacking Ensemble for Binary Classification

---

## Overview

The notebook includes:
- Data preprocessing, including handling categorical variables and class imbalance
- Training and evaluating base models (Random Forest, Gradient Boosting, and Decision Tree)
- Constructing a stacking ensemble with Logistic Regression as the meta-model
- Comparing the performance of the models using various metrics (accuracy, precision, recall, F1-score) and calculating percentage differences between models

## Contents

1. **Data Preprocessing**: Steps to load data, handle categorical variables, and address class imbalance using undersampling.
2. **Model Training**: Each base model is trained individually, and evaluation metrics are printed.
3. **Stacking Ensemble**: The stacking model is constructed with base models and a meta-model.
4. **Performance Comparison**: Metrics for each model are compared and percentage differences calculated for comparison.

## Models Used

- **Random Forest**: A robust, ensemble-based model using multiple decision trees.
- **Gradient Boosting**: A boosting algorithm that builds models sequentially to correct errors from previous models.
- **Decision Tree**: A simple model used as one of the base estimators.
- **Stacking Ensemble**: Combines the above models using Logistic Regression as the meta-model to get final predictions.

## Methodology

1. **Stacking Ensemble**: This technique uses multiple base models to generate predictions on the training data. A meta-model is trained on these meta-features to learn how to best combine the base models' outputs.
2. **Evaluation**: Each model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

For detailed results, including percentage differences, see the notebook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

--- 

