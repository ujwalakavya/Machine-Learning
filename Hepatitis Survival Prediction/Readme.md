# Hepatitis Survival Prediction

This project focuses on predicting survival outcomes of hepatitis patients using machine learning classification techniques. The dataset includes both categorical and numeric variables, allowing for a comprehensive analysis and model development.

---

## Objective
To build and evaluate classification models to predict whether a patient with hepatitis will survive or not, leveraging Python's Scikit-learn library and advanced techniques like hyperparameter tuning and ensemble stacking.

---

## Key Concepts Covered
1. **Baseline Models:** Initial implementation of four classifiers with default parameters:
   - Linear Support Vector Classifier (LinearSVC)
   - Decision Tree Classifier
   - Random Forest Classifier
   - K-Nearest Neighbors (KNN)
   
2. **Hyperparameter Tuning:** Optimizing the Random Forest Classifier by modifying at least three hyperparameters using random search.

3. **Feature Importance:** Analyzing feature contributions using `feature_importances_` property of Random Forest.

4. **Ensemble Stacking:** Combining predictions from all four classifiers into a single stacked model using a Multilayer Perceptron (MLP) as the stacking classifier.

5. **Evaluation Metrics:** Comparing models based on Accuracy, Precision, Recall, and F1-Score.

---

## Project Highlights
1. **Baseline Model Performance:**
   - Recorded performance metrics for all classifiers with default settings.
   - Established a baseline for comparison with tuned models.

2. **Random Forest Hyperparameter Tuning:**
   - Conducted random search to find the best hyperparameters for Random Forest.
   - Improved model performance by optimizing parameters like tree depth, number of estimators, and splitting criteria.

3. **Feature Importance:**
   - Identified the top 5 most important features contributing to the Random Forest predictions.

4. **Ensemble Stacking:**
   - Combined predictions from LinearSVC, Decision Tree, Random Forest, and KNN into a stacked ensemble model using MLP.
   - Evaluated performance improvement with stacking over individual models.

5. **Results Comparison:**
   - Detailed comparison of performance metrics (accuracy, precision, recall, and F1-score) across default, tuned, and stacked models.

---

