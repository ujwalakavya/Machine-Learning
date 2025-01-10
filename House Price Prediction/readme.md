# House Price Prediction

This project focuses on predicting house prices using various regression techniques and handling missing data effectively. The dataset, sourced from the Kaggle competition "House Prices: Advanced Regression Techniques," presents a regression problem with a wide range of features influencing housing prices.

Dataset available at: [House Prices: Advanced Regression Techniques - Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

---

## Objective
To build and evaluate regression models that predict house prices with high accuracy, leveraging Python's Scikit-learn library and techniques like hyperparameter tuning, feature selection, and ensemble methods.

---

## Key Concepts Covered
- **Regression Techniques:** Using models such as Random Forest, Decision Tree, Support Vector Regression, Gradient Descent, and MLP Regressor.
- **Handling Missing Data:** Techniques for imputing missing values and ensuring clean data for regression analysis.
- **Hyperparameter Tuning:** Optimizing model performance with cross-validation using grid search and other methods.
- **Ensemble Methods:** Combining predictions from multiple models using one-layer stacking for improved results.
- **Feature Selection:** Implementing methods like SelectFromModel, SequentialFeatureSelector, and GeneticSelectionCV to identify the most important features.
- **Model Evaluation:** Comparing individual and stacked models based on metrics like Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
- **Kaggle Submissions:** Submitting predictions for benchmarking and performance comparison.

---

## Project Highlights
1. **Data Preprocessing:**
   - Addressed missing data using methods such as `fillna` and interpolation.
   - Analyzed and transformed features to improve model performance.

2. **Modeling:**
   - Experimented with a variety of regression models.
   - Conducted hyperparameter tuning and compared results.

3. **Ensemble Predictions:**
   - Built stacked models combining Random Forest, Decision Tree, and Support Vector Machines.
   - Performed hyperparameter tuning on the stacked model for further optimization.

4. **Feature Selection:**
   - Evaluated feature importance using SelectFromModel, SequentialFeatureSelector, and GeneticSelectionCV.
   - Rebuilt regression models using the top-ranked features.

5. **Results and Insights:**
   - Achieved competitive Kaggle scores with individual and ensemble models.
   - Demonstrated the impact of feature selection and ensemble methods on prediction accuracy.

