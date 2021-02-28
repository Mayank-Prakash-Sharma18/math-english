---
title: Remainder Theorems
linktitle: Remainder Theorems
toc: true
type: docs
date: "2021-02-26T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 2. Divisibility & Remainder
    weight: 27

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 27
---

## Concept of Remainder

If a number A is divided by B, then A is the dividend and B is the divisor. There are two possibilities: 

* Either a remainder is left
* Or No remainder is left, i.e. Remainder = 0 (means it completely divides)

Let's see both of these cases in more detail. 

### Remainder is left

Here, Dividend = Divisor × Quotient + Remainder

In other words if on dividing A by B, we get a remainder of r, then we can write A as follows: <br>
A = qB + r <br>
(where q is the quotient, which is a whole number, i.e. it’s value can be 0, 1, 2, 3 ….) <br><br>
E.g. a number when divided by 5 leaves a remainder of 2, can be written as (5q + 2)

{{% alert note %}}
If the dividend is less than divisor (i.e. A < B), then the remainder is the dividend itself. Quotient in such cases will be zero. <br><br>
E.g. when 3 divided by 5, the remainder is 3 itself. And the quotient of this division is 0.
{{% /alert %}}

{{% alert note %}}
If the remainder is greater than divisor (i.e. r > B), then it means that the division is not complete. We need to perform the division till we get a remainder less than the divisor. 

E.g. if we divide 24 by 7, then we can write 24 as follows: <br><br>
24 = 2 × 7 + 10 (here the remainder 10 is greater than the divisor 7, so the division is not complete) <br><br>
24 = 3 × 7 + 3 (here the remainder 3 is less than the divisor 7, so the division is complete)
{{% /alert %}}


### No remainder is left

Here, Dividend = Divisor × Quotient 

If remainder is zero, then: <br>
A = qB <br> <br>
E.g. a number which is completely divisible by 5, i.e. a number which is a multiple of 5, can be written as 5q

{{% alert note %}}
We know that, if on dividing A by B, we get a remainder of r, then: <br>
A = qB + r 

* It means the number A – r, i.e. qB will be completely divisible by B. It will be the largest multiple of B which is less than or equal to A. <br><br>
E.g. on dividing 36 by 5 we get a remainder of 1. So, 36 – 1, i.e. 35 will be completely divisible by 5. So, 35 is the largest multiple of 5 which is less than 36. 

* Also, A + (B - r), i.e. (q + 1) B will be completely divisible by B. It will be the smallest multiple of B which is more than or equal to A. <br><br>
E.g. on dividing 36 by 5 we get a remainder of 1. So, 36 + (5 – 1), i.e. 40 will be completely divisible by 5. So, 40 is the smallest multiple of 5 which is more than 36. 
{{% /alert %}}


## Properties of remainders

### Addition and Remainders

If two dividends A and B, when divided by a divisor Z, leaves remainders $r_1$ and $r_2$ respectively, then <br>
the remainder when A + B is divided by Z is $r_1 + r_2$.

E.g. Remainder [$\frac{18}{5}$] = 3 and Remainder [$\frac{31}{5}$] = 1 <br><br>
∴ Remainder [$\frac{18 + 31}{5}$] = 3 + 1 = 4 

{{% alert note %}}
We know that the remainder must be less than the divisor (i.e. it can attain any value from 0 to Z-1). 

If we get a remainder that is equal to or higher than the divisor, we just need to divide that value with the divisor again and find the real remainder. 

E.g. Remainder [$\frac{18}{5}$] = 3 and Remainder [$\frac{32}{5}$] = 2 <br><br>
∴ Remainder [$\frac{18 + 32}{5}$] = 3 + 2 = 5 = 0 <br><br>
(remainder 5 is the same as the divisor 5, so we divided 5 by 5 again and got the remainder 0.)
{{% /alert %}}

### Subtraction and Remainders

If two dividends A and B, when divided by a divisor Z, leaves remainders $r_1$ and $r_2$ respectively, then <br>
the remainder when A - B is divided by Z is $r_1 - r_2$.

E.g. Remainder [$\frac{17}{5}$] = 2 and Remainder [$\frac{34}{5}$] = 4 <br><br>
∴ Remainder [$\frac{34 - 17}{5}$] = 4 - 2 = 2 

{{% alert note %}}
We know that the remainder must be less than the divisor (i.e. it can attain any value from 0 to Z-1). If we get a remainder that is in the negative, then we need to add the divisor to the remainder. 

E.g. Remainder [$\frac{18}{5}$] = 3 and Remainder [$\frac{31}{5}$] = 1 <br><br>
∴ Remainder [$\frac{31 - 18}{5}$] = 1 - 3 = -2 = 5 – 2 = 3  <br><br>
(remainder -2 is negative, so we added the divisor 5 to it, to get the positive remainder 3.)
{{% /alert %}}
 
