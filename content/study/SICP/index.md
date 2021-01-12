---
title: Notebooks on Structure and Interpretation of Computer Programs
summary: Exercises and projects for Structure and Interpretation of Computer Programs in LISP.
tags: 
- Structure and Interpretation of Computer Programs
- LISP
- Exercises resolution
- Scheme
date: "2021-01-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/Renatochaz/SICP
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
* The shareable code and notebooks are in the [github repository](https://github.com/Renatochaz/SICP) linked in this post. Feel free to access, comment, star or fork, interactions motivate me to produce and share more content for free, and suggestions to improvement are always viewed in a positive light! 

Notebooks (in Scheme) with resolutions and annotation of projects and exercises of the classic Structure and Interpretation of Computer Programs from MIT taught by Prof. Eric Grimson, Prof. Peter Szolovits and Prof. Trevor Darrell in Spring 2005.

Basic course description (From MIT OCW): 
"This course introduces students to the principles of computation. Upon completion of 6.001, students should be able to explain and apply the basic methods from programming languages to analyze computational systems, and to generate computational solutions to abstract problems. Substantial weekly programming assignments are an integral part of the course."

Below are the description of avaliable solved exercises and projects in the github repository.

**Projects**

- Project 0.

**Solved exercises **

[SICP Book](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)

- Section 1.1

Exercise 1.1. Below is a sequence of expressions. What is the result printed by the interpreter in response to each expression? Assume that the sequence is to be evaluated in the order in which it is presented.

Exercise 1.2.  Translate the following expression into prefix form

Exercise 1.3.  Define a procedure that takes three numbers as arguments and returns the sum of the squares of the two larger numbers.

Exercise 1.4.  Observe that our model of evaluation allows for combinations whose operators are compound expressions. Use this observation to describe the behavior of the following procedure:

Exercise 1.6.  Alyssa P. Hacker doesn't see why if needs to be provided as a special form. ``Why can't I just define it as an ordinary procedure in terms of cond?'' she asks. Alyssa's friend Eva Lu Ator claims this can indeed be done, and she defines a new version of if:

(define (new-if predicate then-clause else-clause)
  (cond (predicate then-clause)
        (else else-clause)))

Eva demonstrates the program for Alyssa:

(new-if (= 2 3) 0 5)
5

(new-if (= 1 1) 0 5)
0

Delighted, Alyssa uses new-if to rewrite the square-root program:

(define (sqrt-iter guess x)
  (new-if (good-enough? guess x)
          guess
          (sqrt-iter (improve guess x)
                     x)))

What happens when Alyssa attempts to use this to compute square roots? Explain.

Exercise 1.7.  The good-enough? test used in computing square roots will not be very effective for finding the square roots of very small numbers. Also, in real computers, arithmetic operations are almost always performed with limited precision. This makes our test inadequate for very large numbers. Explain these statements, with examples showing how the test fails for small and large numbers. An alternative strategy for implementing good-enough? is to watch how guess changes from one iteration to the next and to stop when the change is a very small fraction of the guess. Design a square-root procedure that uses this kind of end test. Does this work better for small and large numbers?


- Section 1.2

Exercise 1.11.  A function f is defined by the rule that f(n) = n if n<3 and f(n) = f(n - 1) + 2f(n - 2) + 3f(n - 3) if n> 3. Write a procedure that computes f by means of a recursive process. Write a procedure that computes f by means of an iterative process.

Exercise 1.12.  The following pattern of numbers is called Pascal's triangle.


The numbers at the edge of the triangle are all 1, and each number inside the triangle is the sum of the two numbers above it.35 Write a procedure that computes elements of Pascal's triangle by means of a recursive process.

Exercise 1.13.  Prove that Fib(n) is the closest integer to n/5, where  = (1 + 5)/2. Hint: Let  = (1 - 5)/2. Use induction and the definition of the Fibonacci numbers (see section 1.2.2) to prove that Fib(n) = (n - n)/5.





