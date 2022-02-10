---
title: "Dictionaries"
teaching: 0
exercises: 0
questions:
- "What are Dictionaries"
- " How to work with Dictionaries in python?"
objectives:
- "To understand the concept of dictionaries"
---




## What are Dictionaries?
A dictionary is a datatype that stores data in key value pairs. The key and value have a colon between them(:) and the key:value pairs are seperated by "," It is ordered*, changeable and do not allow duplicates.

## Creating a Dictionary
We create a dictionary using curly({}) brackets.
~~~
demo1={'a':10,'b':20,'c':30,'d':40}

print(demo1)
~~~
{: .language-python}

## Accessing elements in a Dictionary
We can access elements using the key:
~~~
print(demo1['a'])
~~~
{: .language-python}

keys(): The keys method returns a list of all the keys in a dictionary
~~~
k= demo1.keys()
print(k)
~~~
{: .language-python}

## Inserting/changing items in a Dictionary:

We can change items using the key. There is also an update() methos that takes a dictionary as an argument to change the values.
~~~
demo1['a']=50
demo1.update({'a':10})
~~~
{: .language-python}

We can also add new elements to a dictionary in the same way:

~~~
demo1['e']=50
demo1.update({'f':60,'g':70})
~~~
{: .language-python}

## Copying a Dictionary:
We can use the copy() method and the dict() function. We cannot simply do dictionary1=dictionary2 as it will only create a reference instead of copying the dictionary.

~~~
demo2=demo1.copy()
demo3=dict(demo1)
~~~
{: .language-python}

## Deletion in Dictionaries:

We use the pop() method and the del keyword to delete elements in dictionaries. We pass the key as an argument to indicate the value to be deleted

~~~
demo1.pop('g')
del demo1['f']
~~~
{: .language-python}

the del keyword can delete the dictionary completely:
~~~
del demo1
print(demo1)
~~~
{: .language-python}

The clear() method is used to empty the dictionary.
~~~
demo1.clear()
~~~
{: .language-python}


## The concept of nested Dictionaries:

A dictionary can dictionaries within itself. This is called a nested dictionary:
~~~
demo4 = {
  "letters" : {
    "a" : "1",
    "b" : 2
  },
  "capital_letters" : {
    "A" : "1",
    "B" : 2
  },
}
# or we can also do the following:

letters = {
  "a" : "1",
  "b" : 2
}
capital_letters = {
  "A" : "1",
  "B" : 2
}


demo5 = {
  "letters" : letters,
  "capital_letters" : capital_letters
}
~~~
{: .language-python}

## Applications of Dictionaries
- Used in Dataframes(Handling data from datasets)
