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
~~~
