# Mall Customers Pattern Analysis Using K-Means Clustering

## Project Overview

This project analyzes customer patterns in a mall using K-Means clustering. The dataset contains customer information including their annual income and spending score. The goal is to identify distinct customer segments to help in targeted marketing strategies.

## Dataset

The dataset used in this project is `Mall_Customers.csv`, which includes the following columns:

- **CustomerID**: Unique ID for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands
- **Spending Score (1-100)**: Spending score assigned to the customer

## Dependencies

This project requires the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Code Explanation
1. **Import Libraries**: Import necessary libraries for data manipulation, visualization, and machine learning.
2. **Load Dataset**: Read the dataset into a Pandas DataFrame.
3. **Data Preparation**: Extract the relevant columns for clustering (Annual Income and Spending Score).
4. **Elbow Method**: Determine the optimal number of clusters using the Elbow method.
5. **K-Means Clustering**: Apply K-Means clustering to segment customers into clusters.
6. **Visualization**: Plot the clusters and cluster centroids to visualize the segmentation.

## Results

The Elbow method was used to determine that 5 is the optimal number of clusters. The clustering results were visualized using a scatter plot.

### Elbow Method Graph

![Elbow Method](https://github.com/yashwanth-smarty/mall-customer-patterns-KMeans-clustering-/blob/main/elbow_graph.png)

### Clustering Results Graph

![Clustering Results](https://github.com/yashwanth-smarty/mall-customer-patterns-KMeans-clustering-/blob/main/kmeans_result.png)

## Conclusion

The clustering analysis provides insights into customer segments, which can be used for targeted marketing strategies and personalized services.

