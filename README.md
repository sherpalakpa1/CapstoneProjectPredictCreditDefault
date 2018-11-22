# CapstoneProjectPredictCreditDefault
Predict Credit Default
The data set consists of 
30,000 rows of records with 25 columns. You can download the excel file to acquire the data from the website. 
 
The Data Set includes following data from the client which will help us to create different machine learning models:- 

➢ Client ID: Unique number used as identity of the clients. 

➢ X1: Amount of the given credit (NT dollar): Limit_Balance 

➢ it includes both the individual consumer credit and his/her family (supplementary) credit. 

➢ X2: Gender (1 = male; 2 = female).  

➢ X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).  

➢ X4: Marital status (1 = married; 2 = single; 3 = others).  

➢ X5: Age (year).  

➢ X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:  

➢ X6 = the repayment status in September, 2005  

➢ X7 = the repayment status in August, 2005 

➢ X8 = the repayment status in July, 2005 

➢ X9 = the repayment status in June, 2005 

➢ X10 = the repayment status in May, 2005 

➢ X11 = the repayment status in April, 2005. 

➢ The measurement scale for the repayment status is:- 

➢ -1 = pay duly 

➢ 1 = payment delay for one month 

➢ 2 = payment delay for two months 

➢ 3 = payment delay for three months 

➢ 4 = payment delay for four months 

➢ 5 = payment delay for five months 

➢ 6 = payment delay for six months 

➢ 7 = payment delay for seven months 

➢ 8 = payment delay for eight months 

➢ 9 = payment delay for nine months and above.  

➢ X12-X17: Amount of bill statement (NT dollar).  

➢ X12 = amount of bill statement in September, 2005 

➢ X13 = amount of bill statement in August, 2005 

➢ X14 = amount of bill statement in July, 2005 

➢ X15 = amount of bill statement in June, 2005 

➢ X16 = amount of bill statement in May, 2005  

➢ X17 = amount of bill statement in April, 2005 

➢ X18-X23: Amount of previous payment (NT dollar). 

➢ X18 = amount paid in September, 2005 

➢ X19 = amount paid in August, 2005 

➢ X20 = amount paid in July, 2005 

➢ X21 = amount paid in June, 2005 

➢ X22 = amount paid in May, 2005 

➢ X23 = amount paid in April, 2005 

➢ Y(default Payment) 1 for yes and 0 for no


• Approach 1: I updated and modified bad data and outliers. 

• Approach 2: I dropped bad data and outliers. 

• Approach 3: I replaced bad data with mode value and outliers with median

Compare Different Machine Learning Models 

• Logistic Regression 

• Decision Tree 

• Gaussian Naïve Bayes Classifier 

• Random Forest Classifier 

• Support Vector Machine

Class Imbalance Folder has 3 ipybn files:

CapstoneProject1ClassImbalanceApproach1, CapstoneProject1ClassImbalanceApproach2, and CapstoneProject1ClassImbalanceApproach3 which includes the code for the project. The jpeg files are the image of different plot.
