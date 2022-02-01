---
title: "Conditional Statements and Flow control"
teaching: 0
exercises: 0
questions:
- "What are conditional statements?"
- "What are control flow statements?"
objectives:
- "Understand Conditional Statements and Control Flow statements"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---
## Conditional Statements
Conditional statements provide us the ability to test a variable against a value and act in one way if the condition is met by the variable or another way if not.

### IF STATEMENT

The IF statement is a decision-making statement that guides a program to make decisions based on specified criteria. The IF statement executes one set of code if a specified condition is met (TRUE) or another set of code evaluates to FALSE.

~~~
lis1= ['good','better','best','bad','worse']

if 'good' in lis1:
  print('Everything is good')


if 'no' in lis1:
  print('Nothing')
print('Done')
~~~

---

### ELIF STATEMENT

The elif statement allows you to check multiple expressions for TRUE and execute a block of code as soon as one of the conditions evaluates to TRUE

~~~
name = 'xyz'


if name=='Jo':
  print('Hi Jo')
elif name=='Mark':
  print('Hi Mark')
elif name=='Frank':
  print('Hi Frank')
elif name=='Mike':
  print('Hi Mike')
else:
  print('No match found')
~~~

---
## Control Flow
Control Flow is the order in which instructions and function calls are implemented. Thw while and for loop provide us a way to manipulate control Flow

### WHILE LOOP

The while loop is used to execute a set of statements as long as a condition is true.

~~~
i = 1
while i < 6:
  print(i)
  i += 1
~~~
> ### We use the BREAK and CONTINUE statements to control the flow of the loop
> #### Break is used to exit the loop
> ~~~
> i = 1
> while i < 6:
>   print(i)
>   if i == 3:
>     break
>     i += 1
> ~~~
> #### Continue is used to stop the current iteration, and continue with the next
> ~~~
> i = 0
> while i < 6:
>   i += 1
>   if i == 3:
>     continue
>   print(i)
>   ~~~


---

### FOR LOOP

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

~~~
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
~~~
> The for loop also has break and continue operators like the while loop

