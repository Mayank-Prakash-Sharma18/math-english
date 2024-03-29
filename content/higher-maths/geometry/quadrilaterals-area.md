---
title: Area of Quadrilaterals
linktitle: Area of Quadrilaterals
toc: true
type: docs
date: "2021-08-18T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 3. Quadrilateral
    weight: 45

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 45
---

Let us see the various formulae that we can use:
* to find area of any general quadrilateral
* to find area of some specific kind of a quadrilateral, e.g. trapezium, rhombus etc. 

## Formulae for Area of Quadrilateral

### Formula 1 

Area of Quadrilateral = $\frac{1}{2}$ × One diagonal × Sum of perpendiculars on that diagonal from opposite vertices
<img src="../../../media/geometry/quadrilateral-area-1.png" alt="Geometry" style="width:54%;height:54%;">
Area of □ABCD = $\frac{1}{2}$ × BD × (AN + CM)

Basically its akin to adding the areas of two triangles, ABD and CDB. 

### Formula 2

Area of quadrilateral = $\frac{1}{2}$ × Product of two diagonals × sine of angle between the two diagonals
<img src="../../../media/geometry/quadrilateral-area-2.png" alt="Geometry" style="width:54%;height:54%;">
Area of □ABCD = $\frac{1}{2}$ × AC × BD × sin θ


## Formulae for Area of Cyclic Quadrilaterals

If the length of the sides of the cyclic quadrilateral are a, b, c and d, then:
<img src="../../../media/geometry/quadrilateral-6.png" alt="Geometry" style="width:54%;height:54%;">

Area of cyclic quadrilateral = $\sqrt{(s - a) (s - b) (s - c) (s - d)}$

Where, s = $\frac{a + b + c + d}{2}$. It is called the semi-perimeter. 


## Formulae for Area of Parallelograms 

Here are a few formulae that we can use for any kind of a parallelogram. 

### Formula 1

Area of parallelogram = Base × Height
<img src="../../../media/geometry/parallelogram-5.png" alt="Geometry" style="width:63%;height:63%;">

In the above figure, Area of parallelogram = AB × h

{{% alert note %}}
If the angle between the base and another side of length 'a' is θ, then: <br>
height (h) = a sin θ
<img src="../../../media/geometry/parallelogram-22.png" alt="Geometry" style="width:63%;height:63%;">

Area of parallelogram = AB × h = AB × a sin θ
{{% /alert %}}

### Formula 2

If the length of two adjacent sides of a parallelogram are a and b, and length of any one of the diagonals is d, then:
<img src="../../../media/geometry/parallelogram-6.png" alt="Geometry" style="width:54%;height:54%;">

Area of parallelogram = 2 $\sqrt{s (s - a) (s - b) (s - d)}$

Where, s = $\frac{a + b + d}{2}$. It is called the semi-perimeter. 


However, there are a few formulae that we can use for some specific kinds of parallelograms. Let's see these too. 

### Formula 3: For Rhombus

If the given parallelogram is a rhombus, the we can also use the following formula to find its area. 
<img src="../../../media/geometry/parallelogram-12.png" alt="Geometry" style="width:54%;height:54%;">

Area of Rhombus = $\frac{1}{2}$ × Product of diagonals = $\frac{1}{2} × d_1 × d_2$

{{% alert note %}}
We use the same formula for finding the area of a kite too. 
<img src="../../../media/geometry/quadrilateral-16.png" alt="Geometry" style="width:45%;height:45%;">

Area of Kite = $\frac{1}{2}$ × Product of diagonals = $\frac{1}{2} × d_1 × d_2$
{{% /alert %}}

### Formula 4: For Square

If the given parallelogram is a square, then we can also use the following formula to find its area. 
<img src="../../../media/geometry/parallelogram-15.png" alt="Geometry" style="width:45%;height:45%;">

Area of Square = $a^2$ = $\frac{d^2}{2}$

{{% alert note %}}
Diagonal of a square, d = $\sqrt{2}$ a
{{% /alert %}}

### Formula 5: For Circumscribed Square

<img src="../../../media/geometry/parallelogram-18.png" alt="Geometry" style="width:45%;height:45%;">

Side of circumscribed square, a = Diameter of the inscribed circle, d

Ratio of area of inscribed circle and area of circumscribed square = $\frac{π r^2}{a^2}$ = $\frac{π d^2/4}{a^2}$ = $\frac{π a^2/4}{a^2}$ = $\frac{π}{4}$

### Formula 6: For Rectangle

#### Formula 6a

If the given parallelogram is a rectangle, then we can also use the following formula to find its area. 
<img src="../../../media/geometry/parallelogram-19.png" alt="Geometry" style="width:72%;height:72%;">

Area of rectangle = Length x Breadth = l x b

#### Formula 6b: Pathway across the middle of a rectangle

Have a look at the pathway across the middle of a rectangle.
<img src="../../../media/geometry/parallelogram-23.png" alt="Geometry" style="width:72%;height:72%;">
Area of path = (l + b – x)x <br>
Perimeter of path = 2(l + b) –  4x = 2(l + b – 2x)

#### Formula 6c: Pathway around a rectangle

Have a look at the pathway around a rectangle (pathway is inside the rectangle).
<img src="../../../media/geometry/parallelogram-24.png" alt="Geometry" style="width:72%;height:72%;">
Area of the path = (l + b – 2x)2x <br>
Primeter = Inner perimeter + Outer perimeter = 2(l + b - 4x) + 2(l + b) = 4 (l + b – 2x)

Have a look at the pathway around a rectangle (pathway is outside the rectangle).
<img src="../../../media/geometry/parallelogram-25.png" alt="Geometry" style="width:72%;height:72%;">
Area = (l + b + 2x)2x <br>
Perimeter = Inner perimeter + Outer perimeter = 2 (l + b) + 2(l + b + 4x) = 4(l + b + 2x)


## Formulae for Area of Trapezium

Area of trapezium = $\frac{1}{2}$ × (Sum of parallel sides) × Height
<img src="../../../media/geometry/trapezium-3.png" alt="Geometry" style="width:54%;height:54%;">

In the above figure, Area of trapezium = $\frac{1}{2}$ × (AB + CD) × h

{{% alert note %}}
Height is the perpendiclar distance between the parallel sides. 
{{% /alert %}}

<br><hr><br>

## Properties related to Area of a Quadrilateral

### Property 1

If two parallelograms have the same base (or same base length), and are between the same parallel lines (i.e. their height is the same), then their area will be equal.
<img src="../../../media/geometry/parallelogram-7.png" alt="Geometry" style="width:99%;height:99%;">
If AB ∥ PQ, then, Area of □ABCD = Area of □ABEF

This is because area of a parallelogram is equal to the product of its base and height. If heights of two parallelograms are the same and the length of their bases too (as is the case above), then they obviously will have the same area. 

### Property 2

If the side/diagonal of a square becomes x times, then the area of the square will become $x^2$ times.

### Property 3

In case of a rectangle (or a square), if its length is increased by x%, then in order to maintain the same area of the rectangle its breadth will have to be decreased by $\frac{100a}{100 + a}$%.

### Property 4

If all the sides of a quadrilateral are increased (or decreased) by x%, then its diagonals are also increased (or decreased) by x%.

{{% alert note %}}
If all of the sides of any 2-D figure are increased (or decreased) by x%, then:
* its perimeter also increases (or decreases) by x%.
* its area changes by $x(2 ± \frac{x}{100})$%. If the dimension is increased, take x as positive. If the dimension is decreased, take x as negative.
{{% /alert %}}