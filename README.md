Customer Segmentation and Targeted Marketing Plan

Project Overview

This project aims to improve an online retail company’s marketing ROI (Return on Investment) by analyzing customer purchase data and segmenting customers into meaningful groups.
Using clustering techniques, customers are grouped based on their recency, frequency, and monetary (RFM) values.
The insights are then used to create personalized marketing strategies that help increase conversion rates, loyalty, and profitability.

Objective

Clean and analyze customer transaction data.

Identify meaningful customer segments using K-Means clustering.

Define customer personas based on behavioral patterns.

Develop targeted marketing strategies for each segment.

Improve marketing ROI through data-driven decisions.

Dataset Description

Dataset Name: Online Retail II

Source: Kaggle

Duration: 20010–2011

Country: United Kingdom

Main Columns:

InvoiceNo: Unique invoice number

StockCode: Product code

Description: Product name or description

Quantity: Number of items purchased

InvoiceDate: Date and time of transaction

UnitPrice: Price per item

CustomerID: Unique customer identifier

Country: Customer’s location

Data Cleaning and Preparation

Combined both yearly sheets (2009–2010 and 2010–2011).

Removed missing or duplicate CustomerIDs.

Dropped transactions with negative quantities (returns).

Created TotalAmount = Quantity × UnitPrice.

Converted InvoiceDate to proper datetime format.

Methodology

Feature Engineering:

Created RFM features:

Recency: Days since last purchase

Frequency: Number of transactions

Monetary: Total spending

Data Scaling:

Standardized RFM features using StandardScaler.

Clustering:

Applied K-Means Clustering.

Used the Elbow Method to determine optimal clusters (K = 4).

Interpretation:

Each cluster was analyzed and labeled to form customer personas.

Results and Insights

Identified Customer Segments:

Cluster	Segment Name	Characteristics

0	Occasional Buyers	Buy rarely, low spenders.

1	Inactive Customers	Haven’t purchased recently, need reactivation.

2	Regular Customers	Moderate buying frequency, steady spending.

3	Loyal / High-Value Customers	Frequent buyers, spend the most.

Customer Personas

Loyal Customers: Frequent, high-value buyers who respond to exclusive offers.

Regular Shoppers: Consistent buyers who value discounts and reward points.

Occasional Buyers: Irregular shoppers needing gentle reminders or offers.

Inactive Customers: Lost customers that require win-back campaigns.

Targeted Marketing Strategy

Segment	Strategy	Goal

Loyal Customers	Loyalty rewards, VIP programs, early access	Retain top customers

Regular Shoppers	Personalized offers, reward points	Increase spending

Occasional Buyers	Reminder emails, 10–15% discounts	Encourage repeat purchases

Inactive Customers	Reactivation and win-back campaigns	Bring back lost customers

Expected Benefits

Enhanced marketing ROI through targeted campaigns.

Better customer retention and satisfaction.

Reduced acquisition cost.

Improved understanding of customer behavior.

Stronger, data-driven marketing decisions.

Conclusion

The project successfully demonstrated how K-Means clustering can segment customers based on their purchasing behavior.
With clearly defined customer personas and tailored marketing strategies, businesses can achieve higher engagement, better retention, and increased ROI through smarter, data-driven marketing.
