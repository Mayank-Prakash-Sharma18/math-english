---
title: Basics of Permutation and Combination
linktitle: Basics 
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

In this article, we will understand the very basic concepts of Permutation and Combination (P & C), and also learn to differentiate between the two. 

## Concept of P & C

***Combination*** - Each of the groups or <strong>selections</strong> which can be made by taking some or all of a number of items. 

Combinations implies ‘selection’ - the order in which the items are taken is not considered as long as the specific things are included.

***Permutation*** - Each of the <strong>arrangements</strong> which can be made by taking some or all of a number of items. 

Permutation implies ‘arrangement’ – ‘order of the items’ is important.

{{% alert note %}}
Point to note: <br>
In the process of arranging a group of distinct items by taking some of them at a time, the job of selection occurs prior to the job of arranging the selected items. <br>
That is, we will select first and only then we will arrange. 
{{% /alert %}}

***Selection***:<br>
Suppose there are 3 books: A, B and C. We have to select 2 books out of these 3. This can be done in 3 ways. i.e. (A and B), (B and C), (C and A). – Selection of A & B is the same as selecting B & A etc.<br>
When we select something, we use the word 'combination', represented by C.

***Arrangement***:<br>
If we are to choose the best and the second best book, there will be 6 ways of doing so, i.e. (A, B), (B, A), (B, C), (C, B), (C, A), (A, C). <br>
Here (A, B) and (B, A) are different because in the first scenario A is the best book, while in the second scenario it is the second best book. <br>
When we arrange something, we use the word permutation, represented by P.


## Identifying the Problem

When you encounter a P & C problem, the first thing you should do is to find out whether it is permutation or combination that is being discussed.  

* Some times the problem states this explicitly:<br><br>
For permutations, "Find the number of permutations that can be made ..." OR "Find the number of arrangements that can be made....." OR "Find the number of ways in which you can arrange.....” (notice the use of keywords permutation and arrangement)<br><br>
For combinations, "Find the number of combinations that can be made.....” OR "Find the number of selections that can be made....." OR "Find the number of ways in which you can select.....” (notice the use of keywords combination and selection)

* Some times the problem states this implicitly:<br><br>
‘How many five-digit numbers can be made from the digits 1, 3, 6, 7 and 9 using each digit once?’<br>
Here, the order of the digits matters, as different orders will make different numbers. So, this is a question of arrangement/permutation.<br><br>
‘Out of a group of six friends, I have to invite two for lunch. In how many different ways can it be done?’<br>
Here, order of items is not important. E.g. if I invite friend 3 and friend 5, then this selection is all I have to do. It does not matter if I invite friend 3 first or friend 5 first. So, this is a question of selection/combination. <br><br>

<hr>

## $C^n_r$ and $P^n_r$ 

Number of combinations of n different things taken r at a time or Selection of r things out of n different things is given by:

$C^n_r$ = $\frac{n!}{r!(n-r)!}$ 

Number of arrangements of n different things taken r at a time or Selecting r things out of n different things and then arranging these r things is given by:

$P^n_r$ = $\frac{n!}{(n-r)!}$

{{% alert note %}}
#### Understanding $P^n_r$ 

While Combination involves only selection, in Permutation we need to select and then arrange. 

So, Permutation = Selection + Arrangement

* Arrangement of r things out of n different things ≡ first selecting r things out of n things ($C^n_r$) and then arranging these r things (r!).<br>
$P^n_r$ = $C^n_r$ × r! <br>
(which is nothing but $\frac{n!}{r!(n-r)!} $ × r! = $\frac{n!}{(n-r)!} $) 

* Arrangement of all n different things:<br>
$P^n_n$ = $C^n_n$ × n! = n! <br>
{{% /alert %}}

##### Q. Find the number of permutations and combinations if n = 6 and r = 2.

Explanation:<br>
<div class="Exp">

$C^n_r$ = $\frac{n!}{r!(n-r)!} = \frac{6!}{2!(6-2)!} = \frac{6!}{2! 4!} = \frac{6 × 5}{2} = 15$  

$P^n_r$ = $\frac{n!}{(n-r)!} = \frac{6!}{(6-2)!} = \frac{6!}{4!} = 6 × 5 = 30$
</div> <br>

### Property 1

$C^n_0$ = $\frac{n!}{0!(n-0)!} $ = $\frac{n!}{n!} $ = 1

$C^n_n$ = $\frac{n!}{n!(n-n)!} $ = $\frac{n!}{n!} $ = 1

### Property 2

$C^n_r$ = $C^n_{n-r}$
(for 0 ≤ r ≤ n)

##### Q. Find the value of $C^9_7$.

Explanation:<br>
<div class="Exp">

$C^9_7$ = $C^9_2 = \frac{9!}{2!(9-2)!} = \frac{9!}{2! 7!} = \frac{9 × 8}{2} = 36$  
</div> <br>

### Property 3

If x and y are non-negative integers such that $C^n_x$  = $C^n_y$  , then:<br>
x = y or x + y = n 

##### Q. If $C^n_8$  = $C^n_{15}$, then what is the value of n?

Explanation:<br>
<div class="Exp">
If $C^n_x$  = $C^n_y$, then x = y or x + y = n <br>
So, n = 8 + 15 = 23
</div> <br>

### Property 4

$C^n_{r-1}$ + $C^n_r$ = $C^{n+1}_r$

(n and r are non-negative integers such that r ≤ n)

For example, $C^5_2 + C^5_3 = C^{5+1}_3 = C^6_3$

### Property 5

$C^n_0$ + $C^n_1$ + $C^n_2$ + ……+ $C^n_n$ = $2^n$

{{% alert note %}}
#### Calculation Tips

* $C^n_r$ = $\frac{n!}{r!(n-r)!} $ <br><br>
So, $C^6_3$ = $\frac{6!}{3!(6-3)!} $ - A little time consuming calculation <br><br>
Better method:<br>
$C^6_3$ = $\frac{6×5×4}{3×2×1} $

* $P^n_r$ = $\frac{n!}{(n-r)!} $ <br><br>
So, $P^6_3$ = $\frac{6!}{(6-3)!} $ - A little time consuming calculation <br><br>
Better method:<br>
$P^6_3$ = 6 × 5 × 4
{{% /alert %}}

