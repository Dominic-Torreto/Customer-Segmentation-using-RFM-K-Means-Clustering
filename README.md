# Customer-Segmentation-using-RFM-K-Means-Clustering
# Overview
This project implements customer segmentation by combining the RFM (Recency, Frequency, Monetary) method with K-Means clustering.
Two different approaches are explored:

RFM Scoring + K-Means Clustering – Customers are scored based on RFM metrics, and these scores are used for clustering.

Raw RFM Values + K-Means Clustering – Directly uses calculated RFM values for clustering without assigning scores.

The dataset consists of three years of retail sales data sourced from Kaggle.

🎯 Motivation
Customer segmentation is a powerful method to better understand clients and address their diverse needs.
Retailers and service providers often store purchase history, which can be analyzed to group customers into segments.
Using RFM analysis, businesses can:

Identify valuable customers

Create personalized offers

Design targeted marketing campaigns

Increase overall sales

RFM stands for:

Recency (R) – Days since the customer's last purchase

Frequency (F) – Total number of purchases

Monetary (M) – Total amount spent by the customer

By combining RFM with clustering techniques, we can effectively categorize customers into actionable groups.

# Dataset
Source: Kaggle (Retail Sales Data)[https://www.kaggle.com/datasets/thedevastator/online-retail-sales-and-customer-data]

Contains: 3 years of sales transactions

Data fields include: Customer ID, Invoice Date, Quantity, Price, and more

🛠 Methodology
Data Preprocessing – Cleaning and formatting raw retail data

RFM Analysis – Calculating Recency, Frequency, and Monetary values for each customer

Approach 1 – Assign RFM scores, then apply K-Means clustering

Approach 2 – Use raw RFM values directly with K-Means clustering

Evaluation & Visualization – Analyze and interpret clusters to derive insights
# Technologies Used
Python 3.6+

Libraries:

pandas

numpy

scikit-learn

scipy

seaborn

matplotlib

# How to Run the Project
Option 1 – Jupyter Notebook / Google Colab:

Open Customer_segmentation.ipynb or Segmentation_Kmeans.ipynb

Run the cells step-by-step
#  Insights & Applications
Identify loyal customers and reward them

Recognize at-risk customers and re-engage them

Understand low-value customers and strategize to increase sales

Optimize marketing spend with targeted campaigns
