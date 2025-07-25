#  Customer Personality Analysis

This project analyzes customer marketing campaign data to identify patterns in customer behavior, segment them into meaningful clusters, and predict which customers are most likely to respond to a campaign.

##  Project Overview

- **Dataset**: Customer personality and campaign data from a Portuguese retailer.
- **Goal**: Segment customers and predict campaign response (`Response` variable).
- **Techniques Used**:
  - Data Cleaning and Preprocessing
  - K-Means Clustering for Customer Segmentation
  - Classification Models: Logistic Regression, Random Forest (with `class_weight='balanced'`)
  - Evaluation: Confusion Matrix, Classification Report

##  Key Findings

- **Clusters**: Four main customer segments identified:
  -  High Spenders
  -  Deal Seekers
  -  Online Shoppers
  -  Inactive Customers

- **Campaign Response**:
  - Customers in **Cluster 3** showed the highest response rate.
  - **Random Forest with class balancing** (`class_weight='balanced'`) improved model recall for the minority class (responders).
  - Accuracy: **89%**
  - Precision for responders: **0.72**
  - Recall for responders: **0.34**

 ## Dataset
The dataset used for this project can be downloaded from:
 https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis

##  Tools & Libraries

- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab


