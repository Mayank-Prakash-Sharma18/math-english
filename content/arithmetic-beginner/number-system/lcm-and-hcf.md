---
title: LCM and HCF
linktitle: LCM and HCF
toc: true
type: docs
date: "2021-02-27T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 3. LCM & HCF
    weight: 33

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 33
---

## What is HCF?

HCF (Highest common factor) or GCD (Greatest common divisor) is the largest possible number which can exactly divide each of the given numbers in the set.

That is, it is the largest possible factor of the given set of numbers.

If a set of numbers has HCF of h, then the numbers will be: <br>
ha, hb, hc, ..... <br>
(a, b, c, ... are co-prime numbers)

## What is LCM?

LCM (Least common multiple) is the smallest possible number which is divisible by each of the given numbers in the set (i.e. leaves no remainder).

That is, it is the smallest possible multiple of each of the given numbers.

{{% alert note %}}
HCF will be lesser than or equal to the least of the numbers in the set. <br>
LCM will be greater than or equal to the greatest of the numbers in the set.
{{% /alert %}}


## Finding LCM and HCF

We can use two methods to find LCM and HCF. Let's learn them both. You can use whichever appeals to you more. 

### Prime factorization method

In Prime factorization method, we first of all find the prime factors of the given numbers.

LCM = product of the maximum power of the prime factors that occurred in ANY of the given numbers.

HCF = product of the maximum power of the prime factors that occurred in ALL of the given numbers.

##### Q. Find the LCM and HCF of 99, 108 and 135.

Explanation:<br>
<div class="Exp">

99 = $3^2$ × 11 <br>
108 = $2^2$ × $3^3$ <br>
135 = $3^3$ × 5

∴ LCM = product of maximum power of prime factors occurring in any number = $2^2 × 3^3$ × 5 × 11 

∴ HCF = product of maximum power of prime factors occurring in all numbers = $3^2$ = 9
</div> <br>


### Division method

#### Using Division method to find HCF

* Step 1: We will apply it two numbers at a time. For example, in the set 99, 108 and 135, we can choose 99 and 108.

* Step 2: We will pick two numbers from the given set and divide the larger with the smaller. On dividing 108 by 99, we get quotient 1 and remainder 9.

* Step 3: Now we divide the divisor with the remainder, i.e. 99 by 9, we get remainder 0. <br><br>
We will repeat this process of dividing the preceding number by the remainder (i.e. Step 3) until we get remainder zero. 

* Step 4: The last divisor will be the required H.C.F., i.e. 9. So, H.C.F. (99, 108) = 9

* Step 5 : Now we will take the H.C.F. we got in the previous step and the next number in the set (i.e. 9 and 135) and follow the Steps 1-4 to find their H.C.F. and so on. <br>
On dividing 135 by 9, we get remainder zero. So, H.C.F. (9, 135) = 9 <br>
Hence, H.C.F. (99, 108, 135) = 9

#### Using Division method to find LCM

Let us have a set of numbers 99, 108 and 135.

* Step 1: Find the number that divides at least 2 of the numbers in the set (say 3) and divide all the numbers in the set with it. So, we will divide 99, 108 and 135 by 3. 

* Step 2: Quotient and non-divisible numbers will carry forward as it is. After division with 3, we are left with: 33, 36, 45 

* Step 3: We will keep on repeating steps 1-2, till we get a set of numbers in which no two numbers are divisible by any other number but 1. <br>
Dividing 33, 36, 45 by 3 again, we get: 11, 12, 15 <br>
Dividing 11, 12, 15 by 3 again, we get: 11, 4, 5 

* Step 4: The product of all the divisors till now (i..e in each step) and all the undivided numbers will be the required L.C.M.  <br>
So. L.C.M. (99, 108, 135) = 3 × 3 × 3 × 11 × 4 × 5 = $2^2 × 3^3$ × 5 × 11

<br><hr><br>

## LCM and HCF of fractions

Steps for finding LCM and HCF of fractions:

* Step 1:  Reduce each fraction to its simplest form (i.e., cancel out any common factors between the denominator and numerator) 

* Step 2: Apply the appropriate formula for HCF or LCM. 

LCM of fractions = $\frac{LCM \hspace{1ex} of \hspace{1ex} numerators}{HCF \hspace{1ex} of \hspace{1ex} denominators}$ <br><br>
E.g. LCM of 2/3, 4/5 and 5/8 = $\frac{LCM \hspace{1ex} (2, 4, 5)}{HCF \hspace{1ex} (3, 5, 8)}$ = 20/1 = 20

HCF of fractions = $\frac{HCF \hspace{1ex} of \hspace{1ex} numerators}{LCM \hspace{1ex} of \hspace{1ex} denominators}$ <br><br>
E.g. HCF of 2/3, 4/5 and 5/8 = $\frac{HCF \hspace{1ex} (2, 4, 5)}{LCM \hspace{1ex} (3, 5, 8)}$ = 1/120


## Properties of LCM & HCF

### Property 1: LCM is a multiple of HCF

Let LCM and HCF of two numbers (x and y) be L and H respectively. <br>
Then, x = Hp and y = Hq, where p and q are two relatively prime numbers.

LCM (x, y), L = Hpq

So, LCM is a multiple of HCF

Let us consider the two numbers 12 and 27. <br>
HCF (12, 27), H = 3 <br>
x = 4 x 3, y = 9 x 3   (4 and 9 are relatively prime numbers) <br>
LCM (12, 27), L = 3 x 4 x 9 = 108  <br>
We can see that 108 is a multiple of 3. 

### Property 2: a x b = LCM (a,b) x HCF (a,b)

Product of any two numbers = Product of their LCM and HCF.

Let us consider the two numbers 12 and 27. <br>
Product of these two numbers = 12 × 27 = 324 <br>
And, LCM (12, 27) = 108 and HCF (12, 27) = 3 <br>
LCM (12, 27) x HCF (12, 27) = 108 x 3 = 324

### Property 3: HCF (a,b) is a factor of a-b

HCF of any two numbers is a factor of the difference between the numbers.

Let us consider the two numbers 12 and 27. <br>
HCF (12, 27) = 3 <br>
Difference between the numbers = 27 – 12 = 15 <br>
We can see that 3 is a factor of 15. 

