![](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwi2uvPh647nAhVHRKwKHXzDDk8QjRx6BAgBEAQ&url=https%3A%2F%2Fwww.retentionscience.com%2Fblog%2Ftop-4-reasons-customers-churn-and-how-to-prevent-it%2F&psig=AOvVaw1XWqHlV6ub6Gom6p1KvZei&ust=1579494823245733)

Customer churn rate is the percentage of customers or subscribers who cancel or don't renew their subscriptions during a given time period. The aim of this project is to find patterns in customer churn and identify customers who might churn in near future based on data provided.

I tried to analyze the possible reasons of a telecom user churn and find key churn identifiers. Mainly, the following hypothesis are tested in this project:
1. Is it because of poor service quality?
2. Are there behavior or demographic trends?
3. Could logistic issues be large factors? 

The key findings from this exercise are:
1. Low end phone users are more churn prone with a very short life span of less than a year.
2. As the age of the device increases, monthly usage of the device decreases, and eventually leads to churn.
3. Local Residents are more loyal while foreigners are churn prone.

Random Forest and XGBoost Classifiers are used to to predict customer churn. The random forest had an out of sample AUC score of 0.683 while XGBoost model gave an out of sample AUC score of 0.693. The models identified Age of Equipment, Months of Service and Handset Price as the most important features.

Based on the provided data, here are my recommendations for the company:
1. Provide better phone upgrade deals - would help retaining low end phone users as well as keep old phone users engaged
2. Re-evaluate pricing models and incentivize customer retention for identified churn customer pool
