# Sms-Spam-detection
Summary of Findings
Introduction
In this analysis, four machine learning models were evaluated for spam detection in SMS messages: Logistic Regression, Naive Bayes, Support Vector Machine (SVM), and Random Forest. The goal was to determine the most effective model based on various
performance metrics.

Model Performance Metrics
Here's a summary of the performance metrics for each model:

In [27]:
Model Accuracy Precision	Recall F1 Score	ROC AUC
0 Logistic Regression 0.954260	0.99 0.664430 0.795181 0.986167
1	Naive Bayes 0.955157	1.00 0.664430 0.798387 0.970855
2	SVM 0.980269	1.00 0.852349 0.920290 0.986938
3	Random Forest 0.970404	1.00 0.778523 0.875472 0.987821

Findings

Best Performing Model: The SVM model achieved the highest scores across most metrics, including Accuracy (0.9803), Recall (0.8523), and F1 Score (0.9203),
indicating it is the most effective model for spam detection.
Logistic Regression: This model provided balanced performance with good precision (0.99) but lower recall (0.6644).
Naive Bayes: Excellent precision (1.00) but similar recall to Logistic Regression, resulting in a slightly lower F1 Score.
Random Forest: Strong performance with high accuracy (0.9713) and good recall (0.7852), though slightly lower than SVM.