### Multiplication and Remainders

If two dividends A and B, when divided by a divisor Z, leaves remainders $r_1$ and $r_2$ respectively, then <br> 
the remainder when A × B is divided by Z is $r_1 × r_2$.

E.g. Remainder [$\frac{18}{5}$] = 3 and Remainder [$\frac{31}{5}$] = 1 <br><br>
∴ Remainder [$\frac{31 × 18}{5}$] = 1 × 3 = 3

{{% alert note %}}
We know that the remainder must be less than the divisor (i.e. it can attain any value from 0 to Z-1). If we get a remainder that is equal to or higher than the divisor, we just need to divide that value with the divisor again and find the real remainder. 

E.g. Remainder [$\frac{17}{5}$] = 2 and Remainder [$\frac{34}{5}$] = 4 <br><br>
∴ Remainder [$\frac{34 × 17}{5}$] = 4 × 2 = 8 = 3  <br><br>
(8 is more than 5, so we divided 8 by 5 again and got the remainder 3.)
{{% /alert %}}

### Powers/Exponents and Remainders

If a dividend A on division by a divisor Z, leaves a remainder r, then <br>
the remainder when An is divided by Z is $r^n$.

E.g. Remainder [$\frac{17}{5}$] = 2 <br><br>
∴ Remainder [$\frac{17^2}{5}$] = $2^2$ = 4 <br><br>

E.g. Remainder [$\frac{18}{5}$] = 3 <br><br>
∴ Remainder [$\frac{18^3}{5}$] = $3^3$ = 27 = 2 <br><br>
(27 is more than 5, so we divided 27 by 5 again and got the remainder 2.) 


## Concept of Negative Remainder

Remainder can be zero or some positive number less than the divisor. It can never be negative. 

But sometimes we encounter negative remainders. Let’s see what they mean and how to handle them with the help of an example.

If 11 is the number being divided and 3 is the divisor, then we can write 11 as: <br>
11 = 3 × 3 + 2  (here 2 is the remainder) <br>
Or 11 = 3 × 4 – 1  (here -1 is the remainder)

Hence -1 is the corresponding negative remainder of the original remainder 2, when the divisor is 3.

To convert any negative remainder into non-negative remainder, just add the divisor to it. <br>
So, original non-negative remainder = negative remainder + divisor = -1 + 3 = 2

Let us generalize this concept: 

If two dividends A and B, when divided by a divisor Z, leaves remainders $r_1$ and $r_2$ respectively, then <br>
the remainder when A - B is divided by Z is $r_1 - r_2$.

Let's have a look at one more example:

Remainder [$\frac{23}{4}$] = 3 and Remainder [$\frac{41}{4}$] = 1 <br><br>
∴ Remainder [$\frac{41 - 23}{4}$] = 1 - 3 = -2  <br><br>
So, original non-negative remainder = negative remainder + divisor = -2 + 4 = 2

<br><hr><br>

## Finding remainder of an expression

There are two methods to find out the remainder of any expression.
*	Cyclicity Method / Pattern Method
* Remainder Theorem method

### Cyclicity method / Pattern Method

We saw earlier that the last digit of the powers of a number repeat in a certain pattern. Similarly,  the remainders of powers of a number also follow a certain pattern of repetition. If we can identify this pattern, we can find out the remainder of any given division.

Let us find the pattern that remainders follow when various powers of 2 are divided by 5.

Remainder [$\frac{2}{5}$] = 2 <br><br>
Remainder [$\frac{2^2}{5}$] = 4 <br><br>
Remainder [$\frac{2^3}{5}$] = 3 <br><br>
Remainder [$\frac{2^4}{5}$] = 1 <br><br>
Remainder [$\frac{2^5}{5}$] = 2 <br><br>
Remainder [$\frac{2^6}{5}$] = 4 <br><br>

So, we can see the pattern of repetition: 2, 4, 3, 1  (here remainder repeats in a cycle of 4)

So, how can we use this information. Let’s see.

We know that the cyclicity when 2 is divided by 5 is 4. 

It means that if the exponent of 2 is any multiple of 4, then the remainder should be 1. So, if the exponent is in the form: <br>
4k + 0, then remainder is 1 <br>
4k + 1, then remainder is 2 <br>
4k + 2, then remainder is 4 <br>
4k + 3, then remainder is 3 <br>
(where k is any whole number, k = 0, 1, 2, 3...)

If we have to find the remainder when $2^{34}$ is divided by 5, we just need to divide 34 by 4 (cyclicity when 2 is divided by 5). The remainder we get is 2 (i.e. 4k + 2). <br>
It means that $2^{34}$ will give the same remainder as $2^2$, i.e. 4. 

