# Online-Retail-Customer-Segmentation

# Introduction : 

* Customer segmentation insights are used to create personalised marketing campaigns and to plan the overall marketing strategy.
* Finding consumers who are dormant or at high risk of churning and addressing their complaints are equally crucial. Companies employ the method of client segmentation for this.
* In business terms, we may say that 20% of clients account for 80% of a company's overall revenue. That is why it is critical to locate this group of people.

## Problem Statement:

In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.


## Attribute Information:
* InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
* StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
* Description: Product (item) name. Nominal.
* Quantity: The quantities of each product (item) per transaction. Numeric.
* InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
* UnitPrice: Unit price. Numeric, Product price per unit in sterling.
* CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
* Country: Country name. Nominal, the name of the country where each customer resides.


## Results
Recency,Frequency,Monetary (RFM) segmentation allows marketers to target specific clusters of customers with communications that are much more relevant for their particular behavior – and thus generate much higher rates of response, plus increased loyalty and customer lifetime value. Like other segmentation methods

![Screenshot (530)](https://user-images.githubusercontent.com/48415899/154788545-257a00df-0958-4944-949c-e255799eb18a.png)


## Conclusion
* This study proposed the use of machine learning techniques to identify the number of segments for online retail customers.
* Indeed, selecting the appropriate features to get the intended outcome was crucial. Here, we performed the RFM (Recency, Frequency, and Monetary) technique to provide features to our model.
* During the model development, we found the optimum number of clusters from the Elbow method and Silhouette Scores.
* So we ran DBSCAN on the dataset, and it yielded a clear number of clusters, namely three.
* Indeed, selecting the number of clusters varies from business to business case.

![Screenshot (531)](https://user-images.githubusercontent.com/48415899/154788783-a5d3ecd2-cb3c-4154-858e-3179d568b759.png)
