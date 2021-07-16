---
# Course title, summary, and position.
linktitle: Introduction to Trigonometry
summary: This is a basic introduction to Trigonometry.
weight: 15

# Page metadata.
title: Introduction to Trigonometry
date: "2021-07-05T00:00:00Z"
lastmod: "2021-07-05T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  trigonometry:
    name: Overview
    weight: 1
---

## What is Trigonometry? 

Trigonometry is a branch of mathematics, that studies relationships involving sides and angles of triangles. 

{{% alert note %}}
So, in layman's terms, we can say that Trigonometry is the study of triangles. 
{{% /alert %}}

The word ‘Trigonometry’ has been made by combining three Greek words:
* ‘tri’ - it means three, 
* ‘gon’ - it means sides and 
* ‘metron’ - it means measure


## Functions in trigonometry

Functions in trigonometry are basically the ratios of the sides of a right-angled triangle. They express the relationship between the acute angle of a right-angled triangle and the length of its sides. 

Have a look at the following figure of a right-angled triangle.
<img src="../../../media/trigonometry/trigonometry-1.png" alt="Trigonometry" style="width:63%;height:63%;">

The main functions in trigonometry are: 

<table>
  <tr>
    <th>Name</th>
    <th>Trigonometry function</th>
  </tr>
  <tr>
    <td>Sine</td>
    <td>sin θ = $\frac{Perpendicular}{Hypotenuse}$ = $\frac{BC}{AC}$</td>
  </tr>
  <tr>
    <td>Cosine</td>
    <td>cos θ = $\frac{Base}{Hypotenuse}$ = $\frac{AB}{AC}$</td>
  </tr>
  <tr>
    <td>Tangent</td>
    <td>tan θ = $\frac{sin \hspace{1ex} θ}{cos \hspace{1ex} θ}$ = $\frac{Perpendicular}{Base}$ = $\frac{BC}{AB}$</td>
  </tr>
  <tr>
    <td>Cosecant</td>
    <td>cosec θ = $\frac{1}{sin \hspace{1ex} θ}$ = $\frac{Hypotenuse}{Perpendicular}$ = $\frac{AC}{BC}$</td>
  </tr>
  <tr>
    <td>Secant</td>
    <td>sec θ = $\frac{1}{cos \hspace{1ex} θ}$ = $\frac{Hypotenuse}{Base}$ = $\frac{AC}{AB}$</td>
  </tr>
  <tr>
    <td>Cotangent</td>
    <td>cot θ = $\frac{1}{tan \hspace{1ex} θ}$ = $\frac{cos \hspace{1ex} θ}{sin \hspace{1ex} θ}$ = $\frac{Base}{Perpendicular}$ = $\frac{AB}{BC}$</td>
  </tr>
</table>

{{% alert note %}}
Sine, Cosine, Tangent, Cosecant, Secant and Cotangent are often abbreviated as sin, cos, tan, cosec, sec, and cot respectively.
{{% /alert %}}

{{% alert note %}}
To remember these ratio, we can memorize them using a mnemonic:
<img src="../../../media/trigonometry/trigonometry-2.png" alt="Trigonometry" style="width:45%;height:45%;">
P → Perpendicular; B → Base; H → Hypotenuse
{{% /alert %}}


### Values of Trigonometric Functions 

Have a look at the values of Trigonometric Functions for some important angles from 0° to 90°. 
<img src="../../../media/trigonometry/trigonometry-3.png" alt="Trigonometry" style="width:90%;height:90%;">

{{% alert note %}}
You should remember these values. 

Just remember sin and cos values, and maybe tan values too. Though you may find out the tan values by dividing sin values by corresponding cos values. 

Values of cosec, sec and cot are reciprocal of the values of sin, cos and tan respectively. 
{{% /alert %}}

{{% alert note %}}
$\frac{1}{0}$ = ∞; $\frac{-1}{0}$ = -∞

Both of these are not defined. 
{{% /alert %}}


### Signs of Trigonometric Functions

So, now we know the values of Trigonometric Functions for angles such as 30°, 45°, 90° etc. All of these angles fall in the first quadrant. 
<img src="../../../media/trigonometry/trigonometry-4.png" alt="Trigonometry" style="width:81%;height:81%;">

But what about such angles in other quadrants, e.g. 120°, 225°, 180° etc. ?

Here are the three steps that you need to follow:

* Step 1: Find out the quadrant to which the angle belongs.

* Step 2: Use the appropriate formula, to find the value of the concerned Trigonometric Function.

* Step 3: Don't forget to use the appropriate sign.

<img src="../../../media/trigonometry/trigonometry-5.png" alt="Trigonometry" style="width:99%;height:99%;">

We can draw following conclusions from the above table:

* The sign of the Trigonometric Function will depend on which quadrant the angle falls in. It can be represented using the following figure:
<img src="../../../media/trigonometry/trigonometry-6.png" alt="Trigonometry" style="width:81%;height:81%;">

* When the angle is a multiple of 180°, e.g. 0°, 180°, 360°, ... etc., then trigonometric function will not get changed. For example, sin (180° - θ) = sin θ, tan (180° + θ) = tan θ etc. 

* When the angle is an odd multiple of 90°, e.g. 90°, 270°, ... etc., then trigonometric function will get changed. For example, cos (90° - θ) = sin θ, sin (270° - θ) = - cos θ

{{% alert note %}}
Also, note that:
<img src="../../../media/trigonometry/trigonometry-7.png" alt="Trigonometry" style="width:36%;height:36%;">
{{% /alert %}}


## Relation between Degree and Radian 

1 radian = $\frac{180°}{π}$

And 1° = $\frac{π}{180°}$ radian 

For example, 90° = 90° × $\frac{π}{180°}$ = $\frac{π}{2}$ radian 

{{% alert note %}}
180° can also be written as π <br>
360° can also be written as 2π

Have a look at the diagram shown below:
<img src="../../../media/trigonometry/trigonometry-9.svg" alt="Trigonometry" style="width:54%;height:54%;">
{{% /alert %}}

In a circle, radian of the angle made by an arc on the centre of the circle, is the ratio of the length of the arc and the radius of the circle. 

In other words, an arc of the same length as that of the radius, will make an angle of 1 radian at the centre of the circle.
<img src="../../../media/trigonometry/trigonometry-10.svg" alt="Trigonometry" style="width:54%;height:54%;">
