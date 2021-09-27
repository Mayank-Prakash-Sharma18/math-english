---
title: Coordinate Geometry - Two Lines
linktitle: Two Lines
toc: true
type: docs
date: "2021-09-23T00:00:00+01:00"
draft: false
menu:
  coordinate-geometry:
    parent: 2. Lines
    weight: 18

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 18
---

In this article, we will discuss some of the concepts related to two lines (on the same plane) - intersecting or parallel. 

## How to find whether two lines are parallel or not?

Two lines on the same plane are parallel if their slopes are equal. Otherwise, they will intersect at some point. 

If the two lines are y = $m_1x + c_1$ and y = $m_2x + c_2$, then: <br>
They will be parallel if $m_1 = m_2$ <br>
$m_1$ and $m_2$ are slopes of the lines. 

If the two lines are $a_1x + b_1y + c_1$ = 0 and $a_2x + b_2y + c_2$ = 0, then: <br>
They will be parallel if $\frac{a_1}{a_2} = \frac{b_1}{b_2}$, or $a_1 b_2 – a_2 b_1$ = 0 <br>

## How to find whether two lines are perpendicular or not?

Two lines on the same plane are perpendicular if the product of their slopes is -1. 

If the two lines are y = $m_1x + c_1$ and y = $m_2x + c_2$, then: <br>
They will be perpendicular if $m_1 × m_2$ = -1 <br>
$m_1$ and $m_2$ are slopes of the lines. 

If the two lines are $a_1x + b_1y + c_1$ = 0 and $a_2x + b_2y + c_2$ = 0, then: <br>
They will be perpendicular if $\frac{a_1}{b_1} = -\frac{b_2}{a_2}$, or $a_1 a_2 + b_1 b_2$ = 0 <br>

## Distance between Parallel lines

Distance between parallel lines always remain the same. To find it we can use the following formula. 

The distance between two parallel lines $ax + by + c_1$ = 0 and $ax + by + c_2$ = 0, is: <br>
d = $\frac{|c_1 - c_2|}{\sqrt{a^2 + b^2}}$

## Point of intersection of two lines

If we have two lines $a_1x + b_1y + c_1$ = 0 and $a_2x + b_2y + c_2$ = 0, then:

$\frac{x}{b_1 c_2 – b_2 c_1} = \frac{y}{c_1 a_2 – c_2 a_1} = \frac{1}{a_1 b_2 – a_2 b_1}$

Thus, point of intersection of these two lines = $\frac{b_1 c_2 – b_2 c_1}{a_1 b_2 – a_2 b_1}, \frac{c_1 a_2 – c_2 a_1}{a_1 b_2 – a_2 b_1}$ <br>
Where $a_1 b_2 – a_2 b_1$ ≠ 0

## Angle between two lines

If θ is the angle between two lines y = $m_1x + c_1$ and y = $m_2x + c_2$, then: <br>
tan θ = $|\frac{m_2 - m_1}{1 + m_2 m_1}|$ or $|\frac{m_1 - m_2}{1 + m_1 m_2}|$ 

If θ is the angle between two lines $a_1x + b_1y + c_1$ = 0 and $a_2x + b_2y + c_2$ = 0, then: <br>
tan θ = $\frac{a_2 b_1 – a_1 b_2}{a_1 a_2 + b_1 b_2}$ 

## Condition of concurrency of three lines

If three lines meet at a single common point, then those three lines are said to be concurrent. 

Three lines $a_1x + b_1y + c_1$ = 0, $a_2x + b_2y + c_2$ = 0, and $a_3x + b_3y + c_3$ = 0, are concurrent if: <br>
$\begin{vmatrix}
a_1 & b_1 & c_1 \newline
a_2 & b_2 & c_2 \newline
a_3 & b_3 & c_3 
\end{vmatrix}$ = 0

or $a_1 (b_2 c_3 – b_3 c_2) – b_1 (a_2 c_3 – a_3 c_2) + c_1 (a_2 b_3 – a_3 b_2)$ = 0

## Summary 

If we have two lines $a_1x + b_1y + c_1$ = 0 and $a_2x + b_2y + c_2$ = 0, then:

* They will be ***Coincident*** if there are infinite solutions of the above two equations. This will happen if: $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$

* They will be ***Parallel*** if there are no solutions of the above two equations. This will happen if: $\frac{a_1}{a_2} = \frac{b_1}{b_2} ≠ \frac{c_1}{c_2}$

* They will be ***Perpendicular*** if there are unique solutions of the above two equations, and $\frac{a_1}{b_1} = -\frac{b_2}{a_2}$

* They will be ***Intersecting*** if there are unique solutions of the above two equations, and $\frac{a_1}{a_2} ≠ \frac{b_1}{b_2}$

