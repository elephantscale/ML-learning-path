<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)

---

# Numpy

## Objective

Learn Numpy

## Reference

### Essentials (★☆☆)

- [Numpy chapter](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html) is an excellent introduction to Numpy 
  - [Data types](https://jakevdp.github.io/PythonDataScienceHandbook/02.01-understanding-data-types.html)
  - [Basics of numpy arrays](https://jakevdp.github.io/PythonDataScienceHandbook/02.02-the-basics-of-numpy-arrays.html)
- Array slicing
  - https://www.w3schools.com/python/numpy_array_slicing.asp - basics
  - https://www.pythoninformer.com/python-libraries/numpy/index-and-slice/ - good graphics

### Intermediate (★★☆)

- [Numpy axis](https://www.sharpsightlabs.com/blog/numpy-axes-explained/) - Read this and understand how axis work
- From [Ch 2  - Numpy](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html) 
  - [Functions](https://jakevdp.github.io/PythonDataScienceHandbook/02.03-computation-on-arrays-ufuncs.html)
  - [Aggregations](https://jakevdp.github.io/PythonDataScienceHandbook/02.04-computation-on-arrays-aggregates.html)
  - [Masking](https://jakevdp.github.io/PythonDataScienceHandbook/02.06-boolean-arrays-and-masks.html)
  - [Fancy indexing](https://jakevdp.github.io/PythonDataScienceHandbook/02.07-fancy-indexing.html)
  - [Sorting](https://jakevdp.github.io/PythonDataScienceHandbook/02.08-sorting.html)


## Checklist

After completing the exercises below, you should be comfortable with

- Using Numpy

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus

### Basics - Creating and modifying arrays

**A1 - Import numpy packge and print out the version (★☆☆)**

**A2 - Create a Numpy array with these elements [1,3,5,7] (★☆☆)**  
Hint : `np.array`

**A3 - Add an element 9 to the above  array to the end (★☆☆)**  
Expected output : [1,3,5,7,9]

**A4 - Add an element 0 to the above  array at the beginning (★☆☆)**  
Expected output : [0,1,3,5,7,9]

**A5 - Create a numpy array of 5 elements.  What are the contents of the array (★☆☆)**  
Hint: `np.empty`

**A6 - Create a numpy array of 5 elements, initialize them to zero (★☆☆)**  
Hint : `np.zero`  
Expected output: `[0,0,0,0,0]`

**A7 - Change the 3rd element of the above array to 100 (★☆☆)**  
Expected output: `[0,0,0,100,0]`

**A8 - Create a numpy array of numbers from 1 to 10 (★☆☆)**  
Hint: `np.arange`  
Expected result: `[1,2,3,4,5,6,7,8,9,10]`

**A9 - Create a random number between and 1 and 100 (★☆☆)**  
Hint: `np.random`

### Indexing

**B1 - Create a numpy array of numbers from 1 to 10.  Print the first and last element (★☆☆)**  
Hint: `np.arange` , `[:0]` and `[:-1]`

**B2 - Create a numpy array of numbers from 1 to 10.  Print out elements after index 2 (★☆☆)**  
Hint: `np.arange`  and `[2:]`  
Expected result: `[3,4,5,6,7,8,9,10]`

**B3 - Create a numpy array of numbers from 1 to 10.  Print out elements from index 2 to 8 (★☆☆)**  
Hint: `np.arange`  and `[?:?]`  
Expected result: `[3,4,5,6,7]`

### Searching

**C1 - Create an array of 10 length with random numbers between 0 to 100.  Print out the maximum and minimum element  (★★☆)**  
Hint: `np.random.?`, `np.max` and `np.min`

**C2 - Create an array of 10 length with random numbers between 0 to 100.  Print out the index of the maximum element (★★☆)**  
Hint: `np.argmax`  

For example, if the array is  
[10, 12, 7,  33, 88, 42, 40, 25, 8, 50]  
the max-index is : 4  (88)

**C3 - Create an array as follows `[4,-2, 0, 1, 3, -5]`.  Only print numbers greater than zero (★★☆)**  
Expected output: `[4,3]`

### Matrix

**D1 - Create an array of numbers 1 to 12.  Shape the above array into a  4x3 matrix (★★☆)**  

```output
Expected output 
[[1,2,3]
 [4,5,6]
 [7,8,9]
 [10,11,12]]
```
Hint: `np.arange` and `np.reshape`

**D2 - Create a multi-dimensional 3x3x3 array with random numbers between 1 and 10.  Print out the sum of all elemenets (★★☆)**  
Hint: `np.sum`

**D3 - Create a 4x3 matrix.  Initialize it with random numbers between 1 and 10.  Print out the sum of numbers per each column and each row (★★☆)**  
Hint: `np.sum`

**D4 - Create two 3x2 matrices.  Join them row wise to create a 6x2 matrix (★★☆)**  
Hint: `np.concatenate`

**D5 - Create two 3x2 matrices.  Join them column wise to create a 3x4 matrix (★★☆)**  
Hint: `np.concatenate`

**D6 - Create a 4x3 matrix.  Splice the matrix into four 1x3 matrices column wise (★★☆)**

### More Exercices

* https://www.w3resource.com/python-exercises/numpy/basic/index.php - This site has tons of great exercises
* [100 Numpy exercises](https://github.com/rougier/numpy-100)

---

## [Contents](../contents.md) / [Python Data Analysis](0-README.md)