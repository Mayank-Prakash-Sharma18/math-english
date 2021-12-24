---
title: Types of Divisibility Questions
linktitle: Divisibility Question Types
toc: true
type: docs
date: "2021-12-23T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 2. Divisibility & Remainder
    weight: 31

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 31
---

In this article, we will try to cover all the types of aptitude questions that are framed on the concepts of Divisibility and Remainder. 

## Type 1

##### Q. What should be the value of x, so that the number 81718x4 is divisible by 8?
<pre>(a) 1   (b) 2    (c) 3   (d) 5</pre>

Explanation:<br>
<div class="Exp">

If a number is exactly divisible by 8, then the last 3 digits of the number must be divisible by 8. Here the last 3 digits are 8x4.

Checking Option (b): <br>
Putting x = 2, we get 824. It is exactly divisible by 8. So, 8171824 must be exactly divisible by 8 too.

Answer: (b)
</div> <br>

##### Q. A number p39q2 is completely divisible by numbers 8 and 11. Here both p and q are single digit natural numbers. What will be the value of the summation of p and q?
<pre>(a) 8   (b) 10    (c) 12   (d) 14</pre>

Explanation:<br>
<div class="Exp">

On checking divisibility by 8. <br>
q = 1 makes the last 3 digits 912. This is divisible by 8. <br>
q = 5 makes the last 3 digits 952. This is divisible by 8. <br>
q = 9 makes the last 3 digits 992. This is divisible by 8.

Since the given number is divisible by 11, so the difference between the sum of digits at odd places and the digits at even places must be either 0 or a multiple of 11.

Let the difference be 0. <br>
Then, p + 9 + 2 = 3 + q <br>
Or 11 + p = 3 + q <br>
or q - p = 8 <br>
Only possible values are 9 and 1. So, sum will be 9 + 1 = 10.

Let's check for other cases when the difference is 11 <br>
11 + p - 3 - q = 11 <br>
or p - q = 3 <br>
The possible values in this case are (9, 6), (8, 5), (7, 4), (6, 3), (5, 2), (4, 1) <br>
Among these cases only (9, 6), (8, 5), (5, 2), and (4, 1) will be divisible by 8. So, the possible values of sum are 15, 13, 7, and 5. 

Now, difference between the sum of odd and even placed digits cannot be 22. <br>
11 + p – 3 – q = 22 <br>
Or p – q = 14 <br>
Since both p and q are single digit natural numbers, this is not possible.

Thus, the possible values of sum are 5, 7, 10, 13 and 15. 

Answer: (b)
</div> <br>


## Type 2

##### Q. How many zeroes are there at the end of the following product?
24 × 32 × 13 × 23 × 31
<pre>(a) 0   (b) 2    (c) 4   (d) 6</pre>

Explanation:<br>
<div class="Exp">

The number of zeroes depend on the number of pairs of 2’s and 5’s that can be formed.

$24 × 32 × 13 × 23 × 31 = (2^3 × 3^1) × 2^5 × 13 × 23 × 31$

As the above product has no 5’s in it, it will have no zeroes at the end.

Answer: (a)
</div> <br>

##### Q. If all the prime numbers greater than or equal to 2 and less than 100 are multiplied, the product will have how many consecutive zeroes at the end? 
<pre>(a) 0   (b) 1    (c) 2   (d) 5</pre>

Explanation:<br>
<div class="Exp">

For number of zeroes at the end, we need to notice numbers 2 and 5 at units place in prime numbers below 100. That’s because only these numbers/digits can produce zero at the end. 

We have just 1 such pair of 2 and 5. These are the prime numbers 2 and 5. Hence, we will get only 1 zero at the end.

Answer: (b)
</div> <br>


## Type 3

##### Q. If a number $44569^{22573}$ is divided by 10, then what will be the remainder?
<pre>(a) 1   (b) 0    (c) 6   (d) 9</pre>

Explanation:<br>
<div class="Exp">

On dividing $9^{odd \hspace{1ex} power}$ by 10, we get 9 as the remainder. <br>
On dividing $9^{even \hspace{1ex} power}$ by 10, we get 1 as the remainder.

22573 is odd. <br>
So, if $44569^{22573}$ is divided by 10, then it will give 9 as the remainder.

Answer: (d)
</div> <br>
