# CreditCardFraudDetection
The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

Credit card Fraud Detection necessitates the use of an ML-based algorithm to accomplish feature extraction and model evaluation. In this project, three machine learning techniques: Random Forest, Linear Regression, and K-Means Clustering are compared and analysed by utilizing the dataset from Kaggle that contains transactions made by credit cards September 2013 by European cardholders to create a fraud transaction detection system.

Following is the methodology employed by this project:
 
Figure 1: Methodology
<img width="472" alt="image" src="https://github.com/pratik3336/CreditCardFraudDetection/assets/76115015/ac5e0712-ecbb-4a88-a55b-3f77a0543c49">


Credit card transactions by European cardholders in September 2013 are contained in this dataset. A total of 492 frauds were detected out of 284,807 transactions that occurred over a two-day period. There is a high degree of unbalance in the dataset. There are 0.172% of all transactions that are classified as positive (frauds). 
Several numerical variables are contained in it, which are the results of a PCA transformation. Data features, background information, and original features have unfortunately been withheld due to confidentiality issues. With PCA, the principal components are V1, V2, ... V28. The table below outlines the features that were not calculated through the PCA algorithm.


In order to address the problem of data imbalance in the credit card fraud detection dataset, this research used three different models: Random Forest Classification, Linear Regression, and XGBoost. The real values were under sampled to 3000 while the fraudulent values were oversampled to 3000 in order to balance the imbalance. Then, a 70:30 split between the training and test sets was applied to the dataset.
The models were trained on the training set, and the accuracy of their predictions on the testing set was used to gauge their performance. When compared to the Linear Regression model, which performed well in terms of accuracy, precision, and how it appeared on the Confusion Matrix and ROC Curves, the Random Forest Classifier and XGBoost models showed overfitting.
Based on these results, it can be said that the Linear Regression model performed better than the other two models and is the best choice for this project's evaluation of credit card fraud transactions.



