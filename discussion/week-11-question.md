---
id: w11-ziqiz13-scaling-noise
title: "Can Standardization Amplify Noise in K-means?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose a dataset has two clearly separated groups along $X_1$, while $X_2$ has much smaller variance and consists entirely of measurement noise unrelated to those groups. Can standardizing both variables to unit variance make a K-means clustering less faithful to the grouping in $X_1$, even though it removes differences in measurement scale? Explain how standardization changes each variable's contribution to squared Euclidean distance.
