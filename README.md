# Segmented Logistic Regression for Spam Email Detection

This repository contains code for a machine learning approach to spam email detection. The approach involves three core steps:
1. Use $k$-means clustering on the feature space to identify potential segmentation.
2. Use a decision tree classifier to learn a logical mapping from input variables to the computed segments.
3. Fit a logistic regression model for each segment.

The approach is interesting, although currently lacks material benefit over a single segmentation alternative.
