---
title: Co-primes
linktitle: Co-primes 
toc: true
type: docs
date: "2021-02-20T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 1. Number System
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

Co-prime numbers are also known as Relatively prime numbers. 

## What are Co-prime numbers?

They are two natural numbers which doesn't have a common factor other than 1, i.e. their H.C.F. is 1. <br>
E.g. (8 and 9), (4 and 5).

{{% alert note %}}
* Two numbers may be co-primes even if none of them are primes individually. E.g. 4 and 9. 

* 1 is relatively prime to all the other natural numbers.
{{% /alert %}}

## Properties of Co-primes 

### Property 1: Consecutive numbers

* Two consecutive odd numbers  are always co-prime numbers. <br>
E.g. (9 & 11),  (15 & 17) etc.

* Three consecutive odd numbers are always co-prime numbers. <br>
E.g. (3, 5 & 7), (21, 23 & 25)

### Property 2: As factors

<strong>How to find whether a number A is divisible by another number B?</strong>

We need to find two co-prime numbers, x and y such that B = x × y 

If A is divisible by both x and y, then it is divisible by B.

E.g. Is 120 divisible by 24? <br>
Now, 24 = 8 × 3   (8 and 3 are co-primes) <br>
As 120 is divisible by both 8 and 3, so it must be divisible by 24 too. 

In other words, if a number is divisible by two co-prime numbers, then the number is divisible by their product also.

We can extend this rule to more than 2 co-primes too.

So, if a number is divisible by more than two co-prime numbers, then the number is divisible by their product also.

E.g. Is 960 divisible by 60? <br>
Now, 60 = 5 × 4 × 3  (5, 4 and 3 are co-primes) <br>
As 960 is divisible by 5, 4 and 3, so it must be divisible by 60 too. 

### Property 3: Euler's function

Euler's function, ϕ(N) = the number of all co-primes to N, which are less than N. <br>
If N = $a^p b^q c^r$ ..... <br>
ϕ(N) = N [1 − $\frac{1}{a}$] [ 1 − $\frac{1}{b}$] [1 − $\frac{1}{c}$] ..... 

##### Q. Example: Find the number of co-primes to 36, which are less than 36. OR <br> If p is relatively prime to 36 and p < 36. Find the number of possible values for p?

Explanation:<br>
<div class="Exp">

36 = $2^2 × 3^2$ <br>
ϕ(36) = 36 [1 − $\frac{1}{2}$] [1 − $\frac{1}{3}$] = 36 × (1/2) × (2/3) = 12 <br>
So, there are 12 possible values for p: <br>
-1, 5, 7, 11, 13, 17, 19, 23, 25, 29, 31, 35.
</div> <br>
 
### Property 4

Sum of all co-primes to N which are less than N = $\frac{N^2}{2}$ [1 − $\frac{1}{a}$] [ 1 − $\frac{1}{b}$] [1 − $\frac{1}{c}$] ..... = ($\frac{N}{2}$) ϕ(N)

##### Q. Find the sum of all co-primes to 18, which are less than 18.

Explanation:<br>
<div class="Exp">

Sum = $\frac{18^2}{2}$ [1 − $\frac{1}{2}$] [ 1 − $\frac{1}{3}$] = 54
</div> <br>





