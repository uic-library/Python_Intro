---
title: "Conditional Statements and Flow control"
teaching: 0
exercises: 0
questions:
- "What are conditional statements?"
- "What are control flow statements?"
objectives:
- "Understand Conditional Statements and Control Flow statements"
---
## Conditional Statements
Conditional statements provide us the ability to test a variable against a value and act in one way if the condition is met by the variable or another way if not.

### If Statement

The IF statement is a decision-making statement that guides a program to make decisions based on specified criteria. The IF statement executes one set of code if a specified condition is met (TRUE) or another set of code evaluates to FALSE.

~~~
lis1= ['good','better','best','bad','worse']

if 'good' in lis1:
  print('Everything is good')


if 'no' in lis1:
  print('Nothing')
print('Done')
~~~
{: .language-python}

---

### Elif Statement

The elif statement allows you to check multiple expressions for TRUE and execute a block of code as soon as one of the conditions evaluates to TRUE

~~~
name = 'xyz'


if name=='Jo':
  print('Hi Jo')
elif name=='Mark':
  print('Hi Mark')
elif name=='Frank':
  print('Hi Frank')
elif name=='Mike':
  print('Hi Mike')
else:
  print('No match found')
~~~
{: .language-python}

---
## Control Flow
Control Flow is the order in which instructions and function calls are implemented. Thw while and for loop provide us a way to manipulate control Flow

### While Loop

The while loop is used to execute a set of statements as long as a condition is true.

~~~
i = 1
while i < 6:
  print(i)
  i += 1
~~~
{: .language-python}

> ## We use the BREAK and CONTINUE statements to control the flow of the loop
> ### Break is used to exit the loop
> ~~~
> i = 1
> while i < 6:
>   print(i)
>   if i == 3:
>     break
>   i += 1
> ~~~
> {: .language-python}
> 
> ### Continue is used to stop the current iteration, and continue with the next
> 
> ~~~
> i = 0
> while i < 6:
>   i += 1
>   if i == 3:
>     continue
>   print(i)
>   ~~~
>   {: .language-python}
{: .callout}


---

### For Loop

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

~~~
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
~~~
{: .language-python}
> The for loop also has break and continue operators like the while loop

## Syntax in Python

### The print statement
The print statement is used to display messages on the screen. The print statement displays everything in string format. 
~~~
print("Introduction to Python")
s="Part"
n=1
print(s)
print(n)
print(2)
~~~
{: .language-python}

### Indentation
Unlike other programming languages that use brackets to indicate blocks of code, in python we use indentation.
~~~
for i in range(0,5):
  print(i**2)
  print(i)
  print('In for loop')
  print("block")
~~~
{: .language-python}

Python will raise an error if you skip indentation. The number of spaces for each block is up to the programmer. However, it should be atleast one space and the number of spaces should be consistent through out that bloack of code.
### Reading input from user:
Python allows us to collect input from user using the input() fuction.
~~~
name=input('Enter your name:')
print("Hello" + name)
~~~
{: .language-python}

### Comments in Python

In any programming language, we use comments to improve code readability and to help with documentation. Comments help us understand what a particular line of code does.

#### Single line comments
~~~
i=0
print(i) # Display the value of i
~~~

#### Multiline comments
To comments multiple lines, we can insert a # at the beginning of every line
~~~
# this is
# to demonstrate
# multiline comments in python
i=0
print(i)
~~~

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
