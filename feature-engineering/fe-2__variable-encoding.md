# Feature Engineering - Variable Encoding

[Back to Index](../README.md)

## Objective

Learn to encode categorical variables

## Reference

### Essential Reading

* [Encoding categorical variables](https://heartbeat.fritz.ai/hands-on-with-feature-engineering-techniques-encoding-categorical-variables-be4bc0715394)
* [Encoding categorical data](https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63)
* [One-Hot Encoding in Python with Pandas and Scikit-Learn](https://stackabuse.com/one-hot-encoding-in-python-with-pandas-and-scikit-learn/)

### Encoding Options

#### __Pandas__

`pd.get_dummies` quick and easy.  Here are some examples

* [The Dummy’s Guide to Creating Dummy Variables](https://towardsdatascience.com/the-dummys-guide-to-creating-dummy-variables-f21faddb1d40)
* [Python Pandas – get_dummies() method](https://www.geeksforgeeks.org/python-pandas-get_dummies-method/)
* [pandas.get_dummies() documentation](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.get_dummies.html)

#### __SKLearn Encoders__

Scikit offers the following encoders:

- `sklearn.preprocessing.LabelEncoder`
- `sklearn.preprocessing.OneHotEncoder`

Try these examples:

* [Categorical encoding using Scikit-Learn](https://towardsdatascience.com/categorical-encoding-using-label-encoding-and-one-hot-encoder-911ef77fb5bd)

#### __Category Encoders__

[Category Encoders](https://contrib.scikit-learn.org/category_encoders/)  are easy to use encoders.

* [Smarter Ways to Encode Categorical Data for Machine Learning](https://towardsdatascience.com/smarter-ways-to-encode-categorical-data-for-machine-learning-part-1-of-3-6dca2f71b159) - a good intro to CE
* [Category Encoders Examples](https://www.kaggle.com/discdiver/category-encoders-examples)

### Extra Reading

## Checklist

After completing the exercises below, you should be comfortable with

* Encoding schemes for categorical variables
* What is the difference between integer indexing vs. one-hot encoding?  Why do we need one-hot encoding?

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### A - Encoding

### A-1 : Index Encoding (★☆☆)

Create the following data frame

```python
import pandas as pd

df = pd.DataFrame({"age" : [65, 32, 24, 55, 45, 30, 35 ],
                   "gender" : ['Male', 'Male', 'Female', 'Male', 'Male', 'Female', 'Female'],
                   "status":['married', 'single', 'single', 'divorced', 'married' ,'single', 'married' ]
                   })
```

```text
   age  gender    status
0   65    Male   married
1   32    Male    single
2   24  Female    single
3   55    Male  divorced
4   45    Male   married
5   30  Female    single
6   35  Female   married
```

Index encode (integer encode) `status` column and `gender` column

### A-2: One-Hot Encoding (★☆☆)

One-hot encode `status` column and `gender` column

#### A-3: Encode Prosper Data (★★☆)

Read [prosper-data-simplified.csv](https://s3.amazonaws.com/elephantscale-public/data/prosper-loan/prosper-loan-data-simplified.csv)

Inspect the data, and identify categorical variables to encode.  Use appropriate encoding

### More Exercises

---

## [Index](../README.md)
