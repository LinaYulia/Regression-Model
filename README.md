# Regression-Model

This is the Boston Housing data frame with 506 rows and 14 columns. Will be shown modeling using Ridge and Lasso regression.

After the data is loaded, the data is split into two parts: namely, train data and test data. There is multicollinearity in the data we have. It can cause a harmful impact. That is, the coefficient on the training data can become unstable.

By creating a correlation heatmap, we can determine which features need to be removed to eliminate multicollinearity. After making sure there is no multicollinearity, we can train the data. First, we need to choose the best lambda value on this dataset using Ridge and Lasso regression modeling.

Then we can do a model evaluation and diagnostic study to see the value of R2. The result obtained on the Lasso and Ridge is above 70%
