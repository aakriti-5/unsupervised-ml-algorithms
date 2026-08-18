Unsupervised Machine Learning Algorithms

A collection of practical implementations of popular Unsupervised Machine Learning algorithms using Python and Scikit-learn.

This project focuses on understanding how clustering algorithms work, how data is prepared before clustering, and how different algorithms identify groups and patterns within unlabeled data.

📌 Algorithms Covered
Algorithm	Type	Main Idea
K-Means	Centroid-based clustering	Groups data points around cluster centroids
Hierarchical Clustering	Hierarchical clustering	Builds a hierarchy of nested clusters
DBSCAN	Density-based clustering	Forms clusters based on data-point density and detects noise
📂 Project Structure
Unsupervised ML Algorithm/
│
├── DBSCAN Clustering.ipynb
├── DBSCAN_README.md
│
├── Hierarichal Clustering Implementation.ipynb
├── Hierarchical_README.md
│
├── K Means Clustering Implementation.ipynb
├── KMeans_README.md
│
└── README.md

🧠 What is Unsupervised Learning?

Unsupervised Machine Learning is a type of machine learning where the model works with unlabeled data.

Instead of being given the correct output for each data point, the algorithm tries to discover hidden patterns, structures, or groups within the data.

Clustering is one of the most common applications of unsupervised learning.

For example, given a dataset containing customer information, a clustering algorithm could group customers with similar characteristics without being explicitly told which customers belong together.

🔬 Algorithms Implemented
1. K-Means Clustering

K-Means divides data into a predefined number of clusters.

The algorithm works by:

Choosing the number of clusters (K)
Initializing cluster centroids
Assigning data points to the nearest centroid
Updating the centroids
Repeating the process until the clusters stabilize

Notebook: K Means Clustering Implementation.ipynb

View K-Means README →

2. Hierarchical Clustering

Hierarchical Clustering creates a hierarchy of clusters.

This project focuses on Agglomerative Clustering, where individual data points are gradually merged into larger clusters.

A dendrogram can be used to visualize the hierarchy and help understand how clusters are formed.

Notebook: Hierarichal Clustering Implementation.ipynb

View Hierarchical Clustering README →

3. DBSCAN

DBSCAN stands for Density-Based Spatial Clustering of Applications with Noise.

Unlike K-Means, DBSCAN does not require the number of clusters to be specified beforehand.

It groups together points that are closely packed and can identify points that do not belong to any cluster as noise/outliers.

Important parameters include:

eps
min_samples

Notebook: DBSCAN Clustering.ipynb

View DBSCAN README →

⚙️ Technologies & Libraries

The project uses:

Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Scikit-learn
🔄 General Machine Learning Workflow

The notebooks follow the general workflow used when applying clustering algorithms:

Raw Data
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Scaling
   ↓
Apply Clustering Algorithm
   ↓
Analyze Clusters
   ↓
Visualize Results

Feature scaling is particularly important for many clustering algorithms because differences in feature magnitudes can affect distance calculations.

📊 K-Means vs Hierarchical vs DBSCAN
Feature	K-Means	Hierarchical	DBSCAN
Number of clusters required beforehand	Yes	Not necessarily	No
Based on	Centroids	Hierarchy	Density
Detects noise/outliers	❌	Limited	✅
Can identify non-spherical clusters	Limited	Better	✅
Uses distance	✅	✅	✅
Dendrogram	❌	✅	❌
🎯 Learning Objectives

Through this project, I explored:

The concept of Unsupervised Learning
Different types of clustering algorithms
Data preprocessing for clustering
Feature scaling
K-Means clustering
Agglomerative/Hierarchical clustering
Dendrograms
DBSCAN clustering
Cluster visualization
Outlier/noise detection
Important clustering parameters
💡 Key Takeaway

Different clustering algorithms are suitable for different types of datasets.

K-Means is simple and effective when the number of clusters is known and the clusters have a suitable shape.

Hierarchical Clustering is useful when we want to understand the relationships and hierarchy between groups.

DBSCAN is particularly useful when clusters have irregular shapes or when detecting noise and outliers is important.

🚀 Future Improvements

Possible improvements to this project include:

Adding more clustering datasets
Comparing clustering algorithms on the same dataset
Implementing additional clustering evaluation metrics
Exploring Silhouette Score
Experimenting with different hyperparameters
Adding more visualizations
Comparing the effect of different feature-scaling techniques
👩‍💻 Author

Aakriti Kandpal

B.Tech CSE — Artificial Intelligence & Machine Learning

This repository is part of my practical learning journey in Machine Learning and Artificial Intelligence.
