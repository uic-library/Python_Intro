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
pantry={'eggs':10,'butter(tbsp)':20,'sugar(oz)':30,'salt(oz)':40}

print(pantry)
~~~
{: .language-python}

## Accessing elements in a Dictionary
We can access elements using the key:
~~~
print(pantry['eggs'])
~~~
{: .language-python}

keys(): The keys method returns a list of all the keys in a dictionary
~~~
k= pantry.keys()
print(k)
~~~
{: .language-python}

## Inserting/changing items in a Dictionary:

We can change items using the key. There is also an update() methos that takes a dictionary as an argument to change the values.
~~~
pantry['eggs']=50
pantry.update({'eggs':10})
~~~
{: .language-python}

We can also add new elements to a dictionary in the same way:

~~~
pantry['Flour']=50
pantry.update({'pepper':60,'olive oil':70})
~~~
{: .language-python}

## Copying a Dictionary:
We can use the copy() method and the dict() function. We cannot simply do dictionary1=dictionary2 as it will only create a reference instead of copying the dictionary.

~~~
pantry_copy_1=pantry.copy()
pantry_copy_2=dict(pantry)
~~~
{: .language-python}

## Deletion in Dictionaries:

We use the pop() method and the del keyword to delete elements in dictionaries. We pass the key as an argument to indicate the value to be deleted

~~~
pantry.pop('olive oil')
del pantry['pepper']
~~~
{: .language-python}

the del keyword can delete the dictionary completely:
~~~
del pantry
print(pantry)
~~~
{: .language-python}

The clear() method is used to empty the dictionary.
~~~
pantry.clear()
~~~
{: .language-python}


## The concept of nested Dictionaries:

A dictionary can dictionaries within itself. This is called a nested dictionary:
~~~
pantry = {
  "Pancakes" : {
    "Flour" : 6,
    "milk" : 2,
    "Eggs": 3
    "Butter" : 6
  },
  "French_toast" : {
    "Bread" : "2",
    "Eggs" : 2,
    "Sugar" : 3
    "milk" :1
  },
}
# or we can also do the following:

Pancakes = {
    "Flour" : 6,
    "milk" : 2,
    "Eggs": 3
    "Butter" : 6
  }
French_toast = {
    "Bread" : "2",
    "Eggs" : 2,
    "Sugar" : 3
    "milk" :1
  }
pantry_2 = {
  "Pancakes" : letters,
  "French_toast" : capital_letters
}
~~~
{: .language-python}

## Applications of Dictionaries
- Used in Dataframes(Handling data from datasets)
