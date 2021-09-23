---
# Course title, summary, and position.
linktitle: Introduction to Complex Numbers
summary: This is a basic introduction to Complex Numbers.
weight: 45

# Page metadata.
title: Introduction to Complex Numbers
date: "2021-09-16T00:00:00Z"
lastmod: "2021-09-18T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  complex-numbers:
    name: Overview
    weight: 1
---

In this article, we will try to understand the basics of an important chapter in Maths – Complex Numbers. 

## What are Complex Numbers?

A complex number is a combination of real and imaginary numbers. It is represented as: a + ib
<img src="../../../media/complex-numbers/complex-number-1.png" alt="Complex Numbers" style="width:72%;height:72%;">

Here ‘a’ and ‘b’ are real numbers and ‘i’ (Iota) is an imaginary number. Value of i is √-1.

So, to understand what complex numbers are, we must understand real numbers and imaginary numbers.

Real numbers (Re) are the numbers that we deal with in our daily life, e.g. zero, positive numbers (1, 2, 5…), negative numbers (-1, -4, -134…), fractions (1/2, 3/5, 5/3…). That is, they consist of all rational and irrational numbers. They can be represented on a number line. Square of any real number is a positive number. 

In contrast, imaginary numbers (Im) cannot be represented on a number line. Why? 

Because they are imaginary – they do not have any tangible value. An imaginary number is the square root of a negative number, e.g. √-3, √-5, etc. In other words, if we square an imaginary number, we will get a negative number as resultant. 

A complex number combines real numbers and imaginary numbers, e.g. 4 + √-5, 3 + √-2, etc. We can also represent these as follows:
* 4 + √-5 = 4 + i5
* 3 + √-2 = 3 + i2
* and so on…. 

{{% alert note %}}
Both real numbers and imaginary numbers are also complex numbers. 
* If in the complex number a + ib, b is zero, then it will be a pure real number. For example, 7 + 0i, -2 + 0i, etc. 
* If in the complex number a + ib, a is zero, then it will be a pure imaginary number. For example, 0 + 2i, 0 – 7i, etc. 
* Even zero is a complex number. It can be represented as 0 + 0i
{{% /alert %}}

### Properties of Complex Numbers

#### Property 1

If a, and b are real numbers and a + bi = 0, then it means that: 
* a = 0, and 
* b = 0

#### Property 2

If a, b, c, and d are real numbers and a + bi = c + di, then it means that: 
* a = c, and 
* b = d

### Graphical Representation of Complex Numbers

To represent a complex number on a graph, we place the real numbers on the X-axis (so called real axis) and imaginary numbers on the Y-axis (so called imaginary axis). 

For example, we can represent the complex number 2 + 4i as follows:
<img src="../../../media/complex-numbers/complex-number-2.png" alt="Complex Numbers" style="width:81%;height:81%;">

The plane having complex numbers is called Argand (or Complex) plane. 

{{% alert note %}}
Just like normal coordinate points, we can also represent complex numbers in polar form. 

In polar form, the real and complex components or a complex number are represented in terms of r and θ. Here, r is the length of the vector from the origin to the point represented by the complex number, and θ is the angle made by such a vector with the real axis.
{{% /alert %}}

### Power of Iota (i)

We already know that, value of i is √-1. That is, i = -1. We can generalize this further. 

If k is an integer, then: <br>
$i^{4k + 1} = i$ <br>
$i^{4k + 2} = i^2 = -1$ <br>
$i^{4k + 3} = i^3 = (-1)i = -1$ <br>
$i^{4k + 4} = i^4 = 1$

We can find negative powers of i too. <br>
For example, $i^{-1} = 1/i = (1/i) × (i/i) = i/i^2 = i/(-1) = -i$

### Absolute Value of Complex Numbers

The absolute value of a real number is the positive value of that number. It is denoted by modulus. 
For example, absolute value of 5, i.e. |5| = 5 

Absolute value of -5, i.e. |-5| = 5

In case of complex numbers, we calculate the absolute value a bit differently. If z = a + ib is a complex number, then:

Absolute value of z = |z| = |a + ib| = $√(a^2 + b^2)$

For example, absolute value of 3 + 4i = |3 + 4i| = $√(3^2 + 4^2) = √(9 + 16) = √25$ = 5 

If $z_1$ and $z_2$ are two complex numbers, then: <br>
$|z_1 + z_2| ≤ |z_1|+|z_2|$

Let’s see some examples. 

If $z_1$ = 3 + 4i, and $z_2$ = 6 + 8i, then: <br>
$z_1 + z_2$ = (3 + 4i) + (6 + 8i) = 9 + 12i <br>
$|z_1| = √(3^2 + 4^2)$ = 5 <br>
$|z_2| = √(6^2 + 8^2)$ = 10 <br>
$|z_1 + z_2| = √(9^2 + 12^2) = √225$ = 15  <br>
Now, 15 = 5 + 10

