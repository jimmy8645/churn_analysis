# Churn problem for Bank Customers

Churn analysis, also known as customer attrition analysis, is a process of examining and understanding the factors that contribute to customer churn or defection in a business. Churn refers to the phenomenon where customers or users of a product or service discontinue their relationship or subscription with a company.

Churn analysis aims to identify patterns, trends, and indicators that can help businesses predict and prevent customer churn. By analyzing customer data and behavior, businesses can gain insights into why customers are leaving and take proactive measures to retain them.

In this project, the aim is to estimate whether a bank's customers leave the bank or not. In addition, the event that defines the customer abandonment is the closing of the customer's bank account.

## Table of Contents

- [Dataset Overview](#dataset-overview)
- [Data Source](#data-source)
- [License](#license)

## Dataset Overview

Dataset consists of 10000 observations and 12 variables.
Independent variables contain information about customers.
Dependent variable refers to customer abandonment.

- RowNumber: corresponds to the record (row) number and has no effect on the output.
- CustomerId: contains random values and has no effect on customer leaving the bank.
- Surname: the surname of a customer has no impact on their decision to leave the bank.
- CreditScore: can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.
- Geography: a customer’s location can affect their decision to leave the bank.
- Gender: it’s interesting to explore whether gender plays a role in a customer leaving the bank.
- Age: this is certainly relevant, since older customers are less likely to leave their bank than younger ones.
- Tenure: refers to the number of years that the customer has been a client of the bank. Normally, older clients are more loyal and less likely to leave a bank.
- Balance: also a very good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.
- NumOfProducts: refers to the number of products that a customer has purchased through the bank.
- HasCrCard: denotes whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.
- IsActiveMember: active customers are less likely to leave the bank.
- EstimatedSalary: as with balance, people with lower salaries are more likely to leave the bank compared to those with higher salaries.
- Exited: whether or not the customer left the bank.

## Data Source

https://www.kaggle.com/mathchi/churn-for-bank-customers

## License

[CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
