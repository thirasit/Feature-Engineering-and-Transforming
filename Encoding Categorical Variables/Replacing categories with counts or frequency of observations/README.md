# **Replacing categories with counts or frequency of observations**

In count or frequency encoding, we replace the categories with the count or the percentage
of observations with that category. That is, if 10 out of 100 observations show the category
blue for the variable color, we would replace blue with 10 when doing count encoding, or
by 0.1 if performing frequency encoding. These techniques, which capture the
representation of each label in a dataset, are very popular in data science competitions. The
assumption is that the number of observations per category is somewhat predictive of the
target. In this work, we will perform count and frequency encoding using pandas and Featureengine.
