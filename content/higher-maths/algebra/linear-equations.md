---
title: Basics of Linear Equations
linktitle: Linear Equations 
toc: true
type: docs
date: "2021-08-07T00:00:00+01:00"
draft: false
menu:
  algebra:
    parent: 2. Equations
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

## What is an Equation?

An equation is an expression of the form f(x) = 0. It may even have more than one variable. 

Based on the highest power of a variable (say x) in an equation, we can have various types of equations. 
* Linear equations - They are equations of first degree, e.g. equation having x.
* Quadratic equations - They are equations of second degree, e.g. equation having $x^2$
* Cubic equations - They are equations of third degree, e.g. equation having $x^3$

{{% alert note %}}
The degree of an equation is the highest power of a variable in the equation, or the combined powers of the variables being multiplied. 

For example, Degree of y + 3 = 0 is 1. <br>
Degree of $y^2$ + x + 2 = 3 is 2 <br>
Degree of $z^3$ + z - 2 = 0 is 3. <br>
Degree of $x^3 y^2$ + $x^2 y$ + y = 0 is 3 + 2 = 5. 
{{% /alert %}}

## What is a Linear Equation? 

They are equations of first degree. For example, x + 3 = 1; x + y = 5

Depending on the number of variables in a linear equation, we can further divide them into the following types:
* Linear equations in one variable - e.g. x + 23 = 21
* Linear equations in two variables - e.g. x + 3y = 7 
* Linear equations in three variables and so on.

### Linear equations in one variable

Equations of the form ax + b = 0 are called linear equations in one variable. Here, a, b are real numbers and a ≠ 0. 

For example, x + 12 = 21. 

Solving linear equations in one variable is pretty easy. Let's see an example.

{{% alert note %}}
To solve for n variables, we need at least n distinct equations. So, to solve for 1 variable, we just need 1 equation. 
{{% /alert %}}

##### Q. Solve 4x + 5 = 25

Explanation:<br>
<div class="Exp">

4x + 5 = 25 <br>
or 4x = 25 - 5 = 20 <br>
or x = 20/4 = 5
</div> <br>

#### Graph of Linear equation in one variable

Graph of a linear equation in one variable is a straight line, which is parallel to one of the axes and perpendicular to the other. 

For example, in the above example, the equation 4x + 5 = 25 was simplified to x = 5. It can be plotted on a graph as follows:
<img src="../../../media/algebra/equation-1.png" alt="Algebra" style="width:63%;height:63%;">


### Linear equations in two variables

Equations of the form ax + by + c = 0 are called linear equations in two variables. Here, a, b and c are real numbers and a, b ≠ 0. 

For example, 2x + 3y - 32 = 0

Solving linear equations in two variables is pretty easy too. We add or subtract the two equations in such a way that one of the variables gets eliminated. Let's see some examples.

{{% alert note %}}
To solve for n variables, we need at least n distinct equations. So, to solve for 2 variables, we need 2 distinct equations. 
{{% /alert %}}

##### Q. Find the values of x and y.
I. x + 2y = 9 <br>
II. x - 2y = 1

Explanation:<br>
<div class="Exp">

I. x + 2y = 9 <br>
II. x - 2y = 1

On adding equations I and II, we get: <br>
2x = 9 + 1 = 10 <br>
or x = 10/2 = 5

Now, we can find the value of y by putting this value of x in any of the two equations. We should choose an equation that will allow us to do less calculations. 

So, putting the value of x in equation II, we get: <br>
5 - 2y = 1 <br>
or 2y = 4 <br>
or y = 2
</div> <br>


##### Q. Find the values of x and y.
I. x + 3y = 32 <br>
II. 2x - 5y = 20

Explanation:<br>
<div class="Exp">

I. x + 3y = 32 <br>
II. 2x - 5y = 20

Unlike earlier examples, here we cannot eliminate one of the options by just adding or subtracting. We need to multiply one of the equations (or both) in such a manner that the coefficient of the variable being eliminated becomes the same in both the equations. 

Here, we will multiply the first equation by 2. So, now our equations will become: <br>
I. 2x + 6y = 64 <br>
II. 2x - 5y = 20

On subtracting equation II from equation I, we get: <br>
(2x + 6y) - (2x - 5y) = 64 - 20 <br>
or 6y + 5y = 44 <br>
or 11y = 44 <br>
or y = 44/11 = 4

