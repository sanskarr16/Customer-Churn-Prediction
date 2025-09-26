# Telecom Customer Churn Prediction

# What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels.As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.

# Objectives:

Finding the % of Churn Customers and customers that keep in with the active services.
Analysing the data in terms of various features responsible for customer Churn
Finding a most suited machine learning model for correct classification of Churn and non churn customers.

# Dataset:

The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents

# Implementation:
Libraries: sklearn, Matplotlib, pandas, seaborn, and NumPy

# Few glimpses of EDA:
#1. Churn Distribution
<img width="983" height="525" alt="Churn Distribution" src="https://github.com/user-attachments/assets/7df24fe5-cfc0-4a1b-9657-7998ce3f781c" />
26.6 % of customers switched to another firm.

#2. Churn distribution with respect to Gender

<img width="651" height="527" alt="distributionWRTGender" src="https://github.com/user-attachments/assets/893847ec-ec87-48df-b158-60492152ef12" />

There is negligible difference in customer percentage/count who chnaged the service provider. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.`

#3. Customer Contract Distribution

<img width="700" height="500" alt="Contract distribution" src="https://github.com/user-attachments/assets/d5390b2f-be88-499e-9718-d753cef3b7f6" />

About 75% of customer with Month-to-Month Contract opted to move out as compared to 13% of customrs with One Year Contract and 3% with Two Year Contract

#4. Contact Distribution
<img width="983" height="525" alt="payment methods" src="https://github.com/user-attachments/assets/9d2ed186-2a22-401b-a311-18aa28fd3b2a" />
<img width="942" height="561" alt="payment ethods with respectto churn" src="https://github.com/user-attachments/assets/ae08b87a-09e6-4675-9526-5bcb0aa6516b" />
Major customers who moved out were having Electronic Check as Payment Method. Customers who opted for Credit-Card automatic transfer or Bank Automatic Transfer and Mailed Check as Payment Method were less likely to move out.

#5. Internet Services
<img width="1202" height="595" alt="internet services" src="https://github.com/user-attachments/assets/687c8366-ec3a-45e1-8cf4-6ef333615ce7" />
Several customers choose the Fiber optic service and it's also evident that the customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service. Customers having DSL service are majority in number and have less churn rate compared to Fibre optic service.

#6. Online Security
<img width="919" height="574" alt="onlineSecurity" src="https://github.com/user-attachments/assets/62a6c344-4ff0-4268-ad03-033fc7f75a99" />
As shown in following graph, most customers churn due to lack of online security






