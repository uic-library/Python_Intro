---
title: "Variables"
teaching: 0
exercises: 0
questions:
- "What are Variables?"
- "How to create a Variable?"
objectives:
- "To understand variables and the rules of naming variables"
---
## What are Variables?

In python, we have constants and variables. A constant does not change its value over time. A variable is a container that is used to store values. The values of the variable can change in accordance to the manipulation being done on it.

## How to create a Variable?

A variable is created the moment you assign a value to it.

~~~

name = "Recipe for pancakes"
no_of_ingredients = 5
print(no_of_ingredients)
print(name)
~~~
{: .language-python}

In python, we can also change the values assigned to the variables, without any restrictions.

~~~
no_of_ingredients = "Recipe for pancakes"    # x is now of type string
name = 5                       # name is now of type int
print(x)
print(name)
~~~
{: .language-python}

## Policy for naming Variables

Variables in python should follow the given rules
- Variable names should start with letter or underscore(_).
- Variable names can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variables are case sensitive(name, Name, NaMe are all different)

