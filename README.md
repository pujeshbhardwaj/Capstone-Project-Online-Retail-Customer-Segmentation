## Online Retail Customer Segmentation (EDA & K-means Clustering)  
**Project Overview**  
This project focuses on customer segmentation for an online retail business. The dataset used contains transaction data from a UK-based and registered non-store online retail business, spanning from 01/12/2010 to 09/12/2011. The primary objective is to gain key insights and segment customers for more effective marketing strategies and programs.  

**Dataset**
- Source: Dr. Daqing Chen, Director: Public Analytics group, School of Engineering, London South Bank University, London, UK.  
- **Dataset Attributes**
InvoiceNo: Invoice number.
StockCode: Product code.
Description: Product name.
Quantity: Quantity of each product per transaction.
InvoiceDate: Date and time of each transaction.
UnitPrice: Unit price in sterling.
CustomerID: Customer number.
Country: Customer's residing country.
**Key Variables for EDA**
StockCode
Quantity
Unit Price

**Problem Statement**  
The primary challenge lies in dealing with a large and raw dataset. The goal is to explore the data, identify key customer segments, and enhance marketing strategies and programs.

**Objectives**
Retail Customer Segmentation: Utilize Exploratory Data Analysis (EDA), Data Cleaning, and K-means Clustering to segment customers.
Data Visualization: Create a dashboard with Key Performance Indicators (KPIs).

**Exploratory Data Analysis (EDA)**
Data Cleaning and Processing

**Visualizations**
Created visualizations for the number of orders, quantity, and revenue for different countries.
Identified top customers contributing the most by number of orders and revenue.

**K-means Clustering**
Employed K-means clustering, an unsupervised machine learning technique.
Grouped similar data points into clusters.
Each data point was assigned to the nearest cluster center (centroid).
Removed outliers to ensure robust clustering results.
- **Feature Selection**
Created a grouped dataset by Customer ID.
Utilized Date and Revenue attributes for feature selection.
Converted Date into frequency and Revenue into monetary value by each customer.
Merged the grouped data with the full data.
- **Outliers Check and Removal**
Sensitivity to outliers necessitated their removal.
- **Choosing the Number of Clusters (K)**
Used the elbow plot method to determine the number of clusters (K).
The graph showed an "elbow" point, indicating that SSD/Inertia starts to level off at 3.
Chose 3 clusters for customer segmentation.
- **Clusters**
Cluster 3 has the highest revenue, monetary value, frequency, and order quantity.
Cluster 2 and Cluster 1 follow, but unit prices remain consistent across all clusters.

**Insights**
The online store has a global presence but is most influential in Europe, especially the UK.
The UK accounts for more than 80% of total orders, order quantity, and revenue share.
Among top countries, Germany and France have higher numbers of orders, while the Netherlands and EIRE have higher order quantity and revenue share.
Surprisingly, the top revenue-contributing customer (CustID - 14646) is from the Netherlands, not the UK.
The most occurring words in the Description column were "CHILDREN," "HEART," and "WHITE."

**Conclusion**
Personalized Marketing: Utilize customer segmentation results to design tailored marketing programs.
Resource Allocation: Offer high-paying customers extra benefits like prime membership and free delivery.
Business Expansion: Focus on expanding to countries with lower order quantity and total revenue contribution.
Customer Retention: Reward and motivate top customers for continuous purchases and provide special recognition.
Digital Marketing Strategies: Implement SEO and SEM strategies to increase website traffic and sales.
This project's findings provide valuable insights for enhancing marketing strategies, customer relationships, and business growth.
