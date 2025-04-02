📌 Project Overview

This project aims to segment customers of a credit card company to optimize marketing strategies. Using K-Means Clustering, we analyze customers' spending habits and financial behaviors to identify distinct customer groups.


📊 Dataset Details

Dataset: Data.csv (8,950 rows × 18 columns)

Column Name              Description

CUST_ID                  Unique customer ID

BALANCE                  Account balance

PURCHASES                Total purchase amount

ONEOFF_PURCHASES          One-time purchase amount

INSTALLMENTS_PURCHASES    Installment purchase amount

CASH_ADVANCE              Cash withdrawal amount

CREDIT_LIMIT              Credit limit

MINIMUM_PAYMENTS          Minimum payment due

TENURE                    Account tenure in months

🚀 Steps in Analysis

1️⃣ Data Preparation - Load dataset, clean missing values, and preprocess features.
2️⃣ Exploratory Data Analysis (EDA) - Understand data distribution and correlations.
3️⃣ Feature Scaling & PCA - Normalize data and apply Principal Component Analysis (PCA) for dimensionality reduction.
4️⃣ K-Means Clustering - Identify customer segments based on spending behaviors.
5️⃣ Results & Visualization - Interpret and visualize clusters.

📌 How to Run the Code

Prerequisites

Ensure you have R installed with the required packages:

install.packages(c('tidyverse', 'ggplot2', 'factoextra', 'FactoMineR'))

Run the Script

Execute the R script using:

source("Customer Segmentation.R")

📈 Results & Insights

- The customers were segmented into 4 clusters.

- Key insights include:
  1. Cluster 1: Customers with lowest amount of all purchases, not much withdrawals, indicates not many transactions of the credit card compared to the other clusters.
  2. Cluster 2: Customers with lowest amount of withdrawal and frequency, however, have the highest amount of all purchases. They have the longest tenure and highest percent of full payments paid, indicating that they are aware of their credits.
  3. Cluster 3: Customers with high amount of balance, high cash advance and high credit limit. Their balance also seemed to be updated frequently, indicates many transactions of the credit card. The customers of this cluster also have high amount of minimum payments, however, lowest percent of full payments paid, indicating higher loans amount and often like to withdraw a lot of money from the credit card.
  4. Cluster 4: Customers with lowest amount of balance and lowest credit limit. The customers of this cluster also have the lowest of minimum payments, payments and tenure; indicating that the transactions made in these credit cards are small transactions.
  5. Cluster 1 & 4 have the lowest amount of purchases compared with the other clusters, hence if there are offers such as reward programs, discounts using credit card, they could be the best target.
  6. Cluster 2 & 3 also has the highest amount of payments compared with the other clusters, indicating how aware they are of their credits. Hence, if there are offers such as loyalty points, they could be the best target.
  7. Cluster 4 relatively has the lowest amount of purchases and payments compared with the other clusters. They also can be offered to zero interest program to increase theirs purchase and payments.

Further analysis can involve (e.g., improving clustering, deeper feature engineering, or visualizations).




📜 License

This project is open-source and available under the MIT License.
