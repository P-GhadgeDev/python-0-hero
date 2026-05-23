## Introduction to Python Data Types

1. What are Data Types?
   1. Data types are the basic building blocks of Python programs.
   2. They define the kind of value a variable can hold.
   3. Understanding them helps you write better and more structured code.

2. Main Python Data Types
   1. Integers (int)
      1. Whole numbers (no decimal)
      2. `Examples`:
          1. ```py
               3
               300
               200
             ```

   2. Floating Point Numbers (float)
      1. Numbers with decimals
      2. `Examples`:
         1. ```py
            2.3
            4.6
            100.0
            ```

   3. Strings (str)
      1. Ordered sequence of characters
      2. `Examples`:
         1. ```py
            "hello"
            'Sammy'
            "2000"
            ```
   4. Lists (list)
      1. Ordered collection of different data types
      2. Mutable (can be changed)
      3. `Example`:
         1. ```py 
            [10, "hello", 200.3]
            ```
   5. Dictionaries (dict)
      1. Key-value pairs (unordered)
      2. `Example`:
         1. ```py
            {"myKey": "value", "name": "Frankie"}
            ```

   6. Tuples (tuple)
      1. Ordered but immutable (cannot change)
      2. `Example`:
         1. ```py
            (10, "hello", 200.3)
            ```

   7. Sets (set)
      1. Unordered collection of unique items
      2. `Example`:
         1. ```py
            {"a", "b"}
            ```
   8. Booleans (bool) 
      1. Logical values
      2. `Only two`:
         1. True
         2. False

## Numbers in Python

1. `Types`:
   1. Integers → Whole numbers
   2. Floats → Decimal numbers
2. Simple Arithmetic Examples
   1. 50 + 50        
      1. # 100
   2. 110 - 10       
      1. # 100
   3. 10 * 10        
      1. # 100
   4. 200 / 2        
      1. # 100

## Important Questions

1. Expression that equals 100:
   1. (20 + 30) * 2

2. Output of:
   1. 1 / 2
      1. 0.5 (Python 3 always returns float)

3. Floating Point Example:
   1. 36.0

4. Why 0.1 + 0.2 - 0.3 ≠ 0.0?
   1. Due to floating-point precision errors
   2. Computers store decimals in binary → small rounding errors occur

5. Integer vs Float
   1. Integer
      1. Whole number
      2. Example: 5
   2. Float
      1. Float
      2. Decimal number
      3. Example: 5.0

## Variables & Assignment
1. What is a Variable?
   1. A name used to store a value
      1. my_dogs = 2
         1. Rules for Variable Names
            1. ❌ Not Allowed:
               1. Cannot start with a number → 2dogs
               2. No spaces → use _ instead → my_dogs
         2. No special symbols:
            1. "", <>/?|\()!@#$%^&*~-+

## Best Practices:

1. Use lowercase (PEP8 style)
   1. my_variable = 10

2. Avoid reserved keywords like:
   1. list, str, int

3. Dynamic Typing in Python
   1. Python allows changing variable types:
      1. my_dogs = 2
      2. my_dogs = ["Sammy", "Frankie"]
         1. Pros:
            1. Flexible
            2. Faster coding 
         2. ❌ Cons:
            1. Can cause unexpected bugs

4. Static Typing Example (C++)
   1. int my_dog = 1;
   2. my_dog = "Sammy";  // Error

## Strings in Python

1. Creating Strings
   1. 'hello'
   2. "hello"
   3. "I don't do that"

2. Indexing
   1. Access individual characters:
      1. word = "hello"
      2. word[0]   # h
      3. word[1]   # e
      4. word[-1]  # o
   2. Index Table:
      1. Character	h	e	l	l	o
      2. Index	0	1	2	3	4
      3. Reverse	-5	-4	-3	-2	-1

3. Slicing
   1. Grab a part of a string:
      1. word = "hello"
      2. word[1:4]    # "ell"
      3. word[::2]    # "hlo"
      4. Syntax:
         1. [start : stop : step]
         2. start → where to begin
         3. stop → where to end (not included)
         4. step → jump size

4. Use what you know about the print() function to print out the phrase "Hello World" . Make sure your capitalization and spacing match.
   1. print("hello world!")

5. String Indexing and Slicing

## String Indexing

1. Write a string index that returns just the letter 'r'  from 'Hello World' .
2. For example, 'Hello World'[0]  returns 'H' 
3. You should only write one line of code for this. 
4. Do not assign a variable name to the string.
   1. 'Hello World'[8]

## String Slicing

1. Use string slicing to grab the word 'ink'  from inside 'tinker' 
2. For example, 'education'[3:6]  returns 'cat' 
3. Remember that when slicing you only go up to but not including the end index.
4. You should only write one line of code for this. Do not assign a variable name to the string.
   1. 'tinker'[1:4]

## String Properties and Methods

1. Immutability
2. String Concatination

## Are strings mutable?

