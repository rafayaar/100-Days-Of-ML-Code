## Day 51 - Hyperparameter Tuning

- This code performs hyperparameter tuning for a RandomForestClassifier using GridSearchCV, searching over various combinations of hyperparameters such as the number of trees (n_estimators), maximum depth of trees (max_depth), minimum samples required to split an internal node (min_samples_split), and minimum samples required for a leaf node (min_samples_leaf).

- The dataset used for this hyperparameter tuning is the Iris dataset, which is loaded from scikit-learn's datasets. The features (X) and target labels (y) are extracted from this dataset.

- After fitting the model to the data using GridSearchCV, the code prints the best combination of hyperparameters found during the search (grid_search.best_params_) and the corresponding cross-validated accuracy (grid_search.best_score_). This helps in identifying the optimal set of hyperparameters for the RandomForestClassifier model.