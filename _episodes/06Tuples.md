---
title: "Tuples"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---



Tuple is also an ordered collection of Python objects. The only difference between tuple and list is that tuples are immutable i.e. tuples cannot be modified after it is created.
 

Creating Tuple
In Python, tuples are created by placing a sequence of values separated by ‘comma’ in (). Tuples can contain any number of elements and of any datatype.

Note: Tuples can also be created with a single element, but it is a bit tricky. Having one element in the parentheses is not sufficient, there must be a trailing ‘comma’ to make it a tuple.


Accessing elements of Tuple
In order to access the tuple items refer to the index number.The index must be an integer. Nested tuples are accessed using nested indexing.

~~~
#Tuples
#Unlike list tuples are enclosed in ()
#Cannot use store/stored functions for tuples because they are immutable

tup=('asdfgh', 16, 78.9, 'mnbvcxz')

print(tup)

print(tup[0])

print(tup[1:3])
~~~
