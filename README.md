# credit-risk-classification

The purpose of this analysis is to use machine learning to predict whether a loan is healthy or high-risk. The dataset used to train the model contains data from over 70,000 loans. The variables considered are loan size, interest rate, borrower income, debt-to-income, number of accounts, derogatory marks, and total debt along with a denotation of whether the loan is healthy or high-risk.


The results of the Classification Report are as follows:

- Precision (healthy loans): 1.00
	A precision of 1.00 means that of all the loans predicted to be healthy, all of them indeed were healthy loans.
- Recall (healthy loans): 1.00
	A recall of 1.00 means that the model is able to correctly identify nearly all of the healthy loans.
- Precision (high-risk loans): 0.86
	A precision of 0.86 means that of all the loans predicted as high-risk, the majority of them were in fact high-risk.
- Recall (high-risk loans): 0.91
	A recall of 0.91 means that the model is able to correctly identify the majority of high-risk loans.
- Accuracy: 0.99
	Accuracy of 0.99 indicates that the model's overall performance in terms of precision and recall is very high.
	

Overall, I highly recommend the use of this model for evaluating the risk of loans. The model is nearly perfect when identifying healthy loans and has great performance when identifying high-risk loans. This means that the chances of incorrectly identifying a high-risk loan as healthy are very slim. For this reason companies can use this model with high confidence that they won't be approving loans that are unnecessarily risky.