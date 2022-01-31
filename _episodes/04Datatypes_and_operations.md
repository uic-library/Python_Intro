---
title: "Datatypes and operations"
teaching: 0
exercises: 0
questions:
- "What is a data type?"
- "What are the different tyes of data types?"
objectives:
- "Learn about data types in python"
- "Learn about basic operations in python"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## What is a data type?
Data type is an attribute associated with a piece of data that tells a computer system how to interpret its value. Understanding data types ensures that data is collected in the preferred format and the value of each property is as expected.

Python has the following data types built-in by default, in these categories:


Numeric Types:	int, float, complex


Sequence Types:	list, tuple, Strings


Mapping Type:	dict


Set Types:	set


Boolean Type:	bool




### Numeric type:


There are 3 numeric types-


INT: These are variables that hold integer values(...-3,-2,-1,0,1,2,3...)


FLOAT: This data type is used to represent real number with floating point representation. It is specified by a decimal point. 


COMPLEX: An complex number is represented by “ x + yi “. Python converts the real numbers x and y into complex using the function complex(x,y). The real part can be accessed using the function real() and imaginary part can be represented by imag().




### Sequence type:
In Python, sequence is an ordered collection of various object. These objects could be of similar or different data types. 


Lists:
List is an ordered collection of data. It is declared using "[]"


Tuples:
Tuples are immutable lists i.e. tuples cannot be modified after it is created. It is declared using "()"


Strings:
Strings are arrays of bytes representing Unicode characters. A string is a collection of one or more characters put in a single quote, double-quote or triple quote.



### Mapping type:


Maps are a data type composed of a collection of (key, value) pairs, such that each possible key appears at most once in the collection. In python, we use dictionary data type as a map. 

Dictionary holds key:value pair. Each key-value pair in a Dictionary is separated by a colon :, whereas each key is separated by a ‘comma’.A Dictionary can be created by placing a sequence of elements within curly {} braces.Dictionary can also be created by the built-in function dict().


> NOTE: Keys cannot be repeated in dictionary.





### Set type:


In Python, Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements.Sets can be created by using the built-in set() function with an iterable object or a sequence by placing the sequence inside curly braces, separated by ‘comma’. Type of elements in a set need not be the same.

### BOOLEAN TYPE:


Boolean is Data type with one of the two built-in values, True or False.
> Note – True and False with capital ‘T’ and ‘F’ are the only valid booleans.












## GET THE DATA TYPE OF THE VARIABLE:
We can use the type() function to understand the data type of the variable
~~~
x="Digital Scholorship Hub"
type(x)
~~~
TYPE CASTING
Type casting is a technique used to convert the data type of the value. In python you can use the following functions to convert the data types:
~~~
a=str(13456)
b=int("1234")
c=float(55)
~~~


## Operations in python

Operators are used to perform modifications on variables. Wr have different types of operations in python 
- Arithmetic operators
- Assignment operators
- Comparison operators
- Logical operators
- Identity operators
- Membership operators
- Bitwise operators

### Arithmetic Operators

These operators are used to perform basic mathematic operations on variables of numeric type.

~~~
x=3
y=4

print(x+y) # print the sum of x and y
print(x-y) # subtraction
print(x*y) # multiplication
print(x/y) #simple division
print(x**y) # print exponential product(x to the power of y)
print(x//y) # floor division
print(x%y) #modulus
~~~

### Assignment Operators
Assignment operators are used to assign values to variables.
~~~
x = 6	
print(x += 2)	#similar to x = x + 2	
print(x -= 2)		#similar to x = x - 2	
print(x *= 2)		#similar to x = x * 2	
print(x /= 2)		#similar to x = x / 2	
print(x %= 2)		#similar to x = x % 2	
print(x //= 2)	#similar to x = x // 2	
print(x **= 2)	  #similar to x = x ** 2	
print(x &= 2)	  #similar to x = x & 2	
print(x |= 2)	  #similar to x = x | 2	
print(x ^= 2)	  #similar to x = x ^ 2	
print(x >>= 2)	  #similar to x = x >> 2	
print(x <<= 2)	  #similar to x = x << 2
~~~

### Comparision Operators
Comparision operators are used to compare two values.

~~~
x=5
y=5
print(x == y)	# checks if x is equal to y
print(x != y) # checks if x is not equal to y	
print(x > y) # checks if x is greayer than y	
print(x < y) # checks if x is less than y	
print(x >= y) # checks if x is greater that or equal to y
print(x <= y) # checks if x is less than or equal to y.
~~~

> Note: In all of the above cases, the result is of boolean type(True or False)


### Logical Operators
Logical operators are used to perform operations on conditional statements.

~~~
x=5
y=10
print(x==5 and y==10) # performs AND operation on the results of the comparision operators(True and True)
print(x==5 or y!=10) # performs OR operation on the results of the comparision operators(True or False)
print(not(x==5)) # reverses the result of the comparision operation.

~~~

