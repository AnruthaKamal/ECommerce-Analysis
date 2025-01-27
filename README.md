# Assessment: eCommerce Transactions Dataset

This repository was created as part of a hiring assessment. The tasks involved Exploratory Data Analysis (EDA), building a Lookalike Model, and performing Customer Segmentation.

## Overview

**Dataset Details**:
- **Customers.csv**: Contains customer details (e.g., CustomerID, Region, SignupDate).
- **Products.csv**: Provides product details (e.g., ProductID, Category, Price).
- **Transactions.csv**: Contains transaction history (e.g., CustomerID, ProductID, TotalValue).

## Tasks

### 1. Exploratory Data Analysis (EDA) and Business Insights
- Performed data exploration and derived actionable insights.
- Provided visualizations and a concise report.

### 2. Lookalike Model
- Developed a model to recommend the top 3 similar customers based on profile and transaction history.
- Used cosine similarity with a weighted combination of customer features (40%) and category engagement (60%).

### 3. Customer Segmentation
- Applied clustering techniques to segment customers.
- Evaluated using DB Index and visualized clusters.
