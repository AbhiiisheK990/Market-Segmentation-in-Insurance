🧠 Market Segmentation using Unsupervised Learning

📌 Project Overview

This project implements an end-to-end customer market segmentation solution using unsupervised machine learning techniques.
The goal is to identify distinct customer groups based on credit card usage behavior to enable targeted recommendations, personalization, and strategic decision-making.

🎯 Business Objective

Segment customers based on spending and transaction behavior

Enable data-driven marketing and financial product recommendations

Support personalization for services such as loans, savings plans, and wealth management

📊 Dataset

~9,000 active credit card users

18 behavioral features

Data represents 6 months of customer usage patterns

🧠 Machine Learning Techniques Used

The following clustering algorithms were implemented and evaluated:

K-Means Clustering

Agglomerative (Hierarchical) Clustering

Spectral Clustering

DBSCAN

Gaussian Mixture Models (GMM)

Clustering performance was assessed using silhouette score, cluster cohesion, and business interpretability.

🔍 Workflow

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Scaling

Model Training & Evaluation

Cluster Interpretation

Model Selection

Deployment using Streamlit

🚀 Application Deployment

A Streamlit web application allows users to:

Input new customer attributes

Predict customer segment (cluster)

Understand customer behavior category in real time

Run the app locally:

streamlit run app.py

📁 Repository Structure
├── Customer Data.csv
├── Clustered_Customer_Data.csv
├── Market_Segmentation_Customer_Data.ipynb
├── app.py
├── kmeans_model.pkl
├── final_model.sav
└── Market segmentation.pdf

📈 Key Outcomes

Identified meaningful customer segments based on behavior

Enabled real-time cluster prediction through a web app

Demonstrated practical application of unsupervised ML in business analytics

🏷️ Tags

Machine Learning Unsupervised Learning Customer Segmentation Clustering
Python Streamlit Data Science
