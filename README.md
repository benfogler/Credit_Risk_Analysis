# Credit_Risk_Analysis


## Overview of the analysis
The purpose of this analysis is to employ machine learning in order to reduce bias in predicting credit risk. To do so, we will use the
imbalanced-learn and scikit-learn libraries to build and evaluate our models. The result of this analsyis should conclude whether
the models should be used to predict credit risk.


## Results

### Naive Random Oversampling Model

* Balanced accuracy score is .65 as seen in snippet below

![Naive](https://user-images.githubusercontent.com/114610539/221435150-77da7ada-32e5-4b8e-b11f-619a773eb991.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .62

![Naive_imbalanced](https://user-images.githubusercontent.com/114610539/221435153-281b7b16-eb58-4c95-b990-ba8ea5872347.png)



### SMOTE Oversampling Model

* Balanced accuracy score is .66 as seen in the snippet below

![smote_balanced](https://user-images.githubusercontent.com/114610539/221435156-4549d3a0-0016-400e-bdfc-81262c9331bc.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .69
![smote_imbalanced](https://user-images.githubusercontent.com/114610539/221435166-42eac152-1283-436c-8233-fa65466c60bf.png)


### Undersampling Model

* Balanced accuracy score is .54 as seen in the snippet below

![undersampling_balanced](https://user-images.githubusercontent.com/114610539/221435168-2a2768a6-daf1-4d77-bb43-5be42dcba1d1.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .40

![undersampling_imbalanced](https://user-images.githubusercontent.com/114610539/221435175-c0c79379-61a8-4c75-95e3-8e0ea10a482c.png)


### Over and Under Sampling Model

* Balanced accuracy score is .64 as seen in the snippet below

![combo_balanced](https://user-images.githubusercontent.com/114610539/221435180-653bfb05-2b30-4709-9c52-dbd2b70ab08a.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .57
![combo_imbalanced](https://user-images.githubusercontent.com/114610539/221435202-acc2c7f3-e60a-4463-8b40-c76944e48a47.png)


### Balanced Random Forest Classifier

* Balanced accuracy score is .79 as seen in the snippet below

![brfc_balanced](https://user-images.githubusercontent.com/114610539/221435209-e697be43-8157-4aab-893f-12e9e2b31717.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .87
![brfc_imbalanced](https://user-images.githubusercontent.com/114610539/221435213-0187621a-67dc-483c-8c5e-34f760a74603.png)



### Easy Ensemble AdaBoost Classifier

* Balanced accuracy score is .93 as seen in the snippet below

![easy_adaboost_balanced](https://user-images.githubusercontent.com/114610539/221435216-f4031d7c-c550-4452-809b-09737a217e97.png)


* Imbalanced accuracy report shows average precision to be .99 and a recall score of .94

![easy_adaboost_imbalanced](https://user-images.githubusercontent.com/114610539/221435220-d48c78f2-ddc8-418f-b1a9-f64b93ee32e5.png)



## Summary

Looking at the results we can see that the average precision across all is .99, and that the two models with the highest
recall scores were both ensemble. The model also reflects them having the highest balanced accuracy scores.

With this, my recommendation would be that the best models to use for unbias predictions would be the two ensemble classifiers.





