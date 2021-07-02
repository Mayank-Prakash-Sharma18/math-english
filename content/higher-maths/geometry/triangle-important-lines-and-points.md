---
title: Important Lines and Points related to a Triangle 
linktitle: Important Lines and Points
toc: true
type: docs
date: "2021-06-27T00:00:00+01:00"
draft: true
menu:
  geometry:
    parent: 2. Triangle
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

In this article, we are going to learn about some important lines and points that are related to a triangle. You will encounter many questions in aptitude exams from this section.

If we drop a line from any vertex of a triangle to the opposite side (or extended opposite side), then that line is called a ***Cevian***. 
<img src="../../../media/geometry/triangle-lines-points-1.png" alt="Geometry" style="width:54%;height:54%;">
There are various types of cevians in a triangle: Medians, Altitudes, Angle Bisectors. 

We will study about all these, along with some other important lines like Perpendicular Bisectors. 

## Medians

A median is a straight line that joins a vertex of a triangle to the mid-point of the opposite side. 
<img src="../../../media/geometry/triangle-lines-points-2.png" alt="Geometry" style="width:54%;height:54%;">
If AD = DB, then CD must be a median.

### Properties of Medians

#### Property 1: Position of Medians

As a triangle has three vertices, it obviously will have three medians. And all of the three medians will always lie inside the triangle. This is true for any triangle. 

#### Property 2: Length of Medians

* In equilateral triangle, all the three medians have the same length.

* In scalene triangle, all the three medians are unequal.

* In Isosceles triangle, two medians are equal, while the third one is of a different length. Medians drawn from vertex of two equal angles are equal. While, the median drawn from vertex of the unequal angle is of a different length, is perpendicular to the side and bisects the vertex angle.
<img src="../../../media/geometry/triangle-lines-points-3.png" alt="Geometry" style="width:54%;height:54%;">

* In right-angled triangle, the median drawn from vertex of right angle to hypotenuse is equal to half of the hypotenuse. 
<img src="../../../media/geometry/triangle-lines-points-4.png" alt="Geometry" style="width:54%;height:54%;">
AD = $\frac{1}{2}$ BC

{{% alert note %}}
The other way round is also true. That is, if a median is equal to half of its corresponding side, then it means that the triangle must be a right-angled triangle.
{{% /alert %}}

{{% alert note %}}
* Perimeter of a triangle > Sum of the three medians of a triangle

* Sum of any two sides of a triangle > Twice the median drawn to the third side.
<img src="../../../media/geometry/triangle-lines-points-9.png" alt="Geometry" style="width:54%;height:54%;">
CA + CB > 2 CD
{{% /alert %}}

Now, let's see some more properties related to medians.

#### Property 3

Medians divide the triangle into six small triangles. Each of these small triangles have equal area.
<img src="../../../media/geometry/triangle-lines-points-8.png" alt="Geometry" style="width:54%;height:54%;">

#### Property 4

A line segment joining any vertex and midpoint of a median, if extended, divides the third side into a ratio of 1 : 2.
<img src="../../../media/geometry/triangle-lines-points-10.png" alt="Geometry" style="width:54%;height:54%;">
If CD is median, and P is midpoint of CD then: 
* CQ : QB = 1 : 2 OR
* CQ = $\frac{1}{3}$ CB


### Centroid

Centroid of a triangle is a point where all of its three medians intersect. 
<img src="../../../media/geometry/triangle-lines-points-5.png" alt="Geometry" style="width:54%;height:54%;">

{{% alert note %}}
The three medians of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Centroid

#### Property 1

Centroid divides the median in a ratio of 2 : 1.
<img src="../../../media/geometry/triangle-lines-points-6.png" alt="Geometry" style="width:54%;height:54%;">

#### Property 2

If we form a triangle by joining the centroid, and the midpoints of any two sides, then its area will be $\frac{1}{12}$th of the area of the original triangle.
<img src="../../../media/geometry/triangle-lines-points-7.png" alt="Geometry" style="width:54%;height:54%;">
Area of ∆DPQ = $\frac{1}{12}$ × Area of ∆ABC

<br><hr><br>

## Altitudes

An altitude of a triangle, is a perpendicular line segment drawn from any vertex to the opposite side. So, it's basically the ***height*** of a triangle. 
<img src="../../../media/geometry/triangle-lines-points-11.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, CD is the altitude with respect to the side AB.

{{% alert note %}}
Obviously, an altitude is going to be the shortest distance from a vertex to its opposite side.
{{% /alert %}}

### Properties of Altitudes

#### Property 1: Position of Altitudes

* In any acute angled triangle, all the three altitudes lie inside the triangle.

