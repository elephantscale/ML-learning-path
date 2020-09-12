<link rel='stylesheet' href='../assets/css/main.css'/>

## [Index](../README.md)/ [Python Data Analysis](0-README.md)

---

# Visualizations in Python

## Objective

Learn graphing and visualization in Python

## Reference

**Matplotlib** is the workhorse of python visualization.  It is old but widely used.

**Seaborn** library aims to give pretty graphs and high level APIs. 

### Essentials (★☆☆)

#### Generic

* [5 Data Visualization Best Practices](https://www.gooddata.com/blog/5-data-visualization-best-practices-0)

#### Visualization in Python
* [Graph libraries in Python](https://towardsdatascience.com/introduction-to-data-visualization-in-python-89a54c97fbed) - A good overview of graphics libraries in Python
* [Python graph gallery](https://python-graph-gallery.com/) is the ultimate website with lots of sample graph and code for both Matplot and Seaborn
* [Visualization section](https://jakevdp.github.io/PythonDataScienceHandbook/04.00-introduction-to-matplotlib.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
* Seaborn aims to give prettier graphs out of the box
  * [Seaborn section](https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
  * [An excellent Seaborn tutorial](https://elitedatascience.com/python-seaborn-tutorial) with Pokemon dataset :-) 

## Checklist

After completing the exercises below, you should be comfortable with

* Creating visualizations using matplot and seaborn
* What is the difference between Seaborn vs Matplotlib?

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### A - Easy

#### A1 - Do a scatter plot of following data (★☆☆)

```python
bills = [50,30,60,40,65,20,10,15,25,35]
tips= [12,7,13,8,15,5,2,2,3,4]
```

* Label x-axis as 'bill'
* Label y-axis as 'tip'

### A2 - Do a boxplot of the following data (★☆☆)

`a = [22, 25, 30, 35, 40, 42, 45, 50, 55, 60, 65, 70]`

### A3 - Do a lineplot of following data (★☆☆)

```text
month  revenue
Jan    10
Feb    12
Mar     7
Apr    15
May    17
```

#### A4 - Do a barplot of above data (★☆☆)

#### A5 - Do a pie chart of following data (★☆☆)

```text
Gender  percentage
M        52
F        40
Unknown   8
```

####  A6 - Plot a histogram of data (★☆☆)


### Exercises 

#### EX-1: Visualize Housing Dataset

- Data: [house-sales.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-simplified.csv)
- Visualize the following
  - Number of sales per bedrooms (bar plot or Pie)
  - Average house price per bedrooms (box plot)
  - Relationship between 'SQFT' vs 'Sale Price' (Scatter plot)
  - Any other interesting plots you can come up with

#### EX-2 - Visualize pokemon data (★★☆)

Download [pokemon data](https://s3.amazonaws.com/elephantscale-public/data/pokemon/pokemon-small.csv)

Read it like this:

```python
pokemon = pd.read_csv('https://s3.amazonaws.com/elephantscale-public/data/pokemon/pokemon-small.csv', index_col=0)

with pd.option_context("display.width", 150):
    print (pokemon)
```

Data looks like this:

```text
           Name   Type 1  Type 2  Total   HP  Attack  Defense  Sp. Atk  Sp. Def  Speed  Stage  Legendary
#                                                                                                       
1     Bulbasaur    Grass  Poison    318   45      49       49       65       65     45      1      False
2       Ivysaur    Grass  Poison    405   60      62       63       80       80     60      2      False
3      Venusaur    Grass  Poison    525   80      82       83      100      100     80      3      False
4    Charmander     Fire     NaN    309   39      52       43       60       50     65      1      False
5    Charmeleon     Fire     NaN    405   58      64       58       80       65     80      2      False
..          ...      ...     ...    ...  ...     ...      ...      ...      ...    ...    ...        ...
147     Dratini   Dragon     NaN    300   41      64       45       50       50     50      1      False
148   Dragonair   Dragon     NaN    420   61      84       65       70       70     70      2      False
149   Dragonite   Dragon  Flying    600   91     134       95      100      100     80      3      False
150      Mewtwo  Psychic     NaN    680  106     110       90      154       90    130      1       True
151         Mew  Psychic     NaN    600  100     100      100      100      100    100      1      False
```

Try the following graphs:

**EX-1A - Do a graph to illustrate how many type-1 Pokemons**  
Hint: histogram

**EX-1B - Illustrate `Attack` points per `Type-1` in a boxplot**  
Hint: You may need to find the average attack points per type first

**Ex-1C - Come up with a graph to explain this data.  Experiment**



### More Exercices


---

## [Index](../README.md)/ [Python Data Analysis](0-README.md)
