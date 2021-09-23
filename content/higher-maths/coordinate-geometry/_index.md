---
# Course title, summary, and position.
linktitle: Introduction to Coordinate Geometry
summary: This is a basic introduction to Coordinate Geometry.
weight: 8

# Page metadata.
title: Introduction to Coordinate Geometry
date: "2021-09-11T00:00:00Z"
lastmod: "2021-09-11T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  coordinate-geometry:
    name: Overview
    weight: 1
---

## What is Coordinate Geometry? 

Coordinate Geometry is a system of geometry where we use ordered pair of numbers to describe the position of points on a plane. The ordered pair of numbers are called coordinates of that point. 
<img src="../../../media/coordinate-geometry/coordinates-1.png" alt="Coordinate Geometry" style="width:63%;height:63%;">

This system was developed by a French mathematician, René Descartes (1596 – 1650). That's why we also call coordinates as Cartesian coordinates. 

Moreover, René Descartes proposed that even lines and curves could be described by equations using this technique. 

Now, let's study this system of geometry in detail. 


## Cartesian Co-ordinate System 

Cartesian Co-ordinate System is used to denote the exact position of a point on a plane. For this we use concepts of axes, and quadrants. 

### Co-ordinates Axes 

Two mutually perpendicular lines on a plane, passing through a point are called Co-ordinates Axes. 
<img src="../../../media/coordinate-geometry/coordinates-2.svg" alt="Coordinate Geometry" style="width:72%;height:72%;">

* The point of intersection of the two axes is called the ***Origin***. 
* The horizontal line is called the ***X-axis*** or the abscissa.
* The vertical line is called the ***Y-axis*** or the ordinate.

### Quadrants

The two perpendicular axes divides the 2-D plane in four sectors. These sectors are called Quadrants, and are named as per the sign of x and y. 
<img src="../../../media/coordinate-geometry/coordinates-3.png" alt="Coordinate Geometry" style="width:72%;height:72%;">

<img src="../../../media/coordinate-geometry/coordinates-4.png" alt="Coordinate Geometry" style="width:81%;height:81%;">

{{% alert note %}}
* Point of the type (+, +) lies in the 1st quadrant. E.g. (2, 3)
    
* Point of the type (-, +) lies in the 2nd quadrant. E.g. (-2, 3)
  
* Point of the type (-, -) lies in the 3rd quadrant. E.g. (-2, -3)
   
* Point of the type (+, -) lies in the 4th quadrant. E.g. (2, -3)
{{% /alert %}}

### Coordinates of a Point

As already mentioned, coordinates of a point are a pair of numbers that define its exact location on a two-dimensional plane. 

* To state the position of a point with reference to the two axes, we just use normal coordinates. 
* To state the position of a point with reference to the origin, we use polar coordinates. 

Let's study them in more detail. 

#### Ordered Pair

We write the coordinates of a point in the form of an ordered pair. For example, (3, 7), (-4, 2), (2.5, -1), etc. 

* The first number in the ordered pair indicates the position of the point with respect to the X-axis. 

* The second number in the ordered pair indicates the position of the point with respect to the Y-axis. 

For example, point P (3, 5) is:
<img src="../../../media/coordinate-geometry/coordinates-3.png" alt="Coordinate Geometry" style="width:72%;height:72%;">
* at a distance of 3 units from the Y-axis, in the direction of positive side of X-axis.
* at a distance of 5 units from the X-axis, in the direction of positive side of Y-axis.

#### Polar Coordinates

To denote the position of a point with respect to the origin (rather than the axes), we use Polar Coordinates. 

To indicate the position of a point, polar coordinates use:
* the distance of a point from the origin (denoted by r), and 
* the angle that the line joining the origin and the point makes with the X-axis (denoted by θ or Φ)

<img src="../../../media/coordinate-geometry/coordinates-5.svg" alt="Coordinate Geometry" style="width:63%;height:63%;">

Polar coordinates of point P are: (r cos Φ, r sin Φ)

#### Converting normal coordinates into polar coordinates

If we have a point P (x, y), we can easily find its polar coordinates. Let's take the example of the point P ($\sqrt{3}$, 1). 

The distance of a point P (x, y) from the origin, r = $\sqrt{x^2 + y^2}
$ = $\sqrt{(\sqrt{3})^2 + 1^2}$ = $\sqrt{3 + 1}$ = $\sqrt{4}$ = 2 units

tan Φ = $\frac{y}{x}$ = $\frac{1}{\sqrt{3}}$ <br>
It means, Φ = 30°

So, x = r cos Φ = 2 cos 30° <br>
y = r sin Φ = 2 sin 30°

Polar coordinates of point P ($\sqrt{3}$, 1) are: (2 cos 30°, 2 sin 30°)

