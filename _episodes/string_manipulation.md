---
title: "String Manipulation"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## What is a String?


As mentioned earlier, a string is a collection of one or more characters put in a single quote, double-quote or triple quote.. A character is anything you can type on the keyboard in one keystroke, like a letter, a number, or a backslash.

Example: "Hub 2",'Digital Scholorship hub'.

## What is String manipulation?

String manipulation is the process of handling and modifying strings for various purposes like parsing etc.

## Why is String Manipulation important?

Most of the data obtained from the user, is in the form of text. Applications use text boxed extensively to capture data accuratley. Therefore, dealing with strings is a top priority for programmers and data enthusiasts alike.

## How to manipulate Strings?

Python offers an array of inbuilt functions aimed at helping with string manipulation. A few of them are discussed below.

### Creation

We create a string by enclosing characters in either " " or  ' '.

s= "Digital Scholorship Hub 2"

We can also type caste a variable into string using str().

s1=str(12345)


### Accessing

Strings are accessed in the same way as lists, i.e using []

a=s[2]
print(a)


### Length of a string

We use len() to find the length of the string.

print(len(s))


### Search and index:

The find function(find("String")) is used to find if the string contains the characters passed as the argument.

print(s.find("H"))


The index function is used to find the index of the word in the string
print(s.index("Hub"))


### Count

The count(count("")) function returned the number if instances of the word present in the string.

print(s.count(" ")) # returns the number of spaces present in the string.


### Slicing

Slicing is used to access character of a string between two indexes. We use [a:b](a and b are indexes) to get the set of characters. It returns the characters in the string from index a to index b-1.

print(s[3:6]) # returns characters from index 3 to index 5

NOTE:


s[a:b] # items start through end-1


s[a:] # items start through the rest of the list


s[:b] # items from the beginning through end-1


s[:] # a copy of the whole list





### Replace

We can replaces characters in a string using the replace function(.replace('','')).


s2= "Math and Science"


s.replace("Science","Statistics") # replace Science with Statistics.


### Upper case and Lower case

print(s.upper()) # print the string in upper case


print(s.lower()) # print the string in lower case


print(s.title()) # print the string in title case


print(s.swapcase()) # swaps the case of the string.


### Reversal of a string

We can reverse a string using the reverse function(reverse()).

print(s.reverse())


### Stripping

In python, we have strip,lstrip,rstring function to remove characters from the beginning or the end of the string. if characters are not specified, it removes the white spaces.

strip(): removes the characters from both ends of the string.


lstrip(): removes characters from the left end of the string(leading characters)


rstrip(): removes characters fro the right end of the strings(trailing characters)



s=" this is an example "
print(s.strip())


### Concatenation

Concatenation means to attach two strings. We can use the '+' operator to concat strings.

s3="Hello"
S4="World"

print(s3+s4)


### Join

The join function(join('word')), adds a word between each character

print(s.join(" ")) # adds a space between each character.


### Testing.

We can test the string for numbers, alphabets etc using the following functions

s = "Digital Scholorship Hub"

s.isalnum() #checks if all the characters are alphanumeric 


s.isalpha() #checks if all the characters are alphabetic


s.isdigit() #checks if string contains digits


s.istitle() #checks if string contains title words


s.isupper() #checks if string contains upper case


s.islower() #checks if string contains lower case


s.isspace() #checks if string contains spaces


s.endswith('d') #checks if string endswith a d


s.startswith('H') #checks if string startswith H

