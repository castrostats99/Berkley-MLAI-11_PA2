# Berkley-MLAI-11_PA2
Code for Practical Application 2

The Extra Trees Regression model selected the following optimal hyperparameters through GridSearchCV: 200 estimators, unrestricted maximum tree depth (max_depth=None), and a minimum of two observations per terminal leaf (min_samples_leaf=2).

The selection of 200 estimators indicates that an ensemble of 200 randomized decision trees performed best among the configurations evaluated. Allowing unrestricted tree depth enables the model to capture complex, nonlinear relationships between vehicle characteristics and market prices. The minimum leaf size of two observations introduces a degree of regularization, helping reduce the likelihood of overfitting to individual vehicle records.

Collectively, these hyperparameters balance predictive flexibility and ensemble stability. Final model suitability is determined by evaluating performance on an independent testing dataset using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R²).
