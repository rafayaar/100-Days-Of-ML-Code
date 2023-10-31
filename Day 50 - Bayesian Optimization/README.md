## Day 50 - Bayseian Optimization

- This code performs hyperparameter optimization for a Support Vector Machine (SVM) classifier using Bayesian optimization with the skopt library.

- It uses the Iris dataset, splits it into training and testing sets, and searches for the best hyperparameters for the SVM model in terms of the 'C' (penalty parameter) and 'gamma' (kernel coefficient) values.

- The code then prints the best hyperparameters found and evaluates the test accuracy of the SVM model with these optimal hyperparameters.