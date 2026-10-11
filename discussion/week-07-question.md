---
id: w07-ziqiz13-pca-before-qda
title: "When Can PCA Make QDA Worse?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose a high-dimensional classification problem has class-specific covariance structure that is important for prediction, but ordinary QDA covariance estimates are unstable. We first apply unsupervised PCA and retain enough principal components to explain 95% of the overall predictor variance, then fit QDA. Why can this reduce test accuracy even though most predictor variance is preserved? Explain how low-variance directions can contain class-separating information and how the number of principal components should be selected without using the test set.
