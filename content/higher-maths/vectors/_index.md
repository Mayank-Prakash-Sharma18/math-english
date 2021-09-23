---
# Course title, summary, and position.
linktitle: Introduction to Vectors
summary: This is a basic introduction to Vectors.
weight: 48

# Page metadata.
title: Introduction to Vectors
date: "2021-08-18T00:00:00Z"
lastmod: "2021-08-18T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  vectors:
    name: Overview
    weight: 1
---

## What are Vectors in Maths?

Vectors are the objects that are denoted by an arrow. They have both:
* Magnitude – denoted by the length of the line of the arrow. 
* Direction – denoted by the head of the arrow. 

<img src="../../../media/vectors/vector-1.png" alt="Vectors" style="width:72%;height:72%;">

Vectors in Maths are also known as Euclidean vectors, Geometric vectors, or Spatial vectors. 

{{% alert note %}}
In contrast to Vectors, Scalars only have magnitude and no direction. For example, Speed is a scalar quantity, while Velocity is a vector quantity. Velocity constitutes of both speed as well as direction. 

For two scalars to be equal, just their magnitude needs to be the same. 

Two vectors are equal only if both their magnitude and direction are the same.
{{% /alert %}}

Vector is represented by an arrow over the name of the vector, e.g. $\overrightarrow{a}$

### Reverse Vector

Reverse vector of a given vector $\overrightarrow{a}$ will be -$\overrightarrow{a}$. It will have the same magnitude as the original vector, but opposite direction. 

### Components of Vectors 

A vector in the x-y plane has two components:
* Horizontal Component
* Vertical Component

While solving questions involving vectors, we will often break vectors into their x and y components. This makes our task much easier. 

If we have a vector $\overrightarrow{a}$, that makes an angle of θ with the horizontal X-axis, then:
<img src="../../../media/vectors/vector-2.png" alt="Vectors" style="width:81%;height:81%;">

* Horizontal Component of the vector, $a_x$ = a cos θ
* Vertical Component of the vector, $a_y$ = a sin θ

{{% alert note %}}
tan θ = $\frac{a_y}{a_x}$
{{% /alert %}}

### Magnitude of Vector

Magnitude of Vector is the length of the vector. It is represented by two vertical lines on both the sides of the given vector, e.g. $\left\lVert a \right\rVert$ 
<img src="../../../media/vectors/vector-3.png" alt="Vectors" style="width:81%;height:81%;">

$\left\lVert a \right\rVert = √(x^2 + y^2)$

{{% alert note %}}
We use double bars here, so as not to get confused with the absolute value, where we use single bars, i.e. |a|
{{% /alert %}}

{{% alert note %}}
Feel free to use the following calculator for finding the magnitude of a vector:

<div><a href="https://planetcalc.com/8246/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4043">Magnitude of a Vector</a><script src="https://embed.planetcalc.com/widget.js?v=4043"></script></div>
{{% /alert %}}

#### Unit Vector

If a vector has unit length, i.e. its magnitude is equal to one, then it’s called a unit vector. It’s represented by a cap or hat above the name of the vector, e.g. $\hat{a}$

***Normalising a vector*** is the process of finding the unit vector of any given vector. To find the unit vector, we just need to divide the given vector by its magnitude. <br>
So, $\hat{a} = \frac{a}{\left\lVert a \right\rVert}$

We use unit vector, when we are just interested in the direction of a vector. 

#### Zero Vector

If a vector has no length, i.e. its magnitude is equal to zero, then it’s called a zero vector. It’s represented by $\overrightarrow{0}$, or 0. 

Sum of any vector with zero vector will result in that vector itself. That is, $\overrightarrow{a} + \overrightarrow{0} = \overrightarrow{a}$

{{% alert note %}}
Zero vector cannot be normalized, i.e. we cannot find unit vector of a zero vector.
{{% /alert %}}


## Operations on Vectors

We can perform operations like Addition, Subtraction, Multiplication on vectors.

### Addition of Vectors

To add two vectors $\overrightarrow{a}$ and $\overrightarrow{b}$, we can use the graphical method. 

To do so, we place the two vectors in such a manner that the tail of one vector is touching the head of the other vector. 
<img src="../../../media/vectors/vector-4.png" alt="Vectors" style="width:81%;height:81%;">

As shown above, their sum $\overrightarrow{a} + \overrightarrow{b}$ will be the vector joining the tail of the first vector with the head of the second vector. 

{{% alert note %}}
Feel free to use the following calculator for addition of vectors:

<div><a href="https://planetcalc.com/8078/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4043">Vector addition</a><script src="https://embed.planetcalc.com/widget.js?v=4043"></script></div>
{{% /alert %}}

