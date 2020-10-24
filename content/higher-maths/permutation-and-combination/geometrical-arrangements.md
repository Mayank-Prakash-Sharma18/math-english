---
title: Geometrical arrangements
linktitle: Geometrical arrangements 
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

## Circular Arrangements

### Linear Vs. Circular arrangement

Say we have a linear arrangement - 1234 <br>
If we move every item one place to the right (in cyclic order), the new arrangement - 4123 

Notice that the old and the new arrangements are not the same. <br>
So, both of them are counted in the n! permutations (which will be 4! in this case).

<img src="../../../media/p-and-c/geometrical-arrangements.png" alt="geometrical arrangements" style="width:81%;height:81%;">

However, if the given arrangement 1234 is circular, then by shifting every item by one place in the clockwise direction, we still get the same arrangement 1234. 

As n! will count both of these cases, we will be counting the same arrangement more than once. The answer we get will be more than the correct answer.

<img src="../../../media/p-and-c/geometrical-arrangements1.png" alt="geometrical arrangements" style="width:90%;height:90%;">

So, you can see that circular arrangement is not same as linear arrangement. Every linear arrangement has a beginning and an end, but a circle has no starting point and no ending point.

To solve this issue we fix the position of one item as reference point (which will act as our starting and end point). Then the remaining (n - 1) items can be arranged as in case of linear arrangements, i.e. in (n - 1)! ways. 

<img src="../../../media/p-and-c/geometrical-arrangements2.png" alt="geometrical arrangements" style="width:90%;height:90%;">

Now even if we move these (n - 1) items by one place in the clockwise direction, then the arrangement that we get will not be the same as the initial arrangement because one item is fixed and it does not move.

{{% alert note %}}
Number of circular permutation of n different things taken all at a time = (n - 1)! ways. <br>

E.g. Four persons around a circular table can be arranged in (4 - 1)! = 6 ways

Note that here Clockwise & Anti-clockwise arrangements are different.
{{% /alert %}}

##### Q. In how many ways can 5 boys be seated around a circular table?

Explanation:<br>
<div class="Exp">
Number of possible circular arrangements = (n - 1)! = (5 - 1)! = 4! = 24
</div> <br>

### Identical Clockwise & Anti-clockwise arrangements 

Let us understand the cases wherein the clockwise & anti-clockwise circular arrangements are the same. 

If four persons 1, 2, 3 and 4 are sitting around a table, then these two arrangements will be considered different and distinct:
* 1234 (in clockwise direction) and 
* 1432 (the same order but in anticlockwise direction). 
So, the clockwise and anticlockwise arrangements are different.

<img src="../../../media/p-and-c/geometrical-arrangements3.png" alt="geometrical arrangements" style="width:54%;height:54%;">

However, if we consider the circular arrangement of a necklace made of four precious stones 1, 2, 3 and 4, then there will be no difference between the clockwise and anticlockwise arrangements. It is because if we take one arrangement and turn the necklace around (front to back), then we get the other arrangement. 

The number of arrangements in such cases will be half of what it is in the case where the clockwise and anticlockwise arrangements are different.

{{% alert note %}}
Summary:

The number of circular arrangements of n distinct items = (n - 1)! <br>
(if clockwise and anticlockwise arrangements are distinct) 

The number of circular arrangements of n distinct items = $\frac{(n - 1)!}{2}$ <br>
(if there is no difference between clockwise and anticlockwise arrangements)
{{% /alert %}}

##### Q. In how many ways can 5 gems be arranged to form a necklace?

Explanation:<br>
<div class="Exp">
Number of possible circular arrangements = $\frac{(n - 1)!}{2}$ = $\frac{(5 - 1)!}{2}$ = $\frac{4!}{2}$ = $\frac{24}{2}$ = 12
</div> <br>

<hr>

## Rectangular Arrangements

Rectangular arrangements may be akin to linear arrangement or circular arrangement. They may even have eccentricities of their own. 

