# K-Means

[Back to Index](../README.md)

---

## Objective

Learn clustering with k-means

## Prerequisite Reading

* Brush up  on [Unsupervised learning](../machine-learning/unsupervised.md)

## Essentials Reading

* [A good intro to kmeans](https://towardsdatascience.com/k-means-a-complete-introduction-1702af9cd8c)
* [A Friendly Introduction to K-Means clustering algorithm](https://medium.com/@tarlanahad/a-friendly-introduction-to-k-means-clustering-algorithm-b31ff7df7ef1)
* [Visualizing kmeans](https://stanford.edu/class/engr108/visualizations/kmeans/kmeans.html)
* [visualizing Kmeans](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)
* [Kmeans intro video](https://www.youtube.com/watch?v=QXOkPvFM6NU) - a nice video (17 mins) by [Luis Serrano](https://serrano.academy/)

## Extra Reading

* Section 10.3 "Clustering", pp 385 in [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)

---

### Implementing K-Means in Scikit-Learn

* [Kmeans in SKLearn tutorial 1](https://towardsdatascience.com/k-means-clustering-with-scikit-learn-6b47a369a83c)
* [kmeans tutorial 2](https://jakevdp.github.io/PythonDataScienceHandbook/05.11-k-means.html)
* [Kmeans tutorial 3](https://www.machinecurve.com/index.php/2020/04/16/how-to-perform-k-means-clustering-with-python-in-scikit/)

## Knowledge Check

* What are the strengths and weaknesses of KMeans?
* Can KMeans predict optimal value for K?
* How will we find optimal K value?
* How will outliers impact Kmeans

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### EX-1: Clustering with synthetic data  (★☆☆)

Use Scikit's  [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html#sklearn.datasets.make_blobs) to generate some data

Cluster it using Kmeans

Start with this notebook: [kmeans-1-intro](https://github.com/elephantscale/guided-machine-learning-labs/blob/master/clustering/kmeans-1-intro.ipynb)

### EX-2: Clustering cars dataset  (★★☆)

We are going cluster cars dataset.

Here is the [cars data set](https://s3.amazonaws.com/elephantscale-public/data/cars/mtcars.csv)

Data looks likes this:

```text
            model   mpg  cyl   disp   hp  drat     wt   qsec  vs  am  gear  
   Ford Pantera L  15.8    8  351.0  264  4.22  3.170  14.50   0   1     5   
        Merc 280C  17.8    6  167.6  123  3.92  3.440  18.90   1   0     4   
       Volvo 142E  21.4    4  121.0  109  4.11  2.780  18.60   1   1     4   
         Merc 230  22.8    4  140.8   95  3.92  3.150  22.90   1   0     4   
```

Only use `mpg` and `cyl` columns and cluster the cars.

You can start with this notebook: [kmeans-2-mtcars](https://github.com/elephantscale/guided-machine-learning-labs/blob/master/clustering/kmeans-2-mtcars.ipynb)

### EX-3: Clustering Uber Trips  (★★☆)

This is a fun lab.  We will cluster Uber pick up locations and figure out where the demand hot-spot is.

Here is [uber dataset](https://elephantscale-public.s3.amazonaws.com/data/uber-nyc/uber-sample-10k.csv)

You can start with this notebook:  [kmeans-3-uber-pickups](https://github.com/elephantscale/guided-machine-learning-labs/blob/master/clustering/kmeans-3-uber-pickups.ipynb)

## More Exercises

---

## [Index](../README.md)
