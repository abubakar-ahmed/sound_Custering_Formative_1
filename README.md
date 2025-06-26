# Sound Dataset Clustering - ML Techniques II Assignment

This project applies clustering techniques on an **unlabeled sound dataset** to explore unsupervised learning using dimensionality reduction and clustering algorithms. The notebook includes feature extraction, PCA and t-SNE analysis, and clustering evaluation using K-Means and DBSCAN.


## Objectives

- Extract meaningful features (Mel Spectrogram) from audio data using Librosa.
- Visualize high-dimensional data before and after dimensionality reduction.
- Apply **PCA** and **t-SNE** to reduce dimensions to 3D for clustering and visualization.
- Perform clustering with **K-Means** and **DBSCAN**.
- Evaluate cluster quality using:
  - Silhouette Score
  - Davies-Bouldin Index
  - Cluster Balance
- Interpret results and compare clustering methods.

## Key Findings

- **PCA** improved clustering performance significantly, aligning with K-Means’ assumptions.
- **t-SNE** offered better visual separation but less consistent clustering results.
- **K-Means** outperformed **DBSCAN** in compactness and stability due to the dataset’s spherical structure.
- Dimensionality reduction proved essential for both performance and visualization.

## Technologies Used

- Python 3.x
- Google colab
- Libraries:
  - `librosa` – for feature extraction
  - `scikit-learn` – for PCA, t-SNE, clustering, and evaluation metrics
  - `matplotlib` & `seaborn` – for plotting
  - `numpy`, `pandas` – for data handling


