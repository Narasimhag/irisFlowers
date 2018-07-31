# irisFlowers
My attempt at classification - 100 days of ML code

In this project, I attempt to get the data from this (https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data) dataset,
visualize it using matplotlib library and apply some Machine Learning algorithms
to it.

# Day #0:
Get the data and visualize it.

# Day #1:
Compare the following algorithms to find the best for this data.
* Logistic Regression (LR)
* Linear Discriminant Analysis (LDA)
* K-Nearest Neighbors (KNN).
* Classification and Regression Trees (CART).
* Gaussian Naive Bayes (NB).
* Support Vector Machines (SVM).

In my case, I've found KNN to be the best with accuracy of 98.3%.

The confusion matrix provides an indication of the three errors made. Finally, the classification report provides a breakdown of each class by precision, recall, f1-score and support showing excellent results

## Results
0.9
[[ 7  0  0]
 [ 0 11  1]
 [ 0  2  9]]
 
                 precision    recall  f1-score   support

    Iris-setosa       1.00      1.00      1.00         7
    Iris-versicolor   0.85      0.92      0.88        12
    Iris-virginica    0.90      0.82      0.86        11

    avg / total       0.90      0.90      0.90        30

## Environment

It would be enough if you have following libraries installed, alongside Python 3+
* scipy: 0.19.1
* numpy: 1.13.1
* matplotlib: 2.0.2
* pandas: 0.20.3
* statsmodels: 0.8.0
* sklearn: 0.19.0

If you face any difficulty in installation, I've included my environment in the repository.
