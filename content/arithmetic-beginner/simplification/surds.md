---
title: Surds
linktitle: Surds 
toc: true
type: docs
date: "2021-07-17T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 3. Indices & Surds
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

## What are Surds?

Surds are a type of irrational numbers. 

All surds are irrational numbers, but the vice-versa is not true. That is, all irrational numbers are not surds. For example, π, e etc. are irrational numbers, but not surds. 
<img src="../../../media/simplification/simplification-8.png" alt="Simplification" style="width:36%;height:36%;">
So, we can say that Surds are a subset of Irrational numbers. 

{{% alert note %}}
Rational numbers - the numbers that can be written in the form of p/q, where p and q are integers and q ≠ 0. <br>
All other numbers are irrational numbers.
{{% /alert %}}


## Types of Surds

$\sqrt[n]{a}$ is surd of order n, given that it is an irrational number (a is a rational number, and n is a positive integer).

Let's see a few examples.

* Surd of order 2, i.e. when n = 2 (also called Quadratic Surds). For example, $\sqrt{5}$, 6$\sqrt{3}$, etc.
* Surd of order 3, i.e. when n = 3. For example, $\sqrt[3]{5}$, 5$\sqrt[3]{7}$ etc.
* and so on ....

{{% alert note %}}
Expressions like $\sqrt{4}$ (= 2), $\sqrt[3]{27}$ (= 3) are not surds, as they are rational numbers. 
{{% /alert %}}


## Quadratic Surds

Amongst surds, we will mostly be dealing with Quadratic Surds, i.e. the surds having square root terms (not any higher roots), i.e. $\sqrt{a}$, where a is a rational number, but not a perfect square. 

We will also deal with expressions having a mix of rational numbers and surds. For example, a + $\sqrt{b}$, a + $\sqrt{b}$ + $\sqrt{c}$ etc. 


### Conjugate of a Surd Expression

If a surd expression is of the form a + $\sqrt{b}$, then its conjugate will be ± (a - $\sqrt{b}$)

Product of a surd expression and its conjugate is always a rational number. 


## Rules of Surds

Now, let us have a look at the rules of surds, that will help us simplify and solve the expressions involving surds. 

### Rule 1

$\sqrt[n]{a}$ = $a^\frac{1}{n}$

$\sqrt[m]{\sqrt[n]{a}}$ = $\sqrt[nm]{a}$ = $\sqrt{a^\frac{1}{nm}}$

$(\sqrt[n]{a})^m$ = $\sqrt[n]{a^m}$

{{% alert note %}}
$(\sqrt[n]{a})^n$ = $\sqrt[n]{a^n}$ = a
{{% /alert %}}

### Rule 2

$\sqrt{a} × \sqrt{b} = \sqrt{ab}$

$\frac{\sqrt{a}}{\sqrt{b}} = \sqrt{\frac{a}{b}}$

### Rule 3

$\sqrt[n]{a} × \sqrt[n]{b} = \sqrt[n]{ab}$

$\frac{\sqrt[n]{a}}{\sqrt[n]{b}} = \sqrt[n]{\frac{a}{b}}$

### Rule 4: If two quadratic surd expressions are equal

If a + $\sqrt{b}$ = c + $\sqrt{d}$, then: <br>
a = c (i.e. rational parts of the quadratic surds expressions will be equal) <br>
b = d (i.e. irrational parts of the quadratic surds expressions will be equal)

{{% alert note %}}
If a + $\sqrt{b}$ = $\sqrt{d}$, then a = 0 and b = d  <br>
If a + $\sqrt{b}$ = c, then a = c and b = 0 
{{% /alert %}}

### Rule 5

$\sqrt{a . \sqrt{a . \sqrt{a \hspace{1ex}...n \hspace{1ex} times}}}$ = $a^{(1 - \frac{1}{2^n})}$

{{% alert note %}}
So, when n = ∞, <br>
$\sqrt{a . \sqrt{a . \sqrt{a \hspace{1ex}...∞}}}$ = a
{{% /alert %}}

### Rule 6

If, $\sqrt{a + \sqrt{a + \sqrt{a \hspace{1ex}...∞}}}$ = p, then p(p - 1) = a


## Rationalization of a Surd

Sometimes we get surds in denominator of fractions. For example, $\frac{1}{a + \sqrt{b}}$

It's hard to work on. So, we rationalize the surd, which is the process of converting the surd in the denominator into a rational number, without changing the value of the fraction. 

To do so, we multiply both the numerator and denominator with the conjugate of the surd in the denominator. So, we will multiply numerator and denominator of $\frac{1}{a + \sqrt{b}}$ by ± (a - $\sqrt{b}$), i.e. either by (a - $\sqrt{b}$) or (- a + $\sqrt{b}$)

{{% alert note %}}
If the surd is of the type $\frac{1}{a + \sqrt{b} + \sqrt{c}}$, then we will have to repeat the process twice. 
{{% /alert %}}

It will become more clear with an example. 

##### Q. Rationalize the denominator of the following surd: <br>
$\frac{1}{3 - \sqrt{11}}$

