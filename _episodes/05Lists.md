---
title: "Lists"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

Lists are just like the arrays, declared in other languages which is a ordered collection of data. It is very flexible as the items in a list do not need to be of the same type.
 

Creating List:

Lists in Python can be created by just placing the sequence inside the square brackets[].



Accessing elements of List


In order to access the list items, we use the index number. For example- we can access the third element by typing list[2]. In Python, negative sequence indexes represent positions from the end of the array. That is -1 refers to the last item, -2 refers to the second-last item, etc.

~~~
list1=[12, 15.5, 'abcd', 'xyz', 34, 256.8]

print(list1)        #Prints list

print(list1[0])     #Prints 1st element in the list

print(list1[1:5])   #Prints 2nd to 5th elements in the list

print(list1[4:])    #Prints all the elements after 4

print(list1[-1])    #Prints the last element
~~~

Removing elements from a List

We use the inbuilt methods del(), pop(),remove().

~~~
lis4=['Lovely day', 45.6, 22, 'Good Night', 'Afternoon', 56, 29, 30, 22]

del(lis4[4])         #Delets the 5th element in the list 
print(lis4)  

lis4.remove(22)      #Removes the element 22. Remove command removes the first matching element
print(lis4)

lis4.pop(1)          #Pops the element present on the first index
print(lis4)
~~~

Other Operations with list

~~~
lis1=[100,99,98,97]
lis2=['abc','xyz',88,28,34,'ijk']

print(len(lis1))     # The len() function is used to get the length of the list
lis3= lis1+lis2      #Adding/Concatenating two lists
print(lis3)
print(lis3[-3:])     #Prints last 3 elements

#Checking if an element is present in the list
lis5=['Illinois','Indiana','Texas','Florida']

'Illinois' in lis5   #The 'in' statement checks whether certain element is present in the list or not. If the element is present it returns True else False
'Arizona' in lis5
'Arizona' not in lis5 #Similar to 'in' statement

#Min Max Function
lis6=[1,34,73,67,99,22,3,4]

print(min(lis6))
print(max(lis6))

#Adding value to the list
lis6.append(56)     #Appends only one element at the end of the list
print(lis6)
lis6.extend([11,2,33]) #Appends multiple elements at the end of the list
print(lis6)

lis6.insert(0,90)   #Inserts element at the mentioned index
print(lis6)

#Sorting elements in a list

lis7=[-6,1,-1,-5,3,6,7,8,22,5,4]

lis7.sort()         #Sorts elements in ascending order

print(lis7)

#Sorted function

lis8=[-3,11,2,3,8,4,1,5,-5,-8,-10,10]

print(sorted(lis8)) #Prints the sorted list

print(lis8)         #Prints the original list. Sorted function doesnot change the original list whereas sort function does

#Reassigning a list
print(lis8)

lis8[0]=100         #Assigns index 0 as 100

print(lis8)

~~~
