---
title: "Lists"
teaching: 0
exercises: 0

objectives:
- "To understand how to work with lists"
---

## What are Lists?
 
Lists are just like the arrays, declared in other languages which is a ordered collection of data. It is very flexible as the items in a list do not need to be of the same type.
 

## Creating a List

Lists in Python can be created by just placing the sequence inside the square brackets[].



## Accessing elements of a List


In order to access the list items, we use the index number. For example- we can access the third element by typing list[2]. In Python, negative sequence indexes represent positions from the end of the array. That is -1 refers to the last item, -2 refers to the second-last item, etc.
> ### Note:
> Indexing in python always starts from 0. In the below example, the index of 12 is 0.

~~~
pantry= ['flour',' baking powder','salt','white sugar','milk','egg','butter','cheese','yeast','vanilla extract','oregano','maple syrup','strawberry jam']


print(pantry)        #Prints list

print(pantry[0])     #Prints 1st element in the list

print(pantry[1:5])   #Prints 2nd to 5th elements in the list

print(pantry[4:])    #Prints all the elements after 4

print(pantry[-1])    #Prints the last element
~~~

## Removing elements from a List

We use the inbuilt methods del(), pop(),remove().

~~~
pantry_1= ['flour',' baking powder','salt','white sugar','milk','egg','butter','cheese','yeast','vanilla extract','oregano','maple syrup','strawberry jam']


del(pantry_1[4])         #Delets the 5th element in the list 
print(pantry_1)  

pantry_1.remove('milk')      #Removes the element 22. Remove command removes the first matching element
print(pantry_1)

pantry_1.pop(1)          #Pops the element present on the first index
print(pantry_1)
~~~


## Other Operations with list

~~~
pantry= ['flour',' baking powder','salt','white sugar','milk','egg','butter','cheese','yeast','vanilla extract','oregano','maple syrup','strawberry jam']
new_items=['pepper','yeast','cinnamon','chilli flakes','oregano']

print(len(pantry))     # The len() function is used to get the length of the list
updated_pantry= pantry + new_items     #Adding/Concatenating two lists
print(updated_pantry)
print(updated_pantry[-3:])     #Prints last 3 elements
~~~


~~~
#Checking if an element is present in the list

'pepper' in updated_pantry   #The 'in' statement checks whether certain element is present in the list or not. If the element is present it returns True else False
'yeast' in updated_pantry
'salt' not in updated_pantry #Similar to 'in' statement
~~~


~~~
#Min Max Function
lis6=[1,34,73,67,99,22,3,4]

print(min(lis6))
print(max(lis6))
~~~


~~~
#Adding value to the list
lis6.append(56)     #Appends only one element at the end of the list
print(lis6)
lis6.extend([11,2,33]) #Appends multiple elements at the end of the list
print(lis6)
updated_pantry.append('olive oil')
updated_pantry.extend(['Mayonnaise','Cream Cheese','Honey'])
lis6.insert(0,90)   #Inserts element at the mentioned index
print(lis6)
~~~


~~~
#Sorting elements in a list

lis7=[-6,1,-1,-5,3,6,7,8,22,5,4]

lis7.sort()         #Sorts elements in ascending order

print(lis7)

#Sorted function

lis8=[-3,11,2,3,8,4,1,5,-5,-8,-10,10]

print(sorted(lis8)) #Prints the sorted list

print(lis8)         #Prints the original list. Sorted function doesnot change the original list whereas sort function does
~~~


~~~
#Reassigning a list
print(lis8)

lis8[0]=100         #Assigns index 0 as 100

print(lis8)

~~~


## Applications of List
- Lists support sequential access so they can be used to store recipes and instructions that need to be followed in order.
- They are also used in Databases
