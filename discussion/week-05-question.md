---
id: w05-ziqiz13-irrelevant-variable-knn
title: "Why Can an Irrelevant Variable Hurt KNN?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose a KNN model already uses several useful standardized predictors. We then add one more standardized predictor that is independent of both the response and the useful predictors. Since the new variable contains no predictive information, why can adding it still increase test error? Explain how it can change which observations are considered nearest neighbors, and whether simply collecting more training data would always solve the problem.
