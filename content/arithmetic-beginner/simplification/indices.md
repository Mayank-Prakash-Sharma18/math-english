---
title: Indices
linktitle: Indices 
toc: true
type: docs
date: "2021-07-17T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 3. Indices & Surds
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

## What are Indices?

If we multiply a number 'a' to itself n times, then we get: <br>
a × a × a ...n times = $a^n$ <br>
Here, a is the base, and n is the power/index/exponent. <br>
We read it as, "a to the power of n"

For example, 4 × 4 × 4 = $4^3$ (read as 4 to the power of 3)

The value of a and n can be positive, negative, zero, or fractions. 


## Rules of Indices

Rules or Laws of Indices are the basic rules/formulae that we use to deal with numbers having powers/indices. 

A student is expected to know the following just as well as he knows addition, multiplication, BODMAS rules. They are considered essential for a person to do basic calculations. 

### First set of Rules

$a^0$ = 1 (where a ≠ 0) <br>
For example: <br>
$3^0$ = 1

$a^1$ = a <br>
For example: <br>
$3^1$ = 3

#### Negative Indices

$a^{-n}$ = $\frac{1}{a^n}$

#### Fractional Indices

$a^\frac{p}{q}$ = $\sqrt[q]{a^p}$

$\sqrt[n]{a}$ = $a^\frac{1}{n}$


### Second set of Rules

Let us first of all see the cases wherein the ***base is the same*** (powers/indices may or may not be the same).

#### Addition of Indices

$a^n$ × $a^m$ = $a^{n + m}$ <br>
For example: <br>
$2^3$ × $2^4$ = $2^{3 + 4}$ = $2^7$

{{% alert note %}}
$\sqrt{a} × \sqrt{a}$ = $a^{\frac{1}{2}}$ × $a^{\frac{1}{2}}$ = $a^{\frac{1}{2} + \frac{1}{2}}$ = $a^1$ = a
{{% /alert %}}

#### Subtraction of Indices

$a^n$ ÷ $a^m$ = $a^{n - m}$ <br>
For example: <br>
$2^4$ ÷ $2^3$ = $2^{4 - 3}$ = $2^1$ = 2

#### Multiplication of Indices

$(a^n)^m$ = $a^{nm}$ <br>
For example: <br>
$(2^3)^5$ = $2^{3 × 5}$ = $2^{15}$


### Third set of Rules

Let us see the cases wherein the bases are different, but ***indices are the same***. 

#### Rule 1

$(ab)^n$ = $a^n$ × $b^n$ <br>
For example: <br>
$(2 × 3)^4$ = $2^4$ × $3^4$

{{% alert note %}}
$\sqrt{ab} = \sqrt{a} × \sqrt{b}$

$\sqrt[p]{ab} = \sqrt[p]{a} × \sqrt[p]{b}$
{{% /alert %}}

#### Rule 2

$(\frac{a}{b})^n$ = $\frac{a^n}{b^n}$<br>
For example: <br>
$(\frac{2}{3})^4$ = $\frac{2^4}{3^4}$<br>

{{% alert note %}}
$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$

$\sqrt[p]{\frac{a}{b}} = \frac{\sqrt[p]{a}}{\sqrt[p]{b}}$
{{% /alert %}}

### Fourth set of Rules

#### Rule 1

If two numbers are equal, and their bases are also equal, then their powers will be equal too. (given that the base is not 0 or ±1)<br>
So, if $a^n$ = $a^m$ (where a ≠ 0 & a ≠ ±1), then n = m <br>
For example, if $3^n$ = $3^5$, then n = 5

#### Rule 2

If two numbers are equal, and their powers are also equal, then two cases may arise (given that the power is not 0): 

* Case I: If the power is an odd number, then the bases will be equal too. <br>
So, if $a^n$ = $b^n$ (where n ≠ 0), then a = b <br>
For example, if $a^7$ = $3^7$, then a = 3

* Case II: If the power is an even number, then the bases will be numerically equal too, but their signs may differ. <br>
So, if $a^n$ = $b^n$ (where n ≠ 0), then a = ±b <br>
For example, if $a^6$ = $3^6$, then a = ±3

{{% alert note %}}
If power is 0, then we cannot determine the relation between the bases a and b. That's because any base raised to the power of 0 gives the same value of 1. <br>
For example, $3^0$ = 1; $4^0$ = 1 etc. 
{{% /alert %}}


## Complex looking Indices

So, you know what indices are and what are the basic rules that we use to simplify expressions having indices. However, there are many expressions that look really weird and complex. Let's have a look at a few of such expressions, and how to deal with them.  

### Nested Indices

Sometimes, we will encounter multiple layers of powers/indices. For example, $(a^n)^m$. We read it as - "a raised to the power n, whole (raised) to the power m".

