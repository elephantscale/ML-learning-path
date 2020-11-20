# Boost Trees

[Back to Index](../README.md)

---

## Objective

Learn Boost Tree algorithms

## Prerequisite Reading

* Brush up  on [Decision Trees](decision-trees.md)
* Brush up  on [Random Forest](random-forest.md)

## Essentials Reading

### Boost Trees

* [Gradient Boosting Classifiers in Python with Scikit-Learn](https://stackabuse.com/gradient-boosting-classifiers-in-python-with-scikit-learn/) - Good explanation of how boost trees work
* [A Gentle Introduction to the Gradient Boosting Algorithm for Machine Learning](https://machinelearningmastery.com/gentle-introduction-gradient-boosting-algorithm-machine-learning/) - good overview of theory

### Extra Reading

* [Gradient Boosting Machine Learning](https://www.youtube.com/watch?v=wPqtzj5VZus) - video of a talk by Professor Trevor Hastie
* Section. 8.2.3 "Boosting", page 321 in [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)

### Implementing Boosting trees in Scikit-Learn

* [Gradient Boosting with Scikit-Learn, XGBoost, LightGBM, and CatBoost](https://machinelearningmastery.com/gradient-boosting-with-scikit-learn-xgboost-lightgbm-and-catboost/)
* [Scikit ensemple methods](https://scikit-learn.org/stable/modules/ensemble.html)
* [GradientBoostingClassifier in Scikit doc](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html)

## Knowledge Check

* What is the basic principle for boost trees?
* What are some implementations of boost trees?

## Exercises

We will be using BT in the same exercises we did in Decision Trees section

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Classification - Synthetic data  (★☆☆)

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using BT

### EX-2: Classification  (★★☆)

- Here is [Bank marketing dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- You may want to encode variables
- Use DT to predict yes/no binary decision
- Visualize the tree
- Create a confusion matrix
- What is the accuracy of the model
- Run Cross Validation to gauge the accuracy of this model

### EX-3: Regression - Synthetic data  (★☆☆)

Use Scikit's [make_regression](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_regression.html) to generate some sample data.

Use RandomForestRegressor to solve this

### EX-4: Regression  (★★☆)

- Use [Bike sharing data](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
- Use RandomForestRegressor to predict bike demand
- Visualize the tree
- Use RMSE, R2 to evaluate the model
- Use Cross Validation to thoroughly test the model performance

## More Exercises

---

## [Index](../README.md)
