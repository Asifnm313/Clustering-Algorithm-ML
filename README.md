# CLUSTERING ALGORITHM IN MACHINE-LANGUAGE

## Iris Dataset Clustering Analysis
## Objective
This project applies KMeans and Hierarchical Clustering techniques to the Iris dataset to group similar data points and analyze patterns without predefined labels.

----

## Dataset
**Source: Built-in Iris dataset from scikit-learn.**
**Features:**
  - **Sepal length, Sepal width, Petal length, Petal width (4 numerical features).**
**Preprocessing:**
  - **Dropped the species column.**
  - **Scaled features using StandardScaler for consistency.**

----

## Key Components
1. **KMeans Clustering**
   - **Approach: Divides data into k=3 clusters using distance-based optimization.**
   - **Output:**
     - Visualized clusters in 2D using PCA.
     - Displayed centroids and evaluated inertia for cluster compactness.
2. **Hierarchical Clustering**
   - **Approach: Creates clusters based on hierarchical relationships, visualized using a dendrogram.**
   - **Output:**
     - Hierarchical relationships visualized through a dendrogram.
     - Cluster assignments displayed with PCA visualization.

---

## Technologies Used
   **Python 3, pandas, numpy, seaborn, matplotlib, scikit-learn, scipy.**

   ---
   
## Results
   - Both algorithms identified 3 distinct clusters in the dataset.
   - KMeans is faster and more scalable, while Hierarchical Clustering provides better visualization of relationships.
