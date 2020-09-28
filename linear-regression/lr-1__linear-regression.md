## [Index](../README.md) 

---

# Linear Regression Intro

## Objective

Learn Linear Regression

## Reference

### Essentials (★☆☆)

#### Basics of Linear Regression

* ["Statistics PL14 - Simple Linear Regression" playlist](https://www.youtube.com/playlist?list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi) offers pretty good coverage of Linear Regression.  Start with the following videos
  - [Statistics 101: Linear Regression, The Very Basics](https://www.youtube.com/watch?v=ZkjP5RJLQF4&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=1&t=1128s&ab_channel=BrandonFoltz)
  - [Statistics 101: Linear Regression, Algebra, Equations, and Patterns](https://www.youtube.com/watch?v=iAgYLRy7e20&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=2&ab_channel=BrandonFoltz)
  - [Statistics 101: Linear Regression, The Least Squares Method](https://www.youtube.com/watch?v=Qa2APhWjQPc&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=3&ab_channel=BrandonFoltz)
  - [Statistics 101: Linear Regression, Fit and Coefficient of Determination](https://www.youtube.com/watch?v=kHZBy1uVNnM&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=4&ab_channel=BrandonFoltz)
  - [Statistics 101: Linear Regression, Standardized Regression](https://www.youtube.com/watch?v=_7pSUXwjEO8&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=5&ab_channel=BrandonFoltz)
  - [Statistics 101: Linear Regression, Understanding Model Error](https://www.youtube.com/watch?v=PhMlPvx1aoY&list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi&index=6&ab_channel=BrandonFoltz)

####  Understanding Errors and Residuals

* [Tutorial: Understanding Regression Error Metrics in Python](https://www.dataquest.io/blog/understanding-regression-error-metrics/)
* [MAE and RMSE — Which Metric is Better?](https://medium.com/human-in-a-machine-world/mae-and-rmse-which-metric-is-better-e60ac3bde13d)

#### Implementing Linear Regression in Scikit-Learn

* [Linear Regression for Machine Learning](https://machinelearningmastery.com/linear-regression-for-machine-learning/)
* [Linear Regression wit Scikit-Learn - a tutorial](https://www.kdnuggets.com/2019/03/beginners-guide-linear-regression-python-scikit-learn.html)

### More Reading

* Continue watching the rest of the videos in ["Statistics PL14 - Simple Linear Regression" playlist](https://www.youtube.com/playlist?list=PLIeGtxpvyG-LoKUpV0fSY8BGKIMIdmfCi)

## Checklist

* What do the following mean?
  - coefficients
  - slope
  - intercept
* Understand different error metrics
  - Sum of Squared Error (SSE)
  - Mean square error (MSE)
  - Mean absolute error (MAE)
  - Root mean squared error (RMSE)
* Regression evaluation metrics
  - r (Person's coefficient)
  - r<sup>2</sup> (Coefficient of determination)
* Generating synthetic dataset for regression (sklearn.datasets.make_regression)
* Familiar with `sklearn.linear_model.LinearRegression`

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### More Exercises

#### Ex-1 - Practice regression with synthetic data (★☆☆)

Here we will use Scikit's `make_regression` to generate some data and fit linear regression.

Start with this notebook : [lr-1__intro](https://github.com/elephantscale/machine-learning-learning-path-labs/blob/master/linear-regression/lr-1__intro.ipynb)

And work through it

#### Ex-2 - Billing and tipping data (★☆☆)

Start with this notebook: [lr-2__tips](https://github.com/elephantscale/machine-learning-learning-path-labs/blob/master/linear-regression/lr-2__tips.ipynb)

Complete the TODO items

#### Ex-3 - House sales data (★★☆)

- Data: [house-sales-full.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-full.csv)
- Label is : SalePrice
- Input features : Start with `Bedrooms`, `Bathrooms`,  `SqFtTotLiving`, `SqFtLot`
- Run linear regression
- What is the R<sup>2</sup> you are getting?
- Can you reason why the R<sup>2</sup> is low?
- Add more features to input and see if you can improve the score
- What is the maximum R<sup>2</sup>  you can attain?  With what features?

---

## [Index](../README.md)
