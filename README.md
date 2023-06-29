# Fraud Detection
This project analyzes and models large datasets to develop algorithms that can identify fraudulent activities, helping businesses mitigate financial risks It provides a set of tools and algorithms to 
identify and flag fraudulent activities based on a given dataset.

# Overview
The Fraud Detection project is designed to help identify and detect fraudulent activities in a given dataset. 
It leverages machine learning algorithms to learn patterns and behaviors associated
with fraudulent transactions, and then uses this knowledge to predict and flag potential fraud.

The project includes a collection of scripts and modules 
that handle various aspects of fraud detection, including 
data preprocessing, model training, evaluation, and prediction. 
It aims to provide an end-to-end solution for fraud detection tasks.

# Dataset
The project assumes a specific dataset format for training and evaluation.
The dataset should be a structured file (e.g., CSV) containing relevant information about each transaction,
including features and labels. Ensure that your dataset adheres to the required format to ensure proper data preprocessing and model training.

 Kindly mail me at brenmathew10@gmail.com for this specific dataset.

# Questions answered:

1.Data cleaning including missing values, outliers and multi-collinearity
 - As the data was normally organized, We did not have a necessity to do high level data cleaning. Although, we dropped the rows with NaN values. We also split the data during data and validation sets. Hence, the data cleaning part was done on a lower level.

2. Describe your fraud detection model in elaboration.
- The fraud detection model used in the code is a Random Forest Classifier. It was trained on a dataset that was preprocessed by converting categorical variables into numerical variables, splitting the dataset into training and validation sets and scaling the numerical variables. The performance of the model is evaluated using metrics such as accuracy, precision, recall, and f1-score.

3. How did you select variables to be included in the model?
- The variables were selected based on their relevance to the target variable, which is 'isFraud'. The 'type', 'amount', 'nameOrig', 'oldbalanceOrg', 'newbalanceOrig', 'nameDest', 'oldbalanceDest', and 'newbalanceDest' were included in the model as they are relevant in detecting fraudulent transactions.

4. Demonstrate the performance of the model by using best set of tools
- The performance of the model is good, achieving an accuracy of 0.999 and a precision of 1.00 on the validation set. The confusion matrix shows that the model predicted all non-fraudulent transactions and correctly identified 11 out of 34 fraudulent transactions.

5. What are the key factors that predict fraudulent customer?
- The key factors that predict fraudulent customers are the transaction amount, old and new balance of the origin account, old and new balance of the destination account, and the type of transaction.

6. Do these factors make sense? If yes, How? If not, How not? 
- Yes, these factors make sense as fraudulent transactions usually involve large amounts of money and transactions between unknown accounts or accounts with no prior history of interaction.

7. What kind of prevention should be adopted while company update its infrastructure?
- To prevent fraud, the company should implement measures such as monitoring a user's behavior, setting transaction limits and implementing 2-factor authentication. The company should also improve its infrastructure, including implementing fraud detection software, regularly monitoring an account activity, conducting regular training for employees to identify potential fraud and improving the overall security.

8. Assuming these actions have been implemented, how would you determine if they work?
- To determine if these actions have been effective, the company should track the number of fraudulent transactions detected over time and compare it to the previous rate. They can also conduct regular audits to identify gaps in the existing fraud prevention measures and take corrective actions to work on them.


