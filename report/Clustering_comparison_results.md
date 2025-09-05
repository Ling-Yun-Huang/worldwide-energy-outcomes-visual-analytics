## Clustering Comparison Results (2025)

This extension study focuses on comparing clustering methods for countries' development levels using energy-related indicators.

### Validation Metrics within Clustering Methods 📊
<img src="../figure/clustering_metrics_comparison.png" width="650">

#### Key Findings
- ✅ **K-Means:** Best performance for 4–5 clusters across all metrics.
- ⚠️ **GMM:** Similar to K-Means but slightly lower scores.
- ❌ **Agglomerative:** Less stable and lower overall performance.

### K-Means vs. GMM 🔄

Comparison of K-Means and GMM clustering with 5 clusters.

<img src="../figure/kmm_gmm_5.png" width="650">

- ✨ **GMM:** Produces softer, probabilistic clusters.
- 📊 **K-Means:** Hard assignment, more distinct clusters.

**Indicator means across clusters show:**

<img src="../figure/rader_plot.png" width="650">

- Apart from **Voice and Accountability**, most indicators in Cluster 0 are similar between the two methods.
- Other clusters show slight differences in means depending on the method used.