* In a right angled triangle, the two sides containing right angle are also the altitudes. While, the altitude from vertex of right angle to hypotenuse will lie inside the triangle.
<img src="../../../media/geometry/triangle-lines-points-14.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, CA, BA & AD are altitudes on the sides AB, AC & BC respectively.

* In obtuse angled triangle, two altitudes from acute angles will lie outside of the triangle. While the altitude from the obtuse angle will lie inside of the triangle.
<img src="../../../media/geometry/triangle-lines-points-15.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, AP, BQ and CR are altitudes on the sides BC, AC & AB respectively.

#### Property 2: Length of Altitudes

* The longest side has the least corresponding altitude. Similarly, the shortest side has the longest corresponding altitude.

* In equilateral triangle, altitude and median are the same. And so, just as was the case with medians, all the three altitudes are equal in length.
<img src="../../../media/geometry/triangle-lines-points-12.png" alt="Geometry" style="width:54%;height:54%;">

* In scalene triangle, all the three altitudes are unequal.

* In Isosceles triangle, two altitudes are equal, while the third one is of a different length. Altitudes/Perpendiculars drawn from vertex of two equal angles (to opposite equal sides) are equal. While, the altitude/perpendicular drawn from vertex of the unequal angle (to opposite unequal side) is of a different length, is median to the side and bisects the vertex angle (i.e. it is altitude, median and angular bisector).
<img src="../../../media/geometry/triangle-lines-points-13.png" alt="Geometry" style="width:54%;height:54%;">
If CA = CB then AP = BQ <br>
CR is not only the altitude, but also the median and angular bisector of ∠ACB.


### Orthocentre

Orthocentre of a triangle is a point where all of its three altitudes intersect. 
<img src="../../../media/geometry/triangle-lines-points-16.png" alt="Geometry" style="width:54%;height:54%;">

{{% alert note %}}
The three altitudes of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Orthocentre

#### Property 1: Position of Orthocentre

* In any acute angled triangle, orthocentre will lie inside the triangle.
<img src="../../../media/geometry/triangle-lines-points-18.png" alt="Geometry" style="width:54%;height:54%;">

* In any right angled triangle, orthocentre is the vertex of the right angle.
 <img src="../../../media/geometry/triangle-lines-points-19.png" alt="Geometry" style="width:54%;height:54%;">

*	In any obtuse angled triangle, orthocentre will lie outside the triangle.
<img src="../../../media/geometry/triangle-lines-points-20.png" alt="Geometry" style="width:54%;height:54%;">

#### Property 2

* In any equilateral triangle, the centroid and orthocentre are the same point.

*	In isosceles triangle vertex, centroid and orthocentre are collinear points.

*	In scalene triangle vertex, centroid and orthocentre are three non-collinear points.

{{% alert note %}}
Sum of three altitudes of a triangle < Sum of three sides of the triangle
{{% /alert %}}

#### Property 3

We already know that, in any isosceles triangle centroid and orthocentre are different, but collinear points.

Moreover, in any isosceles triangle, both of these points lie on the altitude and median drawn from the vertex of the unequal angle to the opposite unequal side. 
<img src="../../../media/geometry/triangle-lines-points-21.png" alt="Geometry" style="width:54%;height:54%;">

The other way round is also true. If in a triangle, we find that the line joining the centroid and orthocentre is the altitude of any side and also bisects it (as a median does), then that triangle must be an isosceles triangle.

#### Property 4

Angle made by any side of a triangle on ortho-centre is supplementary of its opposite angle.
<img src="../../../media/geometry/triangle-lines-points-17.png" alt="Geometry" style="width:54%;height:54%;">

<br><hr><br>

## Angle Bisectors

An angle bisector of a triangle, is a line segment joining a vertex to the opposite side, such that it bisects the vertex angle.  
<img src="../../../media/geometry/triangle-lines-points-22.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, CD is the angle bisector of the angle ∠ACB.

### Properties of Angle Bisectors

#### Property 1: Position of Angle Bisectors

As a triangle has three vertices, it obviously will have three angle bisectors. And all of the three angle bisectors will always lie inside the triangle (just like medians). This is true for any triangle. 

#### Property 2: Length of Angle Bisectors

*	In any equilateral triangle, all the three angle bisectors have the same length.

{{% alert note %}}
In any equilateral triangle, median, altitude and angle bisector are the same line segment.
{{% /alert %}}

*	In any scalene triangle, all the three angle bisectors are unequal in length.

* In any isosceles triangle, two angle bisectors are equal, while the third one is of a different length. Angle bisectors drawn from vertex of two equal angles are equal. While, the angle bisector drawn from vertex of the unequal angle is of a different length, is altitude, as well as median to the opposite side.
<img src="../../../media/geometry/triangle-lines-points-23.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, ∆ABC is an isosceles triangle, as ∠A = ∠B. AP, BQ & CR are angle bisectors, and AP = BQ.

