# Customer-Segmentation-using-LightGBM-Classifier  

*LightGBM* : A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks.  

## Dataset  
Dataset can be accessed from <a href="https://datahack.analyticsvidhya.com/contest/janatahack-customer-segmentation/True/#ProblemStatemen">Analytics Vidhya Janatahack: Customer Segmentation event</a> or it can be downloaded from <a href="https://drive.google.com/drive/folders/1ttqAVPA-MQ-Kaj02Ul_rqjqjIO8SOhum?usp=sharing">here</a>.  

Data consists of:
* Train_aBjfeNk.csv
* Test_LqhgPWU.csv
* sample_submission_wyi0h0z.csv

*<b>Train_aBjfeNk.csv</b>* : It consists of 11 features:  
           1) ID	-Unique ID  
           2) Gender - Gender of the customer  
           3) Ever_Married - Marital status of the customer  
           4) Age - Age of the customer  
           5) Graduated - Is the customer a graduate?  
           6) Profession - Profession of the customer  
           7) Work_Experience	- Work Experience in years  
           8) Spending_Score - Spending score of the customer  
           9) Family_Size - Number of family members for the customer (including the customer)  
           10) Var_1	- Anonymised Category for the customer  
           11) Segmentation	- (target) Customer Segment of the customer  

## Problem Statement  
An automobile company has plans to enter new markets with their existing products (P1, P2, P3, P4 and P5). After intensive market research, they’ve deduced that the behavior of new market is similar to their existing market. 

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy on new markets and have identified 2627 new potential customers. 

You are required to help the manager to predict the right group of the new customers.  

## Strategy  
1) Explore the dataset, find Basic stats for the important features
2) Replace/Drop missing values
3) Label Encoding for the Categorical Features {'Gender' , 'Ever_Married' , 'Graduated','Profession','Spending_Score','Var_1'}  
4) Split Data into Train and Test Data  
5) Model Prediction
6) Find Accuracy on Train and Test data
7) Print Confusion Metrices and Classification Metrices
8) Generate and Save/Download Submission file  
 
<b>Note:</b>  
*sample_submission_wyi0h0z.csv* has two attributes:  

ID: Unique ID  
Segmentation: Predicted segment for customers in the test set  
