# Mall-Customers---Clustering
### Customer Segmentation using Clustering
## Problem
Understanding customer behavior is critical for designing effective marketing strategies. However, in many real-world scenarios, customer segments are not explicitly labeled.

## Goal
* Identify distinct customer segments based on income and spending behavior
* Better understand customer patterns
* Support more informed, data-driven decisions

## Approach
* Performed Exploratory Data Analysis (EDA) to understand the distribution of key variables
* Applied feature scaling to ensure balanced clustering
* Used K-means clustering to segment customers based on Annual Income and Spending Score
* Evaluated different values of k using the Elbow Method and Silhouette Score
* Based on the analysis, k = 5 was selected as the optimal number of clusters

## Customer Segments
* Cluster 0: Young impulsive spenders
Younger customers with relatively low income but high spending behavior
Likely driven by trends, social influence, and impulsive purchases
* Cluster 1: Average middle-class customers
Moderate income and moderate spending behavior
Represent a stable and broad customer base
* Cluster 2: High-income conservative spenders
High income but relatively low spending
More cautious and value-driven in their purchasing decisions
* Cluster 3: Young active shoppers
Younger customers with active purchasing behavior
Consistent engagement and frequent transactions
* Cluster 4: Very wealthy but inactive customers
Very high income but low spending
Untapped high-value segment with low engagement

## Key Insights
The clustering reveals clear differences in customer spending behavior
Customers can be grouped into distinct segments with different value potential
These segments can support more targeted and efficient strategies

## Business Interpretation
Different customer groups exhibit different spending patterns
Segmentation enables more tailored approaches depending on customer behavior
Can support decision-making in areas such as targeting, retention, and budget allocation

## Marketing Strategy
* Cluster 0: Young impulsive spenders
Flash sales and limited-time offers
Social media and influencer-driven campaigns
Trend-based marketing strategies
* Cluster 1: Average middle-class customers
Loyalty programs and retention campaigns
Personalized promotions
Seasonal and value-based offers
* Cluster 2: High-income conservative spenders
Premium positioning and value-focused messaging
Exclusive but rational offers
Trust-building and brand credibility
* Cluster 3: Young active shoppers
Membership programs and rewards
Product bundles and upselling strategies
Frequent buyer incentives
* Cluster 4: Very wealthy but inactive customers
Luxury experiences and personalized services
VIP programs and exclusivity-driven engagement
High-touch, relationship-based marketing

## Tech Stack
Python: Pandas, NumPy
Machine Learning: Scikit-learn (K-means, Silhouette Score)
Visualization: Matplotlib, Seaborn

## Key Takeaway
This project demonstrates how unsupervised learning can be used to uncover structure in unlabeled data, providing a foundation for more informed decision-making.
