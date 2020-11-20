# Random Forest

[Back to Index](../README.md)

---

## Objective

Learn Random Forest algorithms

## Prerequisite Reading

* Brush up  on [Decision Trees](decision-trees.md)

## Essentials Reading

### Random Forest

* [Understanding Random Forest](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)
* [Random Forest algorithm](https://www.youtube.com/watch?v=eM4uJ6XGnSM) - video
* [How to Develop a Random Forest Ensemble in Python](https://machinelearningmastery.com/random-forest-ensemble-in-python/) - good in-depth introduction and code examples
* [Bagging and Random Forest Ensemble Algorithms for Machine Learning](https://machinelearningmastery.com/bagging-and-random-forest-ensemble-algorithms-for-machine-learning/)

#### RF Feature Importance

* [How to Calculate Feature Importance With Python](https://machinelearningmastery.com/calculate-feature-importance-with-python/) - Focus on RF section
* [Explaining Feature Importance by example of a Random Forest](https://towardsdatascience.com/explaining-feature-importance-by-example-of-a-random-forest-d9166011959e)
* [Feature Selection Using Random Forest](https://chrisalbon.com/machine_learning/trees_and_forests/feature_selection_using_random_forest/)

### Extra Reading

* [Random Forests](https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm) - some good theory
* Section. 8.2 "Bagging, Random Forests, Boosting" in [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)

### Implementing Random Forest in Scikit-Learn

* [Random Forest Algorithm with Python and Scikit-Learn](https://stackabuse.com/random-forest-algorithm-with-python-and-scikit-learn/)
* [Scikit Learn documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)
* [Understanding Random Forests Classifiers in Python](https://www.datacamp.com/community/tutorials/random-forests-classifier-python)

## Knowledge Check

* What problem can RF solve?  Classification, regression, both?
* What are the issues with DT, that are solved by RF?
* What are the strengths and weaknesses of RF?
* What are the tuning parameters for RF?  Which is the most important tuning param?
* How do we calculate *feature importance* from RF?

## Exercises

We will be using RF in the same exercises we did in Decision Trees section

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: RF Classification - Synthetic data  (★☆☆)

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using RF

### EX-2: RF Classification  (★★☆)

- Here is [Bank marketing dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- You may want to encode variables
- Use DT to predict yes/no binary decision
- Visualize the tree
- Create a confusion matrix
- What is the accuracy of the model
- Run Cross Validation to gauge the accuracy of this model

### EX-3: RF Regression - Synthetic data  (★☆☆)

Use Scikit's [make_regression](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_regression.html) to generate some sample data.

Use RandomForestRegressor to solve this

### EX-4: RF Regression  (★★☆)

- Use [Bike sharing data](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
- Use RandomForestRegressor to predict bike demand
- Visualize the tree
- Use RMSE, R2 to evaluate the model
- Use Cross Validation to thoroughly test the model performance

## More Exercises

---

## [Index](../README.md)
