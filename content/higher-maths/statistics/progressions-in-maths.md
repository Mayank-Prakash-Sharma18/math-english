---
title: Progressions in Maths
linktitle: Progressions
toc: true
type: docs
date: "2021-08-23T00:00:00+01:00"
draft: false
menu:
  statistics:
    parent: 2. Progressions
    weight: 21

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 21
---

## What are Progressions in Maths?

Progression is a list of numbers that follow a particular pattern, that can be represented via a formula. 

{{% alert note %}}
Unlike any other general sequence of numbers, in case of progressions we can find the nth term using a formula. That’s what differentiates a progression from a general sequence of numbers. 
{{% /alert %}}

## Types of Progressions

There are three kinds of progressions that you will encounter in Maths. These are:
* Arithmetic Progression (AP)
* Geometric Progression (GP)
* Harmonic Progression (HP)

Let’s study them in more detail. 

## Arithmetic Progression

Arithmetic Progression is a sequence of numbers, such that there is a common difference between any two adjacent terms. 

Let the first term of an arithmetic progression be ‘a’, and the common difference be ‘d’. So, the arithmetic progression will be: <br>
a, a + d, a + 2d, a + 3d, .....

In other words, in an arithmetic progression each successive term is the sum of its previous term and a certain fixed number (called the common difference). 

For example, the following is an arithmetic progression with the first term 2, and a common difference of 3. <br>
2, 5, 8, 11, 14, 17 .....

{{% alert note %}}
The first term of an arithmetic progression, as well as the common difference can be positive, negative or zero.
{{% /alert %}} 

### Arithmetic Progression Formulae

#### Common difference 

If we have an arithmetic progression: $a_1, a_2, a_3, ..... a_{n - 1}, a_n$

Then, Common difference of the Arithmetic Progression, <br>
d = $a_2 – a_1 = a_3 - a_2 = ..... = a_n - a_{n - 1}$

* If the common difference is positive, then each subsequent term of the arithmetic series will be more than the previous one.  
* If the common difference is negative, then each subsequent term of the arithmetic series will be less than the previous one.  

#### nth Term of Arithmetic Progression

Let the first term of an arithmetic progression be ‘a’, the nth term be ‘$a_n$’, and the common difference be ‘d’.

Then the nth term, $a_n$ = a + (n - 1) d

##### Q. Find the 10th term of AP: 1, 2, 3, 4, 5 ......

Explanation:<br>
<div class="Exp">

Given, AP: 1, 2, 3, 4, 5 .....

So, a = 1, n = 10, and d = 2 - 1 = 1

We know that, nth term, $a_n$ = a + (n - 1) d <br>
So, 10th term, $a_{10}$ = 1 + (10 - 1) 1 = 1 + 9 = 10
</div> <br>

#### Sum of the terms of an Arithmetic Progression

##### Formula 1

If the first term of an arithmetic progression is ‘a’, the common difference is ‘d’ and the number of terms is ‘n’, then:

Sum of n terms of an arithmetic progression = $\frac{n}{2}$ [2a + (n − 1) × d]

##### Formula 2

If the first term of an arithmetic progression is ‘a’, and the last term is ‘l’, then:

Sum of n terms of an arithmetic progression = $\frac{n}{2}$ (first term + last term) = $\frac{n}{2}$ (a + l)

##### Q. Find the sum of the elements of the following series: 8, 9, 10, 11, 12, 13, 14

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Formula 1 <br><br>

Given, a = 8, d = 9 - 8 = 1 and n = 7

We know that, Sum of n terms of an arithmetic series = $\frac{n}{2}$ [2a + (n − 1) × d]

Or S = $\frac{7}{2}$ [2 × 8 + (7 - 1) 1] = $\frac{7}{2}$ [16 + 6] = $\frac{7}{2}$ [22] = 7 × 11 = 77
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Formula 2 <br><br>

Given, a = 8, l = 14 and n = 7

Sum of n terms of an arithmetic series = $\frac{n}{2}$ (a + l) 

Or S = $\frac{7}{2}$ [8 + 14] = $\frac{7}{2}$ [22] = 7 × 11 = 77
</div><br>

#### Arithmetic Mean

Arithmetic Mean = Sum of all terms in the AP / Number of terms in the AP


## Geometric Progression

Geometric Progression is a sequence of numbers, such that there is a common ratio between any two adjacent terms. 

Let the first term of a geometric progression be ‘a’, and the common ratio be ‘r’. So, the geometric progression will be: <br>
a, ar, a$r^2$, a$r^3$, .....

In other words, in a geometric progression each successive term is the multiplication of its previous term and a certain fixed number (called the common ratio). 

For example, the following is a geometric progression with the first term 2, and a common ratio of 3. <br> 
2, 6, 18, 54, 162, ..... 

{{% alert note %}}
The first term of a geometric progression, as well as the common ratio can be positive or negative. 
{{% /alert %}} 

### Geometric Progression Formulae

#### nth Term of Geometric Progression

Let the first term of a geometric progression be ‘a’, the nth term be ‘$a_n$’ and the common ratio be ‘r’.

Then the nth term, $a_n = a r^{n - 1}$

#### Sum of the terms of a Geometric Progression

##### Formula 1

If the first term of a geometric progression is ‘a’, the common ratio is ‘r’ and the number of terms is ‘n’, then:

Sum of n terms of a geometric progression (if r > 1) = $\frac{a (r^n – 1)}{r – 1}$

Sum of n terms of a geometric progression (if r < 1) = $\frac{a (1 – r^n)}{1 – r}$

{{% alert note %}}
The above formulae will be valid only if r ≠ 1. 
{{% /alert %}}

##### Formula 2

If a geometric progression has infinite terms, and r > 1, then each subsequent term in the series will be greater in value than the previous one. So, the sum of the terms of such a series would be infinite too.

However, if a geometric progression has infinite terms, and −1 < r < 1, then the sum of the terms of such a series would be finite. We can find it using the following formula.

Sum of infinite terms of a geometric progression (if −1 < r < 1) = $\frac{a}{1 – r}$ 

##### Q. Find the sum of the geometric series 64, 32, 16, 8, 4, ..... upto infinity.

Explanation:<br>
<div class="Exp">

First term, a = 32 <br>
Common ratio, r = 32 / 64 = 0.5

We know that, the sum of infinite terms of a geometric progression (if r < 1) = $\frac{a}{1 – r}$ = $\frac{64}{1 – 0.5}$ = 64 / 0.5 = 128
</div> <br>

#### Geometric Mean

Geometric Mean = nth root of the product of n terms in the Geometric Progression


## Harmonic Progression

Harmonic Progression is obtained by taking the reciprocal of the terms of an arithmetic progression. 
For example, the following is an arithmetic progression: 

2, 5, 8, 11, 14, 17 ..... (with the first term 2, and a common difference of 3)

So, the harmonic progression will be: <br>
1/2, 1/5, 1/8, 1/11, 1/14, 1/17, ..... 

{{% alert note %}}
In other words, the reciprocal of the terms in harmonic progression form an arithmetic progression.
{{% /alert %}} 

### Harmonic Progression Formulae

#### nth Term of Harmonic Progression

Let the first term of a harmonic progression be ‘a’, the nth term be ‘$a_n$’ and the common difference be ‘d’.

Then the nth term, $a_n = \frac{1}{[a + (n - 1) d]}$

#### Harmonic Mean

For two terms ‘a’ and ‘b’, Harmonic Mean = $\frac{2 ab}{a + b}$ 

