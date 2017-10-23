# Converted_Customers_Predictions
Notebook to predict customer conversion 

Actions taken:
1. Exploratory data analysis - no missing values, no imputing needed, at first no clear correlation between columns and y, unbalanced training set
2. Data transformation - dummy encoding of string variables
3. Balance data set
4. Feature scaling of age
5. Apply different models and evaluate performance on test set - Logistic Regression, SVM, Gradient Boosted Trees and Random Forests
6. Model stacking - create folds of training data, predict on test folds and include predictions in raw training data and test data
7. Train Gradient Boosted Trees on stacked model and create final predictions

Next steps:
- Gather more data for better predictions, do feature engineering
- Implement majority voting and test if this would result in better performance 
