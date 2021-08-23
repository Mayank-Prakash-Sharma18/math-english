---
title: Determinants
linktitle: Determinants 
toc: true
type: docs
date: "2021-08-17T00:00:00+01:00"
draft: false
menu:
  matrices:
    parent: 2. Determinant
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

## What is Determinant of a Matrix?

Determinant of a matrix is a number that we can calculate from a square matrix. 

{{% alert note %}}
Square matrix is a matrix that has the same number of rows and columns. We can calculate determinant of only a square matrix. 
{{% /alert %}}

Determinant is denoted by using two vertical lines, i.e. | |. 

For example, if A is a square matrix, then its determinant will be denoted as |A|.

{{% alert note %}}
We also use two vertical lines to denote absolute values. Don’t get confused. 
{{% /alert %}}

We use determinants in various fields of mathematics, for example:
* To find the inverse of a matrix.
* To solve two linear equations of two variables. 
* In Calculus, etc. 

So, now let’s understand how to find the determinant of a matrix. 


## Finding Determinant of a Matrix

We can find determinant of only ***square matrices***, i.e. matrices having as many rows as columns. 

There are various methods to find determinant of a matrix. But we generally use the Laplace expansion method. 

It is easy to remember and apply on small matrices, such as a 2 × 2 matrix, or a 3 × 3 matrix etc. However, it becomes tedious to apply on bigger matrices. 

### Laplace expansion method 

#### For 2 × 2 matrix

A 2 × 2 matrix has 2 rows and 2 columns, as the matrix displayed below:

$\begin{bmatrix}
a & b \newline
c & d
\end{bmatrix}$
 
Its determinant, |A| = ad – bc 

{{% alert note %}}
It can also be visualized via a picture:
<img src="../../../media/matrix/matrix-7.png" alt="Matrix" style="width:18%;height:18%;">
{{% /alert %}}
 
For example, if B = 
$\begin{vmatrix}
1 & 2 \newline
3 & 4 
\end{vmatrix}$
 , then:

|B| = 1 × 4 – 2 × 3 = 4 – 6 = -2 

#### For 3 × 3 matrix

A 3 × 3 matrix has 3 rows and 3 columns, as the matrix displayed below:

$\begin{bmatrix}
a & b & c \newline
d & e & f \newline
g & h & i
\end{bmatrix}$

Its determinant, |A| = 
a . $\begin{vmatrix}
e & f \newline
h & i
\end{vmatrix}$ - 
b . $\begin{vmatrix}
d & f \newline
g & i
\end{vmatrix}$ +
c . $\begin{vmatrix}
d & e \newline
g & h
\end{vmatrix}$
= a (ei - hf) -  b (di - gf) + c (dh - ge)

So, we multiply ‘a’ with a determinant of a 2 × 2 matrix, which is formed by removing the elements in a’s row and column. We do the same for ‘b’ and ‘c’. In case of ‘b’, we also place a minus sign in front of it. 

{{% alert note %}}
It can also be visualized via a picture:
<img src="../../../media/matrix/matrix-8.png" alt="Matrix" style="width:63%;height:63%;">
{{% /alert %}}
 
For example, if C =
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6 \newline
7 & 8 & 9
\end{bmatrix}$
 , then:

|C| = 1 (5 × 9 - 6 × 8) - 2 (4 × 9 - 6 × 7) + 3 (4 × 8 - 5 × 7) = 1 (45 - 48) - 2 (36 - 42) + 3 (32 - 35) = -3 - 2 (-6) + 3 (-3) = -3 + 12 - 9 = 0

{{% alert note %}}
We can continue the same pattern even for larger matrices. 

That is, we multiply ‘a’ by the determinant of the matrix which is formed by removing the elements in a’s row and column. 

Then, we do this for the whole row, while placing the signs in front of them in the following pattern: +, -, +, -, + and so on. 
{{% /alert %}}

