# Mall-Customers---Clustering
📊 Customer Segmentation using Clustering

Problem
Understanding customer behavior is critical for designing effective marketing strategies.
However, in many real-world scenarios, customer segments are not explicitly labeled.

Goal:
Identify distinct customer segments based on income, spending behavior, and demographics to enable targeted marketing strategies and improve overall customer value.

Approach
To uncover hidden patterns in customer behavior, an unsupervised learning approach was applied:
Performed Exploratory Data Analysis (EDA) to understand feature distributions and relationships
Applied data preprocessing and feature scaling to ensure meaningful clustering
Used K-means clustering to segment customers based on behavioral and financial attributes
Determined the optimal number of clusters using both the Elbow Method and Silhouette Score, ensuring well-separated and meaningful segments
Customer Segments
The analysis revealed distinct customer groups with different behavioral patterns:
Cluster 1: High-value customers
High income and high spending behavior
Strategy: Focus on retention and personalized premium offers
Cluster 2: Price-sensitive customers
Lower income and moderate spending
Strategy: Target with discounts and value-driven campaigns
Cluster 3: Low-engagement customers
Low spending and low interaction
Strategy: Re-engagement campaigns or reduced acquisition spend
Cluster 4: Young impulsive spenders
High spending relative to income, likely driven by trends
Strategy: Leverage limited-time offers and trend-based campaigns

Key Insights
Customer behavior is not uniform — distinct segments exhibit different spending patterns
Some segments offer higher lifetime value and should be prioritized
Others require tailored strategies to improve engagement or cost-efficiency

Business Recommendations
Prioritize retention strategies for high-value customer segments
Apply targeted promotions to price-sensitive users
Optimize marketing spend by reducing focus on low-engagement segments
Personalize campaigns based on behavioral segmentation

Tech Stack
Python (Pandas, NumPy)
Scikit-learn (K-means, evaluation metrics)
Matplotlib / Seaborn
