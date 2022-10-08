# Bank-Analytics
Machine Learning Project to analyze bank customer data, and provide marketing analytics to the bank.

## Project Overview
Analyzed previous bank marketing campaign data to derive insights into different customer segments, built a machine learning model to predict if a customer subscribes to  a Term Deposit or not and give suggestions to target the right customers and increase the success rate of the marketing campaign.

## Algorithms
After the exploratory data analysis and the data preprocessing, the data was split into training and test data(20 percent) using Stratified Random Split technique.
Then the model was built with different algorithms initially, such as Logistic regression, Support Vector Machines, K-neighbours Classifiers, Decision Tree,Multi Layer Perceptron classifier, Gradient Boost, Random Forests, Gaussian Naive Bayes Classifiers. The accuracy's were tested and Gaussian Naive Bayes was finally selected to build the final model.

## Results and conclusions
1. Term Deposit Prediction: Our Model predicts with 84.6% Accuracy for new customers based on Data that whether he is going to opne a Term Deposit or Not.

2. Campaign Calls: Maximum 3 marketing calls should be placed to any potential customer.

3. Age : 20s or below that age or 60 and above are the best targets as the probability of success of marketing call is higher.

4. Occupation : Students and retired people are the best targets.

5. House Loan and Balances : We can observe that people with housing loans have a lesser balance, and hence have a lower probability of opening a term deposit. Hence people with no housing loans and higher balances are a better target for the marketing campaign.

6. Duration of call : We can notice that the duration of call is highly correlated to the customer opening a term deposit. The higher the call duration, the better the chances of opening a term deposit. Therefore, the sales agent should have an interactive call with the customer.

