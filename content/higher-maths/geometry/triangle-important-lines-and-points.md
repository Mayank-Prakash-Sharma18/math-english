---
title: Important Lines and Points related to a Triangle 
linktitle: Important Lines and Points
toc: true
type: docs
date: "2021-06-27T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 2. Triangle
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

In this article, we are going to learn about some important lines and points that are related to a triangle. You will encounter many questions in aptitude exams from this section.

If we drop a line from any vertex of a triangle to the opposite side (or extended opposite side), then that line is called a ***Cevian***. 
<img src="../../../media/geometry/triangle-lines-points-1.png" alt="Geometry" style="width:90%;height:90%;">
There are various types of cevians in a triangle: Medians, Altitudes, Angle Bisectors. 

We will study about all these, along with some other important lines like Perpendicular Bisectors. 

## Medians

A median is a straight line that joins a vertex of a triangle to the mid-point of the opposite side. 
<img src="../../../media/geometry/triangle-lines-points-2.png" alt="Geometry" style="width:90%;height:90%;">
If AD = DB, then CD must be a median.

### Properties of Medians

#### Property 1: Position of Medians

As a triangle has three vertices, it obviously will have three medians. And all of the three medians will always lie inside the triangle. This is true for any triangle. 

#### Property 2: Length of Medians

* In equilateral triangle, all the three medians have the same length.

* In scalene triangle, all the three medians are unequal.

* In Isosceles triangle, two medians are equal, while the third one is of a different length. Medians drawn from vertex of two equal angles are equal. While, the median drawn from vertex of the unequal angle is of a different length, is perpendicular to the side and bisects the vertex angle.
<img src="../../../media/geometry/triangle-lines-points-3.png" alt="Geometry" style="width:63%;height:63%;">

* In right-angled triangle, the median drawn from vertex of right angle to hypotenuse is equal to half of the hypotenuse. 
<img src="../../../media/geometry/triangle-lines-points-4.png" alt="Geometry" style="width:63%;height:63%;">
AD = $\frac{1}{2}$ BC

{{% alert note %}}
The other way round is also true. That is, if a median is equal to half of its corresponding side, then it means that the triangle must be a right-angled triangle.
{{% /alert %}}

{{% alert note %}}
* Perimeter of a triangle > Sum of the three medians of a triangle

* Sum of any two sides of a triangle > Twice the median drawn to the third side.
<img src="../../../media/geometry/triangle-lines-points-2.png" alt="Geometry" style="width:99%;height:99%;">
CA + CB > 2 CD
{{% /alert %}}

Now, let's see some more properties related to medians.

#### Property 3

Medians divide the triangle into six small triangles. Each of these small triangles have equal area.
<img src="../../../media/geometry/triangle-lines-points-8.png" alt="Geometry" style="width:90%;height:90%;">

#### Property 4

A line segment (AQ) joining any vertex and midpoint of a median (P), if extended, divides the third side (CB) into a ratio of 1 : 2.
<img src="../../../media/geometry/triangle-lines-points-10.png" alt="Geometry" style="width:90%;height:90%;">
If CD is median, and P is midpoint of CD then: 
* CQ : QB = 1 : 2 OR
* CQ = $\frac{1}{3}$ CB


### Centroid

Centroid of a triangle is a point where all of its three medians intersect. 
<img src="../../../media/geometry/triangle-lines-points-5.png" alt="Geometry" style="width:90%;height:90%;">

{{% alert note %}}
The three medians of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Centroid

#### Property 1

Centroid divides the median in a ratio of 2 : 1.
<img src="../../../media/geometry/triangle-lines-points-6.png" alt="Geometry" style="width:90%;height:90%;">
For example, in the above figure OC : OD = 2 : 1

#### Property 2

If we form a triangle by joining the centroid, and the midpoints of any two sides, then its area will be $\frac{1}{12}$th of the area of the original triangle.
<img src="../../../media/geometry/triangle-lines-points-7.png" alt="Geometry" style="width:90%;height:90%;">
Area of ∆OPQ = $\frac{1}{12}$ × Area of ∆ABC

<br><hr><br>

## Altitudes

