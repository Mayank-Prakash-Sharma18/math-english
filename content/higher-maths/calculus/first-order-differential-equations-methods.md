---
title: Methods to solve First Order Differential Equations
linktitle: Solutions of First Order Differential Equations
toc: true
type: docs
date: "2021-09-25T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 3. Differential Equation
    weight: 54

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 54
---

## What are First Order Differential Equations? 

The highest derivative in a first order differential equation is the first derivative (i.e. $\frac{dy}{dx}$). 

There's no one size fits all method to solve all kinds of Differential Equations. There are many, and we have to learn through practice which method to use in a given scenario. 

But let's not put the cart before the horse. We should get to know the various methods at our disposal first. 


## Various Methods for solving First Order Differential Equations

### Separation of Variables

In this method, we separate the variables and then integrate. 

So, obviously we can use this method only if we can move all x and dx terms to one side of the equation, and all y and dy terms to the other side. 

##### Q. Solve $\frac{dy}{dx} = \frac{k}{y}$, where k is a constant. 

Explanation:<br>
<div class="Exp">

Let's separate the x and y variables. 

$\frac{dy}{dx} = \frac{k}{y}$ 

or y dy = k dx

Now, we can integrate both sides of the above equation separately. 

∫ y dy = $\frac{y^2}{2}$ + c <br>
(where c is a constant)

∫ k dx = kx + d <br>
(where c is a constant)

So, $\frac{y^2}{2}$ + c = kx + d <br>
or $\frac{y^2}{2}$ = kx + m <br>
(where m = d - c)

or y = $\sqrt{2(kx + m)}$
</div> <br>


### Typical method for solving First Order Linear Differential Equations

#### What are Linear Differential Equations?

Differential Equation is linear if no variable or derivative in it has exponent other than one (i.e. no $y^2$, no $\sqrt{y}$, no $\frac{d^2y}{dx^2}$, etc). Also, there should be no functions in it, e.g. cos y, log y, etc.

A linear Differential Equation can only have y, and $\frac{dy}{dx}$. 

General form of Linear Differential Equation: $\frac{dy}{dx}$ + F(x) y = G(x) <br>
For example, 2y + 5$\frac{dy}{dx}$ = 3x

{{% alert note %}}
***First order differential equation*** is one in which the highest derivative is the first derivative (i.e. $\frac{dy}{dx}$). It doesn't matter what exponents/powers y or $\frac{dy}{dx}$ have. 
{{% /alert %}}

To solve ***First Order Linear Differential Equations***, we can use a special method. Let's see. 

We create two new functions of x, called u and v, such that y = uv. Now, we just need to find the values of u and v. 

Let's see this method in detail. 

**Step 1**: As y = uv. <br>
So, $\frac{dy}{dx} = u \frac{dv}{dx} + v \frac{du}{dx}$ (from Product Rule of derivatives)

We will substitute this in the standard form of Linear Differential Equation, i.e. $\frac{dy}{dx}$ + F(x) y = G(x)

**Step 2**: We separate the parts containing v.

**Step 3**: Put v term equal to 0. 

**Step 4**: Solve the differential equation in u and x (that we got in the last step), using separation of variables method. Find the value of u. 

**Step 5**: Place the value of u in the equation that we got in Step 2. Solve it to find v. 

**Step 6**: Now, as we know both u and v, just find the value of y (as y = uv).

Things will become clearer if we see an example. 

##### Q. Solve $\frac{dy}{dx} = \frac{y}{x} + 3$

Explanation:<br>
<div class="Exp">

We need to reconstruct the given equation in this form: $\frac{dy}{dx}$ + F(x) y = G(x)

$\frac{dy}{dx} = \frac{y}{x} + 3$ <br>
or $\frac{dy}{dx} - \frac{y}{x} = 3$

{{% alert note %}}
$\frac{dy}{dx} - \frac{y}{x}$ means that at many point of the curve, slope - $\frac{y}{x}$ will be equal to 3. 
{{% /alert %}}

**Step 1**: Substitute y = uv, and $\frac{dy}{dx} = u \frac{dv}{dx} + v \frac{du}{dx}$ in this equation.

$\frac{dy}{dx} - \frac{y}{x} = 3$ <br>
or $u \frac{dv}{dx} + v \frac{du}{dx} - \frac{uv}{x} = 3$

**Step 2**: We separate the parts containing v.

$u \frac{dv}{dx} + v \frac{du}{dx} - \frac{uv}{x} = 3$ <br>
or $u \frac{dv}{dx} + v (\frac{du}{dx} - \frac{u}{x}) = 3$

**Step 3**: Put v term equal to 0. 

So, $\frac{du}{dx} - \frac{u}{x}$ = 0 <br>
or $\frac{du}{dx} = \frac{u}{x}$

**Step 4**: Solve the differential equation in u and x (that we got in the last step), using separation of variables method. Find the value of u. 

$\frac{du}{dx} = \frac{u}{x}$ <br>
or $\frac{du}{u} = \frac{dx}{x}$ <br>

