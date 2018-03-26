---
title: Checking for prime numbers
layout: post
author: joe.burton
permalink: /checking-for-prime-numbers/
source-id: 1cSi1JPg57zLP5YpA6d3SLG67Bm73b7lYrNGTAwSR110
published: true
---
This week we used python 3 to try and create a piece of code that would be able to tell you if an inputted integer was a prime number or not. My code opens with asking for a whole number, which it then converts into an integer. I then defined a function called is_prime. Now came the difficult part. We worked out that you could use the type of division in python that will only give you the remainder. We also decided that you could use this to check if a number was cleanly divisible by another number. What I wanted to do was to create a single function that would go through all the possible things that the input number could be divisible by, and check if they were divisible by anything. To do this, I eventually decided to use multiple variables, within the function, and cause them to change throughout the running time of a while loop. I then used one of these variables to create a short piece of code that would decide if the number inputted waas prime or not.

Here is my code:

print("Give me a whole number")

print("The larger it is, the longer this will take")

n = input("")

n = int(n)

def is_prime(n):

  u = 2

  p = 0

  while u <= n/2:

    if n % u == 0:

      p = p + 1

    u = u + 1

  if p == 0:

    print(n,"is a prime number")

  else:

    print(n,"is not a prime number")

is_prime(n)

