#  📑 AI Model to detect medical insurance fraud
### **Experience solving problems by training multiple classification models**
***
## ✔ This project has two main objectices
>* ### Our goal is to create a fair and trustworthy insurance system.   
>* ### We hope to create a safer and more efficient system that benefits both insurance companies and customers.   
  
 ***
## ✔ Main part in project
>* ### Data Preprocessing
>     >#### a) [Using Medical Insurance Claim Fraud Dataset provided by Kaggle](https://www.kaggle.com/datasets/nyashachizampeni/medical-insurance-claim-fraud)
>     >#### b) Checking Missing Values   
>     >#### c) Categorical variables are processed using one-hot encoding   
>     >#### d) Transforming age data extraction from patient_dom   

  🔗 After we picked Classification Model   
    e) Using Scaler (StandardScaler, MinMaxScaler)  
    f) 2-dimensional reduction principal component analysis PCA  
    // We added various methods because we hoped to enhance the model's accuracy.  


>* ### Used feature
>     >#### gender : most basic feature
>     >#### location : where most fraudulent customers are located
>     >#### patient_dob : customer date of birth
>     >#### cause : insurance status cause // We can check that many fraud customer usually say reason of the joining to insurance.
>     >#### Fee Charged : be added fee // 수수료 따라서 사기 여부를 파악할 수 있는 힌트가 될 수 있음
>     >#### membership_preiod : terms of medical insurance membership
>     >#### number_of_claims : count medical insurance fraud
>     >#### number_of_dependants : the size of a dependant // 부양 수에 따라 사기 여부를 파악할 수 있을 것 같아서
>     >#### label : label means result of 0 or 1 
>  It contains 15 variables, including gender, age, cause of accident, claim amount, and fraud status.
This data serves as the foundation for training machine learning models to classify fraudulent and genuine claims.
Other feature excluded because we can effectively model learning by excluding.   
  
>* ### Train several classification models
>     >#### a) xgboost -- We used   
>     >#### b) RandomForestClassifier   
>     >#### c) Voting   
>     >#### d) LGBM Classifier   
>     >#### e) Logistic Regression    
>     >#### f) Decision Tree   
       
  >* ### To imporve the model's performance
  >   >#### a) Modification of preprocessing process like e,f in Data Preprocessing part   
  >   >#### b) Attemptes to tune the optimal hyperparameters by GridSearchCV
     
  >* ### To create webpage using Flask
>  We used pycharm to create webpage.  But, It's not perfect yet Because result.html don't bring data learning results...😭 // This is unresolved issues in our project.
  
***
## ✔ Limitations
 >* #### No significant change in the accuracy -- Almost Accuracy is about 0.80 //so we are ROC curve is very bad :( 


***
### **We felt that we needed to study more on our project 💻**
  
  

  
