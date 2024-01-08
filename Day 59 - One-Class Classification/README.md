## Day 58 - Multivariate Regression

- One-Class Classification is designed for scenarios where only the "normal" class is available during training, making it suitable for anomaly detection or identifying instances that deviate from the norm.

- The One-Class SVM algorithm is commonly used for OCC due to its ability to learn a decision boundary around the normal class and identify deviations as outliers during testing.

- The nu parameter in the One-Class SVM model determines the expected proportion of outliers. Fine-tuning this parameter is crucial; too low a value may result in capturing too many outliers as inliers, while too high a value may lead to the opposite. Experiment and adjust nu based on your specific data characteristics.
