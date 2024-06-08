# Bitcoin_Prediction

Data Preprocessing:
  •	Loaded the Bitcoin dataset.
  •	Checked for missing values and handled them by forward filling.
  •	Visualized missing values using a heatmap.
  •	Explored the data distribution and statistics.
Feature Scaling: 
  •	Scaled the features using Min-Max scaling.
Model Selection and Training:
  •	Tried various regression models including K-Nearest Neighbors, Ridge Regression, Lasso Regression, Linear Regression, Polynomial Regression, and Support Vector Regression (with and without kernels).
  •	Tuned hyperparameters using techniques like GridSearchCV.
  •	Evaluated models using both train-test split and cross-validation.
Prediction:
  •	Used the Lasso Regression model to predict Bitcoin prices on the test dataset.
Results:
  •	Evaluated the models based on training scores, test scores, and cross-validation scores.
  •	Compiled the results into a DataFrame for comparison.
  •	Analysis shows that the Polynomial Lasso Regression model achieved high accuracy on both the training and test sets. The results seem promising, indicating that the chosen model can effectively predict Bitcoin 
    prices.

