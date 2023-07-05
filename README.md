# Credit-Fraud-Detection
Link Rpubs : https://rpubs.com/Ilyashaikall/CreditFraudDetection

1. Introduction
   
The purpose of this project
Every year, fraudulent transactions with credit cards result in billions of dollars in losses. The key to minimizing these losses is the development of effective fraud detection algorithms, and increasingly, these algorithms depend on cutting-edge machine learning methods to assist fraud investigators. However, designing fraud detection algorithms is particularly challenging due to the non-stationary distributions of the data, the extremely imbalanced classification distributions, and the continuous streams of transactions. Moreover, obtaining publicly available information is difficult due to confidentiality concerns, which leaves many questions unanswered regarding how to approach this problem

Some facts you need to know about Credit Card Fraud
- Over 127 million adults in America, which is nearly half of the population, have encountered fraudulent transactions on their credit or debit cards. This highlights the widespread nature of card fraud and its impact on individuals.

- More than one in three people who use credit or debit cards have experienced card fraud multiple times. This indicates that card fraud is not an isolated incident but a recurring problem for a significant portion of card users.

- The average fraudulent charge on American credit and debit cards amounts to $62 per transaction. This translates to an estimated total of approximately $8 billion in attempted fraudulent transactions. This staggering amount underscores the financial impact and magnitude of card fraud.

- Only around 40% of cardholders have activated email or text notifications from their banks or credit card issuers. This means that a large percentage of cardholders may not receive immediate alerts about potentially fraudulent activities on their cards.

- Among the victims who have enabled notifications, only 19% had to take further action to reverse fraudulent charges. In contrast, approximately 81% of victims who did not have these warnings had to undertake additional measures. This indicates the effectiveness of timely notifications in minimizing the potential consequences of fraudulent charges.

Why can this machine learning model be useful for Credit Fraud Detection?
To find patterns of fraud, credit card fraud detection (CCFD) needs to analyze vast amounts of transaction data. Due to the large data volumes and the constantly evolving tactics of fraudsters, human investigators are unable to effectively address this issue. Over the past decade, machine learning (ML) methods have become an increasingly important component of CCFD as they enable searching and detecting patterns in extensive data sets. It has been demonstrated that ML algorithms can significantly enhance the effectiveness of fraud detection systems and aid fraud investigators in identifying fraudulent transactions.

The model that demonstrates the highest predicted performance in detecting fraud within a specific set of transactions is considered the optimal model for a fraud detection system. By leveraging historical credit card transaction data, we attempted to estimate and predict future fraudulent transactions. Consequently, if fraudulent activities can be forecasted, it would assist fraud investigators in better proposing policies for real-world regulations.

2. Dataset Overview
ULB’s dataset from Kaggle -> (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

The dataset contains credit card transactions done by European cardholders in September 2013. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is quite unbalanced, with frauds making up 0.172% of all transactions in the positive class (frauds) account. There are 284807 observations and 31 columns in this dataset. There are 1 response variable and 30 predictor variables. Additionally, 30 of them are numerical, while 1 is binary. The response variable, “Class,” has a value of 1 in cases of fraud and 0 in all other cases.
