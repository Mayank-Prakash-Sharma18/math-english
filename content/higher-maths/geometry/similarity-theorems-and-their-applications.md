---
title: Similarity Theorems and their applications
linktitle: Similarity Theorems and their applications
toc: true
type: docs
date: "2021-08-15T00:00:00+01:00"
draft: false
menu:
  geometry:
    parent: 2. Triangle
    weight: 27

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 27
---

Now, as we have already understood the concept of similarity of triangles, let's see some of the theorems and concepts based on it and their applications. 

## Theorem 1: Thales theorem

Thales theorem is also known as ***Basic proportionality theorem***. 

A line segment, which is parallel to one of the sides of a triangle, cuts the other two sides of that triangle in the same ratio, and it will form a new triangle similar to the original triangle. 
<img src="../../../media/geometry/similarity-5.png" alt="Geometry" style="width:45%;height:45%;"> 

In the above figure, AB ∥ PQ. <br>
As ∠C = ∠C, ∠A = ∠P, ∠B = ∠Q, so ∆ABC ~ ∆PQR

And as ∆ABC ~ ∆PQR, $\frac{AB}{PQ}$ = $\frac{BC}{QC}$ = $\frac{AC}{PC}$

Also, $\frac{AP}{PC}$ = $\frac{BQ}{QC}$ <br>
$\frac{AC}{AP}$ = $\frac{BC}{BQ}$

{{% alert note %}}
The converse is also true. If a line segment divides two sides of a triangle in the same ratio, then this line segment must be parallel to the third side. 

That is, if $\frac{AP}{PC}$ = $\frac{BQ}{QC}$, then it means that PQ ∥ AB. 
{{% /alert %}}

Now, let us see some special cases of Thales theorem and some related rules. 

### Special case of Thales theorem

The line segment joining the mid-points of two sides of a triangle is parallel to and half in length of the third side of that triangle. 
<img src="../../../media/geometry/similarity-6.png" alt="Geometry" style="width:45%;height:45%;"> 

If P and Q are the mid-points of AC and BC, then PQ ∥ AB, and PQ = $\frac{1}{2}$ AB

So, Area of ∆PQC = $\frac{1}{4}$ ∆ABC <br>
And, Area of ∆PQC = $\frac{1}{3}$ □ABQP 

{{% alert note %}}
In other words, if a line parallel to one of the sides of a triangle bisects the second side, then it will bisect the third side too. 

If PQ ∥ AB & P is midpoint of AC, then Q too will be the midpoint of BC. 
{{% /alert %}}

### Related rule 

A line segment joining midpoints of two sides of a triangle will bisect the line joining the vertex to the third side too. 
<img src="../../../media/geometry/similarity-7.png" alt="Geometry" style="width:45%;height:45%;"> 

In above figure, as P and Q are the midpoints of sides AC and BC respectively, so CZ = XZ. 


## Theorem 2

In right-angled triangle, perpendicular drawn from the vertex of right angle to hypotenuse divides the triangle into two parts and forms two small triangles similar to each other and also similar to the original triangle.
<img src="../../../media/geometry/similarity-8.png" alt="Geometry" style="width:45%;height:45%;"> 

In the above figure, ∆ABC ~ ∆DAB ~ ∆DAC

* $AC^2$ = CB × CD   ... (1)
* $AB^2$ = BC × BD   ... (2)
* $AD^2$ = DC × DB   ... (3)

From these three we can drive three more equations. 

Using equations 1 and 2, we get: <br>
$\frac{AC^2}{AB^2}$ = $\frac{CD}{BD}$

Using equations 2 and 3, we get: <br>
$\frac{AB^2}{AD^2}$ = $\frac{BC}{DC}$

Using equations 1 and 3, we get: <br>
$\frac{AC^2}{AD^2}$ = $\frac{CB}{DB}$

* $\frac{1}{AD^2}$ = $\frac{1}{AC^2}$ + $\frac{1}{AB^2}$ <br><br>
or AD = $\frac{AC × AB}{BC}$


## Theorem 3: Related to Trapezium

Diagonals of trapezium (AB ∥ CD) divide it into four triangles. 
<img src="../../../media/geometry/similarity-9.png" alt="Geometry" style="width:54%;height:54%;"> 

* Two triangles along the parallel side are similar, i.e. ∆DOC ~ ∆AOB
* Two triangles along the non-parallel sides are equal in area, i.e. Area of ∆AOD = Area of ∆BOC

