---
title: Rules of Differential Calculus 
linktitle: Rules of Differentiation
toc: true
type: docs
date: "2021-09-22T00:00:00+01:00"
draft: false
menu:
  calculus:
    parent: 1. Differential Calculus
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

We already have understood how we calculate derivatives of some simple functions. However, in most of the questions that we will face in exam, things would probably not be so simple. 

Many a times we will have to calculate derivatives of complex functions, which are made by combining simple functions in various ways. 

For example, we know that: <br><br>
$\frac{d}{dx} sin x = cos x$ <br><br>
$\frac{d}{dx} cos x = - sin x$ 

However, $\frac{d}{dx} sin x \hspace{1ex} cos x ≠ cos x (- sin x)$

We will have to follow some rules of Differential Calculus to find out derivatives of such complex expressions. Let's see some of these rules.


## Rules of Differential Calculus

We will represent functions f(x) and g(x) as f and g. And their derivatives f'(x) and g'(x) as f' and g'.

### Multiplication by constant Rule

$\frac{d}{dx} c f = c f'$

##### Q. What is $\frac{d}{dx} 5x^2$

Explanation:<br>
<div class="Exp">

$\frac{d}{dx} 5x^2$ = 5 $\frac{d}{dx} x^2$ = 5 (2x) = 10x
</div> <br>


### Sum and Difference Rule

$\frac{d}{dx} [f + g] = f' + g'$ <br><br>
$\frac{d}{dx} [f - g] = f' - g'$

##### Q. What is $\frac{d}{dx} (x^2 + sin x)$

Explanation:<br>
<div class="Exp">

$\frac{d}{dx} (x^2 + sin x)$ = $\frac{d}{dx} x^2 + \frac{d}{dx} sin x$ = 2x + cos x
</div> <br>


### Product and Division Rule

$\frac{d}{dx} [f . g] = f' . g + f . g'$ <br><br>
$\frac{d}{dx} [f / g] = \frac{f' . g - f . g'}{g^2}$

{{% alert note %}}
**Special Case:**

$\frac{d}{dx} [1 / f] = \frac{- f'}{f^2}$
{{% /alert %}}

##### Q. What is $\frac{d}{dx} x sin x$

Explanation:<br>
<div class="Exp">

$\frac{d}{dx} x sin x = x \frac{d}{dx} sin x + sin x \frac{d}{dx} x$ = x cos x + sin x
</div> <br>


### Composition of Functions Rule

$\frac{d}{dx} fºg = (f'ºg) . g'$ <br>
or $\frac{d}{dx} f(g) = f'(g) . g'

{{% alert note %}}
We can also represent the above in the following manner.

$\frac{dy}{dx} = \frac{dy}{du} . \frac{du}{dx}$
{{% /alert %}}

##### Q. What is $\frac{d}{dx} sin x^3$

Explanation:<br>
<div class="Exp">

Here, g = $x^3$, and so f(g) = sin g

So, f'(g) = cos g = cos $x^3$ <br>
g' = $\frac{d}{dx} g = \frac{d}{dx} x^3 = 3x^2$

$\frac{d}{dx} sin x^3 = f'(g) . g' = 3x^2 . cos x^3$
</div> <br>

