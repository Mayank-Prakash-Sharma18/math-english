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

## Circular Arrangements (Distinct items)

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

## Circular Arrangements (Identical items)

If all items in a circular arrangement are identical, then there is only one way in which we can arrange them. 

##### Q. In how many ways can 10 identical red balls and one white ball be symmetrically arranged on a circular table?
<pre>(a) 1   (b) 10!    (c) 9!   (d) 11!</pre>

Explanation:<br>
<div class="Exp">

Here we are supposed to arrange, i.e. it's a question of permutation. 

However, the 10 red balls are identical. Hence, no matter how we arrange them and the single white ball on the circular table symmetrically, we will effectively get the same kind of arrangement. 

Answer: (a)
</div> <br>

<hr>

## Rectangular Arrangements

Rectangular arrangements may be akin to linear arrangement or circular arrangement. They may even have eccentricities of their own. 

##### Q. In how many ways can 16 guests be seated on a rectangular table, such that 8 guests are sitting on either side?
(a) $C^{16}_8$ × 8! <br>
(b) $C^{16}_8$ × 8! × 8! <br>
(c) 8! × 8! <br>
(d) 16!

Explanation:<br>
<div class="Exp">

We have to place 16 guests on a rectangular table, such that 8 are sitting on one side, and the other 8 on the other side. 

We can choose 8 guests out of the 16 in $C^{16}_8$ ways. Once selected, they can be arranged in 8! ways.

Similarly, the remaining 8 guests may also be arranged in 8! ways. 

So, total number of ways of selecting and then arranging these 16 guests = $C^{16}_8$ × 8! × 8!

Answer: (b)
</div> <br>


##### Q. 16 guests have to be seated on a rectangular table, such that 8 guests are sitting on either side. If 5 guests want to sit on a particular side, and 2 guests want to sit on the other side, then in how many ways can they be seated?
(a) $C^9_3$ × 8! <br>
(b) 5! 2! 8! <br>
(c) 8! × 7! <br>
(d) $C^9_3$ × 8! × 8!

Explanation:<br>
<div class="Exp">

We have to place 16 guests on a rectangular table, such that 8 are sitting on one side, and the other 8 on the other side. 

As 5 guests want to sit on a particular side (say Side I), and 2 on the other side (say Side II). So, we just need to make our selection from the remaining (16 - 7) = 9 guests. 

Number of ways to choose the 3 remaining guests to be placed on Side I from among 9 guests = $C^9_3$ <br>
Now, (9 - 3) = 6 guests remain to be seated. <br>
Number of ways to choose the 6 remaining guests to be placed on Side II from among 6 guests = $C^6_6$ = 1

Once selected, guests sitting on each side of the table can be arranged in 8! ways amongst themselves.

So, total number of ways of selecting and then arranging these 16 guests = $C^9_3$ × 8! × 8!

Answer: (d)
</div> <br>
