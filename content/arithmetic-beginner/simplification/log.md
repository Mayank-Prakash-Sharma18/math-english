---
title: Basics of Logarithm
linktitle: Basics of Logarithm
toc: true
type: docs
date: "2021-08-17T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 4. Logarithms
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

## What is Logarithm?

Logarithms are related to the concept of exponents/powers/indices. In fact, they are another way of writing exponents/indices/powers. 

We write logarithm as log in short. It is represented as $log_b$ a. 

{{% alert note %}}
We read $log_b$ a = p as: log base b of a is p, OR log of a with base b is p. 

For example, $log_2$ 8 = 3 can be read as: “log base 2 of 8 is 3”, or “log of 8 with base 2 is 3”.
{{% /alert %}}


## Relationship between exponents and logarithms

In general terms, $log_b$ a = p can also be written as a = $b^p$. Here, b is the base, p is the power, and a is called the argument. 
 
We can represent the relationship between b, a and p using either equation. While changing one form of equation into another, remember that base of the logarithm is the same as the base of the exponent expression. 

For example, we know that $2^3$ = 8, i.e. when we raise 2 to the power of 3, then we get 8.

In other words, we can say that we can get 8 from 2, if we multiply it 3 times, i.e. $log_2$ 8 = 3. So, it answers the question – “By what power should we raise 2 to get 8?”. The answer we get on solving a logarithm is the power. 

Let’s see one more example, $log_3$ 27 = ? 

We basically need to find out, “By what power should we raise 3 to get 27?”, or “How many times should we multiply 3 by itself to get 27?” We can see that 3 × 3 × 3 = 27. So, we need to multiply 3 three times by itself. So, $log_3$ 27 = 3. 


## Some restrictions on the values of log variables

In a logarithm, say $log_b$ a, the variables a and b cannot attain all possible values. There are some restrictions that we need to keep in mind. Let’s see them one by one. 

### Restriction on value of base of log

The base of log must be positive too, but not equal to 1. 

{{% alert note %}}
#### Why the value of base of log cannot be equal to 1?

Let’s take an example, where b = 1. <br>
Let $log_1$ 5 = p. <br>
It can also be written as 5 = $1^p$. But no matter what the value of p is, $1^p$ can never be equal to 5.
{{% /alert %}}

### Restriction on value of argument of log

The argument of log must be positive. Logarithms of negative numbers are not defined. 

$log_b$ a = p, can also be written as a = $b^p$. We already know that ‘b’ must be positive. So, it means that a will definitely be positive too. 

### No restrictions on the value of a log

If $log_b$ a = p, then p can attain any value – positive, negative or decimal. 

For example, $log_2$ 16 = 4, $log_{10}$ 0.5 = -0.3, $log_{10}$ 20 = 1.3


## Special Logarithms

The base of logarithm can attain any value (except 1). But in most of the questions you encounter, you will come across two base values more often than others. 

These are 10 and e. These two values are so common that most of the scientific calculators have dedicated buttons for them. 

### Common Logarithm

When the base of a log is 10, then we call it a common logarithm. For example, $log_{10}$ 5. 

{{% alert note %}}
This base value is so common, that it is taken as the default base value if its not mentioned explicitly. That is, log a means $log_{10}$ a. 
{{% /alert %}}

We can use it to find the number of digits in any number. We know that, $10^p$ has d digits, such that p < d ≤ (p + 1), and d is a whole number. <br>
For example, $10^{18.5}$ has 19 digits before the decimal. 

So, if we know the value of the common log of a number, then we can tell how many digits it has before the decimal. Log of $10^p$ will be: <br>
$log_{10}$ $10^p$ = p $log_{10}$ 10 = p. It means that $10^p$ has d digits, such that p < d ≤ (p + 1), and d is a whole number.<br>
For example, $log_{10}$ $10^{18.5}$ = 18.5. It means that $10^{18.5}$ has 19 digits. 

### Natural Logarithm

When the base of a log is e, then we call it a natural logarithm. For example, $log_e$ 5. 
e is called Euler's Number, and its value is about 2.71828

{{% alert note %}}
$log_e$ is also written as ln in short. So, you will often find $log_e$ a written as ln a. 
{{% /alert %}}


## Properties of Logarithm

### Property 1

$log_b$ a = $\frac{log \hspace{1ex} a}{log \hspace{1ex} b}$

{{% alert note %}}
$log_b$ b = log b/log b = 1. <br>
For example, $log_{10}$ 10 = 1, $log_e$ e = 1, $log_2$ 2 = 1, etc.

$log_b$ 1 = log 1/log b = 0/log b = 0. ($b^0$ = 1)
{{% /alert %}}

So, $log_b$ a = $\frac{1}{log_a \hspace{1ex} b}$

Also, $log_b$ a = log a/log b = (log a/log m) × (log m/log b) = $\frac{log_m \hspace{1ex} a}{log_m \hspace{1ex} b}$

### Property 2

$log_b$ (ac) = $log_b$ a + $log_b$ c

$log_b (\frac{a}{c})$ = $log_b$ a - $log_b$ c

{{% alert note %}}
However, the following would be wrong: <br>
$log_b$ (a + c) = $log_b$ a + $log_b$ c  (incorrect) <br>
$log_b$ (a + c) = $log_b$ a × $log_b$ c  (incorrect)
{{% /alert %}}

### Property 3: Power in argumnet

$log_b \hspace{1ex} a^n$ = n $log_b$ a

$log_b \hspace{1ex} \sqrt[n]{a}$ = $log_b \hspace{1ex} (a)^{1/n}$ = $\frac{1}{n}$ $log_b$ a

{{% alert note %}}
$b^{log_b \hspace{1ex} a}$ = a
{{% /alert %}}

### Property 4: Power in base

$log_{b^n}$ a = $\frac{1}{n}$ $log_b$ a

$log_{b^{1/n}}$ a = n $log_b$ a

