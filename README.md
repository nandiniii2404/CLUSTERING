# 🧠 Clustering Assignment - Breast Cancer Dataset

This repository contains the solution to a clustering assignment using the **Breast Cancer Wisconsin Diagnostic** dataset from the UCI Machine Learning Repository.

## 📚 Dataset Information

- **Source**: [UCI ML Repo - Dataset #17](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- **Fetched using**: `ucimlrepo` Python package
- **Instances**: 569
- **Features**: 30 (Real-valued)
- **Classes**: Benign / Malignant (used only for evaluation, not clustering)

## 📦 Libraries Used

- `ucimlrepo`
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

## 🧼 Preprocessing

- Feature scaling using `StandardScaler`
- Dimensionality reduction (for visualization) with `PCA`

## 🤖 Clustering Techniques Applied

1. **KMeans Clustering**
2. **Agglomerative Clustering**
3. **DBSCAN**

## 📊 Evaluation Metrics

- **Silhouette Score**
- **Davies-Bouldin Index**
- **Calinski-Harabasz Index**

## 🧾 Output Files

| File Name | Description |
|-----------|-------------|
| `clustering_results.csv` | Cluster labels from all 3 methods added to the original dataset |
| `clustering_metrics.csv` | Evaluation metrics for all clustering methods |

## 📈 Visualizations

Scatter plots of clusters were generated using the first two PCA components for all clustering techniques.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/nandiniii2404/CLUSTERING.git
   cd CLUSTERING
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   *(Or manually install: `ucimlrepo`, `scikit-learn`, `matplotlib`, `pandas`)*

3. Run the notebook in Google Colab or Jupyter.

---

## 🙋‍♀️ Author

**Nandini**  




