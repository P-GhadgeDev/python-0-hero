## NumPy & Notebooks – Simplified Notes

1. What is NumPy?
   1. NumPy (Numerical Python) is a powerful library used for:
      1. Mathematical operations
      2. Working with arrays
      3. Scientific computing

2. Why NumPy is Fast?
   1. Written in C language
   2. Compiled → runs much faster than normal Python
   3. Can be up to 50x faster than Python lists

3. Origin of NumPy
   1. Year Library Creator
   2. 1995 Numeric Jim Hugunin
   3. 2000 Numarray Space Telescope Science Institute
   4. 2005 NumPy Travis Oliphant

4. NumPy was created by merging Numeric + Numarray

## Notebooks

1. What is a Notebook?
   1. A Notebook (.ipynb file) allows you to:
      1. Write code 🧑‍💻
      2. Run code ▶️ 
      3. See output 📊
      4. Add notes, equations, images, charts 📝
   2. Everything in one place!

3. Popular Notebook
   1. Jupyter Notebook
      1. One of the most widely used tools
      2. Can be installed using Anaconda
   2. Also works in:
      1. VS Code
      2. Google Colab

4. Useful Notebook Commands
   1. Shortcut	    Function
   2. Shift + Enter	Run cell
   3. Shift + Tab	Show documentation

## Google Colab
   
1. Online notebook by Google
2. No installation required
3. Runs in browser
4. Supports GPU/TPU

## Modules & Packages
  
1. What is a Module?
   1. A single Python file containing code
2. What is a Package?
   1. A collection of modules

## Popular Packages
   
1. NumPy
2. Pandas
3. Matplotlib
4. Seaborn
5. Scikit-learn
6. TensorFlow

## NumPy Arrays vs Python Lists

1. Python List 
   1. Mixed data types allowed
   2. Slower performance
   3. Low memory efficiency
   4. Requires loops for operations
      1. `[1, "hello", 3.5]`

2. NumPy Array
   1. Only same data type
   2. Much faster (C-level speed)
   3. High memory efficiency
   4. Supports vectorized operations 
      1. `import numpy as np`
      2. `np.array([1, 2, 3])`

3. Key Differences
   1. Feature	Python List	NumPy Array
   2. Data Type	Mixed	Same only
   3. Speed	Slow	Very fast
   4. Memory	Less efficient	More efficient
   5. Operations	Manual loops	Vectorized

## NumPy Topics Index

1. NumPy Arrays
   1. Creation of arrays
   2. Basic structure
2. NumPy Indexing
   1. Access elements
   2. Slicing arrays
3. NumPy Operations
   1. Mathematical operations
   2. Vector operations

## Array Operations

1. Arithmetic operations
   1. Broadcasting
   2. Deep and Shallow copy
   3. Matrix operations
2. Advance Array Manipulation
   1. Stacking Array
   2. Splitting Array

## Summary

1. NumPy is a fast numerical library written in C
2. Arrays are its core feature
3. Notebooks (like Jupyter/Colab) help in interactive coding
4. NumPy is faster, efficient, and powerful compared to Python lists