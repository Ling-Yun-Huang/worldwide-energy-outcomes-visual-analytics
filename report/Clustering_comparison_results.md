# Clustering Comparison Results (2025)

This extension study focuses on comparing clustering methods for countries' development levels using energy-related indicators.

## Methods Compared
- 🔹 **K-Means**: Hard clustering, interpretable, good balance between group separation and stability.
- 🔹 **Agglomerative Hierarchical Clustering**: Dendrogram-based, less stable with 5 clusters.
- 🔹 **Gaussian Mixture Model (GMM)**: Soft clustering, allows probabilistic group membership, slightly lower validation scores.

## Validation Metrics
| Metric | Description | Best Method |
|--------|------------|-------------|
| 🧩 Silhouette | Measures cohesion vs separation | K-Means |
| 📏 Calinski–Harabasz | Higher is better, measures cluster separation | K-Means |
| 🔍 Davies–Bouldin | Lower is better, measures cluster similarity | K-Means |

## Key Findings
- ✅ **K-Means (5 clusters)** provides the most interpretable and balanced clustering.
- ⚠️ Agglomerative clustering shows instability in cluster assignment, especially for small countries.
- 🌫️ GMM captures overlapping clusters but has slightly lower validation scores.
- 📊 Comparative plots reveal differences in cluster centers, indicator patterns, and relative distributions.

## Observations
- Group characteristics remain broadly consistent with the original project (2024).
- Some small or outlier countries may shift clusters depending on method.
- Visual analysis highlights where methods agree vs diverge, helping choose clustering strategy for policy or energy analysis.

## Visual Summary
- 📈 Cluster comparison plots
- 🌍 Map of clusters for K-Means and GMM
- 🔹 Radar plots (Z-score) to show indicator differences per group
