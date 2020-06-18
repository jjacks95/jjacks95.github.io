---
layout: post
mathjax: true
title: Logistic Regression
---
Linear regressions are models of the form:

$$y = \beta_0 + \beta_1 x1 + \beta_2 x2 + ... + \epsilon$$

where, $x_n1,..., x_n$ are my different features.

## How to deploy Logistic Regression model with sklearn

To employ this model in sklearn, I need to first import it


```python
from sklearn.linear_model import LogisticRegression
```

and then call the fit and predict methods:


```python
model = LogisticRegression()
```


```python
model.fit(X_train, y_train)
```


```python
y_pred = model.predict(X_test)
```
