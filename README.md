# CODEC - Detecting Linear Corrleations in Dense Clusters with CoMad PCA

---

When  reading  the  word  comedian  one  probably  expects  a
scientific decompostion of the entertainment industry. But in context of
statistic and data mining, the comedian refers to a measure for the joint
median of two random variables. In this preliminary work we introduce
CODEC - COrrelations in DEnse Clusters - a method for detecting lin-
ear correlations in dense clusters utilizing a comedian-based PCA. The
idea of CODEC is intriguingly simple: first a density-based clustering is
performed using the well established clustering method DBSCAN. Then
on each of the clusters PCA is performed. Instead of using the covari-
ance matrix we use the comedian matrix as a basis for performing PCA.
The experiments show that a comedian-based PCA is more robust to-
wards noise and outliers, yielding eigenvectors which represent the linear
correlation better than its covariance-based competitor
