# 📊 RFM Cluster Analysis of Corporate Clients

## 🛠 Project Overview:

This project involves performing a detailed RFM (Recency, Frequency, Monetary) analysis to segment corporate clients based on their purchasing behavior. Using advanced clustering techniques, the analysis aimed to categorize clients into distinct groups, enabling targeted marketing strategies and better customer relationship management.

## 🚀 Key Components:

### Data Exploration and Cleaning:

- Imported and cleaned the dataset, consisting of 9,818 sales records from corporate clients.
- Handled missing values, standardized city names, and removed non-relevant data entries to ensure data consistency and accuracy.
  
### RFM Analysis:

- **Recency:** Calculated the number of days since each client's last purchase.
- **Frequency:** Counted the total number of transactions for each client.
- **Monetary Value:** Summed up the total sales value for each client.
- Combined these metrics to assign an RFM score to each client, ranking them on a scale based on their purchasing behavior.
  
### Customer Segmentation:

- Segmented clients into categories such as "Best Clients," "Valuable Clients," "Neutral Clients," "Less Important Clients," and "Lost Clients" based on their RFM scores.
- Created visualizations to display the distribution of clients across these segments and the geographic distribution of top clients.
  
### Clustering Analysis:

- Applied several clustering algorithms, including K-Means, Hierarchical Clustering, DBSCAN, and Gaussian Mixture Models, to group clients into clusters.
- Used the Elbow Method and Silhouette Score to determine the optimal number of clusters.
- Performed dimensionality reduction using PCA and t-SNE for visualization of cluster groups in a two-dimensional space.
  
### Feature Engineering:

- Engineered additional features such as the number of days between the first and last purchase, average sales per transaction, and most frequent purchase quarter.
- Encoded categorical variables and transformed the data for optimal model performance.
  
### Results Interpretation:

- Identified key client segments and provided insights into customer behavior.
- Suggested targeted marketing strategies based on the cluster analysis to enhance customer retention and increase sales.
  
## 📊 Skills Demonstrated:

- RFM Analysis and Customer Segmentation
- Advanced Clustering Techniques (K-Means, DBSCAN, etc.)
- Data Cleaning, Feature Engineering, and Visualization
- Dimensionality Reduction (PCA, t-SNE)
- Strategic Business Insights based on Data Analytics
