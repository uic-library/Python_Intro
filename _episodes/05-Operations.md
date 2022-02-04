---
title: "Operations"
teaching: 0
exercises: 0
questions:
- "What Operators?"
- "What are the different types of Operators in python?"
objectives:
- "Learn about basic operations in python"
---

## Operations in python

Operators are used to perform modifications on variables. We have different types of operations in python 
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
{: .language-python}

### Assignment Operators
Assignment operators are used to assign values to variables.
~~~
x = 6	
x += 2	#similar to x = x + 2	
x -= 2		#similar to x = x - 2	
x *= 2		#similar to x = x * 2	
x /= 2		#similar to x = x / 2	
x %= 2		#similar to x = x % 2	
x //= 2	#similar to x = x // 2	
x **= 2	  #similar to x = x ** 2	
x &= 2	  #similar to x = x & 2	
x |= 2	  #similar to x = x | 2	
x ^= 2	  #similar to x = x ^ 2	
x >>= 2	  #similar to x = x >> 2	
x <<= 2	  #similar to x = x << 2
~~~
{: .language-python}

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
{: .language-python}

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
{: .language-python}

### Identity Operators

Identity operators are used to check if the objects are same based on the memeory allocation-

~~~
x=[1,2,3]
y=[1,2,3]
z=y
print(z is y) # returns True as z is the same object as y
print(z is x) # returns False as z is not the same object as x
print(z is not x) # returns True as z is not the same object as x
~~~
{: .language-python}

### Membership Operators

Membership operators are used to check if a sequence is present in an object

~~~
x=["Digital","Scholoarship","Hub"]
print("Hub" in x)# prints True, as "Hub" is in list x
print(2 not in x)# prints True, as 2 is not in list x
~~~
{: .language-python}

### Bitwise Operators

Bitwise operators are used to compare Binary numbers

~~~
a = 5
b = 6
 
print( a & b) # Print bitwise AND operation
print( a | b) # Print bitwise OR operation
print( ~a) # Print bitwise NOT operation
print( a ^ b) # print bitwise XOR operation


a = 1
print( a >> 1) # print bitwise right shift operator
print(a << 1) # print bitwise left shift operator
~~~
{: .language-python}
