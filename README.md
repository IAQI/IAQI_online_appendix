# online_appendix
This is an online appendix for the academic paper "Predicting Audit Failure Using Machine Learning"

## Tuned Models 
Test Year is the year of the hold-out testing sample. Suppose test year is t, then the model is tuned based on sample spanning from t-6 to t-2 with t-2 as the hold-out validation set. The details of sample splitting for hyperparameter tuning are provided in Figure 1 of the paper. 

Misclassification cost ratio is the ratio between false-negative and false-positive errors. This ratio is used in the undersampling procedure performed on the non-audit-failure instances in the training set. Details are provided in the Appendix of the paper. 

Algorithm indicates the algorithms: AB is AdaBoost, LR is logistic regression, GB is Gradient Boosting, XGB is Extreme Gradient Boosting, SVM is support vector machine,  RF is random forest. 

Tuned Model is the hyperparameter-tuned model.
