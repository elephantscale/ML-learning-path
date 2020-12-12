# Python Data Structures - Dictionaries

[Index](../README.md)/ [Python](0-README.md)

---

## Objective

Learn the **dictionary** data structures in python


## Reference

### Essentials

* From [Byte of Python](https://python.swaroopch.com/) read the following chapters
  - [Data structures](https://python.swaroopch.com/data_structures.html) read dictionary section
* From [Dive into Python3](https://diveintopython3.problemsolving.io), read the following chapters
  - [Native data types](https://diveintopython3.problemsolving.io/native-datatypes.html) - read dictionary section

## Checklist

After completing the exercises below, you should be comfortable with

- Using dictionaries

## Exercises

### Difficulty Level

★☆☆  - Easy  
★★☆  - Medium  
★★★  - Challenging  
★★★★ - Bonus


### A - Dictionary Basics

#### A1 - Create a dictionary  with following contents (★☆☆)

```text
    a -> 2,
    c -> 5,
    b -> 1,
    d -> 3
```

#### A2 - given a key, get a value (★☆☆)

what is the value for key 'a'?  
what is the value for key 'x' ?

#### A3 - add a Key-value to map (★☆☆)

Add `e -> 4` to the above map

#### A4 - Check if given key is in a map? (★☆☆)

key : 'a'  
key : 'x'

#### A5 - Loop through a map and print all key value pairs (★☆☆)


#### A6 - create a dict that returns a default value for non existing keys (★☆☆)

For example the dict has following KV

```text
    a -> 2,
    c -> 5,
    b -> 1,
    d -> 3
```

existing key : `d['a'] --> 2`  
non existing key returns zero : `d['x'] --> 0`


### B - Medium

#### B1 - de-dupe (★★☆)

* Create a list of 50 random numbers between 1 and 100 (including).  
* print only unique numbers from the list, eliminating duplicates

#### B2 : Get the frequency of the elements in a list (★★☆)

For example if the list is  
`['a', 'b', 'a', 'c', 'b', 'a']`
Expected output is :
```
  'a' -> 3,
  'b' -> 2,
  'c' -> 1
```

#### B3 : Sort dictionary  by values (★★☆)

For example, if the dictionary is 
```
  a -> 4
  b -> 5
  c -> 2
```

The expected output is :

```
  c -> 2 
  a -> 4
  b -> 5
```

### More Exercises

- <https://www.w3resource.com/python-exercises/dictionary/>
