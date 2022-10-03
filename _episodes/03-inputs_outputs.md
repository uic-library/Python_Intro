---
title: "Inputs and Outputs"
teaching: 0
exercises: 0
questions:
- "What, Why and Who"
---


## Collect user input

The 'input' method provides an easy way to coolect user input.
~~~

name= input('What is your name?')
~~~
{: .language-python}

In python, all imputs are stored as strings. You can change the data type using type casting

~~~

number = input("Enter a number")
number= int(number)
~~~
{: .language-python}


## Output in Python
You can display output using python

~~~
print("Hello!")
name = "Digital Scholarship Hub"

print(f'Hello {name}! How are you?')
~~~
{: .language-python}

## Using % Operator
We can use ‘%’ operator. % values are replaced with zero or more value of elements.
- %d – integer
- %f – float
- %s – string
- %x – hexadecimal
- %o – octal

~~~
num = int(input("Enter a value: "))

print("The number is %d" %num)
~~~
{: .language-python}

## Comments in Python:
Comments are texts starting with '#' that are sprinked in the code. Python ignores these sentences while compilation. Comments are a great tool to - 
- Improve readibilty
- Explain code 
- Testing code

~~~
r = int(input())
v= (4/3)*(3.14)*(r**3)
print(v)

r = int(input()) #reading input, i.e radius
v= (4/3)*(3.14)*(r**3) #calculate volume
print(v) #print volume
~~~
{: .language-python}


### Multiline comments
To comments multiple lines, we can insert a # at the beginning of every line
~~~
# this is
# to demonstrate
# multiline comments in python
i=0
print(i)
~~~
{: .language-python}

Or, we can use a multiline string. We is triple quotes(''' ....... ''') for multiline string comments
~~~
'''
the following loop prints 
the value of the variable i, 
as long as it is less that 5
'''
i=0
while i<6:
 print(i)
 i=i+1
~~~
{: .language-python}

