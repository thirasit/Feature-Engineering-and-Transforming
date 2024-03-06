# **Performing multivariate imputation by chained equations**

Multivariate imputation methods, as opposed to univariate imputation, use the entire set of
variables to estimate the missing values. In other words, the missing values of a variable are
modeled based on the other variables in the dataset. Multivariate imputation by chained
equations (MICE) is a multiple imputation technique that models each variable with
missing values as a function of the remaining variables and uses that estimate for
imputation. In this work, we will implement MICE using scikit-learn.
