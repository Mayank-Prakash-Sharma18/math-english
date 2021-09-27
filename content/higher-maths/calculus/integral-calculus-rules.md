---
title: Rules of Integral Calculus 
linktitle: Rules of Integration
toc: true
type: docs
date: "2021-09-25T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 2. Integral Calculus
    weight: 33

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 33
---

We already have understood how we calculate integrals of some simple functions. However, in most of the questions that we will face in exam, things would probably not be so simple. 

Many a times we will have to calculate integrals of complex functions, which are made by combining simple functions in various ways. 

We will have to follow some rules of Integral Calculus to find out integrals of such complex expressions. Let's see some of these rules.


## Rules of Integral Calculus

We will represent functions f(x) and g(x) as f and g. And their derivatives f'(x) and g'(x) as f' and g'.

### Multiplication by constant Rule

∫c f(x) dx	= c ∫f(x) dx <br>
(Where c is a constant)

##### Q. What is ∫ 3 $x^3$

Explanation:<br>
<div class="Exp">

∫ 3 $x^3$ = 3 ∫ $x^3$ = 3 $\frac{x^4}{4}$
</div> <br>


### Sum and Difference Rule

∫(f + g) dx	= ∫f dx + ∫g dx

∫(f - g) dx	= ∫f dx - ∫g dx

##### Q. What is ∫ (x + cos x)

Explanation:<br>
<div class="Exp">

∫ (x + cos x) = ∫ x + ∫ cos x = $\frac{x^2}{2}$ + sin x
</div> <br>


### Integration by Parts

We use this rule to integrate product of two functions. 

∫ f . g dx	= f ∫g dx - ∫f' (∫g dx) dx

{{% alert note %}}
Here, we need to choose which function will take the place of f and which one will come in place of g. Our aim will be to ensure that our calculation is the least complex. 

So, f should be a function that gets simpler after differenciation, and g should be a function that gets simpler after integration. 

In general, we should choose the following functions in place of f (i.e. for differenciation), in that order:
* Inverse trigonometric functions: $sin{-1}x, cos{-1}x, tan{-1}x$
* Logarithmic functions: ln x, log x
* Algebraic functions: $x^2$, $x^3$, $x^4$
* Trigonometric functions: sin x, cos x, tan x
* Exponential functions: $e^x$, $2^x$

So, if we have to integrate $x^2$ sin x, then differenciate $x^2$ and integrate sin x. 
{{% /alert %}}

##### Q. What is ∫ x  cos x

Explanation:<br>
<div class="Exp">

The first thing we should do is to choose which function will be f and which will take the place of g. 

Let f = x <br>
And g = cos x

Now, f' = $\frac{d}{dx} x = 1$ <br>
∫g dx = ∫cos x dx = sin x

∫ f . g dx	= f ∫g dx - ∫f' (∫g dx) dx <br>
So, ∫ x  cos x = $x sin x - ∫ sin x \hspace{1ex} dx = x sin x + cos x + c$ 
</div> <br>


### Integration by Substitution

We can simplify the process of integration by substituting complex functions with simpler variables. Let's see how. 

To do so, the functions to be integrated must be in the following form: <br>
∫ f (g(x)) g'(x) dx <br>
Then on putting u = g(x), we get ∫ f (u) u' dx, or ∫ f (u) du

For example, ∫ cos ($x^3$) . 3$x^2$ dx <br>
Here, $\frac{d}{dx} x^3$ = 3$x^2$

So, we can simplify the above expression. <br>
∫ cos ($x^3$) . 3$x^2$ dx = ∫ cos (u) . u' dx = ∫ cos (u) du <br>
(Where u = $x^3$)

This is obviously a much simpler expression to work on. Once we have found the integral of the above expression, we can later on substitute the value of u. 

{{% alert note %}}
This method will work only on a few expressions. Many a times, the expression will not be given in this form. You will have to identify that this pattern exists, and do some rearrangements. 
{{% /alert %}}

