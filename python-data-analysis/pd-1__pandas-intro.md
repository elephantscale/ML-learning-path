<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)

---

# Pandas Intro

## Objective

Learn Pandas

## Reference

### Essentials (★☆☆)

- **Pandas cheat Sheets:** [1](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) ,  [2](http://datacamp-community-prod.s3.amazonaws.com/dbed353d-2757-4617-8206-8767ab379ab3) , [3](https://drive.google.com/file/d/1UHK8wtWbADvHKXFC937IS6MTnlSZC_zB/view)
- [Pandas section](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html) is a very good introduction to Pandas
  - [Intro to Pandas](https://jakevdp.github.io/PythonDataScienceHandbook/03.00-introduction-to-pandas.html)
  - [Pandas data types](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html)
- [Pandas axis](https://www.geeksforgeeks.org/python-pandas-dataframe-axes/)
- Indexing and Selection
  - [Indexing](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html)
- Operating on dataframes
  - [Aggregation](https://jakevdp.github.io/PythonDataScienceHandbook/03.08-aggregation-and-grouping.html)


### More Resources

- [Python for data analysis](https://www.oreilly.com/library/view/python-for-data/9781449323592/) - A great book by Wes McKinney  (the original creator of Pandas)

## Checklist

After completing the exercises below, you should be comfortable with

- Using Pandas

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### A - Creating dataframes

**A1 - Import Pandas and print out the current version (★☆☆)**

**A2 - Create an empty dataframe (★☆☆)**  

**A3 - Create a dataframe from a dictionary**  
Create a dictionary like this first.  And then convert it into a dataframe
```text
d = {'a': [1, 2],
     'b': [3, 4] }
```

**A4 - Create the following dataframe (★☆☆)** 

Expected output:

```text
            city  population  rainfall
0       San Jose          10      15.5
1  San Francisco           5      10.2
2    Los Angeles          30       5.5
3        Seattle           7      50.5
```

**A5 - Print the shape of above dataframe (★☆☆)**  
Hint : `pd.shape`

### B - Indexing and Slicing

**B1 - In the above dataframe, print out `population` column (★☆☆)**  
Expected output:

```text
0    10
1     5
2    30
3     7
```

**B2 - Print out column 2**   
Expected output:

```text
0    15.5
1    10.2
2     5.5
3    50.5
```

**B3 - In the previous example, just print out the city names, without index (★☆☆)**  
Hint : `values`  
Expected output:   `['San Jose', 'San Francisco', 'Los Angeles', 'Seattle']`

**B4 - Print out the row for `San Francisco` (★☆☆)**  
Hint: `iloc`  
Expected output:

```text
city          San Francisco
population                5
rainfall               10.2
```

**B5 - Print out rainfall number for Settle (★☆☆)**

### C - Manipulating DF

**C1 - Set population  for San Francisco  to 12 (★☆☆)**  
Hint: `iloc`  

Expected output:  

```text
            city  population  rainfall
0       San Jose          10      15.5
1  San Francisco          12      10.2
2    Los Angeles          30       5.5
3        Seattle           7      50.5
```

**C2 - Add a new row as follows (★☆☆)**  
`city: 'San Diego', population: 8, rainfail: 7.5`  
Hint : `pd.append`  
Expected output:

```text
            city  population  rainfall
0       San Jose          10      15.5
1  San Francisco          12      10.2
2    Los Angeles          30       5.5
3        Seattle           7      50.5
0      San Diego           8       7.5
```

### D - Searching

**D1 - Print rows where population > 10 (★★☆)**  

Hint : `cities['population'] > 10`  and `pd.loc`

Expected output:

```text
            city  population  rainfall
1  San Francisco          12      10.2
2    Los Angeles          30       5.5
```

**D2 - Print rows where population > 10 and rainfal < 10 (★★☆)**  

Expected output:

```text
            city  population  rainfall
2    Los Angeles          30       5.5
```

### E - Reading Files

**E1 - Read the csv files (★☆☆)**  
Read the [house-sales-sample.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-sample.csv).   

Hint: `pd.read_csv`

**E2 - Print out the column types of the above dataframe (★☆☆)**  
Hint: `df.dtypes`

**E3 - Print out the information about the above dataframe.  Note the datatypes and memory usage (★☆☆)**  
Hint: `df.info()`

**E4 - And how many sales for 'Bedrooms = 4' (★☆☆)**  
Hint: `query` or df indexing or `size`

### More Exercices

- https://www.w3resource.com/python-exercises/pandas/index.php
- https://www.machinelearningplus.com/python/101-pandas-exercises-python/
- https://github.com/guipsamora/pandas_exercises




---

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)
