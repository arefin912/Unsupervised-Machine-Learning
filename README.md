🌸 Unsupervised Clustering on the Iris Dataset

This project demonstrates a complete unsupervised machine learning workflow using the classic Iris dataset. It explores natural groupings in the data using KMeans and DBSCAN, along with feature scaling and dimensionality reduction (PCA) for better visualization and clustering performance.

📊 Dataset Overview

Dataset: Iris Dataset

Samples: 150

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Type: Unlabeled (used for unsupervised learning)

🔧 Technologies & Libraries Used

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

StandardScaler

PCA

KMeans

DBSCAN

🧠 Workflow Summary
1️⃣ Data Loading & Exploration

Loaded the Iris dataset

Checked:

Dataset shape

Summary statistics

Missing values

Renamed columns for better readability

2️⃣ Data Preprocessing

Applied StandardScaler to normalize features

Ensured fair distance-based clustering

3️⃣ Dimensionality Reduction

Used Principal Component Analysis (PCA)

Reduced 4D feature space → 2D for visualization

4️⃣ Optimal Cluster Selection

Applied the Elbow Method for KMeans

Identified k = 3 as the optimal number of clusters

5️⃣ KMeans Clustering

Performed clustering with n_clusters = 3

Visualized clusters using PCA-reduced features

Observed clear separation between groups

6️⃣ DBSCAN Clustering

Applied DBSCAN (eps = 0.5, min_samples = 5)

Detected:

Dense clusters

Noise points (outliers)

Visualized results using sepal features

📈 Key Insights

KMeans works well when clusters are well-separated and roughly spherical.

DBSCAN is effective for detecting arbitrary-shaped clusters and noise.

PCA significantly improves interpretability and visualization.

Feature scaling is essential for distance-based algorithms.

📁 Project Structure
.
├── iris_clustering.ipynb
└── README.md

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/iris-clustering.git


Open the notebook:

jupyter notebook iris_clustering.ipynb


Run all cells sequentially.

🎯 Learning Outcomes

Practical understanding of unsupervised learning

Comparison between centroid-based and density-based clustering

Importance of scaling and dimensionality reduction

Hands-on experience with real-world ML workflow

👤 Author

Md. Shams Arefin
CSE Student, ULAB
Interested in Machine Learning, Computer Vision, and AI Engineering