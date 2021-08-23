---
title: Basics of Matrix
linktitle: Basics of Matrix 
toc: true
type: docs
date: "2021-08-16T00:00:00+01:00"
draft: false
menu:
  matrices:
    parent: 1. Matrix
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## What is Matrix?

Matrix is a two-dimensional array of numbers. In it numbers are arranged in rows and columns, and they are enclosed by a square bracket, i.e. by [ ]. 

For example, 
$\begin{bmatrix}
1 & 2 & 3 \newline
a & b & c
\end{bmatrix}$
 
{{% alert note %}}
Matrix is singular, while Matrices is plural. 
{{% /alert %}}

### Rows and Columns of a Matrix

The rows are horizontal, i.e. numbers written left to right. <br>
The columns are vertical, i.e. numbers written from top to bottom. 

For example, in the matrix A = 
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6
\end{bmatrix}$:
* the two horizontal rows are: (1, 2, 3) and (4, 5, 6)
* the three vertical columns are: (1, 4), (2, 5) and (3, 6)

So, the above matrix is a 2 × 3 matrix (row × column).

### Denoting an element of a Matrix

While we use capital letters to denote matrices, we use small letters to denote their elements. 
An element in a matrix can be denoted using row and column numbers in the subscript. The row number is written first, followed by the column number. 

For example, in the above matrix A, $a_{1,2}$ means the element in the first row and second column, which is 2. 

Similarly, $a_{2,3}$ means the element in the second row and third column, which is 6. 

{{% alert note %}}
You may remember it using a mnemonic ***arc***, i.e. $a_{r,c}$. The name of the matrix in small letter, with rows and columns in subscript (in that order). 
{{% /alert %}}


## Properties of Matrices

### Addition and Subtraction of Matrices

Two matrices having the same rows and columns can be added or subtracted. 
<img src="../../../media/matrix/matrix-1.png" alt="Matrix" style="width:54%;height:54%;">

For example:

$\begin{bmatrix}
1 & 2 \newline
3 & 4
\end{bmatrix}$ +
$\begin{bmatrix}
5 & 6 \newline
7 & 8
\end{bmatrix}$ = 
$\begin{bmatrix}
6 & 8 \newline
10 & 12
\end{bmatrix}$

$\begin{bmatrix}
5 & 6 \newline
7 & 8
\end{bmatrix}$ -
$\begin{bmatrix}
1 & 2 \newline
3 & 4
\end{bmatrix}$ = 
$\begin{bmatrix}
4 & 4 \newline
4 & 4
\end{bmatrix}$

### Multiplication of Matrices

We may encounter two types of multiplications when matrices are involved. 

#### Scalar multiplication

We can multiply a matrix by a constant (called scalar). 
<img src="../../../media/matrix/matrix-2.png" alt="Matrix" style="width:99%;height:99%;">

For example, 
3 ×
$\begin{bmatrix}
1 & 2 \newline
3 & 4
\end{bmatrix}$ = 
$\begin{bmatrix}
3 & 6 \newline
9 & 12
\end{bmatrix}$
 
{{% alert note %}}
When we multiply a matrix by -1, we get the negative matrix. 
{{% /alert %}}

#### Multiplication of two Matrices

We can also multiply two metrices, say A × B. We will study this in more detail in a separate article. 

{{% alert note %}}
We cannot divide two matrices in a traditional way. Rather we multiply one matrix with the inverse of the other matrix. 

For example, if we have to find out A/B, then we will do it this way: <br>
A/B = A × (1/B) = A × $B^{-1}$ <br>
Where $B^{-1}$ is the ***Inverse*** of matrix B. 
{{% /alert %}}

### Transposing a Matrix

To transpose a matrix, we just swap the rows and columns. 

For example, if we have a matrix A = 
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6
\end{bmatrix}$, then: <br><br>
Transpose of matrix A, $A^T$ = 
$\begin{bmatrix}
1 & 4 \newline
2 & 5 \newline
3 & 6
\end{bmatrix}$

