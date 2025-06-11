# Market Signals

This project explores how market-facing behaviors like product reviews, survey responses and purchasing preferences can reveal latent consumer segments and possible anomalies. The work combines exploratory data analysis (EDA), anomaly detection and clustering techniques to uncover actionable insights for marketing strategy.


## Overview

The analysis is divided into two main streams:

1. **Fake Reviews Detection**  
   Used EDA to examine review behaviors and surface unusual patterns that may signal fake or suspicious reviews.

2. **Audience Clustering**  
   Segments users based on survey responses and demographic features using the K-Prototypes model, designed for mixeddata.

## Notebooks

- [`Fake_reviews_EDA.ipynb`](https://github.com/CassandraMaldonado/Market_signals/blob/main/Fake_reviews_EDA.ipynb)  
  Focused on identifying outliers in review behavior by analyzing variables such as review length, star rating distributions, review frequency and potential spamming patterns.

- [`EDA.ipynb`](https://github.com/CassandraMaldonado/Market_signals/blob/main/EDA.ipynb)  
  Analyzed a mixed survey dataset to identify distinct customer clusters. Used K-Prototypes to uncover latent audience groups and explore their implications for targeted outreach.

## Key Techniques

- Exploratory Data Analysis (EDA)
- Outlier Detection
- Clustering with K-Prototypes
- Visualization of High-Dimensional Data with PCA
- Customer Segmentation Strategy

## Tech Stack

- Python
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`
- `kmodes` (for K-Prototypes clustering)
- `plotly` (for interactive visuals)

## 📌 Insights

- Detected reviewer behaviors that may indicate manipulation or inorganic activity.
- Identified clear audience segments with distinct platform preferences and behavioral traits, providing a foundation for future ad targeting or personalization.

---

## 🚀 Next Steps

- Apply supervised modeling to predict user behavior from cluster labels.
- Incorporate external platform usage data to refine targeting strategy.
- Extend anomaly detection to time-based review patterns.

---

## 📁 Structure
