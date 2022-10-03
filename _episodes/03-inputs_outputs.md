
---
title: "inputs and Outputs"
teaching: 0
exercises: 0
questions:
- "What, Why and Who"
---


## Collect user input

The 'input' method provides an easy way to coolect user input.
~~~

name= input('What is your name?')
~~~
{: .language-python}

In python, all imputs are stored as strings. You can change the data type using type casting

~~~

number = input("Enter a number")
number= int(number)
~~~
{: .language-python}


## Output in Pythom
You can display output using python
~~~
print("Hello!")
name = "Digital Scholarship Hub"

print(f'Hello {name}! How are you?')

~~~
{: .language-python}

## Using % Operator
We can use ‘%’ operator. % values are replaced with zero or more value of elements.
- %d – integer
- %f – float
- %s – string
- %x – hexadecimal
- %o – octal
~~~

num = int(input("Enter a value: "))

print("The number is %d" %num)

~~~
{: .language-python}

