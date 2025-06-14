# Agricultural Market Segmentation and Analysis
📌 Overview
This project applies machine learning clustering techniques to segment Indian agricultural markets based on pricing data. The analysis helps identify market patterns, pricing trends, and geographic segmentation to optimize agricultural trade and decision-making.

📂 Dataset
The dataset used for this study contains:

Geographic Variables: State, District, Market

Commodity Variables: Commodity Type, Variety

Pricing Variables: Min Price, Max Price, Modal Price

Temporal Variable: Arrival Date

🔗 Dataset Source: Kaggle - Indian Agriculture Data

📊 Clustering Techniques Used
🔹 1. K-Means Clustering
Used Elbow Method to determine optimal clusters (k=3).

Segmented markets into low, mid, and high price segments.

Silhouette Score: 0.764

🔹 2. Hierarchical Clustering
Used Ward’s method for minimum intra-cluster variance.

Verified segmentation with dendrogram analysis.

Similar results as K-Means, with clear geographic price variations.

🔹 3. DBSCAN Clustering
Applied Density-Based Clustering to detect outliers.

Identified high-priced commodities (e.g., Black Pepper, Cardamom).

Silhouette Score: 0.514

📈 Key Findings & Insights
✅ South India (Kerala, Tamil Nadu): High-priced spices dominate markets.
✅ North & Central India: Stable pricing for grains and pulses.
✅ Islands (Andaman & Nicobar): Higher logistics costs lead to premium pricing.
✅ Commodity Segmentation:

Low-price markets: Grains, Vegetables

Mid-price markets: Pulses, Fruits

High-price markets: Spices, Nuts

🚀 Project Implementation
🔧 Technologies Used
🐍 Python

📦 Pandas, NumPy (Data Processing)

🔢 Scikit-Learn (Machine Learning)

📊 Matplotlib, Seaborn (Data Visualization)



