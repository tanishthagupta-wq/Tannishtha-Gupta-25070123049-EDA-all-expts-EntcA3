# STUDY OF NUMPY LIBRARY (Python)

Name- Tannishtha Gupta <br/>
Branch- EnTC A3 <br/>
PRN- 25070123049 <br/>

---

## Title Page

**Project Name:** Study of NumPy Library in Python <br/>
**Purpose:** Understanding NumPy Arrays and Operations <br/>
**Language:** Python <br/>

---

## Aim of the Study

The aim of this project is to study the **NumPy (Numerical Python) library** and understand how it is used for numerical computations.

This project focuses on:

* Creating NumPy arrays  
* Performing mathematical operations  
* Understanding array properties  
* Indexing and slicing  
* Performing statistical and matrix operations  

---

## Introduction

NumPy (Numerical Python) is one of the most powerful and widely used Python libraries for numerical and scientific computing.

It provides support for:

* Large multi-dimensional arrays  
* Mathematical functions  
* Linear algebra operations  
* Statistical operations  

NumPy is faster than Python lists because it is implemented in C and optimized for performance.

---

## Study of NumPy (Instructions)

* Import NumPy library  
* Create NumPy arrays  
* Study array attributes (shape, size, ndim, dtype)  
* Perform indexing and slicing  
* Apply mathematical operations  
* Perform statistical functions  
* Understand reshaping and transformation of arrays  
* Compare NumPy arrays with Python lists  

---

## Key Concepts Covered

* Importing NumPy  
* Creating arrays  
* Array dimensions  
* Array indexing  
* Array slicing  
* Array reshaping  
* Mathematical operations  
* Statistical operations  
* Broadcasting  
* Matrix operations  

---

# THEORY (NumPy Library)

---

#  Importing NumPy

NumPy is imported using the keyword `import`.

import numpy as np


Here, `np` is an alias (short name) used for convenience.

---

#  Creating NumPy Arrays

Arrays are created using `np.array()` function.



arr = np.array([1, 2, 3, 4])


NumPy arrays are different from Python lists because:

* They are faster
* They require less memory
* They support vectorized operations

---

#  Types of Arrays

## 1D Array



np.array([1, 2, 3])


## 2D Array



np.array([[1, 2], [3, 4]])


## 3D Array



np.array([[[1,2],[3,4]]])


---

#  Array Attributes

NumPy arrays have important attributes:

* `arr.ndim` → Number of dimensions  
* `arr.shape` → Shape of array (rows, columns)  
* `arr.size` → Total number of elements  
* `arr.dtype` → Data type of elements  

Example:



arr = np.array([[1,2,3],[4,5,6]])
print(arr.shape)


---

#  Special Array Creation Functions

## zeros()

Creates array filled with zeros.



np.zeros((2,3))


## ones()

Creates array filled with ones.



np.ones((2,3))


## arange()

Creates array with evenly spaced values.



np.arange(1, 10)


## linspace()

Creates array with specified number of evenly spaced values.



np.linspace(0, 10, 5)


---

#  Indexing and Slicing

Indexing is used to access specific elements.



arr[0]
arr[1,2]


Slicing is used to access a range of elements.



arr[0:2]
arr[:,1]


NumPy slicing works similar to Python lists but supports multi-dimensional slicing.

---

#  Mathematical Operations

NumPy supports element-wise operations.



arr + 5
arr * 2
arr1 + arr2


Operations include:

* Addition
* Subtraction
* Multiplication
* Division
* Power

These operations are faster compared to normal loops.

---

#  Statistical Functions

NumPy provides built-in statistical functions:

* `np.sum()` → Sum of elements  
* `np.mean()` → Average  
* `np.median()` → Median  
* `np.max()` → Maximum value  
* `np.min()` → Minimum value  
* `np.std()` → Standard deviation  

Example:



np.mean(arr)


---

#  Reshaping Arrays

Reshaping changes the structure of an array.



arr.reshape(2,3)


Important rule:
Total elements must remain the same.

---

# Matrix Operations

NumPy supports matrix multiplication.



np.dot(arr1, arr2)


Or



arr1 @ arr2


It also supports:

* Transpose (`arr.T`)
* Determinant
* Inverse (with linear algebra module)

---

# Broadcasting

Broadcasting allows NumPy to perform operations on arrays of different shapes.

Example:



arr + 10


Here, 10 is automatically added to every element.

---

# Advantages of NumPy

* Faster than Python lists  
* Efficient memory usage  
* Supports multi-dimensional arrays  
* Built-in mathematical functions  
* Used in Data Science and Machine Learning  

---

# Disadvantages of NumPy

* Requires installation  
* Less flexible compared to lists  
* Fixed data type (mostly homogeneous data)  

---

# Tools Used

* Python Interpreter  
* Jupyter Notebook (.ipynb)  
* VS Code / IDLE  
* NumPy Library  

---

# Applications of NumPy

* Data Science  
* Machine Learning  
* Artificial Intelligence  
* Scientific Computing  
* Financial Analysis  
* Signal Processing  
* Image Processing  

---

# Conclusion

NumPy is a powerful library for numerical computation in Python.

Through this study, we learned:

* How to create NumPy arrays  
* How to access and modify elements  
* How to perform mathematical and statistical operations  
* How to reshape arrays  
* How NumPy improves performance compared to Python lists  

Understanding NumPy is essential for advanced topics like **Pandas, Machine Learning, and Artificial Intelligence**.

---

