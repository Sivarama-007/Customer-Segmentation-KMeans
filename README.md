# Customer Segmentation Using K-Means Clustering

## Project Overview
This project uses the K-Means clustering algorithm to segment customers based on their **Annual Income** and **Spending Score**. The goal is to identify distinct customer groups for targeted marketing and business strategy development.

---

## Dataset
The dataset used is `Mall_Customers.csv` which contains 200 records and 5 columns:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Steps Performed

1. **Importing Dependencies**  
   Imported essential Python libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, and `sklearn.cluster.KMeans`.

2. **Data Loading & Exploration**  
   Loaded the data into a Pandas DataFrame and explored its shape, summary info, and checked for missing values.

3. **Feature Selection**  
   Selected the features `Annual Income (k$)` and `Spending Score (1-100)` for clustering.

4. **Determining Optimal Number of Clusters**  
   Used the Elbow Method by plotting Within-Cluster Sum of Squares (WCSS) for 1 to 10 clusters to find the optimal number of clusters (5 clusters chosen).

5. **Training the K-Means Model**  
   Trained the K-Means model with 5 clusters and predicted cluster labels for each customer.

6. **Visualization**  
   Visualized the clusters with different colors and marked the cluster centroids.

---

## Results
- The dataset was segmented into 5 distinct clusters.
- Each cluster groups customers with similar spending behavior and income levels.
- The visual plot clearly shows the segmentation and cluster centroids.

---

## How to Run
1. Upload the `Mall_Customers.csv` file to your Google Colab environment or specify the correct path.
2. Run the notebook cells sequentially.
3. Observe the elbow plot and cluster visualization to understand customer segmentation.

---

## Tools & Libraries
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
