# Naive Bayes

[Back to Index](../README.md)

---

## Objective

Learn Naive Bayes

## Essentials Reading

### Understanding Classifications

[Read the basics of classifications](classifications.md)

### Basics of Naive Bayes

* [Naive Bayes explained](https://www.youtube.com/watch?v=sjUDlJfdnKM) - video
* [Another Naive Bayes explanation](https://www.youtube.com/watch?v=O2L2Uv9pdDA) - video
* [Naive Bayes intro](https://www.geeksforgeeks.org/naive-bayes-classifiers/)

### Implementing Naive Bayes in Scikit-Learn

* [Naive Bayes Classification using Scikit-learn](https://www.datacamp.com/community/tutorials/naive-bayes-scikit-learn)
* [Naive Bayes algorithm in Scikit](https://scikit-learn.org/stable/modules/naive_bayes.html)

## Extra Reading

## Checklist

Check your knowledge:

* What data NB works best with?
* What are the 3 types of NB?
* Calculate the probability of Queen card, given I got a face card from a 52 deck of cards   -  P (queen | face) 
  - First calculate the probability of getting a face card
  - calculate the probability of getting a queen card
  - Now calculate the P(queen | face)

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Practice with synthetic data

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) or [make_classification](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_classification.html#sklearn.datasets.make_classification) to generate some sample data.

Try to separate them using NB

### EX-2: SPAM detection

- Here is [SMS Spam dataset](https://elephantscale-public.s3.amazonaws.com/data/spam/SMSSpamCollection.txt)
- Start with this [notebook](https://github.com/elephantscale/guided-machine-learning-labs/blob/master/naive-bayes/naive-bayes-1-spam.ipynb)
- Use NB to predict spam / ham
- Create a confusion matrix
- What is the accuracy of the model

### EX-3 - BONUS Lab

- Choose another text or categorical data from [data section](../data.md)
- And solve it with naive bayes

## More Exercises


---

## [Index](../README.md)
