# 🍷 Wine Dataset Clustering Analysis

This project performs a comparative performance study of different clustering algorithms on the Wine dataset from the UCI Machine Learning Repository. It evaluates the impact of various preprocessing techniques on the clustering results.

## 📊 Dataset

- **Source**: [UCI Wine Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data)
- **Attributes**: 13 chemical analysis features of wines derived from three different cultivars.
- **Target**: Class label (1, 2, or 3) indicating wine type (used only for reference; not in clustering).

---

## 🔍 Project Overview

### ✅ Objective

To assess how different preprocessing techniques affect clustering performance using various clustering algorithms.

### ⚙️ Techniques Applied

#### 🔧 Preprocessing:
- No Processing
- Standard Normalization
- Power Transformation
- PCA (Principal Component Analysis)
- Combinations like Transform + Normalize, Transform + Normalize + PCA

#### 📈 Clustering Algorithms:
- KMeans
- Agglomerative (Hierarchical) Clustering
- Mean Shift

#### 📏 Evaluation Metrics:
- Silhouette Score (higher is better)
- Calinski-Harabasz Index (higher is better)
- Davies-Bouldin Score (lower is better)

---

## 🧪 Results

- **Bar plots** showing score comparisons across different algorithms and preprocessing methods.
- **Heatmaps** for each metric when `n_clusters = 3`.

---

## 📂 File Structure

```plaintext
📦wine-clustering-analysis
 ┣ 📄 clustering_analysis.ipynb        # Jupyter notebook with full code
 ┣ 📄 README.md                         # You're here!
