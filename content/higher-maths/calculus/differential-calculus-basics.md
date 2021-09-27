---
title: Basics of Differential Calculus 
linktitle: Basics of Differentiation
toc: true
type: docs
date: "2021-09-21T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 1. Differential Calculus
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## What is Differential Calculus?

Sometimes we are interested in knowing the ***rate of change*** of a given function. This can be done by finding the slope of the line joining two points on a curve. 
<img src="../../../media/calculus/differential-calculus-1.png" alt="Calculus" style="width:18%;height:18%;">

Slope = $\frac{Change \hspace{1ex} in \hspace{1ex} Y}{Change \hspace{1ex} in \hspace{1ex} X} = \frac{y_1 - y_2}{x_1 - x_2}$

Closer the two points will be, the more accurate result we will get. If the distance between the two points is made infinitesimal (i.e. almost zero), then we can find the function's instantaneous rate of change at a certain point.
<img src="../../../media/calculus/differential-calculus-2.png" alt="Calculus" style="width:27%;height:27%;">

This is what we do by finding the derivative of a function. That is, ***Derivative of a function is the function's instantaneous rate of change (or slope) at a certain point.***

To find derivatives of functions, we use the method of differentiation. This is called as Differential Calculus. 

{{% alert note %}}
Derivative of a function, f(x) is denoted by f'(x) or $\frac{d}{dx}$

So, the derivative of f(x) equals f'(x), OR d dx of f(x) equals f'(x).
{{% /alert %}}

Let's try to understand this process mathematically and using some examples. 


## How to find derivative of a function?

If we have a function, y = f(x), then on changing the input from x to (x + Δx), the output changes from f(x) or y to f(x + Δx) or (y + Δy).

Slope = $\frac{Change \hspace{1ex} in \hspace{1ex} Y}{Change \hspace{1ex} in \hspace{1ex} X} = \frac{Δy}{Δx} = \frac{f(x + Δx) - f(x)}{Δx}$

As Δx gets closer to zero, we will get the function's instantaneous rate of change at a certain point. This is what we do while finding derivatives of a function. 

That is, derivative of a function f(x), will be: <br>
f'(x) = $\lim_{Δx\to 0} \frac{f(x + Δx) - f(x)}{Δx}$

Let's see an example. 

##### Q. Find the derivative of the function f(x) = $x^2$

Explanation:<br>
<div class="Exp">

We know that, f(x) = $x^2$

So, f(x + Δx) = $(x + Δx)^2 = x^2 + 2xΔx + (Δx)^2$

Now, Slope = $\frac{Δy}{Δx} = \frac{f(x + Δx) - f(x)}{Δx} = \frac{x^2 + 2xΔx + (Δx)^2 - x^2}{Δx} = \frac{2xΔx + (Δx)^2}{Δx} = 2x + Δx$

As, Δx tends towards 0, the value of (2x + Δx) will tend towards 2x. That is, $\lim_{Δx\to 0} (2x + Δx)$ = 2x

So, the derivative of the function f(x) = $x^2$, $\frac{d}{dx} x^2$ is 2x. 

The derivative of $x^2$ equals 2x, OR d dx of $x^2$ equals 2x.

In other words, the slope of a function at any given point will be 2x. As x is a variable, the slope of the curve will be different at different points. 
</div> <br>

{{% alert note %}}
Slope of most of the curves have both constant and variable components, e.g. 2x, 3$x^2$, etc. So, the slope of the curve varies, depending on where on the curve we are measuring it. 

In contrast, slope of all straight lines are constant, e.g. 2, 5, -3, etc. So, the slope of a straight line remains constant, no matter where on the line we are measuring it. 

Let's see how. We will find the derivative of the straight line, y = 3x. 

We know that, Slope = $\frac{Δy}{Δx} = \frac{f(x + Δx) - f(x)}{Δx} = \frac{3(x + Δx) - 3x}{Δx} = \frac{3Δx}{Δx}$ = 3 

So, the derivative of 3x equals 3 (i.e. a constant)
{{% /alert %}}

However, we do not get enough time in exams to drive derivatives of each and every function. So, we should remember the derivatives of some of the most common functions, such as $x^2$, $x^3$, sin x, cos x, etc. 


## Derivatives of some common functions

Here's a list of the derivatives of some common functions that we will encounter. Though we can drive these values just the way we did in this article above. However, it will be a good idea to mug these up to fasten our speed in the exam. 

### Derivative of a Constant

Derivative of a Constant is always zero. 

$\frac{d}{dx} c$ = 0 <br>
(where c is a constant)

### Derivatives of Straight Lines

Derivative of a Straight Line is always a constant. 

$\frac{d}{dx} x$ = 1 

$\frac{d}{dx} cx$ = c <br>
(where c is a constant)

### Derivative of Squares, Cubes, Roots, etc. 

$\frac{d}{dx} x^n$ = n$x^{n - 1}$

So, let's see the derivatives of some of the functions based on the above rule. 

$\frac{d}{dx} x^2$ = 2x <br><br>
$\frac{d}{dx} x^3$ = 3$x^2$ <br><br>
$\frac{d}{dx} x^{1/2}$ = (1/2)$x^{-1/2}$ <br><br>
$\frac{d}{dx} x^{-1}$ = -$x^{-2}$ <br><br>
$\frac{d}{dx} x^{-2}$ = -2$x^{-3}$

### Derivative of Exponentials and Logarithms

$\frac{d}{dx} e^x = e^x$ <br><br>
$\frac{d}{dx} a^x = ln(a) \hspace{1ex} a^x$

$\frac{d}{dx} ln(x) = \frac{1}{x}$ <br><br>
$\frac{d}{dx} log_a(x) = \frac{1}{x \hspace{1ex} ln(a)}$

### Derivative of Trigonometry functions

$\frac{d}{dx} sin x = cos x$ <br><br>
$\frac{d}{dx} cos x = - sin x$ <br><br>
$\frac{d}{dx} tan x = sec^2 x$

$\frac{d}{dx} sin^{-1} x = \frac{1}{\sqrt{1 - x^2}}$ <br><br>
$\frac{d}{dx} cos^{-1} x = - \frac{1}{\sqrt{1 - x^2}}$ <br><br>
$\frac{d}{dx} tan^{-1} x = \frac{1}{1 + x^2}$

{{% alert note %}}
x must be in radians. 
{{% /alert %}}

