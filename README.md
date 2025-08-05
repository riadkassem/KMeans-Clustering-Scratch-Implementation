# K-Means Clustering from Scratch

This project demonstrates a scratch implementation of the K-Means clustering algorithm using Python. It involves clustering customer data based on features like **Annual Income** and **Spending Score**, helping identify distinct customer segments.

## 📊 Dataset Overview

The dataset appears to include:
- `CustomerID`
- `Genre`
- `Age`
- `Annual_Income_(k$)`
- `Spending_Score`

Only the relevant numerical features are used for clustering.

## 🚀 Features

- K-Means algorithm implemented manually (no use of `sklearn.cluster.KMeans`)
- Euclidean distance calculation
- Random initialization of centroids
- Iterative updating until convergence
- Visualizations of clusters and centroids
- Silhouette score explanation for cluster quality

## 📁 File

- `kmeans_scratch_implementation.ipynb` — Main notebook with full code and output visualizations.

## 🧠 Concepts Covered

- Unsupervised learning
- Clustering
- Euclidean distance
- Convergence condition
- Silhouette score (for evaluating clustering quality)

## 📌 How to Run

1. Clone the repo
2. Open the notebook with Jupyter or VS Code
3. Run all cells in order

## ✅ Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn` (if included)

You can install them via:

```bash
pip install pandas numpy matplotlib seaborn
```

## 📷 Sample Output

The notebook contains plotted clusters like this:

```
[ Customer Data Scatterplot ]
```

## 🧾 License

This project is for educational purposes and is not licensed for production use. Attribution is appreciated.
