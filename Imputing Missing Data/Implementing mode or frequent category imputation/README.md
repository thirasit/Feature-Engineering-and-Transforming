# **Implementing mode or frequent category imputation**

Mode imputation consists of replacing missing values with the mode. We normally use this
procedure in categorical variables, hence the frequent category imputation name. Frequent
categories are estimated using the train set and then used to impute values in train, test,
and future datasets. Thus, we need to learn and store these parameters, which we can do
using scikit-learn and Feature-engine's transformers; in the following work, we will learn
how to do so.