An altitude of a triangle, is a perpendicular line segment drawn from any vertex to the opposite side. So, it's basically the ***height*** of a triangle. 
<img src="../../../media/geometry/triangle-lines-points-11.png" alt="Geometry" style="width:90%;height:90%;">
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
<img src="../../../media/geometry/triangle-lines-points-15.png" alt="Geometry" style="width:99%;height:99%;">
In the above figure, AP, BQ and CR are altitudes on the sides BC, AC & AB respectively.

#### Property 2: Length of Altitudes

* The longest side has the least corresponding altitude. Similarly, the shortest side has the longest corresponding altitude.

* In equilateral triangle, altitude and median are the same. And so, just as was the case with medians, all the three altitudes are equal in length.
<img src="../../../media/geometry/triangle-lines-points-12.png" alt="Geometry" style="width:54%;height:54%;">

* In scalene triangle, all the three altitudes are unequal.

* In Isosceles triangle, two altitudes are equal, while the third one is of a different length. Altitudes/Perpendiculars drawn from vertex of two equal angles (to opposite equal sides) are equal. While, the altitude/perpendicular drawn from vertex of the unequal angle (to opposite unequal side) is of a different length, is median to the side and bisects the vertex angle (i.e. it is altitude, median and angular bisector).
<img src="../../../media/geometry/triangle-lines-points-13.png" alt="Geometry" style="width:99%;height:99%;">
If CA = CB then AP = BQ <br>
CR is not only the altitude, but also the median and angular bisector of ∠ACB.


### Orthocentre

Orthocentre of a triangle is a point where all of its three altitudes intersect. 
<img src="../../../media/geometry/triangle-lines-points-16.png" alt="Geometry" style="width:63%;height:63%;">

{{% alert note %}}
The three altitudes of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Orthocentre

#### Property 1: Position of Orthocentre

* In any acute angled triangle, orthocentre will lie inside the triangle.
<img src="../../../media/geometry/triangle-lines-points-16.png" alt="Geometry" style="width:63%;height:63%;">

* In any right angled triangle, orthocentre is the vertex of the right angle.
 <img src="../../../media/geometry/triangle-lines-points-19.png" alt="Geometry" style="width:54%;height:54%;">

*	In any obtuse angled triangle, orthocentre will lie outside the triangle.
<img src="../../../media/geometry/triangle-lines-points-20.png" alt="Geometry" style="width:99%;height:99%;">

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
<img src="../../../media/geometry/triangle-lines-points-21.png" alt="Geometry" style="width:63%;height:63%;">

The other way round is also true. If in a triangle, we find that the line joining the centroid and orthocentre is the altitude of any side and also bisects it (as a median does), then that triangle must be an isosceles triangle.

#### Property 4

Angle made by any side of a triangle on ortho-centre is supplementary of its opposite angle.
<img src="../../../media/geometry/triangle-lines-points-17.png" alt="Geometry" style="width:63%;height:63%;">
So, ∠AOB + ∠ACB = 180°

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
<img src="../../../media/geometry/triangle-lines-points-23.png" alt="Geometry" style="width:99%;height:99%;">
In the above figure, ∆ABC is an isosceles triangle, as ∠A = ∠B. AP, BQ & CR are angle bisectors, and AP = BQ.

#### Property 3

Angular bisector of a triangle divides the opposite side in the ratio of the other two sides.
<img src="../../../media/geometry/triangle-lines-points-22.png" alt="Geometry" style="width:54%;height:54%;">
If in the above figure CD is an angular bisector, then $\frac{AD}{BD}$ = $\frac{AC}{BC}$

{{% alert note %}}
In other words, we can say that if a line passing through a vertex of a triangle divides the opposite side in the ratio of the other two sides, then the line must be the angular bisecor of the angle at the vertex.
{{% /alert %}}

{{% alert note %}}
Similarly, the external angular bisector of an angle of a triangle divides the opposite side externally in the ratio of the sides containing the angle.
<img src="../../../media/geometry/triangle-lines-points-32.png" alt="Geometry" style="width:81%;height:81%;">
If in the above figure CD is an external angular bisector, then $\frac{AD}{BD}$ = $\frac{AC}{BC}$
{{% /alert %}}

#### Property 4: Angle made by two Angular Bisectors

##### Angular Bisectors of interior angles

