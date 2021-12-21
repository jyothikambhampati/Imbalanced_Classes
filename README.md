# Imbalanced_Classes

This master thesis is a study about handling an imbalanced classification problem where
atleast one of the classes constitutes only a very small minority of the data. In this
thesis, we have evaluated the performance of various linear and non-linear classifiers
such as logistic regression, LDA, random forest, support vector machines etc and
reviewed methods such as joint sampling techniques, alternative cutoffs for classifiers
thresholds to deal with imbalanced classification. We identified the few performance
metrics such as precision, recall, F-score in order to evaluate classifier performance
when combined with methods dealing with imbalance. We applied our learning’s to a
case study based on bank marketing data after data pre-processing including feature
selection methods based on RFE, Boruta and XGBoost. Processed data is used to create
new balanced datasets using joint sampling techniques such as SMOTE, NCL, Tomek,
K-means clustering which are then feeded as input to the classifier. With this approach,
we realized there is information loss as we are modifying the data in order to remove
imbalance and it is challenging to find how much amount of sampling has to be done.
We then reviewed another alternative approach of finding optimal threshold used by
classifier using ROC and PR curves. We established maximizing F-score using PR
curve as a better alternative to find the optimal value for cut off. With this approach, we
were able to overcome the problem of information loss seen with joint sampling
methods.
Keywords: Imbalanced data, Machine Learning, Over/Under Samplings, Classification,
Optimal Threshold, ROC / PR curve, Feature selection.
