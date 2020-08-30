<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)

---
# STATS-1: Basic Statistics

## Generic

* Really good collection of video lecture series by [Brandon Foltz](https://www.youtube.com/c/BrandonFoltz/featured)
* [Statistics and probability course](https://www.khanacademy.org/math/statistics-probability) from Khan Academy
* Highly recommend **Practical Statistics for Data Scientists, 2nd Edition** ([Oreilly link](https://www.oreilly.com/library/view/practical-statistics-for/9781492072935/),  [Amazon](https://www.amazon.com/_/dp/149207294X))



## Population vs. Sample

* [Population vs. Sample](https://mathbitsnotebook.com/Algebra1/StatisticsData/STPopSample.html)
* [Population vs. Sample video from Khan academy](https://www.youtube.com/watch?v=hsPCte_PcVA)
* [Population vs. Sample video by Brandon Foltz](https://www.youtube.com/watch?v=8X2xfwBP4uo&list=PLIeGtxpvyG-KqNeLQVhw8yv9MI5dd0ky_)
* [Ch 2 : Data and Sampling Distributions](https://www.safaribooksonline.com/library/view/practical-statistics-for/9781491952955/ch02.html#Chapter_2) of the  book : **'Practical Statistics for Data Scientists'** ([Safari link](https://www.safaribooksonline.com/library/view/practical-statistics-for/9781491952955/),  [Amazon Link](https://www.amazon.com/_/dp/1491952962?tag=oreilly20-20))  

## Variable Types

* [Variable types](https://towardsdatascience.com/data-types-in-statistics-347e152e8bee)
* [Data types - video](https://www.youtube.com/watch?v=hZxnzfnt5v8)

## Numerical Data Analysis

* [Mean/Median/Mode - video by Brandon Foltz](https://www.youtube.com/watch?v=HPrzOr8FCwA&list=PLIeGtxpvyG-K82r1fgL-DO1xKg133PXKh&index=5)
* [Standard deviation - video by Brandon Foltz](https://www.youtube.com/watch?v=JIIXQaMXBVM)
* [Trimmed Mean](https://www.investopedia.com/terms/t/trimmed_mean.asp)
* [Trimmed Mean - video](https://www.youtube.com/watch?v=G0qMS-o6r4M)

## Summarizing/Describing Data

* [Graphing categorical variables - video by Brandon Foltz](https://www.youtube.com/watch?v=vrWYw8d2830&t=2s)
* [Understanding histograms - video by Brandon Foltz](https://www.youtube.com/watch?v=zC3GaPBJ4c4&list=PLIeGtxpvyG-K82r1fgL-DO1xKg133PXKh&index=2)

## Covariance / Correlation

* [Covariance - video by Brandon Foltz](https://www.youtube.com/watch?v=xGbpuFNR1ME)
* [Correlation - video by Brandon Foltz](https://www.youtube.com/watch?v=4EXNedimDMs)
* [Covariance Matrix - video by Brandon Foltz](https://www.youtube.com/watch?v=locZabK4Als)


## Exploratory Data Analytics

* [Ch 1 : Exploratory Data Analysis](https://www.safaribooksonline.com/library/view/practical-statistics-for/9781491952955/ch01.html) of the  book : **'Practical Statistics for Data Scientists'** ([Safari link](https://www.safaribooksonline.com/library/view/practical-statistics-for/9781491952955/),  [Amazon Link](https://www.amazon.com/_/dp/1491952962?tag=oreilly20-20))  


## Check List

You should be familiar with the following
- Population vs. sample
- Variable types (quantitative, discrete, continuous)
- Plot basic graphs
- Do numerical analysis such as mean, median, variance, standard deviation
- Correlation

## Exercises

These are simple exercises designed to reinforce your learning so far.

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1 -  Mean / Median / STD (★☆☆)

We have some sample salary data (in thousands) from two cities.  

```
city1 = [15,12, 20, 25, 50, 35, 75, 80, 60, 45, 36]
city2 = [40,42, 45, 60, 55, 52, 56, 52, 62, 57, 48]
```

Calculate mean, median, variation, standard deviation for both city data.

### EX-2 - NBA Player Stats (★★☆)

* Read  [nba player stats data](https://s3.amazonaws.com/elephantscale-public/data/nba/nba-player-stats.csv)
* Extract `Salary` column
* Find min/max/mean/median of salary
* Is there a large variance in salary?  How will you find out?
* Find the 10% trimmed mean of salary
* Do some plots for salary  
Hint: boxplot and histograms

### EX-3 - Correlation of NBA Player Stats (★★☆)

* Read  [nba player stats data](https://s3.amazonaws.com/elephantscale-public/data/nba/nba-player-stats.csv)
* Extract `Height` and `Weight` columns
* You will notice the height is in feet-inches format.  For example 6-4.  You will need to convert this to single numeric format.
  - Create a new column called `height_cm`
  - Conversion formula is:   
  `cm  = feet * 30.48 + inches * 2.54`
* Is there a correlation between `height` and `weight` ?
* Create a plot to illustrate the relationship


### EX-4 - Correlation Matrix for House Sales Data (★★☆)
* Read [house-sales.csv](https://elephantscale-public.s3.amazonaws.com/data/house-prices/house-sales-simplified.csv)
* Create a correlation matrix for this data
* Analyze which attributes affect `Saleprice`

---

## [Contents](contents.md)
