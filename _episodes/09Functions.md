---
title: "Functions"
teaching: 0
exercises: 0
questions:
- "What are functions?"
- "Why do we need functions?"
- "How to use functions?"
- "What are Lambdas?"
objectives:
- "To understand how to use functions in python."
---

## What are Functions?
Functions are a set of instructions(code) bundled together to achieve a specific outcome.

## Why do we need Functions?
One of the main advantages of functions is that it encourages code reusability. Instead of writing the lines of code at multiple places, we can write it as a fucntion and call it when needed.

## How to use functions in python?
In Python a function is defined using the def keyword:

~~~
def my_function():
  print("Hello from a function")
~~~
{: .language-python}

## How to call functions in python?
To call a function, use the function name followed by parenthesis:

~~~
def my_function():
  print("Hello from a function")

my_function()
~~~
{: .language-python}

## What are arguments?
We can pass data to our functions, so that it can use it for computations.This data being passed is called an argument. You specify the value of an argument when you call the function.

~~~
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")
~~~
{: .language-python}

---
## LAMBDAS
A lambda function has no name when defining it, and it is contained in one line of code. We used the keyword LAMBDA to declare it.

~~~
x = lambda a : a + 10
print(x(5))
~~~
{: .language-python}
