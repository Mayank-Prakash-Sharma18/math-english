---
title: Circle Basics
linktitle: Circle Basics
toc: true
type: docs
date: "2021-08-30T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 5. Circle
    weight: 66

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 66
---

## What is a Circle?

It is a set of all those points that are at a fixed distance from another point on the same plane. 
<img src="../../../media/geometry/circle-1.png" alt="Geometry" style="width:63%;height:63%;">


## Basic Terms related to Circle

### Centre and Radius 

The fixed point inside a circle that is equidistant from all the points on that circle, is called the ***Centre*** of that circle. 

The line segment joining any point on the circle with its centre is called the ***Radius***. 
<img src="../../../media/geometry/circle-2.png" alt="Geometry" style="width:63%;height:63%;">

### Chord and Diameter

The line segment joining any two points on the circle is called a ***Chord*** of that circle. 
<img src="../../../media/geometry/circle-3.png" alt="Geometry" style="width:54%;height:54%;">

The chord that passes through the centre of a circle is the ***Diameter*** of that circle. It's invariably the largest chord of that circle. 
<img src="../../../media/geometry/circle-4.png" alt="Geometry" style="width:63%;height:63%;">

Length of the diameter of a circle = 2 × Length of the radius of a circle

{{% alert note %}}
All diameters of a circle have the same length. 
{{% /alert %}}

### Arc and Semi-circle

A piece of circle between two points is called an ***Arc***. 
<img src="../../../media/geometry/circle-5.png" alt="Geometry" style="width:63%;height:63%;">

The bigger arc is called the Major arc, while the smaller arc is called the Minor arc. 
<img src="../../../media/geometry/circle-6.png" alt="Geometry" style="width:63%;height:63%;">

The arc joining the opposite points of a diameter is called the Semi-circle. There are no minor or major arcs in such a case; only two equal semi-circles.
<img src="../../../media/geometry/circle-7.png" alt="Geometry" style="width:63%;height:63%;">

### Segment and Sectors

Segment is the region between a chord and an arc of a circle. 

The segment made with major arc is called major segment. While, the segment made with minor arc is called minor segment.
<img src="../../../media/geometry/circle-8.png" alt="Geometry" style="width:63%;height:63%;">

Sector is the region between an arc and the two radii, joining the centre of the circle to the end points of the arc.

The sector made with major arc is called major sector. While, the sector made with minor arc is called minor sector.
<img src="../../../media/geometry/circle-9.png" alt="Geometry" style="width:63%;height:63%;">

{{% alert note %}}
When two arcs are equal, then both segments and both sectors become one and the same and each is known as a semi-circular region.
{{% /alert %}}
  
### Secant and Tangent

Secant is a line that intercepts the circle at two points.

Tangent to a circle is a line that touches the circle at only one point.
<img src="../../../media/geometry/circle-10.png" alt="Geometry" style="width:72%;height:72%;">

{{% alert note %}}
The tangent to a circle is a special case of the secant. 
{{% /alert %}}

The point where a tangent touches the circle is called the ***common point***. Only one tangent can touch any given point on a circle. 

### Concentric circles

Concentric circles are two or more circles that:
* are on the same plane, and
* have the same centre. 
<img src="../../../media/geometry/circle-11.png" alt="Geometry" style="width:36%;height:36%;">

### Common Tangents

A tangent that touches two circles is called a common tangent. 

Common tangent can be of two types:
* Direct common tangent - A direct common tangent divides the line passing through centres of two circles externally in the ratio of their radii. 
<img src="../../../media/geometry/circle-24.png" alt="Geometry" style="width:99%;height:99%;">

* Transverse common tangent - A traverse common tangent divides the line passing through centres of two circles internally in the ratio of their radii. 
<img src="../../../media/geometry/circle-25.png" alt="Geometry" style="width:72%;height:72%;">

Two circles can have :
* a maximum of 4 tangents
* a minimum of 0 tangents. 

So, in total 5 cases are possible. Let's see these cases.

#### Case 1: 4 Common tangents

Two circles, not touching each other have:
* 2 Direct common tangents
* 2 Transverse common tangents

Here, Distance between the centres of two circles > Sum of their radii (i.e. $r_1 + r_2$)
<img src="../../../media/geometry/circle-26.png" alt="Geometry" style="width:81%;height:81%;">

#### Case 2: 3 Common tangents

Two circles, touching each other externally have:
* 2 Direct common tangents
* 1 Transverse common tangent

Here, Distance between the centres of two circles = Sum of their radii (i.e. $r_1 + r_2$)<img src="../../../media/geometry/circle-27.png" alt="Geometry" style="width:81%;height:81%;">

#### Case 3: 2 Common tangents

Two circles, intersecting each other at two points have:
* 2 Direct common tangents
* No Transverse common tangents

Here, Difference of their radii (i.e. $|r_1 - r_2|$) < Distance between the centres of two circles < Sum of their radii (i.e. $r_1 + r_2$)
<img src="../../../media/geometry/circle-28.png" alt="Geometry" style="width:81%;height:81%;">

#### Case 4: 1 Common tangent

Two circles, touching each other internally have only 1 common tangent.

Here, Distance between the centres of two circles = Difference of their radii (i.e. $|r_1 - r_2|$)
<img src="../../../media/geometry/circle-29.png" alt="Geometry" style="width:81%;height:81%;">

#### Case 5: No Common tangents

Two circles, one inside the other but not touching have no common tangents. 

Here, Distance between the centres of two circles < Difference of their radii (i.e. $|r_1 - r_2|$)
<img src="../../../media/geometry/circle-30.png" alt="Geometry" style="width:36%;height:36%;">

