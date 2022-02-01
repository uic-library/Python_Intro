---
title: "Variables"
teaching: 0
exercises: 0
questions:
- "What are Variables?"
- "How to create a Variable?"
objectives:
- "To understand Variables and the rules of naming variables"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## What are Variables?

In python, we have constants and variables. A constant does not change its value over time. A variable is a container that is used to store values. The values of the variable can change in accordance to the manipulation being done on it.

## How to create a Variable?

A variable is created the moment you assign a value to it.

~~~
x = 5
name = "Python for Beginners"
print(x)
print(name)
~~~

In python variables need not be declared with a particular type. We can also change them as required

~~~
x= "Python for Beginners" # x is now of type string
name= 5 #name is now of type int
print(x)
print(name)
~~~


## Policiy for naming Variables

Variables in python should follow the given rules
- Variable names should start with letter or underscore(_).
- Variable names can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variables are case sensitive(name, Name, NaMe are all different)

