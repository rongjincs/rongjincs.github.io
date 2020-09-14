---
title: "The Bias Method for Robust Centered Principal Component Analysis"
collection: publications
permalink: /publication/tkdd
venue: 'ACM Transactions on Knowledge Discovery from Data (TKDD)'
date: 2020-04-04
citation: 'Baokun He, Guihong Wan, <b>{Rong Jin}</b>, and Haim Schweitzer. <i>ACM Transactions on Knowledge Discovery from Data (TKDD).</i>.'
---
[[PDF]](https://rongjinutd.github.io/files/.pdf)
  
## Abstract
Many robust implementations of principal component analysis (PCA) remove outliers from the data and compute the principal
components of the remaining data. The robust centered variant requires knowledge of the center of the non-outliers. Unfortunately,
the non-outliers center is unknown until after the outliers are determined, and using an inaccurate center may lead to the detection of
wrong outliers. We demonstrate this problem in several known robust PCA algorithms. We describe a method that implicitly centers
the non-outliers, implemented by appending a constant (bias) value to each data point. This bias method can be used with “black box”
robust PCA algorithms by augmenting their input with minimal change to the algorithm itself.
