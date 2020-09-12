<link rel='stylesheet' href='../assets/css/main.css'/>

## [Index](../README.md)

---

# Feature Engineering - Variable Encoding

## Objective

Learn to encode categorical variables

## Reference

### Essential Reading

* [Encoding categorical variables](https://heartbeat.fritz.ai/hands-on-with-feature-engineering-techniques-encoding-categorical-variables-be4bc0715394)
* [Encoding categorical data](https://towardsdatascience.com/understanding-feature-engineering-part-2-categorical-data-f54324193e63)
* [Categorical encoding using Scikit-Learn](https://towardsdatascience.com/categorical-encoding-using-label-encoding-and-one-hot-encoder-911ef77fb5bd)

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
df = pd.DataFrame({"customer_id":[1,2,3,4,5,6,7], 
                      "status":['married', 'single', 'single', 'divorced', 'married' ,'single', 'married' ]})
```

```text
   customer_id    status
0            1   married
1            2    single
2            3    single
3            4  divorced
4            5   married
5            6    single
6            7   married
```

Index encode (integer encode) `status` column

### A-2: One-Hot Encoding (★☆☆)

One-hot encode `status` column in the above dataframe

#### A-3: Encode Prosper Data (★★☆)

Read [prosper-data-simplified.csv](https://s3.amazonaws.com/elephantscale-public/data/prosper-loan/prosper-loan-data-simplified.csv)

Inspect the data, and identify categorical variables to encode.  Use appropriate encoding


### More Exercices


---

## [Index](../README.md)/ [Python Data Analysis](0-README.md)
