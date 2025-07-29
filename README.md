Financial Performance Analysis using Machine Learning

📄 Project Overview

This project applies machine learning and data analysis to explore financial data from various companies and uncover the key drivers of profitability. The aim is to provide strategic insights using clustering, regression, and visualization techniques. It was conducted as part of a team project at École Centrale Casablanca.

📊 Objectives

Clean and preprocess financial datasets

Calculate financial ratios and key performance indicators (KPIs)

Use clustering (KMeans + PCA) to segment companies by performance

Predict profitability using regression models (Random Forest, Ridge, Lasso)

Interpret the economic meaning of the patterns and model outputs

📂 Dataset

Realistic financial data (revenues, profit, assets, liabilities, etc.)

Mix of categorical (sector, country) and numerical variables

Target variable: Profit

⚙️ Tools and Libraries

Python, pandas, NumPy

scikit-learn (PCA, KMeans, RandomForest, Ridge, Lasso)

matplotlib, seaborn

Google Colab

📝 Methodology

1. Data Cleaning and Preprocessing

Removed missing values and irrelevant columns

Standardized column names and handled outliers

2. KPI Calculation

Net Profit Margin

Return on Assets (ROA)

Asset Turnover

3. Data Visualization

Correlation heatmaps

Boxplots by country

Profit vs Sales scatter plots

Monthly sales evolution

4. Clustering with KMeans and PCA

Normalized KPI variables

Used KMeans to cluster companies into 3 performance groups

Reduced dimensions using PCA for visual interpretation

5. Regression Modeling

Random Forest to predict profit and rank variable importance

Ridge and Lasso regression for comparison and regularization

Error metrics: MSE, convergence notes

🌎 Results and Insights

Sales is the strongest predictor of profit, followed by Net Margin

Three financial profiles detected:

High-margin specialists

High-volume competitors

Balanced performers

Sector impacts performance: e.g., Government & Midmarket = high margins

📊 Key Visuals

Heatmap of financial variable correlations

PCA 2D scatterplot of clusters

Feature importance bar chart (Random Forest)

Decision tree outlining profitability segments

📗 Deliverables

Notebook

PDF Report

Sample dataset (available upon request)

✨ Improvements to Consider

Hyperparameter tuning for ML models

Add clustering validation (Silhouette Score, Davies-Bouldin Index)

Deploy as Streamlit dashboard

Include interactive filters for sector/country

🔗 Link to Notebook

Open in Google Colab

