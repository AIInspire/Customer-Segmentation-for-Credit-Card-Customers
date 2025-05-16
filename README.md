# 📊 Customer Segmentation for Credit Card Customers

This project applies unsupervised learning techniques to segment credit card customers based on behavioral patterns. The goal is to provide actionable business insights and recommendations for targeted marketing, retention strategies, and product development.

## 📁 Dataset

- **Source**: [Kaggle - Customer Segmentation Credit Cards](https://www.kaggle.com/code/des137/customer-segmentation-credit-cards)
- The dataset contains anonymized customer data, including purchase behaviors, cash advances, payment history, and credit utilization.

## 🎯 Project Objectives

1. Explore and understand customer transaction patterns.
2. Identify the optimal number of customer clusters.
3. Perform customer segmentation using clustering algorithms.
4. Profile each cluster with behavioral traits.
5. Provide business insights and strategic recommendations.

## 🧪 Project Workflow

### 1. Data Exploration & Preprocessing
- Handled missing values with median imputation.
- Removed irrelevant columns (e.g., customer IDs).
- Standardized features using z-score normalization.
- Conducted outlier detection and visualization.

### 2. Feature Engineering
Created additional features to capture behavioral patterns:
- `PURCHASES_RATIO`, `CASH_ADVANCE_RATIO`, `CREDIT_UTILIZATION`
- `PAYMENT_RATIO`, `PURCHASES_PER_TENURE`, and others

### 3. Clustering
- Dimensionality reduction using PCA
- Compared **K-Means** and **GMM**
- Selected **K-Means with k=5** (best Silhouette Score = 0.498)

### 4. Cluster Profiling
Identified five distinct customer segments:
- **Cluster 0**: One-off Spenders  
- **Cluster 1**: Disciplined Full Payers  
- **Cluster 2**: Frequent Installment Shoppers  
- **Cluster 3**: Heavy Cash Advance Users  
- **Cluster 4**: Balanced, High-Value Engaged Users  

### 5. Visualization
- PCA cluster scatter plot
- Silhouette score chart
- Radar plots and boxplots for feature comparisons

### 6. Business Insights & Recommendations
- Suggested marketing strategies for each cluster
- Identified high-risk vs. high-value customer types
- Provided product and retention recommendations

## 📈 Results

- K-Means clustering revealed interpretable and useful segments.
- Each cluster represents unique customer behavior patterns.
- Strategic insights support targeted business actions.

## 🚧 Limitations

- No demographic or credit score data
- Analysis based only on transactional features

## 🚀 Future Enhancements

- Add customer demographics and income levels
- Use DBSCAN/HDBSCAN for advanced segmentation
- Build a dashboard for interactive data exploration

## 🧾 Deliverables

- ✅ Final report with findings and recommendations
- ✅ Cluster analysis and visualizations
- ✅ Business interpretation of customer segments

---

