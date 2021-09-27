---
title: Basics of Differential Equation 
linktitle: Basics of Differential Equation
toc: true
type: docs
date: "2021-09-25T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 3. Differential Equation
    weight: 51

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 51
---

## What is Differential Equation?

Differential Equation is an equation that has a function (say y), and one or more of its derivatives ($\frac{dy}{dx}$). 

For example, y + $\frac{dy}{dx}$ = 3x


## Order and Degree of Differential Equations

* Order - The highest derivative in the Differential Equation, i.e. first derivative ($\frac{dy}{dx}$), second derivative ($\frac{d^2y}{dx^2}$), etc.

* Degree - The exponent of the highest derivative. 

For example, consider the following Differential Equations: 

y + $(\frac{dy}{dx})^2$ = 3x <br>
Here, the highest derivative is just first derivative ($\frac{dy}{dx}$). So, order is 1. <br>
The exponent of the highest derivative is 2. So, degree is 2. 

$y^2$ + xy + $(\frac{dy}{dx})^4$ + $(\frac{d^3y}{dx^3})^2$ = $e^x$ <br>
Here, the highest derivative is third derivative ($\frac{d^3y}{dx^3}$). So, order is 3. <br>
The exponent of the highest derivative is 2. So, degree is 2.


## Types of Differential Equations

### Ordinary and Partial Differential Equations

One major classification of Differential Equations is based on the number of independent variables in it. 

* Ordinary Differential Equations (ODEs) - equations that have only one independent variable (e.g. y). 
* Partial Differential Equations (PDEs) - equations that have two or more independent variables.

We will mostly be dealing with Ordinary Differential Equations (ODEs). 

### Linear and Non-Linear Differential Equations

Differential Equation is linear if no variable or derivative in it has exponent other than one (i.e. no $y^2$, no $\sqrt{y}$, no $\frac{d^2y}{dx^2}$, etc). Also, there should be no functions in it, e.g. cos y, log y, etc.

A linear Differential Equation can only have y, and $\frac{dy}{dx}$. 

General form of Linear Differential Equation: $\frac{dy}{dx}$ + F(x) y = G(x)

Here, F(x) and G(x) are functions of x. 

For example, 2y + 5$\frac{dy}{dx}$ = 3x

All other differential equations are non-linear differential equations, e.g. Second Order Differential Equations. 

{{% alert note %}}
#### Second Order Differential Equations

General form of Second Order Differential Equation: $\frac{d^2y}{dx^2} + F(x) \frac{dy}{dx} + G(x) y = 0$

Second Order Equations maybe of many types, such as homogeneous, non-homogeneous, autonomous, constant coefficients, undetermined coefficients etc.
{{% /alert %}}


### Bernoulli Equations

General form of Bernoulli Differential Equation: $\frac{dy}{dx} + F(x) y = G(x) y^n$ <br>
(Where n can be any real number, except 0 or 1)

When n = 0, then it becomes a Linear Differential Equation. 

{{% alert note %}}
#### Homogeneous Equations

$\frac{dy}{dx}$ = F ($\frac{y}{x}$)

In such a case, we can replace $\frac{y}{x}$ by another variable (say v), and then solve it. 

For example, $\frac{dy}{dx} = \frac{x^2 + y^2}{xy} = \frac{x}{y} + \frac{y}{x} = (\frac{y}{x})^{-1} + \frac{y}{x}$

$\frac{dy}{dx} = \frac{y}{x} - (\frac{y}{x})^2$

<!-- Second Order Differential Equation will be a Homogeneous Equation if Q(x) = 0.  -->
{{% /alert %}}


