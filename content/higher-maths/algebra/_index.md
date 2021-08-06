---
# Course title, summary, and position.
linktitle: Introduction to Algebra
summary: This is a basic introduction to Algebra.
weight: 21

# Page metadata.
title: Introduction to Algebra
date: "2021-06-28T00:00:00Z"
lastmod: "2021-06-28T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  algebra:
    name: Overview
    weight: 1
---

## What is Algebra? 

Algebra is a part of mathematics where we use letters/symbols to represent numbers in an equation/formula/inequality, and then manipulate them using some rules. 

{{% alert note %}}
#### Symmetrical and Unsymmetrical expression

* Unsymmetrical expression: It is an expression in which the weight of all the variables (say a, b,c ...) is not the same. <br><br>
For example, $a + b + c^2, a^2 + b^2 – c^2, a^3 + b^3 + c^2$ etc

* Symmetrical expression: It is an expression in which the weight of all the variables is equal. <br><br>
For example, a + b + c, 3a + 3b + 3c, $a^2 + b^2 + c^2, a^3 + b^3 + c^3$, ab + bc + ca etc. <br><br>
So, in a symmetrical expression we can interchange the positions of the variables. 
{{% /alert %}}


## Algebra Formulae

Now, let's have a look at some of the basic formulae that we are going to use in this chapter. 

### Square Formulae

#### Square Formulae Type 1: Two Variables

$(x + y)^2 = x^2 + y^2 + 2xy = (x – y)^2 + 4xy$ <br>
$(x – y)^2 = x^2 + y^2 – 2xy = (x + y)^2 - 4xy$

$x^2 – y^2 = (x + y)(x – y)$ <br>
$x^2 + y^2 = (x + y)^2 – 2xy = (x – y)^2 + 2xy$

$(x + y)^2 + (x – y)^2 = 2(x^2 + y^2)$ <br>
$(x + y)^2 – (x – y)^2 = 4xy$

#### Square Formulae Type 2: Three Variables

$(x +y + z)^2 = x^2 + y^2 + z^2 + 2(xy + yz + zx)$ <br>
$(x – y + z)^2 = x^2 + y^2 + z^2 + 2(–xy – yz + zx)$ <br>
$(x - y – z)^2 = x^2 + y^2 + z^2 + 2(-xy + yz – zx)$

#### Square Formulae Type 3

If $(x – a)^2 + (y – b)^2 + (z – c)^2$ = 0, then x – a = 0, y – b = 0 & z – c = 0 <br>
i.e. If $A^2 + B^2 + C^2$ = 0, then A = B = C = 0

$A^2 + B^2 + C^2 – AB – BC – CA$ = 0, then A = B = C


### Cubic Formulae

#### Cubic Formulae Type 1: Two Variables

$(x + y)^3 = x^3 + y^3 + 3xy (x + y)$ <br>
$(x – y)^3 = x^3 – y^3 – 3xy(x – y)$

$(x + y)^3 + (x – y)^3 = 2x(x^2 + 3y^2)$ <br>
$(x + y)^3 – (x – y)^3 = 2y(3x^2 + y^2)$

$x^3 + y^3 = (x + y) (x^2 + y^2 – xy) = (x + y)^3 – 3xy (x + y)$ <br>
$x^3 – y^3 = (x – y) (x^2 + y^2 + xy) = (x – y)^3 + 3xy (x – y)$

{{% alert note %}}
$x^n – y^n = (x – y) (x^{n - 1} + x^{n - 2}.y + x^{n - 3}.y^2 + ... + y^{n - 1})$
{{% /alert %}}

#### Cubic Formulae Type 2: Three Variables

$(x + y + z)^3 = x^3 + y^3 + z^3 + 3(x + y) (y + z) (z + x)$ 

$x^3 + y^3 + z^3 – 3 xyz = (x + y + z) (x^2 + y^2 + z^2 – xy – yz – zx)$ <br>
= $(x + y + z) × \frac{1}{2} [(x - y)^2 + (y - z)^2 + (z - x)^2]$ <br>

{{% alert note %}}
When x + y + z = 0, then $x^3 + y^3 + z^3 = 3xyz$
{{% /alert %}}


### Function and Inverse Function Formulae

#### Type 1: $x + \frac{1}{x}$

If $x + \frac{1}{x}$ = a, then:

* $x - \frac{1}{x} = \sqrt{a^2 - 4}$

* $x^2 + \frac{1}{x^2} = a^2 - 2$

* $x^3 + \frac{1}{x^3} = a^3 - 3a$

{{% alert note %}}
If $x + \frac{1}{x}$ = 1, then $x^3$ = –1. <br>
If $x + \frac{1}{x}$ = -1, then $x^3$ = 1

If $x + \frac{1}{x}$ = 2, then x = 1 <br>
If $x + \frac{1}{x}$ = -2, then x = – 1

If $x + \frac{1}{x} = \sqrt{3}$, then $x^6$ = –1
{{% /alert %}}

#### Type 2: $x - \frac{1}{x}$

If $x - \frac{1}{x}$ = a, then:

* $x + \frac{1}{x} = \sqrt{a^2 + 4}$

* $x^2 + \frac{1}{x^2} = a^2 + 2$

* $x^3 - \frac{1}{x^3} = a^3 + 3a$

#### Type 3: $x^2 + \frac{1}{x^2}$

If $x^2 + \frac{1}{x^2}$ = a, then:

* $x + \frac{1}{x}$ = $\sqrt{a + 2}$

* $x - \frac{1}{x}$ = $\sqrt{a - 2}$

If $x^2 + \frac{1}{x^2}$ = 1, then:

* $x^3 + \frac{1}{x^3}$ = 0 and $x^6$ = –1

#### Type 4: Higher Even Powers

$x^4 + \frac{1}{x^4} = (x^2 + \frac{1}{x^2})^2 - 2 = [(x - \frac{1}{x})^2 + 2]^2 - 2$

$x^6 + \frac{1}{x^6} = (x^3 + \frac{1}{x^3})^2 - 2 = (x^2 + \frac{1}{x^2})^3 - 3(x^2 + \frac{1}{x^2})$

#### Type 5: Higher Odd Powers

$x^5 + \frac{1}{x^5} = (x^2 + \frac{1}{x^2}) (x^3 + \frac{1}{x^3}) - (x + \frac{1}{x})$ <br><br>
$x^7 + \frac{1}{x^7} = (x^4 + \frac{1}{x^4}) (x^3 + \frac{1}{x^3}) - (x + \frac{1}{x})$

$x^5 - \frac{1}{x^5} = (x^2 + \frac{1}{x^2}) (x^3 - \frac{1}{x^3}) - (x - \frac{1}{x})$ <br><br>
$x^7 - \frac{1}{x^7} = (x^4 + \frac{1}{x^4}) (x^3 - \frac{1}{x^3}) + (x - \frac{1}{x})$


## Algebra Properties

### Property 1: Distributive law

x (y + z) = xy + xz 


### Property 2: Componendo and Dividendo

If $\frac{a}{b} = \frac{x}{y}$, then $\frac{a + b}{a - b} = \frac{x + y}{x - y}$ 

If $\frac{x + y}{x - y}$ = z, then , $\frac{x}{y} = \frac{z + 1}{z - 1}$ 