{{% alert note %}}
Vectors obey the commutative law of addition, i.e.  $\overrightarrow{a} + \overrightarrow{b} = \overrightarrow{b} + \overrightarrow{a}$

Vectors also obey the associative law of addition, i.e.  $(\overrightarrow{a} + \overrightarrow{b}) + \overrightarrow{c} = \overrightarrow{a} + (\overrightarrow{b} + \overrightarrow{c})$
{{% /alert %}}

### Subtraction of Vectors

Subtraction of vectors is similar to addition of vectors. Here, we just add the reverse vector of the vector being subtracted. 

That is, $\overrightarrow{a} - \overrightarrow{b} = \overrightarrow{a} + \overrightarrow{(-b)}$

### Multiplication of Vectors

There are various types of multiplications possible when vectors are involved. Let’s see them. 

#### Scalar Multiplication

When a vector is multiplied by a scalar quantity, then it’s called a Scalar Multiplication. 

Scalar Multiplication may change the magnitude of the vector, i.e. it may scale down (make it smaller) or scale up (make it larger) the vector.

Scalar Multiplication with positive numbers will not change the direction of the vector. However, Scalar Multiplication with a negative scalar will reverse the direction of the vector.  

For example, 3 . $\overrightarrow{a} = \overrightarrow{3a}$ <br>
0 . $\overrightarrow{a} = \overrightarrow{0}$   (The zero on the left is the number 0, while the zero on the right is the vector 0.) <br>
1 . $\overrightarrow{a} = \overrightarrow{a}$ <br>
(-1) . $\overrightarrow{a} = \overrightarrow{(-a)}$

{{% alert note %}}
If $\overrightarrow{a}$ and $\overrightarrow{b}$ are two vectors, and $S_1$ & $S_2$ are scalar quantities, then: <br>
$S_1 (\overrightarrow{a} + \overrightarrow{b}) = S_1 \overrightarrow{a} + S_1 \overrightarrow{b}$ <br>
$(S_1 + S_2) \overrightarrow{a} = S_1 \overrightarrow{a} + S_2 \overrightarrow{a}$
{{% /alert %}}

#### Vector Multiplication

When we multiply two or more vectors, then it is called Vector Multiplication. 

There are two types of vector multiplications: 
* Cross Product – it results in a vector quantity
* Dot Product – it results in a scalar quantity

Let’s study them in detail. 

##### Cross Product of Vectors 

As already mentioned, the cross product of two vectors results in a vector quantity (i.e. a quantity that has both magnitude and direction). We use cross sign (×) to represent it.

For example, cross product of two vectors will be represented as $\overrightarrow{a} × \overrightarrow{b}$
<img src="../../../media/vectors/vector-5.png" alt="Vectors" style="width:72%;height:72%;">

$\overrightarrow{a} × \overrightarrow{b}$ = $\left\lVert a \right\rVert$  $\left\lVert b \right\rVert$ sin θ $\hat{n}$

Where $\left\lVert a \right\rVert$ and $\left\lVert b \right\rVert$ are the magnitudes of the vectors $\overrightarrow{a}$ and $\overrightarrow{b}$ respectively, and θ is the angle between those two vectors.

$\hat{n}$ is a unit vector. It shows the direction of the multiplication of these two vectors.

{{% alert note %}}
Feel free to use the following calculator for cross product of vectors:

<div><a href="https://planetcalc.com/8313/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4043">Cross product calculator</a><script src="https://embed.planetcalc.com/widget.js?v=4043"></script></div>
{{% /alert %}}

##### Dot Product of Vectors 

As already mentioned, the dot product of two vectors always results in a scalar quantity (i.e. a quantity that only has magnitude and no direction). We use dot sign (.) to represent it.

For example, dot product of two vectors will be represented as $\overrightarrow{a} . \overrightarrow{b}$

$\overrightarrow{a} . \overrightarrow{b}$ = $\left\lVert a \right\rVert$  $\left\lVert b \right\rVert$ cos θ

{{% alert note %}}
Feel free to use the following calculator for dot product of vectors:

<div><a href="https://planetcalc.com/8245/" data-lang="en" data-code="" data-colors="#263238,#435863,#090c0d,#fa7014,#fb9b5a,#c25004" data-v="4043">Dot product</a><script src="https://embed.planetcalc.com/widget.js?v=4043"></script></div>
{{% /alert %}}

{{% alert note %}}
We can describe vectors, and vector operations (addition, subtraction, and scalar multiplication) with or without reference to any coordinate system.
{{% /alert %}}
