---
title: Problems based on the concept of Combination
linktitle: Combination 
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

In this article, we will have a look at the various problems that are formulated on the concept on ***Combination***. 

Compare this with the next article on Permutation, to further enhance your knowledge regarding the differences between these two closely related concepts. 

## n distinct items

### Selecting r items

Number of ways to select r items from n distinct items = $C^n_r$

Number of ways to select all n distinct items = $C^n_n$ = $C^n_0$ = 1 (Only one possible way)

##### Q. Out of 9 members in a team, 3 have to be chosen as module leads. In how many ways can it be done?

Explanation:<br>
<div class="Exp">
Number of ways of choosing 3 members out of 9 distinct members = $C^n_r$ <br>
= $C^9_3$ = $\frac{9×8×7}{3×2×1}$  = 84
</div> <br>

### Selecting 0, 1 or more items

Out of n items, 0 item can be selected in $C^n_0$ ways; 1 item can be selected in $C^n_1$ ways; 2 items can be selected in $C^n_2$ ways; three items can be selected in $C^n_3$ ways and so on.

So, Number of ways to select 0 or more items from n distinct items = $C^n_0$ + $C^n_1$ + $C^n_2$ + … + $C^n_n$ = $2^n$    

Number of ways to select 1 or more items from n distinct items = $C^n_1$ + $C^n_2$ + … + $C^n_n$ = $2^n$ - 1     <br><br>

{{% alert note %}}
Another way to look at it:<br>
In making selections each item can be dealt with in two ways; it is either selected or rejected. 

So, number of ways to select 0 or more items from n distinct items = $2^n$. 

But, these $2^n$ ways also include the case when all the items are rejected.
Hence, number of ways to select 1 or more items from n distinct items = $2^n$ — 1.
{{% /alert %}}

##### Q. In how many ways can a person invite one or more of his 5 friends to his birthday party?

Explanation:<br>
<div class="Exp">
The person needs to select one or more from 5 distinct members. <br>
So, required number of ways = $2^n$ - 1 = $2^5$ - 1 = 32 – 1 = 31
</div> <br>

<hr>

## n identical items

Number of ways to select all items – Only one possible way

Number of ways to select r items from n identical items = 1  <br>
(as whichever set of items you select, they will be identical)

Number of ways to select 0 or more items from n identical items = n + 1    

Number of ways to select 1 or more items from n identical items = n

The total number of ways in which a selection can be made by taking some or all out of p + q + r + ....... things, where p are alike of one kind, q alike of a second kind, r alike of a third kind and so on is [(p + 1)(q + 1)(r + 1) ...] - 1

<hr>

## Mix of identical and distinct items

The total number of ways of selecting one or more items from p identical items of one kind; q identical items of second kind; r identical items of third kind and n different items is:
[(p + 1)(q + 1)(r + 1)]$2^n$ - 1 
