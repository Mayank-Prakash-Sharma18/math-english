---
title: Remainders of a set of multiple numbers
linktitle: Remainders of a set of multiple numbers
toc: true
type: docs
date: "2021-02-27T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 2. Divisibility & Remainder
    weight: 30

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 30
---

Sometimes we are given a remainder(s) that is/are got on:
* dividing a set of different numbers with the same divisor.
* dividing the same number with different divisors. 

Let's see the different cases that emerge in such cases and how to approach them. 

## Case 1: Common remainder (dividend is same, divisors vary)

Let us consider the case where the number being divided is the same, but divisors vary. 

If we get the same remainder r, when a number is divided by different divisors (say x, y or z), then:

The number is of the form: <br>
k (LCM of x, y and z) + r <br>
(where k is any whole number) 

When k = 0, then the number is the remainder itself (and is less than the divisor). It will be the least possible value of such a number.

##### Q. Find the highest two digit number which leaves a remainder of 3, when it is divided by 6 or 9?

Explanation:<br>
<div class="Exp">

The number will be of the form: k (LCM of 6 and 9) + 3 = 18k + 3

If k = 0; 18k + 3 = 3 <br>
If k = 1; 18k + 3 = 21 <br>
If k = 2; 18k + 3 = 39 <br>
If k = 3; 18k + 3 = 57 <br>
If k = 4; 18k + 3 = 75 <br>
If k = 5; 18k + 3 = 93 <br>
If k = 6; 18k + 3 = 111

Therefore the required two digit number = 93.
</div> <br>


## Case 2: Common Negative Remainder (dividend is same, divisors vary)

Here again, the number being divided is the same, but divisors vary. 

If we get the same negative remainder -r when a number is divided by different divisors (say x, y or z), then:

The number is of the form: <br>
k (LCM of x, y and z) - r <br>
(where k is any natural number) 

When k = 1, then we get the least possible value of such a number.

##### Q. Find the highest two digit number which leaves remainders of 3 and 6, when it is divided by 6 and 9 respectively?

Explanation:<br>
<div class="Exp">

Negative remainder = Divisor – Positive Remainder = 6 – 3 (or 9 - 6) = 3

The number will be of the form: k (LCM of 6 and 9) - 3 = 18k - 3

If k = 1; 18k - 3 = 15 <br>
If k = 2; 18k - 3 = 33 <br>
If k = 3; 18k - 3 = 51 <br>
If k = 4; 18k - 3 = 69 <br>
If k = 5; 18k - 3 = 87 <br>
If k = 6; 18k - 3 = 105

Therefore the required two digit number = 87.
</div> <br>

## Case 3: Different remainders (dividend is same, divisors vary)

Let us see the cases where the divisors, as well as the remainders (positive or negative) are different, but the number being divided is the same.

##### Q. Find the smallest single digit and double digit number which leaves remainders 3 and 8 when divided by 5 and 9 respectively.

Explanation:<br>
<div class="Exp">

Let the number be 'N'. <br>
Remainder (N/5) = 3 & Remainder (N/9) = 8 <br>
Therefore, we can write the number as, N = 5q + 3  Or N = 9p + 8 <br>
(where ‘q' and ‘p’ are quotients, and whole numbers).

So, 5q + 3 = 9p + 8 <br>
Or 5q = 9p + 5 <br>

LHS of the equation (i.e. 5q) is a multiple of 5 for any natural number value of ‘q‘. So, the RHS must be a multiple of 5 too. 

When p = 0, 9p + 5 = 5, which is multiple of 5. (It satisfies the above condition.) <br>
So, the required smallest single digit number, N = 9p + 8 = (9 × 0) + 8 = 8

When p = 5, 9p + 5 = 50, which is multiple of 5. (It satisfies the above condition.) <br>
So, the required smallest double digit number, N = 9p + 8 = (9 × 5) + 8 = 53
</div> <br>


## Case 4: Common remainder (dividends vary, divisor is same)

In this case, the numbers being divided will vary, but divisor will be the same.

If we get the same remainder r when different numbers (say x, y or z) are divided by the same divisor, then:

The largest possible divisor = HCF [(x - y) (y - z) (z - x)] OR HCF [(x - y) (y - z)]

##### Q. Find the largest divisor which divides 43, 78 and 92, leaving the same remainder in each division.

Explanation:<br>
<div class="Exp">

Required divisor = HCF [92 − 78, 78 − 43] = HCF [14, 35] = 7

We can check that Remainder [$\frac{43}{7}$] = Remainder [$\frac{78}{7}$] = Remainder [$\frac{92}{7}$] = 1
</div> <br>

## Case 5: Different remainders (dividends vary, divisor is same)

Here again, the numbers being divided will vary, but divisor will be the same.

If we get the remainders (say a, b and c) when different numbers (say x, y or z respectively) are divided by the same divisor, then:

The largest possible divisor = HCF [(x - a) (y - b) (z - c)] 

##### Q. Find the largest divisor which divides 43, 78 and 99, leaving the remainders 5, 2 and 4 respectively.

Explanation:<br>
<div class="Exp">

Required divisor = HCF [43 − 5, 78 − 2, 99 - 4] = HCF [38, 76, 95] = 19

We can check that Remainder [$\frac{43}{19}$] = 5 <br><br>
Remainder [$\frac{78}{19}$] = 2 <br><br>
Remainder [$\frac{99}{19}$] = 4
</div> <br>


