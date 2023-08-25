# ***'onenonly.learn' Module, part of One-n-Only python package***

## Machine Learning Algorithms Implementation  

***This repository contains Python implementations of several machine learning algorithms, including Linear Regression, Logistic Regression, k-Nearest Neighbors (KNN) Classifier, and Naive Bayes Classifier. These implementations are designed for educational purposes and can serve as a learning resource for understanding the underlying concepts of these algorithms.***

### ***Linear Regression***  

The `LinearRegression` class provides a basic implementation of linear regression. It supports fitting a linear regression model to a given dataset and making predictions using the learned coefficients.

```python
from onenonly.learn import LinearRegression
from sklearn import model_selection
import numpy as np

np.random.seed(51)
num_samples = 50
x = np.random.rand(num_samples, 1) * 10
y = 2 * x + 1 + np.random.randn(num_samples, 1)

xtrain,xtest,ytrain,ytest = model_selection.train_test_split(x,y,test_size=0.33,random_state=42)

model = LinearRegression()

model.fit(xtrain,ytrain)

pred = model.predict(xtest)
print(pred)
```

### ***Logistic Regression***  

The `LogisticRegression` class provides an implementation of logistic regression. It supports fitting a logistic regression model to a given dataset and making binary classification predictions using the learned weights and bias.

```python
from onenonly.learn import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler

xtrain,xtest,ytrain,ytest = train_test_split(x,y,test_size=0.2,random_state=42)

scaler = StandardScaler()
X_train_scaled = scaler.fit_transform(xtrain)
X_test_scaled = scaler.transform(xtest)

logreg_model = LogisticRegression()
logreg_model.fit(X_train_scaled, ytrain)
pred = logreg_model.predict(X_test_scaled)
print(pred)
```

### ***k-Nearest Neighbors (KNN) Classifier***  

The `KNNClassifier` class implements the k-Nearest Neighbors algorithm for classification. It supports fitting the model to a training dataset and making predictions using the k-nearest neighbors approach.

```python
from onenonly.learn import KNNClassifier

xtrain = np.array([[1, 2], [2, 3], [3, 4], [5, 5]])
ytrain = np.array([0, 0, 1, 1])

xtest = np.array([[2.5, 3.5], [4, 4], [1, 1]])
knn_classifier = KNNClassifier(k=2)
knn_classifier.fit(xtrain,ytrain)
predictions = knn_classifier.predict(xtest)
```

