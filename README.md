# E-Commerce Customer Behavior — Exploratory Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an e-commerce customer behavior dataset containing information about customer purchasing activity, engagement, campaign response, and behavioral patterns.

The analysis focuses on understanding customer behavior, identifying relationships between important variables, analyzing customer segments, and extracting meaningful business insights using Python and statistical analysis.

---

## 🎯 Objectives

- Analyze customer purchasing and behavioral patterns
- Understand the distribution of customer segments
- Explore relationships between customer activity and monetary value
- Analyze campaign response behavior
- Identify important correlations between customer attributes
- Detect and investigate potential outliers
- Perform statistical significance testing
- Derive actionable business-oriented insights

---

## 📊 Dataset

The dataset contains **10,000 customer records** and **14 attributes**.

### Main Features

| Feature | Description |
|---|---|
| Customer_ID | Unique customer identifier |
| Recency | Number of days since the customer's recent activity |
| Frequency | Number of purchases/orders |
| Monetary | Customer monetary value |
| Avg_Order_Value | Average order value |
| Session_Count | Number of customer sessions |
| Avg_Session_Duration | Average session duration |
| Pages_Viewed | Number of pages viewed |
| Clicks | Number of clicks |
| Campaign_Response | Whether the customer responded to a campaign |
| Wishlist_Adds | Number of wishlist additions |
| Cart_Abandon_Rate | Cart abandonment rate |
| Returns | Number of returned items |
| Segment_Label | Customer segment |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## 🔍 Analysis Performed

The project includes:

1. Data loading and initial inspection
2. Data quality assessment
3. Descriptive statistical analysis
4. Customer segment distribution analysis
5. Numerical feature distributions
6. Outlier detection using the IQR method
7. Pearson and Spearman correlation analysis
8. Bivariate analysis
9. Customer behavioral analysis
10. Campaign response analysis
11. Segment-level behavioral analysis
12. Statistical significance testing
13. Business-oriented interpretation of findings

---

## 📈 Key Findings

### Customer Engagement

Session Count showed a very strong positive monotonic association with Monetary Value.

**Spearman correlation: ρ = 0.9226, p < 0.0001**

This indicates that customers with higher session activity generally tend to have higher monetary values.

### Cart Abandonment

Cart Abandonment Rate showed a very strong negative monotonic association with Monetary Value.

**Spearman correlation: ρ = -0.8871, p < 0.0001**

Customers with higher cart abandonment rates generally tend to have lower monetary values.

### Recency

Recency showed a very strong negative monotonic association with Monetary Value.

**Spearman correlation: ρ = -0.8791, p < 0.0001**

This suggests that customers with higher recency values generally tend to have lower monetary values.

### Campaign Response

Campaign responders had a higher median monetary value than non-responders.

- Responders median monetary value: **1,953**
- Non-responders median monetary value: **475**
- Median difference: **1,478**

A Mann–Whitney U test indicated that the difference was statistically significant at the 5% significance level.

---

## 📊 Visualizations

The project includes visualizations such as:

- Customer segment distribution
- Monetary value distribution
- Correlation heatmap
- Session Count vs Monetary Value
- Cart Abandonment Rate vs Monetary Value
- Recency vs Monetary Value
- Campaign Response vs Monetary Value

---

## ⚠️ Limitations

The dataset exhibits strong correlations among several behavioral variables and predefined monetary-based customer segments. Therefore, the findings should be interpreted as **exploratory associations rather than causal relationships** or generalizations to real-world customer populations.

Correlation and statistical significance do not imply causation.

---
