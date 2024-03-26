# Python_RFM-Analysis-project

## 1. Introduction
### 1.1. Business question

SuperStore is a global retail company. The Marketing Department wants to run marketing campaigns during the Christmas and New Year holidays to thank customers for their past support of the company. In addition, potential customers can be exploited to become loyal customers.

The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch appropriate marketing campaigns. Analyze the current situation of the company and give suggestions to the Marketing team
With the retail model of the Superstore company, which indicator should be most focused in the 3 indicators R, F, and M?

### 1.2 About RFM
The “RFM” in RFM analysis stands for recency, frequency and monetary value.
- Recency: measures how recently a customer has made a purchase.
- Frequency: measures how often a customer has made purchases.
- Monetary Value: measures the total amount of money a customer has spent on purchases.
RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores

Reference 
[RFM Analysis For Successful Customer Segmentation] (https://www.putler.com/rfm-analysis)
### 1.3. Dataset
Dataset has 2 tables which are Segmentation, e-commerce retail with 8 fields including Invoice number, StockCode (Product (item) code),	Description (Product (item) name.),	Quantity,	Invoice Date,	Unit Price,	CustomerID,	Country from 2010 to 2011
#### 1.3.1. E-commerce Retail information dataframe 
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/c0f4a82a-03c5-4964-acbb-4a5c8fb057d4)

### 1.3.2. Segmentation information dataframe
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/26edd8df-732a-44c8-a7a3-542da017e918)

## 2. Data Visualization and Insight
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/2dcd5757-d124-4269-9f5c-ccc0501ba2d6)
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/a9a4ec18-7853-4a2f-bd27-a8cda617a30d)

2 Segment with the highest proportion of customers are Champions (19,26%) and Hibernating customers (16,33%). Champions is also the group that accounts for the highest revenue nearly 60%

Depending on each groups focusing on the different 3 indicators R, F, and M
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/f64c2c37-4869-43b1-85b7-e0751b47420f)
![image](https://github.com/uyennguyen307/Python_RFM-Analysis-project/assets/162019618/0ef3da6e-0d1e-4412-a99a-731e2a085c6d)

The Champions group should prioritize Recency over Frequency & Monetary since their most loyal may make many purchases & many times  throughout the year 



