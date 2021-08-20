# Online-Retail-Customer-Segmentation
## Problem Description :
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
## Data Description
A transnational data set with transactions occurring between 1st December 2010 and 9th December 2011 for a UK-based online retailer. The company mainly sells unique all-occasion gifts. and Many customers of the company are wholesalers.
## Attribute Information :
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. Description: Product (item) name. Nominal. Quantity: The quantities of each product (item) per transaction. Numeric. InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated. UnitPrice: Unit price. Numeric, Product price per unit in sterling. CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. Country: Country name. Nominal, the name of the country where each customer resides.
## Model Summary :
Built a clustering model using K-means and Agglomerative clustering to identify major customer segments on transactions data for the UK based non-store online retail.
Engineered new features to obtain new features such as RFM, busist days, time, month, RFMGroup, and RFMScore for getting more details about the customer.
Obtained optimal number of clusters using Silhouette Analysis, Elbow Method and visual inspection of dendogram resulting from Hierarchical Clustering .
Leveraged the visualization library t-SNE for multi-dimentional scaling to visualize and validate the inter-cluster separation and intra-cluster similarity.
## Conclusion :
* Here are the final number of clusters obtained .
![Alt text](https://user-images.githubusercontent.com/81186352/122783863-92546600-d2cf-11eb-888d-054214faf04e.png "Optional title")
