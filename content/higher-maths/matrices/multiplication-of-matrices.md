---
title: Multiplication of Matrices
linktitle: Multiplication of Matrices 
toc: true
type: docs
date: "2021-08-17T00:00:00+01:00"
draft: false
menu:
  matrices:
    parent: 1. Matrix
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

We already know the basics of Matrices. Now, in this article, we will study the concept of multiplication of metrices in detail. 


## Can we multiply two matrices?

Yes, we can. We can multiply a matrix by a constant (called scalar multiplication), and we can also multiply two matrices. 

But we cannot multiply any two given matrices. They should fulfil some conditions. Let’s see. 


## Conditions for Multiplication of two Matrices

We can multiply two matrices only if they fulfil the following condition.

The number of columns in the first matrix, must be the same as the number of rows in the second matrix. 

So, we can multiply the following two matrices (called dot multiplication): <br>
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6
\end{bmatrix}$ ×
$\begin{bmatrix}
2 & 4 \newline
1 & 7 \newline
5 & 1
\end{bmatrix}$

The first matrix has 3 columns and the second matrix has 3 rows. 

{{% alert note %}}
When we multiply m × **n** matrix with a **n** × p matrix, then the resultant will be a m × p matrix. 
{{% /alert %}}

Now, without further ado let’s see how to multiply two matrices. 


## Multiplication of two Matrices

We multiply two matrices using ***Dot Multiplication***. 

To get the first number of the resultant matrix, we multiply the numbers of the first row of first matrix, with the corresponding numbers of the first column of second matrix. 

That’s how we start, and then we move ahead as per the size of the matrices. We can understand it much better via some examples.

##### Q. Multiply the following two matrices, and find the resultant matrix. 
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6
\end{bmatrix}$ ×
$\begin{bmatrix}
2 & 4 \newline
1 & 7 \newline
5 & 1
\end{bmatrix}$

Explanation:<br>
<div class="Exp">

The first matrix is 2 × 3, and the second matrix is 3 × 2. So, we can multiply these matrices. 

###### First element

To get the first element of the resultant matrix, we need to multiply the numbers of the first row of first matrix, with the corresponding numbers of the first column of second matrix. 
<img src="../../../media/matrix/matrix-3.png" alt="Matrix" style="width:45%;height:45%;">

So, the first element = (1 × 2) + (2 × 1) + (3 × 5) = 2 + 2 + 15 = 19

###### Second element

To get the second element of the resultant matrix, we need to multiply the numbers of the first row of first matrix, with the corresponding numbers of the second column of second matrix. 
<img src="../../../media/matrix/matrix-4.png" alt="Matrix" style="width:45%;height:45%;">

So, the second element = (1 × 4) + (2 × 7) + (3 × 1) = 4 + 14 + 3 = 21

###### Third element

To get the third element of the resultant matrix, we need to multiply the numbers of the second row of first matrix, with the corresponding numbers of the first column of second matrix. 
<img src="../../../media/matrix/matrix-5.png" alt="Matrix" style="width:45%;height:45%;">

So, the third element = (4 × 2) + (5 × 1) + (6 × 5) = 8 + 5 + 30 = 43

###### Fourth element

To get the fourth element of the resultant matrix, we need to multiply the numbers of the second row of first matrix, with the corresponding numbers of the second column of second matrix. 
<img src="../../../media/matrix/matrix-6.png" alt="Matrix" style="width:45%;height:45%;">

So, the fourth element = (4 × 4) + (5 × 7) + (6 × 1) = 16 + 35 + 6 = 57

Now, since the first matrix was 2 × 3, and the second matrix was 3 × 2, the resultant matrix we got is 2 × 2. 
</div> <br>

Now, let us see some properties related to multiplication of two metrices. 


## Properties related to Multiplication of Metrices

### Property 1: Order of Multiplication

Unlike arithmetic multiplication, the order of multiplication can make a difference in case of metrices. In other words, we can say that Commutative law of multiplication is not true in case of multiplication of matrices.  

So, if A and B are two numbers, then we can say that A × B = B × A. For example, 4 × 5 = 5 × 4 (Commutative law of multiplication)

However, if A and B are two metrices, then we cannot say that A × B = B × A. In fact, many a times we even won’t be able to multiple them in opposite order, and even if we can then in most of the cases the resultant matrix would be different. 

For example, if A = 
$\begin{bmatrix}
1 & 2 & 3 \newline
4 & 5 & 6
\end{bmatrix}$
and B = 
$\begin{bmatrix}
5 \newline
7 \newline
8
\end{bmatrix}$
 , then:
* We can find A × B, as A has 3 columns and B has 3 rows. So, we can multiply them.
* However, we cannot find B × A, as B has 1 column and A has 2 rows. 

If A = 
$\begin{bmatrix}
1 & 2 \newline
4 & 5
\end{bmatrix}$
and B = 
$\begin{bmatrix}
0 & 3 \newline
6 & 7
\end{bmatrix}$
 , then:

* A × B = 
$\begin{bmatrix}
12 & 17 \newline
30 & 47
\end{bmatrix}$

* B × A = 
$\begin{bmatrix}
12 & 15 \newline
34 & 47
\end{bmatrix}$

As you can see, the resultant matrices are different in the two cases. 

{{% alert note %}}
Sometimes, A × B = B × A, even in case of metrices, e.g. if one of the metrices is an identity matrix. 
{{% /alert %}}

### Property 2: Identity Matrix

Identity matrix is a square matrix, wherein all the diagonal elements are 1 and the rest of the elements are 0. It is denoted by the symbol **I**. 

For example, 
$\begin{bmatrix}
1 & 0 & 0 \newline
0 & 1 & 0 \newline
0 & 0 & 1
\end{bmatrix}$
is a 3 × 3 identity matrix. 

{{% alert note %}}
A square matrix has the same number of rows and columns. 
{{% /alert %}}

If we multiply any matrix (say A) with an identity matrix, then we get the same resultant matrix A. So, A × I = A

For example, 
$\begin{bmatrix}
1 & 2 \newline
4 & 5
\end{bmatrix}$ × 
$\begin{bmatrix}
1 & 0 \newline
0 & 1
\end{bmatrix}$ = 
$\begin{bmatrix}
1 & 2 \newline
4 & 5
\end{bmatrix}$

And if we can multiply them in reverse, then that will be equal to A too, i.e. I × A = A

For example, 
$\begin{bmatrix}
1 & 0 \newline
0 & 1
\end{bmatrix}$ × 
$\begin{bmatrix}
1 & 2 \newline
4 & 5
\end{bmatrix}$ = 
$\begin{bmatrix}
1 & 2 \newline
4 & 5
\end{bmatrix}$

