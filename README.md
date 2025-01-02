#  📌 AI Model to detect medical insurance fraud
<Experience solving problems by training multiple classification models>

✔ This project has two main objectices
  • Our goal is to create a fair and trustworthy insurance system.
  • We hope to create a safer and more efficient system that benefits both insurance companies and            customers.
 
✔ Main part in project
  • Data Preprocessing
     a) Using Medical Insurance Claim Fraud Dataset provided by Kaggle
     b) Checking Missing Values
     c) Categorical variables are processed using one-hot encoding
     d) Transforming age data extraction from patient_dom

     ≻≻ After we picked Classification Model 
     e) Using Scaler (StandardScaler, MinMaxScaler)
     f) 2-dimensional reduction principal component analysis PCA
     // We added various methods because we hoped to enhance the model's accuracy.
     
  • Train several classification models
     a) xgboost -- We used 
     b) RandomForestClassifier
     c) Voting
     d) LGBM Classifier
     e) Logistic Regression 
     f) Decision Tree
       
  • To imporve the model's performance
     a) Modification of preprocessing process like e,f in Data Preprocessing part
     b) Attemptes to tune the optimal hyperparameters by GridSearchCV

✔ Limitations
  • No significant change in the accuracy -- Almost Accuracy is about 0.80 //so we are ROC curve is very bad :( 

We felt that we needed to study more on our project 💻
  
  

  
