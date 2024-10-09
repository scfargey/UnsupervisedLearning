# Unsupervised Learning - Clustering Analysis

This project focuses on applying unsupervised machine learning techniques to analyze wholesale customer data. The main goal is to explore customer spending behaviors and segment them into meaningful clusters using KMeans, Hierarchical Clustering, and Principal Component Analysis (PCA).



## Project Overview

This project aims to explore and segment customers from a wholesale dataset using unsupervised learning techniques. The project covers:

- Exploratory Data Analysis (EDA) to uncover insights in the dataset.
- **KMeans Clustering**: Used to create clusters of similar customers based on their purchase behavior.
- **Hierarchical Clustering**: Explored customer segmentation using dendrograms.
- **Principal Component Analysis (PCA)**: Used for dimensionality reduction to better visualize and analyze the data.





## Results

Exploratory Data Analysis (EDA):

Correlation Analysis: We found that when people spend more on Grocery, they also tend to spend more on Detergents_Paper (0.92 correlation) and Milk (0.73 correlation). This means people who buy a lot of groceries often buy a lot of milk and detergent too.
Also, we saw that Channel 1 is somewhat related to higher spending in Grocery (0.61) and Detergents_Paper (0.64), meaning people in Channel 1 spend more in these categories.

Outliers: We found some unusual cases where people spend a lot more on Grocery and Fresh items. These people could be very big spenders or there could be mistakes in the data.

KMeans Clustering
Optimal Clusters: We used something called the Elbow Method and figured out that the best way to divide the customers is into 3 groups (or clusters).

Cluster Analysis:

Cluster 1: These are customers who spend a lot on everything, especially Grocery and Milk. They are high-value customers.
Cluster 2: These customers spend a moderate amount on everything, especially on Fresh and Frozen items.
Cluster 3: These customers spend the least, especially on Grocery and Detergents_Paper.
By dividing customers into these groups, companies can focus their marketing or special offers on specific customer types.

Dendrogram: We used a dendrogram (a type of tree diagram) and saw that the data can also be split into 3 groups, just like in the KMeans analysis. This shows that both methods give similar results.


Principal Component Analysis (PCA)
Dimensionality Reduction: We used PCA to simplify the data. Instead of looking at all the original features, we reduced them to just 2 important components, which explained about 72.46% of the differences between customers.

Key Features:

The first main component was mostly influenced by Grocery, Milk, and Detergents_Paper. This means spending in these areas is the biggest way customers differ.
The second main component was mostly influenced by Fresh and Frozen items, showing that these two categories represent a different type of customer behavior.

Insights
We can now clearly see the differences in how customers spend, especially in Grocery, Milk, and Fresh products. Companies can use these findings to create more focused marketing campaigns or promotions.
Channel 1 customers are more likely to spend more on Grocery and Detergents_Paper, so these categories may be good areas for targeted promotions.
We found some customers who are outliers, meaning they spend way more than others. These customers could be very valuable or their data might need to be checked for errors.
