---
title: Basics of Integral Calculus 
linktitle: Basics of Integration
toc: true
type: docs
date: "2021-09-24T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 2. Integral Calculus
    weight: 30

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 30
---

## What is Integral Calculus?

Integration is a process via which we add up small parts (generally called slices) to find the value of the whole. 

The whole may be an area, volume, etc. But generally, we will be finding the area between the curve of a function and the x-axis. 
<img src="../../../media/calculus/integral-calculus-1.png" alt="Calculus" style="width:63%;height:63%;">

Let's see how we will use the process of Integration to find the area between the curve of a function and the x-axis. 

We can divide the area to be calculated into rectangular slices. Then we will calculate the area of each of these rectangular slices and add them up. 
<img src="../../../media/calculus/integral-calculus-2.png" alt="Calculus" style="width:63%;height:63%;">
However, as you can see in the graph given above, the calculated area may not be very accurate. 

To get more accurate answer, we need to decrease the width of each of the slices (and thus increase the number of slices). As these slices will appraoch zero in width (and hence infinite in number), the calculated value of the area approaches the correct answer.
<img src="../../../media/calculus/integral-calculus-3.png" alt="Calculus" style="width:63%;height:63%;">

However, it's easier said than done. How can we add up the area of so many slices? 

That's where the process of integration comes in. 

{{% alert note %}}
The process of integration is the reverse of the process of differenciation. 

That is, in Differential Calculus we find out the derivatives of functions. For example, derivative of $x^2$ is 2x. 

While in Integral Calculus we find out the original function from its derivative. For example, integral of 2x is $x^2$ + c, where c is a constant. 
{{% /alert %}}


## Representing Integration

Before we move further, let's see how we represent Integration. 

The symbol we use for Integration is: ∫ 

You may have noticed that it looks like 'S', as it represents the idea of summation of slices. 

If we want to find the integral of a function f(x), then we will represent is as follows: <br>
∫ f(x) dx

dx means that the slices have to be added in the direction of the x-axis, and also that their width approaches zero. 

For example, ∫ 2x dx = $x^2$ + c <br>
(where c is a constant, called 'Constant of Integration')

{{% alert note %}}
#### Why do we write a constant in the integral value?

We already know that the process of integration is the reverse of the process of differenciation. 

$\frac{d}{dx} x^2$ = 2x 

Also, $\frac{d}{dx} (x^2 + c)$ = 2x 

That's because, derivative of a constant is always 0, i.e. $\frac{d}{dx} c$ = 0. 

So, while reversing this process, we cannot tell whether the original function had a constant or not. So, to cover this possibility we add a constant in the integral value. c can be 0, -2, 3, 5, 333, etc. 
{{% /alert %}}


## Integral of some common functions

Here's a list of the integrals of some common functions that we will encounter. 

{{% alert note %}}
As derivatives and integrals are opposite to each other, if the function whose integral we are trying to find is on the result side of a derivative, then we will get our answer straightaway. 

For example, we know that $\frac{d}{dx} tan x = sec^2 x$ <br>
So, ∫ $sec^2 x$ dx = tan x + c
{{% /alert %}}

### Derivative of a Constant

∫ a dx = ax + c <br>
(where a and c are constants)

### Derivatives of Variables

∫ x dx = $\frac{x^2}{2}$ + c

### Derivative of Squares, Cubes, Roots, etc. 

∫ $x^n$ dx = $\frac{x^{n + 1}}{n + 1}$ + c <br>
(Here, n should not be equal to -1)

So, let's see the integrals of some of the functions based on the above rule.

∫ $x^2$ dx = $\frac{x^3}{3}$ + c

∫ $x^3$ dx = $\frac{x^4}{4}$ + c

### Derivative of Reciprocal

∫ $x^{-1}$ dx = ln |x| + c

### Derivative of Exponentials and Logarithms

∫ $e^x$ dx = $e^x$ + c

∫ $a^x$ dx = $\frac{a^x}{ln \hspace{1ex} a}$ + c

∫ ln x dx = x ln x - x + c

### Derivative of Trigonometry functions

∫ cos x dx = sin x + c

∫ sin x dx = - cos x + c

∫ $sec^2 x$ x dx = tan x + c

{{% alert note %}}
x must be in radians. 
{{% /alert %}}

