# Decision Trees

[Back to Index](../README.md)

---

## Objective

Learn Decision Tree algorithms

## Essentials Reading

### Understanding Classifications

[Read the basics of classifications](../classifications/classifications.md)

### Understanding Regressions

[Read the basics of regressions](../regressions/regressions.md)

### Decision Trees

* [Decision Trees in Machine Learning](https://towardsdatascience.com/decision-trees-in-machine-learning-641b9c4e8052)
* [Classification And Regression Trees for Machine Learning](https://machinelearningmastery.com/classification-and-regression-trees-for-machine-learning/)
* [Decision trees explained](https://www.youtube.com/watch?v=RmajweUFKvM) - video
* [Understanding Gini index](https://towardsdatascience.com/gini-index-vs-information-entropy-7a7e4fed3fcb)

### Implementing Decision Trees in Scikit-Learn

* [Decision tree classifier tutorial in scikit learn](https://www.datacamp.com/community/tutorials/decision-tree-classification-python)
* [Decision tree regressor tutorial](https://heartbeat.fritz.ai/implementing-regression-using-a-decision-tree-and-scikit-learn-ac98552b43d7)
* [Scikitlearn documentation on trees](https://scikit-learn.org/stable/modules/tree.html)
* [Visualizing trees in scikit learn](https://mljar.com/blog/visualize-decision-tree/)

## Extra Reading

* Ch. 8 "Decision Trees" in [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)

## Knowledge Check

* What problem can decision trees solve?  Classification, regression, both?
* What are the strengths and weaknesses of Decision Trees?
* What is 'greedy algorithm'?
* How can we stop the tree from further dividing?
* Name some 'stopping criteria' to stop tree dividing further
* What is 'pruning'?
* What is a Gini index

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: DT Classification - Synthetic data  (★☆☆)

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using DT

### EX-2: DT Classification  (★★☆)

- Here is [Bank marketing dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- You may want to encode variables
- Use DT to predict yes/no binary decision
- Visualize the tree
- Create a confusion matrix
- What is the accuracy of the model
- Run Cross Validation to gauge the accuracy of this model

### EX-3: DT Regression - Synthetic data  (★☆☆)

Use Scikit's [make_regression](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_regression.html) to generate some sample data.

Use DTRegressor to solve this

### EX-4: DT Regression  (★★☆)

- Use [Bike sharing data](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
- Use DTRegressor to predict bike demand
- Visualize the tree
- Use RMSE, R2 to evaluate the model
- Use Cross Validation to thoroughly test the model performance

## More Exercises

---

## [Index](../README.md)
