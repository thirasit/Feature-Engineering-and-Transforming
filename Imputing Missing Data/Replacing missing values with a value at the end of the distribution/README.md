# **Replacing missing values with a value at the end of the distribution**

Replacing missing values with a value at the end of the variable distribution is equivalent
to replacing them with an arbitrary value, but instead of identifying the arbitrary values
manually, these values are automatically selected as those at the very end of the variable
distribution. The values that are used to replace missing information are estimated using
the mean plus or minus three times the standard deviation if the variable is normally
distributed, or the inter-quartile range (IQR) proximity rule otherwise. According to the
IQR proximity rule, missing values will be replaced with the 75th quantile + (IQR * 1.5) at
the right tail or by the 25th quantile - (IQR * 1.5) at the left tail. The IQR is given by the 75th
quantile - the 25th quantile.
