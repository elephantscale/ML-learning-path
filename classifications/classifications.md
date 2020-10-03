# Classification

[Back to Index](../README.md)

## Essential Reading

### Understanding Classifications

* [4 Types of Classification Tasks in Machine Learning](https://machinelearningmastery.com/types-of-classification-in-machine-learning/)
* [Regression and Classification | Supervised Machine Learning](https://www.geeksforgeeks.org/regression-classification-supervised-machine-learning/)
* Ch 4 - Classification of book [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) offers good overview of Classification.

### Classification Metrics

* [The 5 Classification Evaluation metrics every Data Scientist must know](https://towardsdatascience.com/the-5-classification-evaluation-metrics-you-must-know-aa97784ff226)
* [Performance Metrics for Classification problems in Machine Learning](https://medium.com/@MohammedS/performance-metrics-for-classification-problems-in-machine-learning-part-i-b085d432082b)

#### Confusion Matrix

* [Quick intro to confusion matrix](https://www.youtube.com/watch?v=wpp3VfzgNcI&ab_channel=DataScienceDojo) - video
* [Simple guide to confusion matrix terminology](https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/)
* [What is a Confusion Matrix in Machine Learning](https://machinelearningmastery.com/confusion-matrix-machine-learning/)

#### ROC Curve

* [Understanding AUC - ROC Curve](https://towardsdatascience.com/understanding-auc-roc-curve-68b2303cc9c5)
* [ROC and AUC, Clearly Explained!](https://www.youtube.com/watch?v=4jRBRDbJemM&ab_channel=StatQuestwithJoshStarmer) - video

### Classification Metrics in Sci-kit Learn

* [sklearn model evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html#)

### Extra Reading

* [Tour of Evaluation Metrics for Imbalanced Classification](https://machinelearningmastery.com/tour-of-evaluation-metrics-for-imbalanced-classification/)

## Checklist

Check your knowledge:

* How is classification different from regression?
* What is difference between binary classification and multi-class classification?  Give some examples
* What are some of the different classification algorithms?
* How do we test the accuracy of an algorithm?
* Understand the following terms:
  - Confusion matrix
  - accuracy
  - true positive
  - false negative
* What is ROC curve?  How is that useful?
* What is AUC?  How is that used?

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Draw a Confusion Matrix  (★☆☆)

We have 10 type-A, and 20 type-B.  
Imagine, we have a perfect classifier.  
Draw a perfect confusion matrix

|               | Predicted A | Predicted B |
|---------------|-------------|-------------|
| Actual A (10) | ???         | ???         |
| Actual B (20) | ???         | ???         |

### EX-2: Draw a Confusion Matrix (★★☆)

From the previous example, the classifier produced the following:

- for class A, out of 10 test samples, it predicted 7 correctly as A.  3 it mis-predicted as B
- for class B, out of 20 test samples, it predicted 15 correctly as B, 5 it mis-predicted as A

Draw the confusion matrix

|               | Predicted A | Predicted B |
|---------------|-------------|-------------|
| Actual A (10) | ???         | ???         |
| Actual B (20) | ???         | ???         |

And calculate the following:

- accuracy
- precision
- recall

---

## [Index](../README.md)
