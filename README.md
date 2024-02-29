# HW-2_regularization

**Task 1:** 
1. Fit a Linear Regression model using `train_X_prepared` as predictor, and `train_y` as a response.
2. Then, calculate the testing RMSE using `test_X_prepared` as predictor, and `test_y` as a response.

**Task 2:**
1. Fit a Ridge Regression model with tuning parameter $\alpha=10$ using `train_X_prepared` as predictor, and `train_y` as response. Then, calculate the testing RMSE using `test_X_prepared` as predictor, and `test_y` as response.
2. Use grid search to choose the best $\alpha$ value (You may need multiple grid searches). Then use the Ridge model with the best alpha value to calculate the testing RMSE.

**Task 3:**
1. Fit a LASSO Regression model with tuning parameter $\alpha=1000$ using `train_X_prepared` as predictor, and `train_y` as response. Then, calculate the testing RMSE. Can the LASSO model help select variables?
2. Use grid search to choose the best $\alpha$ value (You may need multiple grid searches). Use the LASSO model with the best $alpha$ value to calculate the testing RMSE.

**Task 4:**
1. Fit an Elastic Regression model with `alpha=10` and `l1_ratio=0.1` using `train_X_prepared` as predictor, and `train_y` as response. Then, calculate the testing RMSE. Can the LASSO model help select variables?
2. Use grid search to choose the best settings for $alpha$ and `l1_ratio` value (You may need multiple grid searches). Use the LASSO model the best settings to calculate the testing RMSE.
