# Californiahouseprice
The project involves constructing a basic predictive model using Linear Regression to estimate house prices in California, leveraging the California dataset provided by the Scikit-learn library.

Initially, an exploratory data analysis (EDA) was conducted to gain insights into the dataset. During this phase, correlations among some predictor variables were observed. Subsequently, tests were performed to identify multicollinearity, utilizing the variance inflation factor (VIF) to gauge the degree of correlation between variables. The VIF results revealed multicollinearity within the dataset, surpassing the threshold of 5. However, considering the project's context, no features were dropped as the presence of multicollinearity was expected to have minimal impact on the model's performance.

Prior to model training, it was recognized that scaling the training dataset was necessary. This step was crucial due to the varying scales of the features, potentially affecting the model's performance. Consequently, the same scaling transformations were applied to the test set to ensure consistency.

In addition to linear regression, ridge and lasso regression techniques were employed to model the dataset. Among these, lasso regression exhibited superior performance compared to the previous models, albeit not by a significant margin
