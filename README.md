
# 🚀 Telecom Customers Churn Analysis and Prediction 

## What is Customer Churn ? 

**Customer churn**, also known as **customer attrition**, is when a customer chooses to stop using products or services of a company. But with each customer who churns, there are usually early indicators or metrics that can be uncovered with churn analysis.

**For example**, The Telecom Industry faces a lot of Churn (with annual churn rate of 15-25%) because the customers can choose from a variety of service providers and actively switch from existing to another.
While looking at both Business operational insights and customer experience insights along the customer feedbacks is foundational in order to predict churn.  
A scenario where a customer who has declined in recent visits and gives a feedback score of 6 of 10 after their latest shopping experience, could have an increased probability of churning.

## What is Churn Analysis and Prediction is important for companies ? 
Generally in a business perspective it costs more to acquire new customers than it does to retain existing customers. In fact, an increase in customer retention of just 5% can create at least a 25% increase in profit. This is because returning customers will likely spend 60% more on a company's products and services. As a result, the company can spend less on the operating costs of having to acquire new customers by spending time and money on convincing an existing customer to select your company over competitors because they've already made their mind.

However, if a company could forecast why and which customers are likely to leave ahead of time, **it can focus on customer retention efforts only on these "high risk" clients**. This helps in achieving the goal of expanding its customer base and retrieve more customers loyalty.

## How to address and reduce Customer Churn?

To reduce customer churn, Companies need to predict which customers are at high risk of churn.

**Exploratory Data Analysis** is done in order to detect the reasons behind the customer's churn, where we can find the insights by making the relationship between number of churns and other attributed of dataset.

**Applying Maching Learning Models** will help to predict the probability of which customer is more likely to churn in the future.

By providing solution for churn, businesses can preserve their market position,and also grow and thrive with more customers network, the lower the cost of initiation and the larger the profit.

## Objectives in this Analysis

**Objective is to find solutions and suggestions for any possible churning.**

* What is the percentage of Customers who are with the active services and Customers who Churn ?      
* Does gender play a role in Customers Churn ?   
* Does the type of service provided leads to more/less Customers Churn?  
* What's the most profitable service types?  
* Profitable features and services by the company?


## Implementation

**Dataset used in the program:** 🔗[Telecom Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn?datasetId=13996&sortBy=voteCount)

The dataset contains:
```bash
1. Churn Column
2. Services provided by the Company to its Customer
3. Customer's Information Columns
4. Customer's Demographic Columns
```
**Libraries used in the program:**

* [NumPy](https://numpy.org/doc/stable/) and [Pandas](https://pandas.pydata.org/docs/) - Data Manipulation
* [Matplotlib](https://matplotlib.org/stable/index.html), [Seaborn](https://seaborn.pydata.org/), [Plotly](https://plotly.com/python/) - Data Visualization
* [Sklearn](https://scikit-learn.org/0.21/documentation.html) - Models Implementation & Evaluation

**Models used in the program:**
```bash
1. Support Vector Classifier (SVC)
2. Random Forest Classifier
3. Logistic Regression
4. Decision Tree Classifier
5. Adaboost Classifier
```

From the Above models, we can say that the **Random Forest Model** performs much better than the other models. 