In such cases, we first solve the expression inside the brackets. Then we raise the resultant to the power which is outside the brackets. That is, we move from inside to outside. <br>
For example, $(2^4)^3$ = $16^3$ = 4,096

{{% alert note %}}
Note that, $(a^n)^m$ = $a^{nm}$ $\hspace{1ex}$ (it's not equal to $a^{n^m}$)<br>
So, we could have solved the above as follows: <br>
$(2^4)^3 = 2^{4 × 3} = 2^{12}$ = 4,096
{{% /alert %}}


### Indices having Indices

Sometimes, we will encounter expressions wherein the powers/indices are not simple numbers. Rather powers/indices are themselves having powers/indices. For example, $a^{n^m}$. Here the index/power is $n^m$.

In such cases, we first solve the expression at the top. That is, we move from top to bottom. <br>
For example, $2^{3^2}$ = $2^9$ = 512

<br><hr><br>

## Types of questions on Indices

You will come across the following types of questions in the chapter of Indices:

* Simplification
* Solving for an unknown variable
* Comparison of numbers

Let's have a look at a few examples to get a better idea. 

### Type 1: Simplification

Complex expressions will be provided to you with different bases and powers. You will have to simplify them using the rules mentioned above. 

##### Q. Simplify and find the value of the following expression: <br>
$(0.04)^{-1.5}$

Explanation:<br>
<div class="Exp">

We know that: $a^{-n}$ = $\frac{1}{a^n}$

So, $(0.04)^{-1.5}$ = $(\frac{1}{0.04})^{1.5}$ = $(\frac{100}{4})^{1.5}$ = $25^{1.5}$ = $(5^2)^{1.5}$ = $(5^2)^{\frac{3}{2}}$ = $(5)^{2 × \frac{3}{2}}$ = $5^3$ = 125 
</div> <br>


### Type 2: Solving for an unknown variable

Some equation will be provided to you. You will have to solve that equation for the unknown base or power. 

##### Q. If $1024^{x - 3}$ = $16^x$, then find the value of x. 

Explanation:<br>
<div class="Exp">

$1024^{x - 3}$ = $16^x$ <br>
or $(2^{10})^{x - 3}$ = $(2^4)^x$ <br>
or $2^{10x - 30}$ = $2^{4x}$ <br>

As the base is the same, so powers must be too. <br>
That is, 10x - 30 = 4x <br>
or 6x = 30 <br>
or x = 5
</div> <br>


### Type 3: Comparison of numbers

In such type of questions, you will be provided a few expressions with powers. You will be asked to compare the values of these expressions and then:
* find the smallest or the largest expression, or
* arrange the expressions in ascending or descending order of their values. 

##### Q. Arrange the following numbers in ascending order. <br>
$125^8$, $25^{12}$, $625^5$

Explanation:<br>
<div class="Exp">

We can express the given numbers with base 5. 

$125^8$ = $(5^3)^8$ = $5^{3 × 8}$ = $5^{24}$ <br>
$25^{12}$ = $(5^2)^{12}$ = $5^{2 × 12}$ = $5^{24}$ <br>
$625^5$ = $(5^4)^5$ = $5^{4 × 5}$ = $5^{20}$

Now, as the bases of all the above expressions are the same, we just need to compare their powers. 

So, the numbers in ascending order will be: $5^{20}$ < $5^{24}$ = $5^{24}$ <br>
or $625^5$ < $25^{12}$ = $125^8$
</div> <br>

##### Q. Find the smallest number from amongst the following numbers. <br>
$2^{40}$, $4^{18}$, $8^{12}$, $3^{21}$ <br>
(a) $2^{40}$ <br>
(b) $4^{18}$ <br>
(c) $8^{12}$ <br>
(d) $3^{21}$

Explanation:<br>
<div class="Exp">

The given numbers are: $2^{40}$, $4^{18}$, $8^{12}$, and $3^{21}$. <br>
We can also write them as: $2^{40}$, $2^{36}$, $2^{36}$, and $3^{21}$. (as 4 = $2^2$, and 8 = $2^3$)

So, we basically need to find the smallest one from among $2^{36}$, and $3^{21}$. As we cannot have two correct answers, it must be $3^{21}$. 

Answer: (d)

{{% alert note %}}
Sometimes, in Aptitude exams you need not even solve the entire question. This saves you some extra seconds and it eventually makes all the difference. But if you are a typical Maths student, this incomplete answer may cause you to feel a mild Zeigarnik effect. So, here’s the rest of the solution: 

We can rewrite $2^{36}$ and $3^{21}$ as: <br>
$2^{12}$ and $3^7$ <br>
or, 4096 > 2187

Hence, $3^{21}$ is the smallest number. 
{{% /alert %}}
</div> <br>

