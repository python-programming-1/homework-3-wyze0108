# Homework 3

The Collatz Conjecture
https://en.wikipedia.org/wiki/Collatz_conjecture

1. Write a function named collatz() that takes in one parameter, maybe call it 'num'.
2. If the number is even, then collatz should print and return the num // 2. If the number is odd, collatz() should print and return 3 * num + 1
3. Write a program that lets a user type in an integer and keeps calling collatz on that number until the function returns 1. 
4. Wrap your program with Try and Except statements to catch if a user tries to type a non-integer value like 'cat'. The error you'll get will be usually ValueError if you pass an string to an int() function like int('cat')

Notes:

No matter what number you put in, eventually, you'll arrive at 1. Weird right? There is no mathematical proof, just conjecture.

To determine if an integer is odd or even you may use the following expressions:

even if number % 2 == 0
and odd if number % 2 == 1


The output of this program could look something like this:

Enter number:
3

10

5

16

8

4

2

1
