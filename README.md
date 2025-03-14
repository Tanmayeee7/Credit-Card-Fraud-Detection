Dataset used in this project is from Kaggle, which contains a set of transactions having no null or missing values. If the class of a particular transaction is zero, it indicates that the transaction taken under consideration is legitimate. However, class equal to one indicates fraudulent exchange.

The dataset was highly imbalanced as more than 90% data points were present in the legitimate transactions class. Under-sampling was used to produce a balanced dataset of 492 points. Logistic Regression was preferred due to its simplicity and effectiveness in binary classification problems. However, it was noticed that the accuracy score of the model was less than 0.75. Thus, random forest classifier was opted – with estimators set to 100. Evaluation metrics included precision, recall, F1 score. The accuracy on test data was found out to be 0.928 while ROC-AUC score turned out to be the highest: 0.9728. 