The angle made by angular bisectors of any two angles = 90° + $\frac{1}{2}$ × Third angle.
<img src="../../../media/geometry/triangle-lines-points-24.png" alt="Geometry" style="width:90%;height:90%;">
∠ADB = 90° + $\frac{1}{2}$ ∠ACB

{{% alert note %}}
In other words, we can say that the angle made by any side of a triangle on incentre is equal to 90° + $\frac{1}{2}$ × Opposite angle

We will study about incentre soon. 
{{% /alert %}}

##### Angular Bisectors of exterior angles

The angle made by angular bisectors of any two exterior angles = 90° - $\frac{1}{2}$ × Third angle.
<img src="../../../media/geometry/triangle-lines-points-25.png" alt="Geometry" style="width:99%;height:99%;">
∠ADB = 90° - $\frac{1}{2}$ ∠ACB

##### Angular Bisectors of interior angle and exterior angle

The angle made by angular bisectors of one interior and one exterior angle = $\frac{1}{2}$ × Third angle..
<img src="../../../media/geometry/triangle-lines-points-26.png" alt="Geometry" style="width:99%;height:99%;">
∠ADB = $\frac{1}{2}$ ∠ACB

#### Property 5

Angle made by altitude and angle bisector on a vertex = Half of the difference between other two opposite angles
<img src="../../../media/geometry/triangle-lines-points-33.png" alt="Geometry" style="width:90%;height:90%;">
In the above figure, CD is the altitude (CD ⊥ AB) and CE is the angular bisector of ∠C. <br>
So, ∠DCE = $\frac{1}{2}$ (∠A – ∠B)


### Incentre

Incentre of a triangle is a point where all of its three internal bisectors intersect. 
<img src="../../../media/geometry/triangle-lines-points-27.png" alt="Geometry" style="width:90%;height:90%;">

{{% alert note %}}
The three internal bisectors of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}

### Properties related to Incentre

#### Property 1: Position of Incentre

In any triangle, incentre will always lie inside the triangle.

#### Property 2

Incentre of a triangle is equidistant from all the three sides of that triangle.
<img src="../../../media/geometry/triangle-lines-points-28.png" alt="Geometry" style="width:90%;height:90%;">
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

<img src="../../../media/geometry/triangle-lines-points-29.png" alt="Geometry" style="width:90%;height:90%;">

#### Inradius formulae

##### Inradius Formula 1
Inradius of any triangle = $\frac{Area \hspace{1ex} of \hspace{1ex} Triangle}{Semi \hspace{1ex} Perimeter \hspace{1ex} of \hspace{1ex} Triangle}$

##### Inradius Formula 2

<img src="../../../media/geometry/triangle-lines-points-30.png" alt="Geometry" style="width:72%;height:72%;">
Inradius of right-angled triangle = $\frac{Base + Height - Hypotenuse}{2}$


### Excentre

Excentre of a triangle is a point where one of its internal bisectors and two of its external bisectors intersect, i.e. it is the intersection point of the internal bisector of one angle and the external bisectors of the other two angles.
<img src="../../../media/geometry/triangle-lines-points-40.png" alt="Geometry" style="width:99%;height:99%;">

### Excircle

An excircle or escribed circle of a triangle is tangent to one of its sides and also tangent to the extensions of the other two sides. It always lies outside the triangle.

Every triangle has three distinct excircles, each tangent to one of the sides of the triangle.

{{% alert note %}}
* Excircles of a triangle are always larger than its incircle.

* The largest excircle of a triangle is tangent to its longest side, while the smallest excircle is tangent to its shortest side.
{{% /alert %}}

#### Exradii
 
The radii of the excircles are called the exradii. As we have 3 excircles in a triangle, we have 3 exradii too. 
<img src="../../../media/geometry/triangle-lines-points-41.png" alt="Geometry" style="width:99%;height:99%;">

In the triangle shown above, if a, b & c are the sides of the triangle ABC, s is the semi-perimeter of the triangle ABC, and ∆ is the area of the triangle ABC, then:

$r_1$ = $\frac{∆}{s - a}$ <br><br>
$r_2$ = $\frac{∆}{s - b}$ <br><br>
$r_3$ = $\frac{∆}{s - c}$ 

<br><hr><br>

## Perpendicular Bisectors

Perpendicular Bisector of a side of a triangle is a line that passes through the mid-point of that side and is also perpendicular to it. 
<img src="../../../media/geometry/triangle-lines-points-34.png" alt="Geometry" style="width:90%;height:90%;">

