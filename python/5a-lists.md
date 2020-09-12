<link rel='stylesheet' href='../assets/css/main.css'/>

## [Index](../README.md)/ [Python](0-README.md)

---

# Python Data Structures - List

## Objective

Learn the **list** data structures in python

## Reference

### Essentials

* From [Byte of Python](https://python.swaroopch.com/) read the following chapters
  - [Data structures](https://python.swaroopch.com/data_structures.html) - read lists section
* From [Dive into Python3](https://diveintopython3.problemsolving.io), read the following chapters
  - [Native data types](https://diveintopython3.problemsolving.io/native-datatypes.html) - Read sections on Lists
* Understand list slicing
  - [slicing 1](https://towardsdatascience.com/the-basics-of-indexing-and-slicing-python-lists-2d12c90a94cf)

## Checklist

After completing the exercises below, you should be comfortable with

- Using lists


## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonu

### A - Creating Lists

**A1 - Create a list `a = [10,20,30,40,50]` (★☆☆)**  
We will use this list for exercises below

**A2  print out the size of the list (★☆☆)**  
Hint: `len`

**A3 - Append 60 to the end of list (★☆☆)**  
Expected output:  `(10,20,30,40,50,60)`

**A4 - insert 5 at the front of list (★☆☆)**  
Expected output: `(5,10,20,30,40,50,60)`

**A5 - insert 15 at position 2 (between 10,20) (★☆☆)**  
Expected output: `(5,10,15,20,30,40,50,60)`

**A6 - copy the list `a`  into another list `b` (★☆☆)**

**A7 - delete the last element from the copied list `b`  print both to make sure that original list `a` isn't affected (★☆☆)**  
Expected output:  
`a = [10,20,30,40,50]`  
`b = [10,20,30,40]`  

**A8 - Find the max/min elements in a list (★☆☆)**  
Hint: `min`  and `max`

**A9 - Sum up all the elements in list (★☆☆)**  
Hint: `sum`

### B - Accessing/Indexing Lists

Let's work with list `[10,20,30,40,50]`

**B1 - Print first element in list (★☆☆)**   
Hint : `[0]`  
Expected answer : `10`

**B2 - Print the last element of list (★☆☆)**  
Hint : `[-1]`  
Expected output: `50`

**B3 - Print elements at index 2-4 (★☆☆)**  
Expected output: `[30, 40, 50]`

**B4 - Print all elements starting with index 3 (★☆☆)**  
Hint : `[3:]`
Expected output: `[40, 50]`

**B5 - Print the last 3 elements of list (★☆☆)**  
Hint : `[-3:]`  
Expected output: `[30,40,50]`

**B6 - Iterate over the list and print one per line (★☆☆)**  
Hint : `for item in list`


### C - Sorting and Searching 

**C1 - Create a list of 10 random numbers between 0 and 100 (★★☆)**  
Hint: `random.randint`

**C2 - Sort the above list (★★☆)**  
Hint: `sort`

**C3 - Reverse sort the list (★★☆)**

**C4 - Create a list `x=[1,5,10,15,20]`.  Check if 10 is part of the list (★★☆)**  
Hint : `in`  
Expected answer : `True`

**C5 - Check to see if 25 is part of the list (★★☆)**  
Hint : `in`
Expected answer : `False`

**C6 - Create a list of 10 random numbers between 0 and 100.  Print all elements higher than 50 (★★☆)**  


###  Exercises

#### Ex-1 - Work with 2 lists (★★☆)

`a = [1,5,2,10,7,4,6]`  
`b = [1,4,3]`

**Print all numbers common to `a` and  `b` (★★☆)**

**Print all numbers unique to a (not in b) (★★☆)**

#### Ex-2 - Remove duplicates (★★☆)

`a = [3,2,1,5,2,1,6,5]`  
Remove duplicates from a

---

## [Index](../README.md)/ [Python](0-README.md)