Explanation:<br>
<div class="Exp">

The denominator of the given fraction expression is $3 - \sqrt{11}$. It's conjugates are $3 + \sqrt{11}$ and $- 3 - \sqrt{11}$. 

Let's take $3 + \sqrt{11}$, and multiply both the numerator and denominator of the given fraction expression by it. 

$\frac{1}{3 - \sqrt{11}}$ × $\frac{3 + \sqrt{11}}{3 + \sqrt{11}}$ = $\frac{3 + \sqrt{11}}{3^2 - 11}$ = $\frac{3 + \sqrt{11}}{9 - 11}$ = $\frac{3 + \sqrt{11}}{(-2)}$
</div> <br>


## Finding Square Root of a Surd

The square root of a surd of the type a + $\sqrt{b}$, will be of the form $\sqrt{x}$ + $\sqrt{y}$.

Let's see a few methods that we can utilize to find the square root of a surd of the type a + $\sqrt{b}$.

### Method 1

We can just equate the following: <br>

a + $\sqrt{b}$ = $(\sqrt{x}$ + $\sqrt{y})^2$

Solve for x and y. 

Note that in any equation having both rational and irrational terms, the rational parts on the two sides are equal, and the irrational parts on the two sides are equal too. 

### Method 2

Write the given surd in the form of $(\sqrt{x}$ + $\sqrt{y})^2$ or $(\sqrt{x}$ - $\sqrt{y})^2$. 

If we can do so, then it's obvious that the square root of the given surd is ($\sqrt{x}$ + $\sqrt{y}$) or  ($\sqrt{x}$ - $\sqrt{y}$) respectively. 

{{% alert note %}}
We will write surds of the type a + $\sqrt{b}$, i.e. whose irrational part is positive, as $(\sqrt{x}$ + $\sqrt{y})^2$. <br>
We will write surds of the type a - $\sqrt{b}$, i.e. whose irrational part is negative, as $(\sqrt{x}$ - $\sqrt{y})^2$.
{{% /alert %}}

It will become more clear with an example. 

##### Q. Find the positive square root of the following surd: <br>
24 + 4$\sqrt{11}$

Explanation:<br>
<div class="Exp">

As the irrational part of the given surd is positive, we will try to write in the form of $(\sqrt{x}$ + $\sqrt{y})^2$.

Now, $(\sqrt{x}$ + $\sqrt{y})^2$ = $x^2 + y + 2x\sqrt{y}$ <br>
We can see that the coefficient of the irrational term is 2. So, even in our surd we will keep the coefficient of the irrational term as 2. 

So, 24 + 4$\sqrt{11}$ = 24 + 2$\sqrt{4 × 11}$ = 24 + 2$\sqrt{44}$

Now, we need to find two numbers m and n, such that:
* their product is the number inside the square root, i.e. 44.
* their sum is the rational part of the given expression, i.e. 24

Two numbers that satisfy the above two conditions in our case are: 2 and 22. 

So, 24 + 2$\sqrt{44}$ = 22 + 2 + 2$\sqrt{22 × 2}$ = $(\sqrt{22} + \sqrt{2})^2$

Hence, the positive square root of 24 + 4$\sqrt{11}$ is: <br>
$\sqrt{22} + \sqrt{2}$ = $\sqrt{2} (\sqrt{11} + 1)$
</div> <br>


## Comparison of Surds 

Sometimes we may be required to compare some surds. in order to:
* Find the surd having the largest/lowest value.
* Arrange them in ascending or descending order. 

To do so, we follow the following steps:

* ***Step 1***: We subtract the rational parts. Then compare the rest. 

* ***Step 2***: If the things are still not clear, then we square the new surds and subtract the rational parts again. In most of the cases, we can easily compare the surds now. 

However, if we cannot, then we will square them, and subtract the rational parts again. We will repeat this process till we can compare their values with certainity. 

Let's see an example.

##### Q. Which of the following surds is larger? <br>
3 + $\sqrt{22}$ and 4 + $\sqrt{14}$

Explanation:<br>
<div class="Exp">

If we try to find the approximate values of the two surds, then:
* 3 + $\sqrt{22}$ = 3 + 4.something = 7.something
* 4 + $\sqrt{14}$ = 4 + 3.something = 7.something

So, their values are pretty close. 

Let us remove the common rational part. If we subtract 3 from both the surds, then we just need to compare: $\sqrt{22}$ and 1 + $\sqrt{14}$ 

As things are still not very clear, we can square both of them. We will get:
* $(\sqrt{22})^2$ = 22
* $(1 + \sqrt{14})^2$ = 1 + 14 + 2$\sqrt{14}$ = 15 + 2$\sqrt{14}$

Let us remove the common rational part again. If we subtract 15 from both the surds, then we just need to compare: 7 and 2$\sqrt{14}$ 

As things are still not very clear, we can square both of them again. We will get:
* $7^2$ = 49
* $(2\sqrt{14})^2$ = 4 × 14 = 56 

So, 4 + $\sqrt{14}$ is the larger of the two surds. 
</div> <br>

