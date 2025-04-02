📌 Project Overview

This project aims to segment customers of a credit card company to optimize marketing strategies. Using K-Means Clustering, we analyze customers' spending habits and financial behaviors to identify distinct customer groups.

📂 Repository Structure

📁 Customer-Segmentation
│-- 📂 Visualizations (Plots and clustering results)
│-- 📄 README.md (Project Documentation)
│-- 📄 Customer Segmentation.R (R script for analysis)
│-- 📄 Data.csv (Dataset used for clustering)


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

The customers were segmented into X clusters.

Key insights include (to be added based on clustering results).

Further analysis can involve (e.g., improving clustering, deeper feature engineering, or visualizations).

🔥 Future Enhancements

✔️ Improve preprocessing (handle missing values effectively).✔️ Add interactive dashboards (Shiny App).✔️ Use different clustering techniques (DBSCAN, Hierarchical Clustering).



📜 License

This project is open-source and available under the MIT License.