### Remainder Theorem Method

Let p(x) be a polynomial in x. <br>
If p(x) is divided by (x − a). then the remainder will be p(a).

For example, if $x^2 + 3x + 5$ is divided by x – 2, the remainder will be: <br>
f (2) = $2^2$ + (3 × 2) + 5 = 15 

If $x^2 + 3x + 5$ is divided by x + 2, the remainder will be: <br>
f (-2) = $(-2)^2$ + (3 × -2) + 5 = 3 

{{% alert note %}}
A polynomial function in x is a function where only positive integer exponents of x will appear. E.g. quadratic equation, cubic equation, etc. 
{{% /alert %}}

Earlier we used the Pattern method to find the remainder when $2^{34}$ is divided by 5. Let us solve it using Remainder Theorem Method. 

Since the numerator (i.e. dividend) is in terms of powers of 2, we need to express the denominator also in terms of powers of 2. We can write 5 as 4 + 1 = $2^2$ + 1. <br>
Now we need to write the numerator in terms of $2^2 × 2^{34}$ = $(2^2)^{17}$ <br>
Let $2^2$ be x. <br>
So, basically we need to find the remainder when $x^{17}$ is divided by (x + 1). <br>
As per the remainder theorem, the required remainder = f (-1) = $(-1)^{17}$ = -1 = -1 + 5 = 4

### Remainder Theorem Method Vs. Pattern Method

We can use the remainder theorem in cases where the denominator (i.e., the divisor) can be written in the form of one more or one less than some power of the base in the numerator. 

For example: <br>
In case of $\frac{2^{24}}{3}$, $\frac{2^{24}}{5}$ and $\frac{2^{24}}{7}$, the base in the numerator is 2. 

$\frac{2^{24}}{3}$ – here the denominator can be written as 2 + 1 <br><br>
$\frac{2^{24}}{5}$ - here the denominator can be written as $2^2$ + 1 <br><br>
$\frac{2^{24}}{7}$ – here the denominator can be written as $2^3$ - 1 <br><br>

In cases where it is not possible to write the denominator and numerator in this manner, we should rather apply the Pattern Method (rather than the remainder theorem method).

<br><hr><br>


## Generalizations based on Remainder Theorem 

### Generalization 1

$\frac{(p + 1)^n}{p}$ will always give 1 as the remainder for all natural values of p and n.

### Generalization 2

$\frac{p^n}{(p + 1)}$ will always give 1 as the remainder, when n is even.

### Generalization 3

$\frac{p^n}{(p + 1)}$ will always give p as the remainder, when n is odd.


## Remainder properties of Prime numbers 

### Property 1

For any prime p>3, $p^2$ − 1 is a multiple of 24.

E.g. if p = 5, then $5^2$ − 1 = 24
If p = 11, then $11^2$ − 1 = 120 (a multiple of 24)

### Property 2: Fermat's theorem

Let ‘x' and ‘y' be any two prime numbers.

Then $x^y$ − x is always divisible by y. 

E.g. $2^3$ − 2 = 6 is divisible by 3. <br>
$2^5$ − 2 = 30 is divisible by 5. <br>
$3^3$ − 3 = 24 is divisible by 3. 

### Property 3: Fermat's little theorem

Let ‘x' and ‘y' be any two relatively prime numbers (where ‘y’ is a prime number)

Then Remainder [$\frac{x^{y - 1}}{y}$] is 1. 

E.g. if x = 10 and y = 7 <br>
Remainder [$\frac{10^6}{7}$] = 1

Let us double check it. <br>
Remainder [$\frac{10^6}{7}$] = Remainder [$\frac{3^6}{7}$] = Remainder [$\frac{9^3}{7}$] = Remainder [$\frac{2^3}{7}$] = Remainder [$\frac{8}{7}$] = 1

### Property 4: Wilson's theorem

Let ‘p’ be a prime number, then: 

Remainder [$\frac{(p − 1)!}{p}$] is (p − 1).

Remainder [$\frac{(p − 1)! + 1}{p}$] is always zero.

E.g. Let p = 5, then: <br><br>
Remainder [$\frac{(5 − 1)!}{5}$], i.e. Remainder [$\frac{4!}{5}$] is (5 − 1) = 4. <br><br>
Remainder [$\frac{(5 − 1)! + 1}{5}$], i.e. Remainder [$\frac{4! + 1}{5}$] is zero. 


## Remainder properties of Composite numbers

### Property 1: Wilson's theorem

If n is a composite number more than 4, then (n - 1)! will be divisible by n.

E.g. if n = 6, then (6 – 1)! = 5! = 120 is divisible by 6. <br>
If n = 8, then (8 – 1)! = 7! = 5040 is divisible by 8.

{{% alert note %}}
4 is the smallest composite number.
{{% /alert %}}