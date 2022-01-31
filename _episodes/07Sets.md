---
title: "Sets"
teaching: 0
exercises: 0
questions:
- "What are sets?"
- "How to use sets in python"
objectives:
- "Understand how sets work in python"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
## What are sets?
A set is a collection which is unordered and unindexed.

## Creating a set:
Sets are created using curly brackets.

~~~
set_example={"Digital","Scholorship","Hub",2}
print(set_example)
~~~
> #### Remember-   
> Set items are -
> - unordered: We cannot be sure which order the element are stored and displayed in.
> - unchangeable: We cannot update the elements of the set. However, we can insert and delete values.
> - No duplicate values: Sets cannot have two items with the same value.



## Length of a Set:

We use the len() funtion to get the length of the set
~~~
print(len(set_example))
~~~

The set() Constructor:

The set constructor is used to create a set.

~~~
set_constructor=set(("Digital","Scholorship","Hub",2))
print(set_constructor)
~~~

## Inserting elements into a set:

To insert a single element into an existing set, the add method is used.

~~~
set_example.add("Python")
print(set_example)
~~~

Instead of a single element, if you want to append another set or any other iterable object(tuples, lists, dictionaries), we can use the update method

~~~
list_a=["Beginners","Workshop"]
set_example.update(list_a)
print(set_example)
~~~

## Deletion of sets:

To delete an element in a set, we use the remove and discard methods.
~~~
set_example.remove("Beginners")
set_example.discard("Workshop")
~~~
the key difference between these two methods is that remove raises an error if the item to remove does not exist, where as discard does not raise an error.

clear(): This methid will empty the set
~~~
set_example.clear()
~~~

del: this keyword is used to delete the set completely:
~~~
del set_example
~~~

