# Loan-Approval-System-using-Machine-Learning

Purpose: Through this machine learning model, the likelihood of an applicant's portfolio being rejected or accepted is determined based on various features and the effect is computed for better understanding 

Dataset Details: The Loan Approval Dataset is used with 1000 rows and 20 columns 

Technologies used: Matplotlib & Seaborn are used for human-level understanding of a complex dataset, and the data is processed with the NumPy & Pandas libraries; Sklearn with additional functions is utilised for completion of the project 

Preprocessing Performed: Performed Exploratory Data Analysis: Eliminated duplicate samples, Simple imputer function to apply strategy on every column, Encoding: OneHotEncoder & LabelEncoder, Feature Scaling  

Models used/tried: Used KNeighborsClassifier, Naive Bayes and LogisticRegression based on various comparison parameters to obtain the best model 

Evaluation parameters used: Accuracy Score, F1 Score, Precision, Recall & Confusion Matrix 

Result: 
Accuracy and Precision obtained for every model: 
1. KNN Accuracy Score = 76% , KNN Precision Score = 62%
2. LogisticRegression Accuracy Score = 86% , LogisticRegression Precision Score = 78%
3. Naive Bayes Accuracy Score = 80 % , Naive Bayes Precision Score = 80 %

LogisticRegression gave a better accuracy than KNN, but Naive Bayes gave the best result among all  

Future Scope: Feature Engineering can be conducted to improve the model accuracy 
