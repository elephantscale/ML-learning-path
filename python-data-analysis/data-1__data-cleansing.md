<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)

---

# Data Cleansing

## Objective

Learn cleaning up  messy data

## Reference

### Essential Reading

#### Data Cleansing

* [Data cleansing tutorial](https://towardsdatascience.com/what-is-data-cleaning-how-to-process-data-for-analytics-and-machine-learning-modeling-c2afcf4fbf45)
* [Data cleansing with Pandas]( https://medium.com/better-programming/data-cleaning-with-python-pandas-an-introduction-1cfd5cde6884)

#### Handling Missing Data

* [6 Different Ways to Compensate for Missing Values In a Dataset](https://towardsdatascience.com/6-different-ways-to-compensate-for-missing-values-data-imputation-with-examples-6022d9ca0779)
* [Tutorial: Introduction to Missing Data Imputation](https://medium.com/@Cambridge_Spark/tutorial-introduction-to-missing-data-imputation-4912b51c34eb)
* [Simple techniques for missing data imputation](https://www.kaggle.com/residentmario/simple-techniques-for-missing-data-imputation)

### Extra Reading

* [Data cleansing in python](https://towardsdatascience.com/data-cleaning-in-python-the-ultimate-guide-2020-c63b88bf0a0d)
* [Pandas cleanup video](https://www.youtube.com/watch?v=iYie42M1ZyU)

## Checklist

After completing the exercises below, you should be comfortable with

* Explore dataset to figure out if the data needs cleansing
* Identify missing data
* Identify invalid data
* Cleanse data

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus


### A - Handling Missing Data

#### A1 - Handling Missing Data

We have the following data.  What would be a good way to handle missing data?  Please discuss the following choices:

* Drop the rows with missing data
* Substitute zero for missing values
* Substitute another value for missing values  (if so what is that value?)

```text
year     month   rainfall
2019     Jan     10
2019     Feb     12
2019     Mar     ?
2019     Apr     20
2019     May     ?

```

#### A2 - Handling Missing data

How will you handle missing data in this dataset?

```text
Person   Height_cm
A         180
B         ?
C         172
D         155
E         160
F         ?
```

---

### Exercicses

#### EX-1 : Cleanup data (college admission) (★☆☆)

* Start with this [notebook](https://github.com/elephantscale/machine-learning-learning-path-labs/blob/master/python-data-analytics/data-cleanup.ipynb)
* Complete the TODO items

#### EX-2 : Cleaning up House Sales Data (★★☆)

* Read the [house-sales-simplified.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-simplified.csv).
* Identify columns that need data cleanup  
Hint : `Zipcode`
* Convert `SaleDate` to actual date type
* Do a barplot of houses sold per year
* What percentage of data is clen?

#### More Exercices

* [Pandas cleanup](https://www.w3resource.com/python-exercises/pandas/missing-values/index.php)

---

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)
