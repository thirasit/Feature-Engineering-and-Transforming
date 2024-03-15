# **Replacing categories with ordinal numbers**

Ordinal encoding consists of replacing the categories with digits from 1 to k (or 0 to k-1,
depending on the implementation), where k is the number of distinct categories of the
variable. The numbers are assigned arbitrarily. Ordinal encoding is better suited for nonlinear machine learning models, which can navigate through the arbitrarily assigned digits
to try and find patterns that relate to the target.
In this work, we will perform ordinal encoding using pandas, scikit-learn, and Featureengine.
