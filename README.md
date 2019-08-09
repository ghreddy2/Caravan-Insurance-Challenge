# Caravan-Insurance-Challenge
Identify potential purchasers across various locations of USA who might purchase insurance policies of caravan insurance company.

### Problem Statement
Can you predict who would be interested in buying a caravan insurance policy and give an explanation why?

One can find the dataset and the details here: https://www.kaggle.com/uciml/caravan-insurance-challenge

### What One can find here...
Functions to make our task easy to understand(with visualizations) how our data is... 

### Feature selection- Why?
-Reduces Overfitting
-Improves accuracy
-Reduces training time
So, we have used Information value with the help of Weight of evidence.
We have chosen 18 variables after doing this.

The data is a class imbalance problem. So, we have to do Over-sampling or Under-sampling.
So we have used SMOTE, SMOTE+Tomek links, SMOTE+ENN links, Random Over Sampling 

Classification problem- Logistic Regression, Decision Tree, Random Forest, Support Vector Machine.

Model Evaluation Techniques- Confusion Matrix, AUC-ROC Curve, F1-Score, Cohen Kappa Coefficient.

### Result
The highest values were obtained when SMOTE is combined with ENN and random forest classifier is applied on the data. The values are as follows:

F1- score :	0.989, Precision : 0.99, Recall :	0.99, Cohen-Kappa :	0.89, Accuracy : 0.948.
