# Task 6: Customer Segmentation using K-Means Clustering

## Objective
Segment mall customers into distinct groups based on their annual income and spending score using K-Means clustering, to help with targeted marketing strategies.

## Steps Performed
1. Loaded and explored the Mall Customers dataset.
2. Checked for missing values (none found).
3. Renamed columns for clarity (`Annual_Income`, `Spending_Score`).
4. Visualized distributions of Age, Annual Income, and Spending Score.
5. Visualized gender distribution.
6. Selected `Annual_Income` and `Spending_Score` as clustering features.
7. Used the Elbow Method to find the optimal number of clusters (K=5).
8. Applied K-Means clustering with K=5.
9. Visualized the resulting customer clusters and centroids.
10. Analyzed average Age, Income, and Spending Score per cluster.
11. Labeled clusters into meaningful customer segments (e.g., "High Income High Spenders").
12. Saved the final segmented dataset as `mall_customers_segmented.csv`.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn (KMeans, StandardScaler)
- Jupyter Notebook

## Outcome
Customers were successfully segmented into 5 distinct groups based on income and spending behavior, enabling targeted marketing strategies for each segment (e.g., premium offers for high-income high-spenders, retention campaigns for low spenders).

## Files
- `task6_segmentation.ipynb` — notebook with full clustering workflow
- `mall_customers.csv` — raw dataset
- `mall_customers_segmented.csv` — final segmented dataset
- `distributions.png`, `gender_split.png`, `elbow_curve.png`, `customer_clusters.png`, `segment_distribution.png` — visualizations

## Demo Video
[Watch the demo](https://drive.google.com/file/d/1ybdMLuKhT3ObXll_JRl-yXjzEN2gKMC-/view?usp=drive_link)
