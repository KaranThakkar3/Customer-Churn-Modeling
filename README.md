# Customer-Churn-Modeling
## Context 
Customer churn can have a significant impact on a bank's bottom line. Losing customers means losing out on potential revenue and incurring costs associated with acquiring new customers. Hence, the bank wants to predict which customers are at risk of churning and take proactive steps to retain them. 

## Dataset Description
The Bank Customer Churn Prediction dataset contains information about bank customers such as their credit score, age, gender, estimated salary, etc. The dataset has 14 columns, including a unique identifier for each customer. The target variable for this dataset is **'Exited'**, which indicates whether a customer has churned or not

Dataset can be downloaded from here: https://www.kaggle.com/code/kmalit/bank-customer-churn-prediction

## Project Structure
The project is divided into 3 parts:   
&emsp; **Part 1:** Exploratory data analysis (EDA) was performed to gain preliminary insights to the data.  
&emsp; **Part 2:** Selecting the appropriate machine learning algorithm. Following methods were tested:   

        • Logistic Regression          
        • Random Forest
        • Support Vector Machine (SVM)
&emsp; **Part 3:** Evaluating the model's accuracy and other evaluation metrics to determine the most appropriate model. Since the business context is to be able to correctly identify a high proportion of customers who are likely to churn or close their accounts in the future, we shall be focusing on the 'Recall' metric which indicates the model's ability to correctly identify a high proportion of customers who are likely to churn. 

Complete python code can be found here: [churn_prediction](https://github.com/KaranThakkar3/Customer-Churn-Prediction/blob/main/Python%20Notebook/Customer%20Churn%20Prediction.ipynb)
