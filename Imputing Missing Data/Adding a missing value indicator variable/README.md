# **Adding a missing value indicator variable**

A missing indicator is a binary variable that specifies whether a value was missing for an
observation (1) or not (0). It is common practice to replace missing observations by the
mean, median, or mode while flagging those missing observations with a missing
indicator, thus covering two angles: if the data was missing at random, this would be
contemplated by the mean, median, or mode imputation, and if it wasn't, this would be
captured by the missing indicator. In this work, we will learn how to add missing
indicators using NumPy, scikit-learn, and Feature-engine.
