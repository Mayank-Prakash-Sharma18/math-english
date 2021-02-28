---
title: Factors and Multiples
linktitle: Factors and Multiples
toc: true
type: docs
date: "2021-02-21T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 1. Number System
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

## Concept of Factors and Multiples

Let A and B be any two natural numbers.

If A/B is a natural number, then it means that:
* A is a multiple of B
* B is a factor of A

In other words, we can say that factors of a number are all those numbers that completely divide the given number, i.e. those that leave no remainder. 

{{% alert note %}}
1 is a factor of all numbers as it divides all the number completely. 
{{% /alert %}}

Factor of a number cannot be greater than the number (infact the largest factor will be the number itself). Thus the factors of any number will lie between 1 and the number itself (both inclusive) and thus are limited. <br>
E.g. Factors of 6 are: 1, 2, 3 and 6. 

The smallest multiple will be the number itself and the number of multiples would be infinite.
E.g. Multiples of 6 are: 6, 12, 18 ... so on. 

You may have noticed that every successive multiple appears as the sixth number after the previous.

##### Q. Can you find the number of multiples of 6 less than 62?

Explanation:<br>
<div class="Exp">

We just need to find out the quotient when we divide 150 by 6 (and ignore the remainder).
So, 62/6 = 10 <br>
Hence, there are 10 multiples of 6 less than 62. <br>
We can  check it by writing all these multiples: 6, 12, 18, 24, 30, 36, 42, 48, 54, 60.
</div> <br>


## Factorization: Prime Factors

* Factors of a Number: As we have already seen, Factors of a number refers to all the numbers which divide that number completely (i.e. they leave no remainder). <br>
E.g. These are the factors of 12: 1, 2, 3, 4, 6, 12.

{{% alert note %}}
Factors are also called divisors of a number.
{{% /alert %}}

The number is the multiple of its factors/divisors. 

* Prime factors: The factors that are prime numbers. <br>
E.g. These are the prime factors of 12: 2, 3. 

### What is Prime factorization?

Prime factorization of a number is the expression of the number as the product of its prime factors.

N = $p^a q^b r^c$

Where, p, q and r are prime factors of the number, a, b and c are non-negative powers. 

For example, This is the factorized form of 12 in terms of its basic prime factors:
12 = $2^2 × 3^1$

### Finding Number of factors 

If N = $p^a q^b r^c$ <br>
(Where, p, q and r are prime factors of the number, a, b and c are non-negative powers.) <br>
Then, Number of factors of N = (a + 1) (b + 1) (c + 1) <br>
(including 1 and N) 

E.g. 60 = $2^2 × 3^1 × 5^1$

So, possible powers of 2: (0, 1, 2) <br>
Possible powers of 3: (0, 1) <br>
Possible powers of 5: (0, 1) <br>
Each unique combination of these powers gives a distinct factor.  <br>
The number of possible combinations = 3 × 2 × 2 = 12 <br>
Since there are 12 different combinations of the powers of 2, 3 and 5, there are 12 distinct factors of 60. <br>
We will get the same answer if we apply the formula given above. 

### Finding Number of odd factors

To find the number of odd factors we should ignore the power of the even prime factor (i.e. 2). 

E.g. 60 = $2^2 × 3^1 × 5^1$

We will ignore the power of 2.

So, the number of odd factors of 60 = (1 + 1) (1 + 1) = 4 <br>
These are: 1, 3, 5, 15

### Finding number of even factors

Number of even factors = Total number of factors – Number of odd factors.

E.g. 60 = $2^2 × 3^1 × 5^1$

So, the number of even factors of 60 = 12 – 4 = 8 <br>
These are: 2, 4, 6, 10, 12, 20, 30, 60


## Sum and Product of all factors

### Product of all factors

Product of factors of N = $N^\frac{Number \hspace{1ex} of \hspace{1ex} factors}{2}$

(including 1 and the number itself)

For example: <br>
12 = $2^2 × 3^1$ 

Number of factors of 12 = (2 + 1) (1 + 1) = 3 × 2 = 6 

Product of the factors of 12 = $12^\frac{6}{2}$ = $12^3$

Let us double check this: <br>
Product of the factors of 12 = 1 × 2 × 3 × 4 × 6 × 12 = $12^3$

