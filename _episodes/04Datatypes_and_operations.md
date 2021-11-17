---
title: "Datatypes_and_operations"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
Data type is an attribute associated with a piece of data that tells a computer system how to interpret its value. Understanding data types ensures that data is collected in the preferred format and the value of each property is as expected.

Python has the following data types built-in by default, in these categories:


Numeric Types:	int, float, complex
Sequence Types:	list, tuple, Strings
Mapping Type:	dict
Set Types:	set
Boolean Type:	bool

NUMERIC TYPES:
There are 3 numeric types-
INT: These are variables that hold integer values(...-3,-2,-1,0,1,2,3...)
FLOAT: This data type is used to represent real number with floating point representation. It is specified by a decimal point. 
COMPLEX: An complex number is represented by “ x + yi “. Python converts the real numbers x and y into complex using the function complex(x,y). The real part can be accessed using the function real() and imaginary part can be represented by imag().

SEQUENCE TYPE:
In Python, sequence is an ordered collection of various object. These objects could be of similar or different data types. 
Lists:
List is an ordered collection of data. It is declared using "[]"
Tuples:
Tuples are immutable lists i.e. tuples cannot be modified after it is created. It is declared using "()"
Strings:
Strings are arrays of bytes representing Unicode characters. A string is a collection of one or more characters put in a single quote, double-quote or triple quote.

MAPPING TYPE:
Maps are a data type composed of a collection of (key, value) pairs, such that each possible key appears at most once in the collection. In python, we use dictionary data type as a map. Dictionary holds key:value pair. Each key-value pair in a Dictionary is separated by a colon :, whereas each key is separated by a ‘comma’.A Dictionary can be created by placing a sequence of elements within curly {} braces.Dictionary can also be created by the built-in function dict().
NOTE: Keys cannot be repeated in dictionary.

SET:
In Python, Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements.Sets can be created by using the built-in set() function with an iterable object or a sequence by placing the sequence inside curly braces, separated by ‘comma’. Type of elements in a set need not be the same.

BOOLEAN TYPE:
Boolean is Data type with one of the two built-in values, True or False.
Note – True and False with capital ‘T’ and ‘F’ are the only valid booleans.












GET THE DATA TYPE OF THE VARIABLE:
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
