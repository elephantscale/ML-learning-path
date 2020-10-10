
# Support Vector Machines (SVM) Intro

[Back to Index](../README.md)

---

## Objective

Learn SVM

## Essentials Reading

### Understanding Classifications

[Read the basics of classifications](classifications.md)

### Basics of SVM

* [Understanding Support Vector Machine(SVM)](https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/)
* [Support Vector Machines for Machine Learning](https://machinelearningmastery.com/support-vector-machines-for-machine-learning/)
* [support vector machine (SVM) in layman's terms](https://www.quora.com/What-does-support-vector-machine-SVM-mean-in-laymans-terms)
* [A good animation of kernel trick](https://www.youtube.com/watch?v=3liCbRZPrZA&ab_channel=udiprod)

### Implementing SVM in Scikit-Learn

* [SVM in Scikit Learn documentation](https://scikit-learn.org/stable/modules/svm.html)
* [Support Vector Machines with Scikit-learn](https://www.datacamp.com/community/tutorials/svm-classification-scikit-learn-python)


## Extra Reading

* Ch 9 of book [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) offers good overview of SVM

## Checklist

Check your knowledge:

* What is a maximal-margin classifier?
* What is slack (C) ?
* What are the strengths and weaknesses of SVM?
* Do we need to scale/normalize data before using SVM?
* What is a kernel trick?
* Q1: Which of the following statements are true for SVM (can be more than one)
  - SVM exhibits high variance
  - SVM exhibits high bias
  - SVM can be used for classification
  - SVM can be used for clustering
  - SVM can only do linear separation
  - SVM required that we scale data

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Practice with synthetic data

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using SVM

### EX-2: College Admission Data

Load [college admission data](https://elephantscale-public.s3.amazonaws.com/data/college-admissions/admission-data.csv)

It will look like this:

```text
    admit  gre   gpa  rank
0       0  380  3.61     3
1       1  660  3.67     3
2       1  800  4.00     1
3       0  640  3.19     4
4       0  520  2.93     4
...
```

- Use input features: `gre, gpa, rank`, and predict output: `admit`
- Use Logistic Regression to predict.
- Create a confusion matrix
- What is the accuracy of the model

### EX-3 - BONUS Lab

- Choose a classification dataset from [UCI data repository](https://archive.ics.uci.edu/ml/index.php)
- For example, consider [US Census Income data](http://archive.ics.uci.edu/ml/datasets/Census+Income)
- Run SVM on the data of choice

## More Exercises


---

## [Index](../README.md)
