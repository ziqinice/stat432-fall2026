---
id: w10-ziqiz13-oob-selection-optimism
title: "Can Tuning Make OOB Error Optimistic?"
author: "Ziqi Zhang (ziqiz13)"
---

Suppose we tune a random forest by comparing 50 combinations of `mtry` and node size and choosing the smallest OOB misclassification rate. Each observation's OOB prediction uses only trees that excluded it from their bootstrap samples. How does using those same OOB errors for parameter selection affect the reliability of the minimum OOB error as an estimate of the selected model's generalization error, compared with evaluating one setting chosen in advance?
