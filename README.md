# Credit-Card-Fraud-Detection
Utilize existing credit card fraud data from January 2019 to December 2020 and develop a machine learning model in PySpark to perform Big Data Analysis which inturn leads to the best prediction results in revealing and preventing fraudulent transactions.

## INTRODUCTION
In this modern era, there have always been people who 
will find new ways to access someone’s finances illegally. As
all transactions can easily be completed online with a credit
card, consumers, banks, and merchants are put at risk when
a data breach leads to monetary theft and ultimately the loss
of customers’ loyalty along with the company’s reputation.
Even after numerous mechanisms to stop fraud, fraudsters are
continuously trying to find new ways and tricks to commit
fraud.

## PROJECT OBJECTIVE

***A. Why fraud detection ?***

Consumers in 2020 reported losing over $3.3 billion to
fraud, an increase of $1.5 billion over the amount reported in
2019. Worldwide, businesses are expected to lose $75 billion
to e-commerce fraud from 2019 to 2023. In 2019, the U.S.
accounted for 33.57 percent of all gross card fraud losses
worldwide.

Credit card fraud represented the second most commonly
reported type of identity theft in 2020. In 2020, credit cards
were most frequently identified as the payment method in
fraud reports. According to Federal Trade Commission, there
were over 390k reports of credit card fraud in 2020 and
149M dollars were lost only in the United States. In 2020
the rate of new account credit card fraud attempts rose 48%
as compared to 2019.

Thus, in order to stop these frauds we need a powerful
fraud detection system that not only detects the fraud but
also detects it before it takes place and in an accurate manner.
Detecting real-time fraud transactions is dreadfully difficult.
Given the demographics data, geolocation data and transaction
data, our model will try to classify if a transaction
is fraudulent. If our model were to achieve a high detection
rate for fraudulent transactions, it could help the credit card
merchants to successfully mitigate the frauds committed by
hackers and save millions of dollars.

***B. Applications of ML and Big Data***

Most of the fraudulent transactions follow a similar pattern.
Using data mining and pattern recognition techniques,
we can segment and classify data to search millions of
transactions to find patterns and detect fraud. For our model
to be of high quality, we need to ensure the amount and
quality of data is significant.

***C. Project Goals***

The project goal is to utilize existing credit card fraud data
from January 2019 to December 2020 and develop a model
that will provide the best results in revealing and preventing
fraudulent transactions. For this objective the project will
be supported by results of data visualizations to explore the
data and feature engineering and dimensionality reduction to
incorporate important features. These steps will get the data
ready for our analyses. Next, we will perform exploratory data analysis, time series
analysis to identify the trends, and classification
techniques to identify whether a transaction is fraudulent or legitimate.

## Dataset

* Our Data containing geographical, demographics and transaction features is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020. 
* It was generated using Sparkov Data Generation tool and covers credit cards of 1000 customers doing transactions with a pool of 800 merchants. It is already split into training and test data, where training data contains transactions from 1st Jan 2019 to 21st June 2020 and test data contains transactions from 21st June 2020 to 31st Dec 2020. 
* We will create a baseline model after data preprocessing but that might be underfitted or overfitted, which could be mitigated if a model is trained and tested by a randomly sampled dataset to create a robust model. This is an important step to detect and predict fraudulent or legitimate transactions and not to deteriorate the detection rate and false alarm rate.
* It is important to know the past transaction history of a credit card. Thus, we need to use feature engineering to create columns that can study a card’s frequency of transaction in past 1 day, 1 week, 1 month and 3 months.

![image](https://user-images.githubusercontent.com/84480824/206971263-c89cb7ff-09a0-42f2-ac71-da595a6500d9.png)
![image](https://user-images.githubusercontent.com/84480824/206971292-895b758d-f654-41c4-ad3a-51ab7973f121.png)
![image](https://user-images.githubusercontent.com/84480824/206971323-0007837f-1c99-4c52-a242-fb5a29449f14.png)

**Required PySpark Packages**
![image](https://user-images.githubusercontent.com/84480824/206971426-b7a55e5a-3bd0-48a1-8cc0-faa80ea93742.png)
