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

<img src="images/Model%20performance.png" width = "1000">

Comments: 
- In predicting retention rate, we prefer precision (to reduce false positive) when we want to maximize retetion rate, and prefer recall (to reduce false negative) when we want to reduce the retention costs. Based on the table summary, Adaboost is the best model in terms of precision. Extra Tree and SVM, while do not perform well in terms of Precision compared to others, are able to achieve perfect Recall and thus gain the highest scores in F1 score.
- All models achives a higher score on Recall than Precision.
- Stacking model does not clearly outperform others with respect to any metrics. This indicates that a more complex model is not necessarily better.
- Decision Tree shows a sign of overfitting as its scores on Test dataset are lower than those for train dataset.

<img src="images/ROC%20Curve.png" width = "500" >


 
