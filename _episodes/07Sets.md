---
title: "Sets"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

A set is a collection which is unordered and unindexed.

CREATING A LIST:
Sets are created using curly brackets.

~~~
set_example={"Digital","Scholorship","Hub",2}
print(set_example)
~~~
Remember:
Set items are -
unordered: We cannot be sure which order the element are stored and displayed in.
unchangeable: We cannot update the elements of the set. However, we can insert and delete values.
No duplicate values: Sets cannot have two items with the same value.



Length of a Set:

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

