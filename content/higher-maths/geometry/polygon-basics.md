---
title: Polygons Basics
linktitle: Polygons Basics
toc: true
type: docs
date: "2021-08-18T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 4. Polygons
    weight: 54

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 54
---

## What is a Polygon?

A polygon is a 2 D geometrical figure, bounded by a finite number of line segments. To form a plygon, we need atleast three line segments.


## Types of Polygons

There are various types of polygons. We classify them based on:
* the number of sides they have, or
* the type of sides and angles they have. 

Let's have a look at both of these classifications. 

### Types of Polygons based on Number of Sides

Here's a list of the various polygons that we are probably going to deal with in exams, based on the number of sides they have. 
<img src="../../../media/geometry/polygon-1.png" alt="Polygon" style="width:54%;height:54%;">

{{% alert note %}}
We have already studied Triangles and Quadrilaterals in much detail in previous modules. These two types of polygons are the most important from the perspective of entrance exams. 

Here, we will focus on Polygons in general. 
{{% /alert %}}

### Types of Polygons based on Type of Sides and Angles

#### Convex and Concave Polygons 

* In a Convex Polygon, every angle is less than 180°.

* In a Concave Polygon, at least one angle is more than 180°.

For example, have a look at the following figures: 
<img src="../../../media/geometry/polygon-2.png" alt="Polygon" style="width:72%;height:72%;">

#### Regular and Non-regular Polygon

* In a Regular Polygon, all sides and all angles are equal. 

* In a Non-Regular Polygon, there are atleast two sides which are not equal to each other (and hence there will be atleast two angles which are not equal to each other).

For example, have a look at the following figures: 
<img src="../../../media/geometry/polygon-3.png" alt="Polygon" style="width:99%;height:99%;">


## Formulae related to Polygons

Now, let us have a look at the various formulae that we are going to use extensively while solving questions based on polygons. Some of them will be applicable to any kind of polygon, while some others may be applicable to only regular polygons. 

### Formulae applicable to Any Polygon

These formulae can be applied in case of any kind of polygon. 

#### Formula 1: Sum of Angles

* Sum of all the interior angles of a polygon = (n – 2) x 180° 

* Sum of all the exterior angles of a polygon = 360° 

* Sum of interior angle and exterior angle at any vertex of a polygon = 180°

* Sum of vertex angles of n sided star-shaped polygon = (n – 4) x 180°

#### Formula 2: Number of diagonals

Number of diagonals of a polygon = $C^n_2$ – n = $\frac{n (n-3)}{2}$


### Formulae applicable to Only Regular Polygons

These formulae can be applied only in case of regular polygons. 

#### Formula 1: Measure of Angles

* Measure of each interior angle of a regular polygon = $\frac{(n - 2) × 180°}{n}$

* Measure of each exterior angle of a regular polygon = $\frac{360°}{n}$

#### Formula 2: Area

Area of a regular polygon = $\frac{1}{2}$ × Perimeter × Perpendicular distance from the centre of the regular polygon to any side

{{% alert note %}}
It’s kind of similar to adding the areas of the triangles that make up the polygon. 
{{% /alert %}}

Let's see some examples. 

* Area of equilateral triangle = $\frac{\sqrt{3}}{4} a^2$

* Area of square = $a^2$

* Area of a regular hexagon = $\frac{3 \sqrt{3}}{2} a^2$

{{% alert note %}}
Area of regular Hexagon = 6 × Area of equilateral triangle 
{{% /alert %}}

* Area of a regular octagon = 2(√2 + 1) $a^2$


## Properties of Polygons

### Property 1: Relation between Interior and Exterior angles

In case of a triangle, Sum of interior angles = $\frac{1}{2}$ × Sum of exterior angles = 180°

{{% alert note %}}
Sum of exterior angles of a polygon is always 360°. 
{{% /alert %}}

In case of a rectangle, Sum of interior angles = Sum of exterior angles = 360°

In any other kind of polygon (i.e. except triangle and quadrilateral): <br>
Sum of interior angles > Sum of exterior angles (360°).

