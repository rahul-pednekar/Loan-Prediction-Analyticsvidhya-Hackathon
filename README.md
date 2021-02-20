# Loan-Prediction-Analyticsvidhya-Hackathon
Top 2%  - Loan Prediction Hackathon 

**What are we going to solve ?**
Predict Loan Eligibility for Dream Housing Finance company
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. 
To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.


**To summarize :** In Data Science terms ,this problem falls into the category of "Binary Classification" problem in which the target variable (Loan status) (Which we are supposed to predict) can have two values ("Yes" OR "No")

**Training dataset :** It consists of details of the customer (like Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.) along with the target column which is Loan_Status with values :
 1.  'Y': If Loan is approved 
  2. 'N': If Loan is Not Approved
**Test Dataset :** It consists of similar details for new customers (like Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.) , however without the target column (i.e. Loan_Status)
Using the training dataset we need to prepare a Machine Learning model which will predict the Loan_Status for the customers in the test dataset 
(i.e. For each customer in the test dataset predict whether the loan application will get approved or not)

**What would be the Strategy ? **

Divide the solution approach in simple 9-steps and execute them one after the other
1. Load essential Python Libraries 
2. Load Training/Test datasets in Python environment.
3. Prepare submission file and remove unwanted columns.
4. Exploratory data analysis (EDA).
5. Impute Missing values.
6. Feature Engineering.
7. Build Machine Learning Model & Make prediction on test dataset 
8. Prepare submission file with final prediction
9. Conclusion and Takeaways