If $z_1$ = 1 - 2i, and $z_2$ = 3 + 5i, then: <br>
$z_1 + z_2$ = (1 - 2i) + (3 + 5i) = 4 + 3i <br>
$|z_1| = √(1^2 + 2^2) = √5$ <br>
$|z_2| = √(3^2 + 5^2) = √34$ <br>
$|z_1 + z_2| = √(4^2 + 3^2)$ = 5 <br>
Now, 5 < √5 + √34

### Conjugate of Complex Numbers 

If we have a complex number z = a + ib, then its conjugate will be z̄ = a – ib. Conjugate of a complex number z is denoted by a bar over the complex number, i.e. z̄. 

The addition and multiplication of two conjugate complex numbers results in a real number. In other words, if sum and product of two complex number is real, then those two complex numbers must be conjugate to each other.

{{% alert note %}}
Feel free to use the following Graph Maker for Complex Numbers. It also shows the conjugate of that complex number. 

<div><a href="https://planetcalc.com/7854/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4038">Complex numbers & their Conjugates</a><script src="https://embed.planetcalc.com/widget.js?v=4038"></script></div>
{{% /alert %}} 


## Algebraic Operations on Complex Numbers

Just like real numbers, we can perform the operations of addition, subtraction, multiplication and division on complex numbers too. 

### Addition and Subtraction of Complex Numbers

While adding or subtracting complex numbers, we add/subtract the real parts and imaginary parts separately. 

(a + ib) + (x +iy) = (a + x) + i(b + y) <br>
(a + ib) - (x +iy) = (a - x) + i(b - y)

{{% alert note %}}
Complex numbers obey the commutative law of addition, i.e.  $z_1 + z_2 = z_2 + z_1$ <br>
Complex numbers also obey the associative law of addition, i.e.  $(z_1 + z_2) + z_3 = z_1 + (z_2 + z_3)$
{{% /alert %}} 

### Multiplication of Complex Numbers

In multiplication of complex numbers, we follow a similar process as that of multiplying two binomials, i.e. distributive multiplication.

$(a + ib) . (x + iy) = ax + i^2 by + iay + ibx = (ax - by) + i(ay + bx)$ <br>
(as $i^2$ = -1)

{{% alert warning %}}
As far as multiplication of imaginary numbers is concerned, keep the following point in mind.
In case of imaginary numbers √p × √q is not equal to √pq. 

For example, i × i = √-1 × √-1 = √(-1  × -1) = √1 = 1  (wrong) <br>
We know that, $i^2$ = -1 (and not 1)
{{% /alert %}}

{{% alert note %}}
Complex numbers obey the commutative law of multiplication, i.e.  $z_1 . z_2 = z_2 . z_1$ <br>
Complex numbers also obey the associative law of multiplication, i.e. $(z_1 . z_2) . z_3 = z_1 . (z_2 . z_3)$ <br>
Complex numbers also obey the distributive law, i.e. $z_1 . (z_2 + z_3) = z_1 . z_2 + z_1 . z_3$
{{% /alert %}}

### Division of Complex Numbers

While conducting division of two complex numbers, we multiply both the numerator and denominator with the conjugate of the complex number in the denominator. Then we simplify it. 

$\frac{a + ib}{x + iy} = \frac{(a + ib) . (x - iy)}{(x + iy) . (x - iy)} = \frac{ax + by + i(bx - ay)}{x^2 + y^2} = \frac{(ax + by)}{(x^2 + y^2)} + i \frac{(bx - ay)}{(x^2 + y^2)}$

{{% alert note %}}
Feel free to use the following Graph Calculator for Complex Numbers. 

<div><a href="https://planetcalc.com/7936/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4043">Complex number elementary operations</a><script src="https://embed.planetcalc.com/widget.js?v=4043"></script></div>
{{% /alert %}}


## Complex Number Identities

### Squares

$(z_1 + z_2)^2 = (z_1)^2 + (z_2)^2 + 2 z_1 × z_2$ <br>
$(z_1 – z_2)^2 = (z_1)^2 + (z_2)^2 – 2 z_1 × z_2$ <br>
$(z_1)^2 – (z_2)^2 = (z_1 + z_2)(z_1 – z_2)$

### Cubes

$(z_1 + z_2)^3 = (z_1)^3 + 3(z_1)^2 z_2 + 3(z_2)^2 z_1 + (z_2)^3$ <br>
$(z_1 – z_2)^3 = (z_1)^3 – 3(z_1)^2 z_2 + 3(z_2)^2 z_1 – (z_2)^3$

