---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---




WHAT ARE DICTIONARIES?
A dictionary is a datatype that stores data in key value pairs.The key and value have a colon between them(:) and the key:value pairs are seperated by "," It is ordered*, changeable and do not allow duplicates.

CREATING A DICTIONARY:
We create a dictionary using curly({}) brackets.
~~~
demo1={'a':10,'b':20,'c':30,'d':40}

print(demo1)
~~~

ACCESSING ELEMENTS IN DICTIONARY:
We can access elements using the key:
~~~
print(demo1['a'])
~~~

keys(): The keys method returns a list of all the keys in a dictionary
~~~
k= demo1.keys()
print(k)
~~~

INSERTING/CHANGING ITEMS IN DICTIONARY:

We can change items using the key. There is also an update() methos that takes a dictionary as an argument to change the values.
~~~
demo1['a']=50
demo1.update({'a':10})
~~~

We can also add new elements to a dictionary in the same way:

~~~
demo1['e']=50
demo1.update({'f':60,'g':70})
~~~
COPY DICTIONARIES:
We can use the copy() method and the dict() function. We cannot simply do dictionary1=dictionary2 as it will only create a reference instead of copying the dictionary.

~~~
demo2=demo1.copy()
demo3=dict(demo1)
~~~
DELETION IN DICTIONAIES:

We use the pop() method and the del keyword to delete elements in dictionaries. We pass the key as an argument to indicate the value to be deleted

~~~
demo1.pop('g')
del demo1['f']
~~~

the del keyword can delete the dictionary completely:
~~~
del demo1
print(demo1)
~~~

The clear() method is used to empty the dictionary.
~~~
demo1.clear()
~~~


NESTED DICTIONARIES:

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


