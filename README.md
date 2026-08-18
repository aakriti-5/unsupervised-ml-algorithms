# Unsupervised Machine Learning Algorithms

A collection of practical implementations of popular **Unsupervised Machine Learning clustering algorithms** using Python, Jupyter Notebook, and Scikit-learn.

This project focuses on understanding how different clustering techniques work, how data is prepared before applying them, and how these algorithms can discover patterns and groups in unlabeled data.

## 📌 Algorithms Covered

### 1. K-Means Clustering

K-Means is a **centroid-based clustering algorithm** that divides data into a predefined number of clusters.

It works by assigning data points to the nearest cluster centroid and repeatedly updating the centroids until the clusters stabilize.

### 2. Hierarchical Clustering

Hierarchical Clustering builds a hierarchy of clusters using a **bottom-up (agglomerative) approach**.

A **dendrogram** can be used to visualize the hierarchy and understand how individual data points are progressively merged into larger clusters.

### 3. DBSCAN

DBSCAN (**Density-Based Spatial Clustering of Applications with Noise**) is a density-based clustering algorithm.

It groups closely packed data points together and can identify points that do not belong to any cluster as **noise or outliers**.

## 📂 Project Structure

```text
Unsupervised ML Algorithm/
│
├── DBSCAN Clustering.ipynb
├── DBSCAN_README.md
│
├── Hierarchical Clustering Implementation.ipynb
├── Hierarchical_README.md
│
├── K Means Clustering Implementation.ipynb
├── KMeans_README.md
│
└── README.md
```

Each Jupyter Notebook contains the practical implementation of the corresponding clustering algorithm, while the individual README files provide a brief explanation of the concepts and implementation.

## 🛠️ Technologies & Libraries

* **Python**
* **Jupyter Notebook**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**

## 🎯 Topics Covered

* Unsupervised Machine Learning
* Data Preprocessing
* Feature Scaling
* K-Means Clustering
* Hierarchical Clustering
* Agglomerative Clustering
* Dendrograms
* DBSCAN
* Cluster Formation
* Noise and Outlier Detection
* Cluster Visualization

## 🔄 General Workflow

The notebooks follow a general machine learning workflow:

```text
Data
  ↓
Data Exploration & Preprocessing
  ↓
Feature Scaling
  ↓
Apply Clustering Algorithm
  ↓
Analyze Cluster Assignments
  ↓
Visualize Results
```

## 💡 Key Learning

Through this project, I explored how different clustering algorithms approach the problem of grouping unlabeled data.

* **K-Means** works well when the number of clusters is known and clusters are relatively well-defined.
* **Hierarchical Clustering** helps understand the relationships and hierarchy between data points.
* **DBSCAN** is useful for density-based clustering and identifying noise or outliers.

## 📚 Purpose

This project was created as part of my **practical learning journey in Machine Learning and Artificial Intelligence**.
The goal is to build a strong understanding of fundamental unsupervised learning techniques by implementing them practically rather than only studying their theory.
