# iris_dataset_clustering Project

##  Objective
The goal of this project is to demonstrate clustering techniques using the **Iris dataset** from `sklearn`. Two clustering algorithms were implemented and analyzed:

- **KMeans Clustering**
- **Hierarchical (Agglomerative) Clustering**

This is an unsupervised learning task, so the species (target) column was excluded from the clustering process.

---

##  Dataset
We used the **Iris dataset** available in the `sklearn.datasets` module. It contains 150 samples of iris flowers, each with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

---

## 🧪 Techniques Used

### 🔹 1. KMeans Clustering
- The dataset was clustered into 3 groups.
- Clusters were visualized using sepal features.
- Explained how KMeans works and why it's suitable for this dataset.

### 🔹 2. Hierarchical Clustering
- Performed agglomerative clustering using Ward’s linkage.
- Visualized the dendrogram to understand the clustering hierarchy.
- Used 3 clusters for comparison with KMeans.

---

## 📊 Visualizations
- **KMeans Cluster Plot:** Sepal length vs sepal width with cluster colors.
- **Hierarchical Dendrogram:** Tree plot showing hierarchical merging.
- **Agglomerative Cluster Plot:** Sepal length vs sepal width with cluster labels.

---

## 📦 Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `scipy`

---