Now, on integrating them, we get: <br>
ln u = ln x + c (where c is a constant)<br>
or ln u = ln x + ln k (where ln k is a constant) <br>
or u = kx

**Step 5**: Place the value of u in the equation that we got in Step 2. Solve it to find v. 

$u \frac{dv}{dx} + v (\frac{du}{dx} - \frac{u}{x}) = 3$ <br>
or $kx \frac{dv}{dx} = 3$ (v term is already zero, so we can ignore that part.)<br>

Now, solve it using separation of variables method. <br>
$kx \frac{dv}{dx} = 3$ <br>
or $k dv = 3\frac{dx}{x}$

Now, on integrating them, we get: <br>
kv = 3 ln x + ln c <br>
or kv = ln (c$x^3$) <br>
or v = $\frac{ln (c x^3)}{k}$

**Step 6**: Now, as we know both u and v, just find the value of y (as y = uv).

y = uv = (kx) $\frac{ln (c x^3)}{k}$ = x $ln (c x^3)$
</div> <br>

{{% alert note %}}
#### Homogeneous Equations

$\frac{dy}{dx}$ = F ($\frac{y}{x}$)

In such a case, we can replace $\frac{y}{x}$ by another variable (say v), and then solve it using ***Separation of Variables*** method. 

So, v = $\frac{y}{x}$ (i.e. y = vx)

And $\frac{dy}{dx} = \frac{d(vx)}{dx} = v \frac{dx}{dx} + x \frac{dv}{dx} = v + x \frac{dv}{dx}$

Substitute these values in the original equation and solve for v. Now, put v = $\frac{y}{x}$, and simplify. 
{{% /alert %}}


### Convert Non-linear differential equation into Linear differential equation

We can sometimes convert a non-linear Bernoulli differential equation into a linear differential equation. Then it becomes easy to solve it. 

General form of Bernoulli Differential Equation: $\frac{dy}{dx} + F(x) y = G(x) y^n$ <br>
(Where n can be any real number, except 0 or 1)

We can substitute u = $y^{1 - n}$ in the above equation, and thus turn it into a linear differential equation, which is easier to solve.  

{{% alert note %}}
$\frac{dy}{dx} + F(x) y = G(x) y^n$

* When n = 0, then the above equation becomes a Linear Differential Equation. 

* When n = 1, the the above equation can easily be solved using Separation of Variables method.

In other cases, we can use the method given above. 
{{% /alert %}}

##### Q. Solve $\frac{dy}{dx} + x^3y = x^3 y^3$

Explanation:<br>
<div class="Exp">

It's a Bernoulli Differential Equation of the form: $\frac{dy}{dx} + F(x) y = G(x) y^n$

Here, F(x) = $x^3$, G(x) = $x^3$, n = 3

So, u = $y^{1 - n} = y^{-2}$ <br>
or y = $u^{-1/2}$

So, $\frac{dy}{dx} = (-1/2) u^{-3/2} \frac{du}{dx}$

Now, substitute the values of y and $\frac{dy}{dx}$ in the original equation. <br>
$\frac{dy}{dx} + x^3y = x^3 y^3$ <br>
or $(-1/2) u^{-3/2} \frac{du}{dx} + x^3 u^{-1/2} = x^3 (u^{-1/2})^3$ <br>

To simplify it, let us multiply the equation by -2 $u^{3/2}$. 

$\frac{du}{dx} - 2 u x^3 = -2 x^3$

Now, we can easily solve this equation. 

$\frac{du}{dx} = x^3 (2u - 2)$ <br>
or $\frac{du}{u - 1} = 2 x^3 dx$

Now, we can integrate both sides. <br>
$∫ \frac{1}{u - 1} du = ∫ 2 x^3 dx$ <br>
or ln (u - 1) = 2 $\frac{x^4}{4}$ + c (where c is a constant)<br>
or ln (u - 1) = $\frac{x^4}{2}$ + c <br>
or u - 1 = $e^{(\frac{x^4}{2} + c)}$ <br>
or u = $e^{(\frac{x^4}{2} + c)}$ + 1

As we know that y = $u^{-1/2}$, so we can substitute it in the above equation now. 

{{% alert note %}}
**Short Cut**

We know that, Bernoulli Differential Equation: $\frac{dy}{dx} + F(x) y = G(x) y^n$, where n ≠ 0 or 1

This can be rewritten as: $\frac{du}{dx} + (1 − n) u F(x) = (1 − n) G(x)$

Solve it, and then just substitute y = $u^{(\frac{-1}{n - 1})}$
{{% /alert %}}
</div> <br>


### Exact Equations and Integrating Factors

This method can be used for a first-order differential equation. 

In order for us to use this method, we need to find a function I(x, y) whose partial derivatives can be put in place of M and N in the following equation:

M(x, y)dx + N(x, y)dy = 0

That is, $\frac{∂I}{∂x} dx + \frac{∂I}{∂y}$ dy = 0

Obviously, for this method to work, such a function I(x, y) should exist first of all. 

