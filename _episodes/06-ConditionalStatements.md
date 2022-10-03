---
title: "Conditional Statements and Flow control"
teaching: 0
exercises: 0
questions:
- "What are conditional statements?"
- "What are control flow statements?"
objectives:
- "Understand Conditional Statements and Control Flow statements"
---
## Conditional Statements
Conditional statements provide us the ability to test a variable against a value and act in one way if the condition is met by the variable or another way if not.

### If Statement

The IF statement is a decision-making statement that guides a program to make decisions based on specified criteria. The IF statement executes one set of code if a specified condition is met (TRUE) or another set of code evaluates to FALSE.

~~~
pantry= ['flour',' baking powder','salt','white sugar','milk','egg','butter']

if 'baking powder' in pantry:
  print('We have everything needed to make pancakes!')
else:
  print("You can eat toast!")

if 'syrup' in pantry:
  print('Syrup is optional')
print('Done')
~~~
{: .language-python}

---

### Elif Statement

The elif statement allows you to check multiple expressions for TRUE and execute a block of code as soon as one of the conditions evaluates to TRUE

~~~
pantry= ['flour',' baking powder','salt','white sugar','milk','egg','butter']


if 'milk' in pantry:
  print('We have milk')
elif 'non-dairy milk' in pantry:
  print('Non-Dairy milk is available. We can make vegan pancakes if we have Apple Cider vinegar and vanilla instead of eggs and butter')
else:
  print("Incomplete ingredients")
~~~
{: .language-python}

---
## Control Flow
Control Flow is the order in which instructions and function calls are implemented. Thw while and for loop provide us a way to manipulate control Flow

### While Loop

The while loop is used to execute a set of statements as long as a condition is true.

~~~
butter_in_pantry = 12
servings=0
while butter_in_pantry > 0:
  servings=servings+8
  butter_in_pantry=butter_in_pantry-3
print("Servings:" + str(servings))
~~~
{: .language-python}

> ## We use the BREAK and CONTINUE statements to control the flow of the loop
> ### Break is used to exit the loop
> ~~~
> butter_in_pantry = 150
> servings=0
> while butter_in_pantry > 0:
>   servings=servings+8
>   if servings >= 24:
>     break
>   butter_in_pantry=butter_in_pantry-3
> ~~~
> {: .language-python}
> 
> ### Continue is used to stop the current iteration, and continue with the next
> 
> ~~~
> label_index = 0
> while label_index <= 10:
>   label_index += 1
>   if label_index == 3:
>     continue
>   print("Label "+str(label_index))
>   ~~~
>   {: .language-python}
{: .callout}


---

### For Loop

A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

~~~
pantry= ['flour',' baking powder','salt','white sugar','milk','egg','butter','cheese','yeast','vanilla extract','oregano','maple syrup','strawberry jam']
for x in ingredients:
  print(x)
  print(" ")
~~~
{: .language-python}
> The for loop also has break and continue operators like the while loop




