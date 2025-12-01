# Iris Dataset Clustering

This project demonstrates **unsupervised clustering** on the famous **Iris dataset** using two algorithms: **KMeans** and **Hierarchical Clustering**.

## Dataset
The **Iris dataset** contains 150 samples of flowers with 4 features each:  
- Sepal Length (cm)  
- Sepal Width (cm)  
- Petal Length (cm)  
- Petal Width (cm)  

The dataset has **3 species**: Setosa, Versicolor, and Virginica.

## Clustering Algorithms Used

### KMeans Clustering
- Groups data into **k clusters** based on distance.  
- Works well when clusters are roughly spherical.  
- Steps:
  1. Choose k initial centroids.  
  2. Assign points to the nearest centroid.  
  3. Recompute centroids.  
  4. Repeat until centroids stabilize.

### Hierarchical Clustering (Agglomerative)
- **Bottom-up approach**: each point starts as its own cluster.  
- Repeatedly merges the **closest clusters** based on distance.  
- Produces a **dendrogram** to visualize cluster relationships.  

## Features
- Scaled the dataset using `StandardScaler` for better clustering.  
- Visualized clusters in **2D and 3D plots** using `matplotlib` and `plotly`.  
- Compared clustering results with actual species labels.  

## How to Run
1. Clone the repository:  
```bash
git clone <repo_url>
