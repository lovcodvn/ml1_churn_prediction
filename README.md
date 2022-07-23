# Churn Prediction

## Project Objective

Predict the churn rate of customers for a UK-based online retail store.

## Dataset

The dataset contains all the transactions occurring between 2010 and 2011 for a UK-based online retail store. It has the following data fields

- InvoiceNo: Invoice number, a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
- StockCode: Product (item) code, a 5-digit integral number uniquely assigned to each distinct product.
- Description: Product (item) name.
- Quantity: The quantities of each product (item) per transaction.
- InvoiceDate: Invoice Date and time. the day and time when each transaction was generated in d/m/yy h:m format
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- Country: Country name. Nominal, the name of the country where each customer resides.

## Models

- Decision Tree
- Random Forest
- Extra Tree
- Adaboost
- Gradient Boost
- SVM
- A stacking model

## Results

<img scr="images/Model%20performance.png">
<img scr="images/ROC%20Curve.png">
 
