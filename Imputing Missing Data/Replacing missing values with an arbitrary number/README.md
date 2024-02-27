# **Replacing missing values with an arbitrary number**

Arbitrary number imputation consists of replacing missing values with an arbitrary value.
Some commonly used values include 999, 9999, or -1 for positive distributions. This method
is suitable for numerical variables. When replacing missing values with an arbitrary number, we need to be careful not to
select a value close to the mean or the median, or any other common value of the
distribution. In this work, we will impute missing data by arbitrary numbers using pandas, scikit-learn,
and Feature-engine.
