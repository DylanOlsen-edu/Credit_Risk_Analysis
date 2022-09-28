# Credit_Risk_Analysis
Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this Challenge, I will use various techniques to train and evaluate models with imbalanced classes. I will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* Linear Regression vs Resampled Logistic Regression Model(s)
  * Linear Regression
    * Balanced Accuracy Score
      * 92.2%
    * Precision/Recall (Healthy Loans)
      * 100%/99%
    * Precision/Recall (High-Risk Loans)
      * 85%/91%
  * Resampled Logistic Regression
    * Balanced Accuracy Score
      * 99%
    * Precision/Recall (Healthy Loans)
      * 99%/99%
    * Precision/Recall (High-Risk Loans)
      * 99%/99%
## Summary
The logistic regression model predicted healthy loans(0) with 100 percent accuracy with 99 percent recall. Because high risk loans have a smaller sample size, the model predicted high-risk loans(1) with 85 percent accuracy and 91 percent recall. To make a more clear prediction, we use the oversampling technique with a logistic regression model. The resampled logistic regression model was able to predict both healthy/high-risk loans with 99% accuracy/recall.
    
