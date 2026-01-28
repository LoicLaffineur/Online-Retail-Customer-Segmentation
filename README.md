# 🛍️ Customer Segmentation with RFM & Unsupervised Learning

## 🎯 Business Problem

E‑commerce companies often struggle to understand the diversity of their customer base.
Without clear segmentation, marketing teams waste budget on broad campaigns, fail to retain valuable customers, and miss opportunities for personalization.

**How can we identify distinct customer groups to improve retention, loyalty, and revenue?**

## 💡 Proposed Solution

This project applies **RFM analysis** (Recency, Frequency, Monetary) combined with **K‑Means clustering** to uncover meaningful customer segments in the Online Retail (UCI) dataset.

### Key steps:

- Data cleaning and exploratory data analysis (EDA)  
- RFM feature engineering  
- Log transformation and standardization  
- K‑Means clustering with elbow & silhouette analysis  
- PCA for 2D and 3D visualization  
- Cluster profiling and business interpretation  
- Radar charts to compare customer groups

The final segmentation reveals **five distinct customer personas**, including VIPs, loyal buyers, occasional shoppers, and at‑risk customers.
These insights enable targeted marketing strategies, personalized offers, and improved customer lifetime value.

## 🛠️ Technologies
Python • Pandas • NumPy • Scikit‑learn • Matplotlib • Seaborn • PCA • K‑Means

## 📊 Key Insights

### RFM Segmentation

- **Recency**: days since last purchase  
- **Frequency**: number of orders  
- **Monetary**: total spending  

### Identified Customer Segments

- **Cluster 4 - VIP / Premium Customers**  
----> Very recent, very frequent, extremely high spenders
  
- **Cluster 1 - Loyal High‑Value Customers**  
----> Regular buyers with strong revenue    

- **Cluster 2 - Potential Loyalists**  
----> Good spenders but inactive recently  

- **Cluster 0 - Occasional Buyers**
----> Low frequency and low spend  

- **Cluster 3 - At‑Risk Customers**  
----> Long inactivity and low lifetime value  

These segments provide a strong foundation for retention, reactivation, and loyalty programs.

## 📈 Visualizations

### PCA Clustering (2D)
<img width="844" height="624" alt="pca_clusters" src="https://github.com/user-attachments/assets/7652f809-71f0-43ef-bf5f-e1059b919e21" />

### Radar Charts (Cluster Profiles)
<img width="1196" height="1589" alt="radar_clusters" src="https://github.com/user-attachments/assets/791b44ca-c63c-4674-964d-c287b88742ef" />

### RFM Distributions
<img width="790" height="1490" alt="rfm_distribution" src="https://github.com/user-attachments/assets/579bca0a-7a18-46e7-8502-86429df815b6" />

### Top 10 Products by Revenue (EDA)
<img width="1110" height="701" alt="top_10_products" src="https://github.com/user-attachments/assets/07aafe81-d91e-4ff9-b4d4-19e4251b530d" />

## 🚀 Business Impact
- **Targeted marketing**: personalized campaigns for each customer segment  
- **Higher retention**: identify at‑risk customers before they churn  
- **Revenue growth**: focus on VIPs and high‑value customers  
- **Operational efficiency**: allocate marketing budget where it matters most

This segmentation provides actionable insights for CRM teams, marketing analysts, and e‑commerce managers.

## 🔮 Possible Next Steps

- Build a dashboard for real‑time customer monitoring  
- Combine RFM with product preferences for deeper segmentation  
- Test alternative clustering methods (GMM, DBSCAN, hierarchical)  
- Deploy a marketing recommendation engine based on cluster profiles  
