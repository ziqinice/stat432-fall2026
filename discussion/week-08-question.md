---
id: w08-ziqiz13-accuracy-vs-support-vectors
title: "Can Equal Accuracy Hide Different Margins?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose two linear soft-margin SVMs are fitted to the same data with different cost parameters, and both classify every training observation correctly. Could the fit with the smaller cost parameter still have more support vectors? Explain how correctly classified observations with $0<y_i f(x_i)<1$ affect the hinge loss and support-vector count, and why training accuracy alone would miss this difference.
