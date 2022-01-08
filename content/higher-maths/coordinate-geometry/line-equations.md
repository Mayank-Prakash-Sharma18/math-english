---
title: Coordinate Geometry - Equation of Lines
linktitle: Equation of Lines
toc: true
type: docs
date: "2021-09-14T00:00:00+01:00"
draft: false
menu:
  coordinate-geometry:
    parent: 2. Lines
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

René Descartes proposed that even lines (and curves too) could be described by equations using Coordinate Geometry. 

Let's see how.

## Equation of lines

### Equation of X and Y axes

We will start with the very basic. 
<img src="../../../media/coordinate-geometry/line-equation-1.png" alt="Coordinate Geometry" style="width:63%;height:63%;">

* The equation of Y-axis is x = 0
* The equation of X-axis is y = 0

### Equation of lines parallel to X and Y axes

* The equation of a line parallel to Y-axis is x = a
<img src="../../../media/coordinate-geometry/line-equation-2.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

* The equation of a line parallel to X-axis is y = b
<img src="../../../media/coordinate-geometry/line-equation-3.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

a, b are some constants. 

### Equation of general lines

General equation of straight line is ax + by + c = 0, where x and y are variables and a, b and c are constants. 
<img src="../../../media/coordinate-geometry/line-equation-4.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

Any point lying on a line will satisfy the equation of that line. That is, if we put in the coordinates of that point in the equation of the line, the left hand and right hand sides of the equation will be equal. 

There are a few terms that we must be aware of regarding line equations. 

* ***Angle of inclination and Slope*** - The angle that a line makes with the X-axis in the anti-clockwise direction is called the inclination of that line. In the figure given above, line PQ makes an angle of θ with the X-axis. Slope of the line will be tan θ. 

* ***Intercepts on Axes*** - The distance between the point where a line intercepts an axis and the origin is called the Intercept of that line on that particular axis. In the figure given above, OP and OQ are the X-axis intercept and Y-axis intercept respectively, made by the line PQ. 

{{% alert note %}}
We can rewrite the equation ax + by + c = 0 as follows: <br>
y = $-\frac{a}{b} x - \frac{c}{b}$

The slope of the line, m = tan θ = $-\frac{a}{b}$

* Slope of a line is always measured in anticlockwise direction.
* If slope = ∞, then that line is parallel to y-axis or perpendicular to x-axis.
*	If slope = 0, then that line is parallel to x-axis or perpendicular to y-axis.
{{% /alert %}}

Now, there are various ways in which we can represent the equation of any given line. Let's understand all these forms.

## Various forms of Line Equations

### Intercept Form

If the X-intercept and Y-intercept of a line are a and b respectively, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-10.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

$\frac{x}{a} + \frac{y}{b}$ = 1

Length of the intercept between the two axes = $\sqrt{a^2 + b^2}$

### Slope Intercept Form

If the Y-intercept of a line is c, and the slope of the line is m, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-5.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

y = mx + c

For example, y = 2x + 3
<img src="../../../media/coordinate-geometry/line-equation-6.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

{{% alert note %}}
If the line passes through the origin, then c = 0. 

So, the equation of such a line will be, y = mx

For example, y = 2x
<img src="../../../media/coordinate-geometry/line-equation-7.png" alt="Coordinate Geometry" style="width:81%;height:81%;">
{{% /alert %}}

### Point Slope Form

If a line passes through a point $(x_1, y_1)$, and the slope of the line is m, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-8.png" alt="Coordinate Geometry" style="width:81%;height:81%;">

$(y – y_1) = m(x – x_1)$

### Two Points Form

If a line passes through two points $(x_1, y_1)$, and $(x_2, y_2)$, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-9.png" alt="Coordinate Geometry" style="width:81%;height:81%;">

$(y – y_1) = \frac{y_2 – y_1}{x_2 – x_1} (x – x_1)$

Where, Slope of the line, m = $\frac{y_2 – y_1}{x_2 – x_1}$

### Normal Form

If the length of the perpendicular from the origin to a line (i.e. normal distance) is 'p', and this perpendicular line makes an angle of θ with the positive direction of X-axis, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-11.png" alt="Coordinate Geometry" style="width:81%;height:81%;">

x cos θ + y sin θ = p 

### Parametric Form

It is also called as Distance/Symmetrical Form. 

If a line makes an angle of θ with the positive direction of X-axis, and it passes through points (x, y) and ($x_1, y_1$), which are r units apart, then the equation of the line will be:
<img src="../../../media/coordinate-geometry/line-equation-12.png" alt="Coordinate Geometry" style="width:81%;height:81%;">

$\frac{x - x_1}{cos θ} = \frac{y - y_1}{sin θ}$ = r

Coordinates of point P will be: ($x_1 + r cos θ, y_1 + r sin θ$)

