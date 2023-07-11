English version Main task
1. Implement kNN algorithm for classification problem (or for regression problem, it depends on your variant). The code should implement Parzen-window method from the lecture.
2. For the dataset from your variant:
a. Try to tune parameter ‘k’ and estimate classification or regression quality metrics:
i. For classification: Precision/Recall https://en.wikipedia.org/wiki/Precision_and_recall#Precision
              Практика 2. kNN, LOO, STOLP 1
ii. For regression: r2 https://scikit-learn.org/stable/modules/model_evaluation.html#r2-score b. Implement Leave-one-out algorithm and find optimal hyperparameter ‘k’ value.
c. For optimal ‘k’ value compare your implementation with scikit-learn version of the kNN algorithm:
i. Regression task: https://scikit- learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html#sklearn.neighbors.KNeighborsR
ii. Классификация: https://scikit- learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html#sklearn.neighbors.KNeighborsCla
