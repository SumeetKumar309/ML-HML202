# ML-HML202
ML repository
Ridge Regression-

R-Square has been increased which is a improvement in the model. In ridge regression we increase the value of alpha and see the change as the magnitude of coefficients decreases where the value reaches zero but not absolute zero.
Ridge regression is a way to create a model when the number of variables in a set exceeds the number of observations, or when a data set has multicollinearity.
Unlike least squares method, ridge regression produces a set of coefficient estimates for different values of the tuning parameter. So, it's advisable to use the results of ridge regession (the set of coefficient estimates) with a model selection technique (such as, cross-validation) to determine the most appropriate model for the given data.


Lasso Regression-

Lasso regression is a type of linear regression that uses shrinkage. Shrinkage is where data values are shrunk towards a central point, like the mean. 
The acronym “LASSO” stands for Least Absolute Shrinkage and Selection Operator.
This particular type of regression is well-suited for models showing high levels of muticollinearity or when you want to automate certain parts of model selection, like variable selection/parameter elimination.


Elastic Net Regression-

Elastic net is always preferred over lasso & ridge regression because it solves the limitations of both methods, while also including each as special cases.
Both Ridge and Lasso are combined to get a hybrid regularization technique called as elastic net.
In Lasso, some of the coefficients can be zero, means that it does variable selection as well. Lasso penalizes coefficients unlike ridge (which penalizes squares of coefficients)


