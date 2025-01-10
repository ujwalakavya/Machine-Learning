# Homesite Quote Conversion

This project focuses on predicting the probability that a customer will purchase a quoted insurance plan using machine learning techniques. The dataset, sourced from a Kaggle competition, involves a binary classification problem with an imbalanced dataset, where the majority class significantly outweighs the minority class.

Dataset available at: [Homesite Quote Conversion - Kaggle](https://www.kaggle.com/c/homesite-quote-conversion)

---

## Objective
To build and evaluate machine learning models for binary classification, leveraging techniques to handle imbalanced data, ensemble predictions, and hyperparameter tuning.

---

## Key Concepts Covered
- **Handling Imbalanced Data:**
  - Used SMOTE (Synthetic Minority Oversampling Technique) to address class imbalance and improve minority class prediction.
  - Experimented with different SMOTE percentages to find the optimal configuration.

- **Ensemble Predictions:**
  - Combined predictions from multiple models using one-layer stacking.
  - Utilized classifiers like Decision Tree, Random Forest, SVM, Multilayer Perceptron, and K-Nearest Neighbors.

- **Hyperparameter Tuning:**
  - Optimized the stacked ensemble model for better performance.
  - Compared results with individual model predictions.

- **Model Evaluation:**
  - Evaluated models using metrics like accuracy, precision, recall, and F1-score.
  - Submitted predictions to Kaggle and compared scores.

---

## Project Highlights
1. **Data Preprocessing:**
   - Addressed missing values in the dataset using imputation techniques.
   - Used preprocessed datasets provided for training and testing.

2. **SMOTE Implementation:**
   - Applied SMOTE to generate synthetic samples for the minority class.
   - Experimented with variations of SMOTE to enhance prediction performance.

3. **Modeling:**
   - Built individual classifiers: Decision Tree, Random Forest, SVM, Multilayer Perceptron, and K-Nearest Neighbors.
   - Combined predictions using ensemble methods (stacking).

4. **Results and Insights:**
   - Compared performance metrics of individual models and the stacked ensemble model.
   - Demonstrated the impact of handling imbalanced data on prediction accuracy.

---