Now, putting the value of y in equation I, we get: <br>
x + 3y = 32 <br>
or x + (3 × 4) = 32 <br>
or x + 12 = 32 <br>
or x = 32 - 12 = 20
</div> <br>


##### Q. Find the values of x and y.
I. 4x + 5y = 19 <br>
II. 5x + 4y = 8

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional Method <br><br>

I. 4x + 5y = 19 <br>
II. 5x + 4y = 8

We need to multiply one of the equations (or both) in such a manner that the coefficient of the variable being eliminated becomes the same in both the equations. 

Here, we will multiply first equation by 4, and second equation by 5. So, now our equations will become: <br>
I. 16x + 20y = 76 <br>
II. 25x + 20y = 40

On subtracting equation I from equation II, we get: <br>
(25x + 20y) - (16x + 20y) = 40 - 76 <br>
or 25x - 16x = -36 <br>
or 9x = -36 <br>
or x = -36/9 = -4

Now, putting the value of x in equation II, we get: <br>
5x + 4y = 8 <br>
or 5 × (-4) + 4y = 8 <br>
or -20 + 4y = 8 <br>
or 4y = 8 + 20 = 28 <br>
or y = 28/4 = 7
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Coefficient Interchange Method <br><br>

We can use this method when the coefficients of x and y are interchanged in the two given equations (as is the case here). 

I. 4x + 5y = 19 <br>
II. 5x + 4y = 8

On adding the equations, we get: <br>
9x + 9y = 19 + 8 = 27 <br>
or 9 (x + y) = 27 <br>
or x + y = 3

On subtracting the equations, we get: <br>
-x + y = 19 - 8 = 11 <br>
or y - x = 11

So, now we have constructed two simple equations from the original equations given to us. These are: <br>
III. x + y = 3 <br>
IV. y - x = 11

On adding these two equations, we get: <br>
2y = 14 <br>
or y = 14/2 = 7

Now, putting the value of y in equation IV, we get: <br>
7 - x = 11 <br>
or x = 7 - 11 = -4 
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Using Cramer's Rule <br><br>

This rule can be used to solve any kind of linear equations pair. However, it cannot be said to be a shortcut method. Just have a look. Use it if you like it. 

In this system, we create three determinants:
* denominator determinant, D
* x‐numerator determinant, $D_x$ 
* y‐numerator determinant, $D_y$

Our equations are: <br>
I. 4x + 5y = 19 <br>
II. 5x + 4y = 8

Denominator determinant (D) is formed by taking the coefficients of x and y from the equations written in standard form. <br>

D = $\begin{vmatrix}
4 & 5 \newline
5 & 4
\end{vmatrix}$ = (4 × 4) - (5 × 5) = 16 - 25 = -9

The x‐numerator determinant ($D_x$) is formed by taking the constant terms from the equations and placing them in the x‐coefficient positions and retaining the y‐coefficients.

$D_x$ = $\begin{vmatrix}
19 & 5 \newline
8 & 4
\end{vmatrix}$ = (19 × 4) - (8 × 5) = 76 - 40 = 36

The y‐numerator determinant ($D_y$) is formed by taking the constant terms from the equations and placing them in the y‐coefficient positions and retaining the x‐coefficients.

$D_y$ = $\begin{vmatrix}
4 & 19 \newline
5 & 8
\end{vmatrix}$ = (4 × 8) - (5 × 19) = 32 - 95 = -63

So, x = $\frac{D_x}{D}$ = $\frac{36}{(-9)}$ = -4

y = $\frac{D_y}{D}$ = $\frac{(-63)}{(-9)}$ = 7 
</div><br>


#### Graph of Linear equation in two variables

Graph of a linear equation in two variables is also a straight line. For us to draw its graph, we need at least two solutions to such an equation. 

For example, the various possible solutions of the equation 2x + y = 6 are:
<table>
  <tr>
    <th>x</th>
    <td>0</td>
    <td>3</td>
    <td>1</td>
    <td>...</td>
  </tr>
  <tr>
    <td>y</td>
    <td>6</td>
    <td>0</td>
    <td>4</td>
    <td>...</td>
  </tr>
</table> 

It can be plotted on a graph as follows:
<img src="../../../media/algebra/equation-2.png" alt="Algebra" style="width:81%;height:81%;">