### Sum of all factors

Sum of factors = $(p^0 + p^1 + ... + p^a) (q^0 + q^1 + ... + q^b) (r^0 + r^1 + ... + r^c)$ ... <br>
= $\frac{(p^{a + 1} − 1)}{(p − 1)} \frac{(q^{b + 1} − 1)}{(q − 1)} \frac{(r^{c + 1} − 1)}{(r − 1)}$ ...

(including 1 and the number itself) 

For example: <br>
12 = $2^2 × 3^1$

Sum of the factors of 12 = $\frac{(2^{2 + 1} − 1)}{(2 − 1)} \frac{(3^{1 + 1} − 1)}{(3 − 1)}$ = (7 × 8) / (1 × 2) = 28 

Let us double check this: <br>
Product of the factors of 12 = 1 + 2 + 3 + 4 + 6 + 12 = 28  

{{% alert note %}}
#### Perfect numbers

If the sum of all factors (except that number itself) of a number is equal to the number itself is called a perfect number 

E.g. Factors of 6 except 6 are: 1, 2, 3 <br>
Sum of above factors = 1 + 2 + 3 = 6 <br>

28 and 496 are the other perfect numbers in the first 1000 natural numbers.
{{% /alert %}}


## Number of ways to express a number as the product of two factors

There are two possible cases:

* The number is a non-perfect square 

* The number is a perfect square

### Number is a non-perfect square

For such a number, the number of factors should be even.

The number of ways to express such a number as the product of two factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors}{2}$

For example: <br>
24 = $2^3 × 3^1$ <br>
The number of factors of 24 = (3 + 1) (1 + 1) = 8 <br>
So, the number of ways to express it as the product of two factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors}{2}$ = 8/2 = 4 <br><br>
Let us double check it. <br>
The number 24 can be expressed as the product of two factors in the following ways: 1 × 24, 2 × 12, 3 × 8, 4 × 6. (i.e. 4 ways)

### Number is a perfect square

For such a number, the number of factors should be odd.

Then the number of ways to express such a number as the product of any two factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors + 1}{2}$   (including √Number x √Number) 

And the number of ways to express the number as the product of two distinct factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors - 1}{2}$    (excluding √Number x √Number) 

For example: <br>
25 = $5^2$ <br>
The number of factors of 25 = (2 + 1) = 3 <br>
So, the number of ways to express it as the product of two factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors + 1}{2}$ = (3 + 1)/2 = 2 <br>
And the number of ways to express the number as the product of two distinct factors = $\frac{number \hspace{1ex} of \hspace{1ex} factors - 1}{2}$ = (3 - 1)/2 = 1 <br><br>
Let us double check it. <br>
The number 25 can be expressed as the product of two factors in the following ways: 1 × 25, 5 × 5. (i.e. 2 ways, out of which one is the product of distinct factors)


## Number of ways to express a number as the product of two relatively prime factors

The number of ways to express a number as a product of two co-primes = $2^{n-1}$ <br>
(where n is the number of distinct prime factors of the number)

For example: <br>
24 = $2^3 × 3^1$ <br>
Number of distinct prime factors of 24, n = 2  (i.e. 2 and 3) <br>
So, the number of ways to express 24 as a product of two co-primes = $2^{n - 1}$ = $2^{2 - 1}$ = 2 <br>
These two ways are: 1 × 24, 3 × 8

## Properties of Factors

### Property 1: Factors of Prime Numbers

Perfect square of any prime number has exactly 3 factors. <br>
E.g. Factors of 25: 1, 5 and 25.

### Property 2: Factors of Perfect Squares

All perfect squares have an odd number of factors. <br>
E.g. Factors of 16: 1, 2, 4, 8 and 16, i.e. 5 factors

All non-perfect squares have even number of factors. <br>
E.g. Factors of 15: 1, 3, 5, 15, i.e. 4 factors. 

### Property 3: Divisibility by factors of a factor

If a number is divisible by another number, then it is also divisible by all factors of that number.

Example: 108 is divisible by 36 <br>
Factors of 36 are 1, 2, 3, 4, 6, 9, 12, 18, 36 <br>
Hence, 108 is also divisible by each of the numbers 1, 2, 3, 4, 6, 9, 12, 18, 36.

