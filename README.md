# UCI_online_retail

In this project we will segment customers based on their buying behavior on the market. The dataset is a transactional data that contains transactions from December 1st 2010 until December 9th 2011 for a UK-based online retail.

file : initial_clean.ipynb :
initial cleaning and analysis -----

1. handled Missing values, Data types are inspected and converted where necessary.

2. The dataset is transformed to calculate metrics such as total revenue per transaction and recency for each customer.
Outliers, particularly those with unusually high unit prices or total sums, are identified and examined for validity.
The distribution of sales by country is visualized, and focus is narrowed down to the UK market due to the business's origin.
Monthly sales trends are analyzed to identify anomalies or patterns.

3. RFM Analysis: (Recency, Frequency, Monetary) analysis is performed to segment customers based on their transaction behavior.
Sales contribution by RFM segments is visualized to understand the value contribution of each segment.
Segment 5 customers, identified as high-value customers, are profiled based on recency, frequency, and monetary value metrics.
Product Analysis:

4. The frequency, quantity sold, and revenue generated for each product are calculated.
The top-selling products are identified based on quantity sold and revenue generated.
Monthly revenue trends for the top-selling products are visualized to understand sales patterns over time.

## Next we will dive deeper into our segment 5 analysis using tablaue.

This dataset has been optained from : https://archive.ics.uci.edu/dataset/352/online+retail
as a practice dataset and case study.
