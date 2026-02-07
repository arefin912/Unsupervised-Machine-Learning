# 🌸 Unsupervised Clustering on the Iris Dataset

This project demonstrates a complete **unsupervised machine learning workflow** using the classic **Iris dataset**. The notebook explores natural groupings in the data using **KMeans** and **DBSCAN**, along with **feature scaling** and **dimensionality reduction (PCA)** for effective clustering and visualization.

---

## 📊 Dataset Overview

- **Dataset:** Iris Dataset  
- **Number of Samples:** 150  
- **Number of Features:** 4  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Learning Type:** Unsupervised

---

## 🔧 Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
  - StandardScaler  
  - PCA  
  - KMeans  
  - DBSCAN  

---

## 🧠 Project Workflow

### 1. Data Loading & Exploration
- Loaded the Iris dataset
- Inspected dataset structure
- Checked for missing values
- Renamed columns for clarity

### 2. Data Preprocessing
- Standardized features using **StandardScaler**
- Ensured fair distance computation for clustering

### 3. Dimensionality Reduction
- Applied **PCA** to reduce features from 4D to 2D
- Improved visualization and cluster separability

### 4. Optimal Cluster Selection
- Used the **Elbow Method**
- Identified **k = 3** as the optimal number of clusters

### 5. KMeans Clustering
- Applied KMeans with `n_clusters = 3`
- Visualized clusters using PCA components

### 6. DBSCAN Clustering
- Applied DBSCAN with:
  - `eps = 0.5`
  - `min_samples = 5`
- Identified dense clusters and noise points
- Visualized clusters using sepal features

---

## 📈 Key Observations

- **KMeans** performs well when clusters are compact and well-separated
- **DBSCAN** effectively detects arbitrary-shaped clusters and outliers
- **PCA** enhances interpretability and visualization
- Feature scaling is crucial for distance-based algorithms

---

## 📁 Repository Structure

.
├── iris_clustering.ipynb
└── README.md


---

## 🚀 How to Run

1. Clone the repository:
``bash
git clone https://github.com/your-username/iris-clustering.git

Navigate to the project directory:

cd iris-clustering


Open the notebook:

jupyter notebook iris_clustering.ipynb


🎯 Learning Outcomes

Understanding of unsupervised learning techniques

Hands-on experience with KMeans and DBSCAN

Practical use of PCA for dimensionality reduction

End-to-end ML workflow implementation

👤 Author

Md. Shams Arefin
CSE Student, ULAB
Interested in Machine Learning, Computer Vision, and AI Engineering
