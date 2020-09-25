
# Scikit-Learn Library

([back to Index](README.md))

[Scikit-Learn](https://scikit-learn.org) is the go-to library for machine learning in Python.

## Scikit Intro

* [An Introduction to Scikit Learn](https://towardsdatascience.com/an-introduction-to-scikit-learn-the-gold-standard-of-python-machine-learning-e2b9238a98ab)
* [Introduction to Scikit-Learn](https://jakevdp.github.io/PythonDataScienceHandbook/05.02-introducing-scikit-learn.html)  from [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)


* [Scikit-Learn online documentation](https://scikit-learn.org/stable/index.html) is very extensive and thorough

## Setting up Scikit

* [Setting up scikit-learn](https://scikit-learn.org/stable/install.html)

## Explore Built in Datasets

* [Dataset documentation](https://scikit-learn.org/stable/datasets/index.html)
* [How to use Scikit-Learn Datasets for Machine Learning](https://towardsdatascience.com/how-to-use-scikit-learn-datasets-for-machine-learning-d6493b38eca3)

## Creating synthetic data

* [How to Generate Test Datasets in Python with scikit-learn](https://machinelearningmastery.com/generate-test-datasets-python-scikit-learn/)

## Creating train/test splits

* [Train-Test Split for Evaluating Machine Learning Algorithms](https://machinelearningmastery.com/train-test-split-for-evaluating-machine-learning-algorithms/)
](https://www.bitdegree.org/learn/train-test-split)

## More Reading

* [A good ebook on scikit learn](https://riptutorial.com/Download/scikit-learn.pdf)

### Data Leakage

* [Data normalization before or after train-test split?](https://datascience.stackexchange.com/questions/54908/data-normalization-before-or-after-train-test-split)
* [Data Leakage in Machine Learning](https://machinelearningmastery.com/data-leakage-machine-learning/)

---

## Checklist

You should know the following

* Have Scikit development environment setup
* Explore built-in dataset
* Generate synthetic dataset

---

## Exercises

### A - Basics

#### A1 - Make sure you have scikit installed

```python
import sklearn
sklearn.__version__
# you should see version output
```

### B - Builtin Datasets

#### B1 - Print out all datasets that are included in scikit

#### B2 - Regression dataset: Load boston dataset

- Find out all the columns
- describe the dataframe
- print out sample data
- Use `describe` to understand the data

#### B3 - Classification dataset: Load IRIS dataset

- Find out all the columns
- describe the dataframe
- print out sample data
- Use `describe` to understand the data

### C - Generate Data

#### C1 - make classification dataset

* Use `make_blobs` function to make classification dataset
* visualize the dataset

#### C2 - Use `make_regression` to make a regression dataset

* Use `make_regression` to make a regression dataset
* visualize the dataset

### D - train/test split

#### D1 - Simple train/test split 

Create data like this

```python
import pandas as pd
from sklearn.model_selection import train_test_split

tip_data = pd.DataFrame({'bill' : [50.00, 30.00, 60.00, 40.00, 65.00, 20.00, 10.00, 15.00, 25.00, 35.00],
                        'tip' : [12.00, 7.00, 13.00, 8.00, 15.00, 5.00, 2.00, 2.00, 3.00, 4.00]})

x = tip_data[['bill']]
y = tip_data[['tip']]

# Use train_test_split function (20% test split)
x_train,x_test,y_train, y_test = train_test_split (x,y,test_size=0.2)

```

* Print out `x_train` and `x_test`
* Visually inspect the data, are there any common elements between train and test data?

#### D2 - test/train split on housing data

Read the [house-sales-simplified.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-simplified.csv).

```python
import pandas as pd

house_sales = pd.read_csv(...)

X = extract all columns except `SalePrice`
y = extract `SalePrice` column

```

Now split the X,y data into training and testing.

Print out the length of train and test datasets.

Since the data is too large to visually inspect, how can we programmatically ensure there are no common elements between train and test


### More exercises

* [Scikit exercises](https://www.w3resource.com/machine-learning/scikit-learn/iris/index.php)

---

## [Index](Index.md)
