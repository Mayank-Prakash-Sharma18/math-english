---
title: Cyclicity Method
linktitle: Cyclicity Method
toc: true
type: docs
date: "2021-02-26T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 1. Number System
    weight: 21

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 21
---

## Concept of Cyclicity in Product 

If we multiply any 2 numbers then the last digit of the product will depend on the last digit of these two numbers. 

E.g. if we multiply 23 and 47, the last digit of this product will be the same as the last digit of 3 x 7, i.e. 1.

## Concept of Cyclicity in Powers of numbers 

We can extend this concept to other areas too, e.g. exponents of numbers. 

E.g. Last digit of 3 = 3 <br>
Last digit of $3^2$ (i.e. 3 × 3) = 9 <br>
Last digit of $3^3$ (i.e. 3 × 3 × 3) = 7 <br>
Last digit of $3^4$ (i.e. 3 × 3 × 3 × 3) = 1 <br>
Last digit of $3^5$ (i.e. 3 × 3 × 3 × 3 × 3) = 3

As we can notice, the last digit of the exponents of 3 follow a repetitive pattern: 3, 9, 7, 1

In fact the last digits of the exponents of all numbers have a cyclicity. That is, the last digits of the powers of any number repeat after certain number of steps. If we find out after how many steps the last digit of the powers of a number repeat, then we can find out the last digit of any power of any number. 

In the example above, the cyclicity of 3 was 4, i.e. $3^1$ has the same last digit as $3^5$, $3^2$ has the same last digit as that of $3^6$ and so on. 

Let us look at the powers of 2.

Last digit of $2^1$ is 2
Last digit of $2^2$ is 4 .
Last digit of $2^3$ is 8
Last digit of $2^4$ is 6
Last digit of $2^5$ is 2

As we can notice, the last digit of the exponents of 2 follow a repetitive pattern: 2, 4, 8, 6

So, the cyclicity of 2 is 4, i.e. for powers of 2 the last digits repeat after every 4 steps. $2^1$ has the same last digit as $2^5$, $2^2$ has the same last digit as that of $2^6$ and so on. 

<img src="../../../media/number-system/cyclicity-table.png" alt="Cyclicity Table" style="width:99%;height:99%;">

##### Q. Find the last digit of $2^{39}$.

Explanation:<br>
<div class="Exp">

The cyclicity of 2 is 4. 

The largest multiple of 4 which is less than or equal to 39 is 36. 

So, the last digit of $2^{37}$ will be the same as the last digit of $2^1$ <br>
The last digit of $2^{38}$ will be the same as the last digit of $2^2$ <br>
The last digit of $2^{39}$ will be the same as the last digit of $2^3$, i.e. 8. 
</div> <br>
