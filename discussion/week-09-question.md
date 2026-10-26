---
id: w09-ziqiz13-same-training-kernel
title: "Can Matching Training Kernels Predict Differently?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose two different kernels produce exactly the same pairwise similarity matrix for all observations in a training set, but give different similarities between a new observation and the training observations. If soft-margin SVMs use the same cost parameter, why might they fit the training data equally well yet disagree on the new observation? Explain which similarities matter during fitting and prediction, and what this example suggests about choosing a kernel using training accuracy alone.
