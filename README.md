# credit-risk-classification

## Overview of the Analysis:
The purpose of this analysis is to evaluate and compare the performance of two logistic regression models for loan risk classification. The analysis assesses the models using the original dataset and a resampled training dataset. Key evaluation metrics include accuracy score, precision score, recall score, and f1-score.

## Results:
### Model 1 - Logistic Regression Model with Original Data:
* Accuracy Score: 95%
* Precision Score (Class 0 - Healthy Loan): 100%
* Precision Score (Class 1 - High-Risk Loan): 85%
* Recall Score (Class 0 - Healthy Loan): 99%
* Recall Score (Class 1 - High-Risk Loan): 91%
* f1-Score (Class 0 - Healthy Loan): 100%
* f1-Score (Class 1 - High-Risk Loan): 88%

### Model 2 - Logistic Regression Model with Resampled Training Data:
* Accuracy Score: 99%
* Precision Score (Class 0 - Healthy Loan): 100%
* Precision Score (Class 1 - High-Risk Loan): 84%
* Recall Score (Class 0 - Healthy Loan): 99%
* Recall Score (Class 1 - High-Risk Loan): 99%
* f1-Score (Class 0 - Healthy Loan): 100%
* f1-Score (Class 1 - High-Risk Loan): 91%

## Summary:
The logistic regression models were used for loan risk classification, and their performance was evaluated using the original dataset and a resampled training dataset.

Model 1, trained on the original data, achieved a commendable accuracy score of 95%. It demonstrated excellent precision in predicting Class 0 (healthy loan) with a score of 100%, indicating a low number of false positives. However, the precision score for Class 1 (high-risk loan) was slightly lower at 85%, suggesting a relatively higher number of false positives. The recall score for both classes was good, with 99% for Class 0 and 91% for Class 1. The f1-scores for Class 0 and Class 1 were 100% and 88%, respectively.

Model 2, trained on a resampled training dataset, exhibited significantly improved performance with an accuracy score of 99%. It maintained a perfect precision score for Class 0 (healthy loan), indicating an ability to reliably identify non-risky loans. The precision score for Class 1 (high-risk loan) decreased slightly to 84%, implying a marginally higher number of false positives. However, the recall score for Class 1 increased to an impressive 99%, meaning the model effectively captures the majority of actual high-risk loans. The f1-scores for Class 0 and Class 1 were both high, with 100% and 91%, respectively.

Based on the results, it is recommended to use Model 2, the Logistic Regression Model with Resampled Training Data. This model achieved a higher accuracy score and demonstrated consistent precision, recall, and f1-scores for both classes. Its ability to accurately identify both healthy and high-risk loans is crucial for minimizing false positives and effectively mitigating potential risks. The higher recall score for Class 1 also indicates its ability to capture a larger proportion of actual high-risk loans, which is vital for risk assessment and decision-making processes.
