
# Logistic Regression Intro

[Back to Index](../README.md)

---

## Objective

Learn Logistic Regression

## Essentials Reading

### Understanding Classifications

[Read the basics of classifications](classifications.md)

### Basics of Logistic Regression

* [Statistics PL16 - Logistic Regression](https://www.youtube.com/playlist?list=PLIeGtxpvyG-JmBQ9XoFD4rs-b3hkcX7Uu)  - a video series by Brandon Foltz offer very good coverage of Logistic Regression.  Start with the following videos:
  - [Statistics 101: Logistic Regression, An Introduction](https://www.youtube.com/watch?v=zAULhNrnuL4&list=PLIeGtxpvyG-JmBQ9XoFD4rs-b3hkcX7Uu&index=1)
  - [Statistics 101: Logistic Regression, Logit and Regression Equation](https://www.youtube.com/watch?v=NmjT1_nClzg&list=PLIeGtxpvyG-JmBQ9XoFD4rs-b3hkcX7Uu&index=3)
* [Linear vs. Logistic Regression](https://www.youtube.com/watch?v=OCwZyYH14uw&ab_channel=edureka%21) - video

### Implementing Logistic Regression in Scikit-Learn

* [Understanding Logistic Regression in Python](https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python)
* [Logistic Regression in Python](https://realpython.com/logistic-regression-python/)

## Extra Reading

* [Logistic regression a quick intro](http://bcs.whfreeman.com/webpub/statistics/PSBE4e/Companion_Chapters/Moore_4e_CH17.pdf)
* Ch 4 - Classification of book [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) offers good overview of Classification.
  * Section 4.3 covers Logistic Regression

## Checklist

Check your knowledge:

* What is a sigmoid curve?
* What is the min/max values for sigmoid?
* How do we convert the sigmoid / logistic output to a binary classification (yes/no  or true/false)
* Why is logistic called regression, but we use it for classification?

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Practice logistic regression with synthetic data

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using LogisticRegression

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
- Run Logistic regression on the data of choice

## More Exercises

* [More logistc regression exercises](https://stats.libretexts.org/Bookshelves/Introductory_Statistics/Exercises_(Introductory_Statistics)/Exercises%3A_OpenIntro_Statistics/8.E%3A_Multiple_and_Logistic_Regression_(Exercises))

---

## [Index](../README.md)