1. Strings are mutable (meaning you can't use indexing to change individual elements of a string)

## How do I create comments in my code?

1. You can use the hashtag # to create comments in your code.

## If s = 'Sammy' what is the output of s[2:]?

## If s = 'hello' what is the output of s[1]?

## String Formatting for Printing

1. Offen you will want to "inject" a variable into your string for printing.
2. For example:
   1. my_name = "Jose"
   2. print("Hello " + my_name)
3. There are multiple ways to format strings for printing variables in them.
4. This is known as string interpolation.
5. Let's explore two methods for this:
   1. .format() method
   2. f-strings (formatted string literals)

## Print Formatting

1. Write an expression using any of the string formatting methods we have learned (except f-strings, see note below) to return the phrase 'Python rules!' 
2. `For example, these phrases both return 'I like apples' `:
   1. 'I like %s' %'apples'
   2. 'I like {}'.format('apples')
3. Your solution should be entered on one line. You can not use variable names, only the strings themselves.
4. `NOTE`: At this time, f-strings won't work! Udemy Coding Exercises use Python 3.5.2, and f-strings require Python 3.6 or higher.
   1. '{} {}'.format('Python','rules!')

## Lists

1. Lists are ordered sequences that can hold a variety of object types.
2. They use [] brackets and commas to separate objects in the list.
   1. [1,2,3,4,5]
3. Lists support indexing and slicing.
4. Lists can be nested and also have a variety of useful methods that can be called off of them.

## Lists

1. Create a list that contains at least one string, one integer and one float.
2. For example:
   1. [1, 'two', 3.14159] 
3. Note that the order and number of items doesn't matter. 
4. The answer should just be one list on a single line. 
5. Don't assign a variable name to the list.
   1. ['hello', 42, 3.14]
6. Objects retrieved by location.
7. Ordered sequence can be indexed or sliced.

## 1. How do I index a nested list? For example if I want to grab 2 from [1,1,[1,2]]?

1. You would just add another set of brackets for indexing the nested list, for example: my_list[2][1]. 
2. We'll discover later on more nested objects and you will be quizzed on them later!

## Dictionaries

1. Dictionaries are unordered mappings for storing objects.
2. Previously we saw how list store objects in an ordered sequence, dictionaries use a key-value pairing instead.
3. This key-value pair allows users to quickly grab objects without needing to know an index location.
4. Dictionaries use curly braces and colons to signify the keys and their associated values.
   1. {'key1':'value1','key2':'value2'}
5. So when to choose a list and when to choose a dictionary?
6. Objects retrieved by key name.
7. Unordered and can not be sorted.

## Formatting with .format() method

1. A good way to format objects into your strings for print statements is with the string .format() method. The syntax is:
   1. 'String here {} then also {}'.format('something1','something2')

## Summary

1. Python has multiple data types like int, float, str, list, dict, tuple, set, bool
2. Variables store values and follow naming rules
3. Python uses dynamic typing
4. Strings support indexing and slicing

## What is Python ?

1. Python is a high-level, interpreted general-purpose programming language known for it's readability and wide range of applications such as web development, automation, and data science.

## Why Python ?

1. I prefer Python because it allows rapid development with clean and readable code.
2. It's rich ecosystem supports everything from backend development using frameworks like Django and Flask to data science and automation.
3. This versatility, along with strong community support, makes it highly productive for building scalable applications.

## Decorators

1. What is a Decorator?
   1. A decorator in Python is a way to add extra functionality to an existing function without modifying its code.
   2. Think of it like wrapping a gift 🎁 — the gift (your function) stays the same, but you add extra layers (new behavior) around it.

2. The Problem Decorators Solve
   1. `Suppose you have a simple function`:
      1. ```py
          def simple_func():
            return "Doing simple work"
         ```
   2. `Now you want to add extra behavior, like`:
      1. logging
      2. timing
      3. authentication
      4. debugging
   3. `You have two basic options`:
      1. Modify the original function ❌ (not ideal)
      2. Create a new function that wraps the old one ❌ (gets messy)
   4. `But what if`:
      1. You want to reuse this extra behavior across many functions?
      2. You want to turn it on/off easily?
   5. `The Solution: Decorators ✅`
      1. Decorators let you attach extra functionality dynamically.
      2. ```py
           @some_decorator
           def simple_func():
            return "Doing simple work"
         ```py    
   6. `This is equivalent to`:
      1. ```py
         simple_func = some_decorator(simple_func)
         ```
   7. So the decorator takes the function, modifies/enhances it, and returns a new function.

3. How Decorators Work (Behind the Scenes)
   1. `Let’s build one step-by-step`:
       1. ```py
          def my_decorator(func):
            def wrap_func():
               print("Before function runs")
               func()
               print("After function runs")
               return wrap_func
         ```py
   2. `Now apply it`:
       1. ```py
          @my_decorator
          def simple_func():
            print("Doing simple work")
          ```
   3. `Calling`:
      1. ```py
         simple_func()
         ```
   4. `Output`:
      1. Before function runs
      2. Doing simple work
      3. After function runs 5. 

4. Why Use Decorators?
   1. `Decorators are powerful because they`:
      1. Promote code reuse
      2. Keep your code clean and modular
      3. Allow easy toggling of features
      4. Follow the DRY principle (Don’t Repeat Yourself) 
      5. Real-World Use Cases
   2. `Decorators are heavily used in frameworks like`:
      1. Authentication checks
      2. Logging
      3. Performance measurement
      4. API rate limiting
   3. `Example (timing)`:
      ```py
      import time
      def timer(func):
         def wrapper():
            start = time.time()
            func()
            end = time.time()
            print(f"Execution time: {end - start}")
            return wrapper 
      ```
   4. Key Takeaway
      1. `A decorator is simply`:
         1. A function that takes another function, adds extra behavior, and returns a new function.