{{% alert note %}}
Unlike medians, altitudes and angle bisectors, it is not necessary for a perpendicular bisector to pass through any vertex. 
{{% /alert %}}

### Properties of Perpendicular Bisectors

#### Property 1: Length of Perpendicular Bisectors

* In equilateral triangle, all the three perpendicular bisectors have the same length.

{{% alert note %}}
In any equilateral triangle, median, altitude, angle bisector and perpendicular bisector are the same line segment.
{{% /alert %}}

*	In any scalene triangle, all the three perpendicular bisectors are unequal in length. None of them pass through the vertices. 

* In any isosceles triangle, two perpendicular bisectors are equal, while the third one is of a different length. Perpendicular bisectors drawn on equal sides are equal. While, the perpendicular bisector drawn on the unequal side is of a different length, is median, altitude, as well as angle bisector.
<img src="../../../media/geometry/triangle-lines-points-35.png" alt="Geometry" style="width:90%;height:90%;">
In the figure given above, PP' = QQ'

{{% alert note %}}
Perpendicular bisectors drawn on equal sides of an isosceles triangle do not pass through the vertices.
{{% /alert %}}


### Circumcentre

Circumcentre of a triangle is a point where the three perpendicular bisectors of its sides intersect. 
<img src="../../../media/geometry/triangle-lines-points-36.png" alt="Geometry" style="width:90%;height:90%;">

{{% alert note %}}
In other words, the line segment joining circumcentre and midpoint of any side of the triangle must be perpendicular on that side and vice-versa.
{{% /alert %}}

{{% alert note %}}
The three perpendicular bisectors of any triangle are always concurrent. That is, they always have a common point of intersection.
{{% /alert %}}


### Properties related to Circumcentre

#### Property 1: Position of Circumcentre

* In any acute angled triangle, circumcentre will always lie inside the triangle.
* In any right angled triangle, circumcentre will always be at the midpoint of hypotenuse.
* In any obtuse angled triangle, circumcentre will always lie outside of the triangle.

#### Property 2

Circumcentre of a triangle is equidistant from all the three vertices of that triangle.
<img src="../../../media/geometry/triangle-lines-points-37.png" alt="Geometry" style="width:90%;height:90%;">
In the above figure, DA = DB = DC

#### Property 3

*	In any equilateral triangle, centroid, orthocentre, incentre and circumcentre are the same point.

* In any isosceles triangle, centroid, orthocentre, incentre and circumcentre are four different collinear points.

*	In any scalene triangle, centroid, orthocentre, incentre and circumcentre are four different non-collinear points.

#### Property 4

We already know that, in any isosceles triangle centroid, orthocentre, incentre and circumcentre are different, but collinear points.

Moreover, in any isosceles triangle, all of these four points lie on the line segment joining vertex and midpoint of unequal side. 

#### Property 5

Angle made by any side of a triangle on circumcentre is twice of the opposite angle.
<img src="../../../media/geometry/triangle-lines-points-38.png" alt="Geometry" style="width:90%;height:90%;">
In the above figure, ∠ADC = 2 ∠ABC

{{% alert note %}}
Angle formed by a chord (AB) of a circle on major arc is half the angle formed by it on the centre of that circle.
{{% /alert %}}


### Circumcircle

Circumcircle is a circle that passes through all the three vertices of a triangle and its centre is the circumcentre of that triangle.
<img src="../../../media/geometry/triangle-lines-points-39.png" alt="Geometry" style="width:99%;height:99%;">

#### Circumradius formulae

##### Circumradius formula 1

Length of circumradius = $\frac{Product \hspace{1ex} of \hspace{1ex} sides}{4 × Area \hspace{1ex} of \hspace{1ex} triangle}$

##### Circumradius formula 2

In any right angled triangle, the hypotenuse is the diameter of its circumcircle.

##### Circumradius formula 3

In any equilateral triangle, which has sides of length 'a' each:

In-radius = $\frac{a}{2\sqrt{3}}$ and Circumradius = $\frac{a}{\sqrt{3}}$ <br>
So, Inradius : circumradius = 1 : 2 <br>
Hence, Area of incircle : Area of circumcircle= 1 : 4 

