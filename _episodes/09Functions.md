---
title: "Functions"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

WHAT ARE FUNCTIONS?

Functions are a set of instructions(code) bundled together to achieve a specific outcome.

WHY DO WE NEED FUCNTIONS?
One of the main advantages of functions is that it encourages code reusability. Instead of writing the lines of code at multiple places, we can write it as a fucntion and call it when needed.

HOW TO USE FUNCTIONS IN PYTHON?

In Python a function is defined using the def keyword:

~~~
def my_function():
  print("Hello from a function")
~~~

HOW TO CALL FUCNTIONS?

To call a function, use the function name followed by parenthesis:

~~~
def my_function():
  print("Hello from a function")

my_function()
~~~

WHAT ARE ARGUMENTS?

We can pass data to our functions, so that it can use it for computations.You specify the value of an argument when you call the function.

~~~
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")
~~~

---
LAMBDAS

A lambda function has no name when defining it, and it is contained in one line of code. We used the keyword LAMBDA to declare it.

~~~
x = lambda a : a + 10
print(x(5))
~~~
