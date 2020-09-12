<link rel='stylesheet' href='../assets/css/main.css'/>

## [Index](../README.md)

---

# Feature Engineering - Scaling

## Objective

Learn to scale features

## Reference

### Essential Reading

* [How to Use StandardScaler and MinMaxScaler Transforms in Python](https://machinelearningmastery.com/standardscaler-and-minmaxscaler-transforms-in-python/)
* [Data normalization with Pandas and Scikit-Learn](https://towardsdatascience.com/data-normalization-with-pandas-and-scikit-learn-7c1cc6ed6475)

### Extra Reading

## Checklist

After completing the exercises below, you should be comfortable with

* What is z-score scaling?
* What is min-max scaling?
* What is normalizing
* Scaling data use above methods

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus


### A-1 : Scaling (★☆☆)

Create the following data frame

```python
df = pd.DataFrame({"home_runs": [ 30,  22,  17,  12, 44,   38,  40], 
                      "salary_in_k":[ 700, 450,340, 250, 1200, 800, 950 ]})
```

```text
   home_runs  salary_in_k
0         30          700
1         22          450
2         17          340
3         12          250
4         44         1200
5         38          800
6         40          950
```

Scale the data using min-max scaler on the scale of 0 to 100

### A-2: Standard Scaler (★☆☆)

Use StandardScalar to scale the above data.

### A-3: Normalize  (★☆☆)

Normalize the above data

### A-4: Scale NBA Player Data (★★☆)

Read [nba-player-stats.csv.csv](https://s3.amazonaws.com/elephantscale-public/data/nba/nba-player-stats.csv)

Inspect the data, and scale all numeric columns

### More Exercices

---

## [Index](../README.md)/ [Python Data Analysis](0-README.md)
