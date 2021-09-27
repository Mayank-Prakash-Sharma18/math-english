---
title: Coordinate Geometry - Quadrilateral
linktitle: Quadrilateral
toc: true
type: docs
date: "2021-09-24T00:00:00+01:00"
draft: true
menu:
  coordinate-geometry:
    parent: 4. Quadrilateral
    weight: 36

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 36
---

## Area of a Quadrilateral 

We can find the area of a quadrilateral (i.e. Rhombus, Rectangle, Square, Parallelogram, Kite, Trapezium, etc.) if we know the coordinates of its vertices. Let's see how.

If the vertices of a quadrilateral ABCD are A ($x_1$, $y_1$), B ($x_2$, $y_2$), C ($x_3$, $y_3$), and D ($x_4$, $y_4$), then: <br>
<img src="../../../media/coordinate-geometry/quadrilateral-1.png" alt="Coordinate Geometry" style="width:63%;height:63%;">

Area of the quadrilateral = $ \frac{1}{2} |(x_1 y_2 – x_2 y_1) + (x_2 y_3 – x_3 y_2) + (x_3 y_4 – x_4 y_3) + (x_4 y_1 – x_1 y_4)|$

{{% alert note %}}
We have placed modulus signs in the above formula, because area of a quadrilateral (or any other figure) can never be negative. 

In fact, we can generalize the above formula for any polygon. 

If we have a polygon, whose vertices are ($x_1$, $y_1$), ($x_2$, $y_2$), ($x_3$, $y_3$) .... ($x_n$, $y_n$), then: 

Area of the polygon = $ \frac{1}{2} |(x_1 y_2 – x_2 y_1) + (x_2 y_3 – x_3 y_2) + (x_3 y_4 – x_4 y_3) + .... +$ $(x_{n - 1} y_n – x_n y_{n - 1}) + (x_n y_1 – x_1 y_n)|$
{{% /alert %}}