#### Property 3

Angular bisector of a triangle divides the opposite side in the ratio of the other two sides.
<img src="../../../media/geometry/triangle-lines-points-31.png" alt="Geometry" style="width:54%;height:54%;">
If in the above figure CD is an angular bisector, then $\frac{AD}{BD}$ = $\frac{AC}{BC}$

{{% alert note %}}
In other words, we can say that if a line passing through a vertex of a triangle divides the opposite side in the ratio of the other two sides, then the line must be the angular bisecor of the angle at the vertex.
{{% /alert %}}

{{% alert note %}}
Similarly, the external angular bisector of an angle of a triangle divides the opposite side externally in the ratio of the sides containing the angle.
<img src="../../../media/geometry/triangle-lines-points-32.png" alt="Geometry" style="width:54%;height:54%;">
If in the above figure CD is an external angular bisector, then $\frac{AD}{BD}$ = $\frac{AC}{BC}$
{{% /alert %}}

#### Property 4: Angle made by two Angular Bisectors

##### Angular Bisectors of interior angles

The angle made by angular bisectors of any two angles = 90° + $\frac{1}{2}$ × Third angle.
<img src="../../../media/geometry/triangle-lines-points-24.png" alt="Geometry" style="width:54%;height:54%;">
∠ADC = 90° + $\frac{1}{2}$ ∠ACB

{{% alert note %}}
In other words, we can say that the angle made by any side of a triangle on incentre is equal to 90° + $\frac{1}{2}$ × Opposite angle

We will study about incentre soon. 
{{% /alert %}}

##### Angular Bisectors of exterior angles

The angle made by angular bisectors of any two exterior angles = 90° - $\frac{1}{2}$ × Third angle.
<img src="../../../media/geometry/triangle-lines-points-25.png" alt="Geometry" style="width:54%;height:54%;">
∠ADC = 90° - $\frac{1}{2}$ ∠ACB

##### Angular Bisectors of interior angle and exterior angle

The angle made by angular bisectors of one interior and one exterior angle = $\frac{1}{2}$ × Third angle..
<img src="../../../media/geometry/triangle-lines-points-26.png" alt="Geometry" style="width:54%;height:54%;">
∠ADC = $\frac{1}{2}$ ∠ACB

#### Property 5

Angle made by altitude and angle bisector on a vertex = Half of the difference between other two opposite angles
<img src="../../../media/geometry/triangle-lines-points-33.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, CD is the altitude (CD ⊥ AB) and CE is the angular bisector of ∠C. <br>
So, ∠DCE = $\frac{1}{2}$ (∠A – ∠B)


### Incentre

Incentre of a triangle is a point where all of its three internal bisectors intersect. 
<img src="../../../media/geometry/triangle-lines-points-27.png" alt="Geometry" style="width:54%;height:54%;">

{{% alert note %}}
The three internal bisectors of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Incentre

#### Property 1: Position of Incentre

In any triangle, incentre will always lie inside the triangle.

#### Property 2

Incentre of a triangle is equidistant from all the three sides of that triangle.
<img src="../../../media/geometry/triangle-lines-points-28.png" alt="Geometry" style="width:54%;height:54%;">
In the above figure, IP = IQ = IR

#### Property 3

*	In any equilateral triangle, centroid, orthocentre, and incentre are the same point.

* In any isosceles triangle, centroid, orthocentre and incentre are three different collinear points.

*	In any scalene triangle, centroid, orthocentre and incentre are three different non-collinear points.

#### Property 4

We already know that, in any isosceles triangle centroid, orthocentre and incentre are different, but collinear points.

Moreover, in any isosceles triangle, all of these three points lie on the angle-bisector, altitude, and median drawn from the vertex of the unequal angle to the opposite unequal side. 


### Incircle

Incircle is a circle inside a triangle, such that:
* it touches all the three sides of that triangle and 
* its centre is the incentre of that triangle

<img src="../../../media/geometry/triangle-lines-points-29.png" alt="Geometry" style="width:54%;height:54%;">

### Inradius formulae

#### Inradius Formula 1
Inradius of any triangle = $\frac{Area \hspace{1ex} of \hspace{1ex} Triangle}{Semi \hspace{1ex} Perimeter \hspace{1ex} of \hspace{1ex} Triangle}$

#### Inradius Formula 2

<img src="../../../media/geometry/triangle-lines-points-30.png" alt="Geometry" style="width:54%;height:54%;">
Inradius of right-angled triangle = $\frac{Base + Height - Hypotenuse}{2}$

<br><hr><br>

## Perpendicular Bisectors



 
 


