<link rel='stylesheet' href='../assets/css/main.css'/>

## [Contents](../contents.md) / [Python](0-README.md)

---

# Numpy

## Objective

Learn Numpy

## Reference

### Essentials

- Read [Ch 2  - Numpy](https://jakevdp.github.io/PythonDataScienceHandbook/02.00-introduction-to-numpy.html) from the excellent open source book [Python Data Science Book](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)

## Exercises

### Easy (A)

**A1 - Import numpy packge and print out the version**

**A2 - Create a Numpy array with these elements [1,3,5,7]**  
Hint : `np.array`

**A3 - Add an element 9 to the above  array to the end**  
Expected output : [1,3,5,7,9]

**A4 - Add an element 0 to the above  array at the beginning**  
Expected output : [0,1,3,5,7,9]

**A5 - Create a numpy array of 10 elements.  What are the contents of the array**

**A6 - Create a numpy array of 10 elements, initialize them to zero**  
Hint : `np.zero`

**A7 - Create a numpy array of numbers from 1 to 10.  Print the first element**  

**A8 - Create a numpy array of numbers from 1 to 10.  Print the last element**  
Hint: `np.arange`  and `[:-1]`

**A9 - Create a numpy array of numbers from 1 to 10.  Print out elements after index 2**  
Hint: `np.arange`  and `[2:]`

**A10 - Create a numpy array of numbers from 1 to 10.  Print out elements from index 2 to 8**  
Hint: `np.arange`  and `[2:8]`


**A11 - Create a numpy array of numbers from 1 to 12**  
Hint : `np.arange`

**A12 - Shape the above array into a  4x3 matrix**  

```text
Expected output 
[[1,2,3]
 [4,5,6]
 [7,8,9]
 [10,11,12]]
```
Hint: `np.reshape`

**A9 - Create a random number between and 1 and 20**  
Hint: `np.random`

**A10 - Create an array of 10 length with random numbers between 0 to 100.  Print out the maximum and minimum element**  
Hint: `np.max` and `np.min`

**A10 - Create an array of 10 length with random numbers between 0 to 100.  Print out the index of the maximum element**  
For example, if the array is  
[10, 12, 7,  33, 88, 42, 40, 25, 8, 50]  
the max-index is : 4  (88)

Hint: `np.argmax`

### Medium (B)

**B1 - Create a multi-dimensional 3x3x3 array with random numbers between 1 and 10.  Print out the sum of all elemenets**  
Hint: `np.sum`

**B2 - Create a 4x3 matrix.  Initialize it with random numbers between 1 and 10.  Print out the sum of numbers per each column and each row**  
Hint: `np.sum`

**B3 - Create two 3x2 matrices.  Join them row wise to create a 6x2 matrix**  
Hint: `np.concatenate`

**B4 - Create two 3x2 matrices.  Join them column wise to create a 3x4 matrix**  
Hint: `np.concatenate`

**B5 - Create a 4x3 matrix.  Splice the matrix into four 1x3 matrices column wise**

### More Exercices

* https://www.w3resource.com/python-exercises/numpy/basic/index.php - This site has tons of great exercises
* [100 Numpy exercises](https://github.com/rougier/numpy-100)


## Checklist

At this point, you should be comfortable with

- Using Numpy

---

## [Contents](../contents.md) / [Python](0-README.md)
