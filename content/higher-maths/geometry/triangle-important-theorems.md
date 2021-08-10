---
title: Important Theorems and Rules of Triangle
linktitle: Important Theorems of Triangle  
toc: true
type: docs
date: "2021-08-08T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 2. Triangle
    weight: 21

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 21
---

## Pythagoras Theorem

In a right-angled triangle, the square of the hypotenuse is equal to sum of the squares of the other two sides. 

<img src="../../../media/geometry/triangle-theorems-1.png" alt="Geometry" style="width:72%;height:72%;">
$Hypotenuse^2 = Base^2 + Perpendicular^2$ <br>
or $BC^2 = AB^2 + AC^2$ <br><br>

{{% alert note %}}
We can remember some very common ***Pythagorean Triplets***. You will encounter these pretty frequently.

(3, 4, 5), (5, 12, 13), (6, 8, 10), (7, 24, 25), (8, 15, 17), (9, 40, 41), (11, 60, 61), (30, 40, 50)
{{% /alert %}}

We can also apply this theorem to other types of triangles with some variation. 

In Obtuse angled triangle:
<img src="../../../media/geometry/triangle-theorems-2.png" alt="Geometry" style="width:99%;height:99%;">
$BC^2 = AB^2 + AC^2 + 2 (AB × AD)$

In Acute angled triangle:
<img src="../../../media/geometry/triangle-theorems-3.png" alt="Geometry" style="width:81%;height:81%;">
$BC^2 = AB^2 + AC^2 - 2 (AB × AD)$


## Median related Theorems

### Theorem 1

In ∆ABC, if CD is the median, then: 

<img src="../../../media/geometry/triangle-lines-points-2.png" alt="Geometry" style="width:90%;height:90%;">

$CA^2 + CB^2 = 2 (CD^2 + AD^2)$

Now, as AD = BD. So, we can also write it as: $CA^2 + CB^2 = 2 (CD^2 + BD^2)$

### Theorem 2

In ∆ABC, if AD, BE, CF are the medians, then: 

<img src="../../../media/geometry/theorems-1.png" alt="Geometry" style="width:90%;height:90%;">

$3 (AB^2 + BC^2 + CA^2) = 4 (AD^2 + BE^2 + CF^2)$

### Theorem 3

In right-angled ∆ABC, if BE and CF are the medians drawn from the acute angles, then: 

<img src="../../../media/geometry/theorems-2.png" alt="Geometry" style="width:54%;height:54%;">

$4 (BE^2 + CF^2) = 5BC^2$

That is, four times the sum of the square of the medians drawn from the acute angles is equal to five times the square of the hypotenuse (only in case of right-angled triangle). 


## Sine Rule

Sine rule, or the law of sine is pretty useful in finding the sides and angles of ***any*** triangle. 

In ∆ABC, if a, b and c are the sides and A, B and C are the angles opposite to them respectively, then:
<img src="../../../media/geometry/triangle-11.png" alt="Geometry" style="width:90%;height:90%;">

$\frac{a}{sin \hspace{1ex} A} = \frac{b}{sin \hspace{1ex} B} = \frac{c}{sin \hspace{1ex} C}$

{{% alert note %}}
We use this formula, when:
* two sides and an angle opposite to one of them are given.
* two angles and a side opposite to one of them are given. 
{{% /alert %}}



## Cosine Rule

Cosine rule, or the law of cosine is pretty useful in finding the sides and angles of ***any*** triangle. 

In ∆ABC, if a, b and c are the sides and A, B and C are the angles opposite to them respectively, then:
<img src="../../../media/geometry/triangle-11.png" alt="Geometry" style="width:90%;height:90%;">

$a^2 = b^2 + c^2 - 2bc \hspace{1ex} cos A$ <br>
$b^2 = a^2 + c^2 - 2ac \hspace{1ex} cos B$ <br>
$c^2 = a^2 + b^2 - 2ab \hspace{1ex} cos C$

{{% alert note %}}
We use this formula, when:
* three sides are given.
* two sides and the angle in between those two sides are given. 
{{% /alert %}}


## Mass Point Geometry Theorem

Centre of mass of an object is the point at which the object can be balanced. 

If there are masses $m_1, m_2, m_3,...... m_n$ at a distance of $x_1, x_2, x_3....x_n$ from a fixed point, the centre of mass will be at a distance x from that fixed point where:

x = $\frac{m_1 x_1 + m_2 x_2 + m_3 x_3 + .....+ m_n x_n}{m_1 + m_2 + m_3 + ..... + m_n}$


## Crossed Ladders Theorem

If AB ‖ EF ‖ CD and AD & BC intersect at E, then:
<img src="../../../media/geometry/theorems-4.png" alt="Geometry" style="width:90%;height:90%;">

$\frac{1}{a} + \frac{1}{b} = \frac{1}{c}$ <br>
or c = $\frac{ab}{a + b}$

Now, let's see some other theorems based on Crossed Ladders Theorem. 

### Theorem 1

In ∆ABC, if:
* D lies on the side AC, E lies on the side BC, and AE & BD intersect at M
* DD', CC', MM' and EE' are parallel, then:
<img src="../../../media/geometry/theorems-5.png" alt="Geometry" style="width:90%;height:90%;">

$\frac{1}{DD'} + \frac{1}{EE'} = \frac{1}{CC'} + \frac{1}{MM'}$

### Theorem 2

We can also use Crossed Ladders Theorem to find the area of a triangle. 

In ∆ABC, if:
* D lies on the side AC, E lies on the side BC, and AE & BD intersect at M
* w is the area of the ∆ABC, and x, y, z are the areas of the smaller triangles as shown in the following figure, then: 
<img src="../../../media/geometry/theorems-6.png" alt="Geometry" style="width:90%;height:90%;">

$\frac{1}{w} + \frac{1}{x} = \frac{1}{x + y} + \frac{1}{x + z}$

### Theorem 3

We can also apply Crossed Ladders Theorem in case of trapezium (a quadrilateral with one pair of sides parallel).

If ABCD is a trapezium, such that:
* length of its parallel sides are a and b units respectively
* EF is a line parallel to the trapezium's parallel sides, such that it divides the trapezium's non-parallel sides in the ratio m:n, then:
<img src="../../../media/geometry/theorems-7.png" alt="Geometry" style="width:90%;height:90%;">

Length of EF = a + m $\frac{b - a}{m + n}$


## Some more Theorems 

### Theorem 1

In right-angled ∆ABC, if E and F are any points on perpendicular and base, then: 

<img src="../../../media/geometry/theorems-3.png" alt="Geometry" style="width:54%;height:54%;">

$BE^2 + CF^2 = BC^2 + EF^2$
