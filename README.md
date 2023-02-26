# Credit_Risk_Analysis


## Overview of the analysis
The purpose of this analysis is to employ machine learning in order to reduce bias in predicting credit risk. To do so, we will use the
imbalanced-learn and scikit-learn libraries to build and evaluate our models. The result of this analsyis should conclude whether
the models should be used to predict credit risk.


## Results

### Naive Random Oversampling Model

* Balanced accuracy score is .65 as seen in snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .62




### SMOTE Oversampling Model

* Balanced accuracy score is .66 as seen in the snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .69


### Undersampling Model

* Balanced accuracy score is .54 as seen in the snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .40



### Over and Under Sampling Model

* Balanced accuracy score is .64 as seen in the snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .57


### Balanced Random Forest Classifier

* Balanced accuracy score is .79 as seen in the snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .87



### Easy Ensemble AdaBoost Classifier

* Balanced accuracy score is .93 as seen in the snippet below



* Imbalanced accuracy report shows average precision to be .99 and a recall score of .94




## Summary

Looking at the results we can see that the average precision across all is .99, and that the two models with the highest
recall scores were both ensemble. The model also reflects them having the highest balanced accuracy scores.

With this, my recommendation would be that the best models to use for unbias predictions would be the two ensemble classifiers.





