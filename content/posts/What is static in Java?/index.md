+++
title = 'What is static in Java?'
date = 2024-01-13T15:55:02+05:30
draft = false
author = 'Arun'
featuredImage = "/images/posts/What is static in Java/code.jpeg"


+++

static is a non-access modifier in Java which is used mainly for the purpose of memory management. static belongs to the class instead of the instance of the class. static keyword can be used with:

1. Variables
2. Methods
3. Nested Classes
4. Blocks

In order to create a static member, we need to write the keyword static preceding the declaration of the member.

Static Variables

If a variable is declared as static:
It will get memory only once in the class area at the time of class loading.
The single copy of this variable will be shared among all the instances of the class.
Example of the static variable


Output: 
10
20