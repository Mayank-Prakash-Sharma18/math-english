---
title: Division and Distribution - Part I
linktitle: Division and Distribution - Part I
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

In this article we will learn how to divide and distribute items in groups of <strong>known</strong> sizes. 

We can easily divide or group items in one step.

But distribution is a two step process. <br>
Step 1: To distribute something, first division (i.e. grouping) is done. <br>
Step 2: Then we permute these groups if required. <br>

For example, to distribute 3 items, x, y and z, into two groups and then distribute them among two people: <br>

Step 1: Division of 3 items into 2 groups = $C^3_2$ = 3<br>
(x, y), z<br>
(x, z), y<br>
(y, z), x<br>

Step 2: Permutate these groups, i.e. distribute these groups among two people<br>
They can be distributed among 2 people in 2! ways. <br>

So it is important to distinguish between division and distribution.<br>

## Division

### Division of distinct items into groups of unequal size

Number of ways to divide (m+ n) distinct items into groups of unequal size = $C^{m+n}_m$ × $C^n_n$ 
= $C^{m+n}_m$ = $\frac{(m + n)!}{m! n!}$ <br>
(Note that m ≠ n, i.e. m and n are non-equal) <br>
(Basically it is the same as selecting m items out of m+n items or selecting n items out of m+n items) <br>

Number of ways to divide (m + n + p) distinct items into groups of unequal size = $C^{m+n+p}_m$ × $C^{n+p}_n$ × $C^p_p$ = $C^{m+n+p}_m$ × $C^{n+p}_n$ = $\frac{(m + n + p)!}{m! n! p!}$  <br>
(Note that m ≠ n ≠ p, i.e. m, n and p are non-equal)

For example:

Number of ways to divide 6 distinct items into 2 groups of sizes 2 and 4 = $C^6_2$ = $\frac{6!}{2! 4!}$ 

Number of ways to divide 9 distinct items into 3 groups of sizes 2, 3 and 4 = $C^9_2$ × $C^7_3$ = $\frac{9!}{2! 3! 4!}$ <br><br>

Let’s see one more example: <br>
Number of ways to divide 4 distinct items into 2 groups of sizes 1 and 3 = $C^4_1$ = $\frac{4!}{1! 3!}$ = 4 <br>

Let’s visualize and count manually to check it:
<img src="../../../media/p-and-c/division.png" alt="division" style="width:81%;height:81%;">
The possible groups are: <br>
1, (2, 3, 4) <br>
2, (1, 3, 4) <br>
3, (1, 2, 4) <br>
4, (1, 2, 3) <br>
Total possible groups = 4 <br>

##### Q. In how many ways can 12 persons be divided into three groups having 3, 4 and 5 persons?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Formula Method <br><br>

Groups do not seem to be distinct. So, this is a case of division and not distribution.

Number of ways to divide (m+ n + p) distinct items into groups of unequal size = $\frac{(m + n + p)!}{m! n! p!}$  = $\frac{12!}{3! 4! 5!}$ 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Number of ways of selecting 3 people out of 12 = $C^{12}_3$ <br>
AND Number of ways of selecting 4 people out of the remaining 9 = $C^9_4$  <br>
AND Number of ways of selecting 5 people out of the remaining 5 = $C^5_5$  <br>

So, total number of ways = $C^{12}_3$ × $C^9_4$ × $C^5_5$    <br>
(we will multiply because we need to do all the three steps; notice the word AND) <br>
= $\frac{12!}{(3!9!)}$ × $\frac{9!}{(4!5!)}$ × 1 = $\frac{12!}{(3! 4! 5!)}$ <br>
</div><br>

### Division of distinct items into groups of equal size

Number of ways to divide 2n distinct items into 2 groups of equal size = $\frac{1}{2!}$ $C^{2n}_n$ = $\frac{1}{2!}$ $\frac{2n!}{(n!)^2}$

E.g., Number of ways to divide 6 distinct items into 2 groups of equal size = $\frac{1}{2!}$ $\frac{6!}{(3!)^2}$  

Number of ways to divide 3n distinct items into 3 groups of equal size = $\frac{1}{3!}$ $\frac{3n!}{(n!)^3}$  

E.g., Number of ways to divide 9 distinct items into 3 groups of equal size = $\frac{1}{3!}$ $\frac{9!}{(3!)^3}$

Let’s see one more example: <br>

Number of ways to divide 4 distinct items into 2 groups of equal size = $\frac{1}{2!}$ $\frac{4!}{(2!)^2}$ = 3

Let’s visualize and count manually to check it:
<img src="../../../media/p-and-c/division.png" alt="division" style="width:81%;height:81%;">

The possible groups are:
<img src="../../../media/p-and-c/division1.png" alt="division" style="width:81%;height:81%;">
This is because of symmetry when groups are of equal size (this symmetry is not there when group sizes are different).

We can generalize: <br>
Number of ways to divide mn distinct items into m groups of equal size = $\frac{1}{m!}$ $\frac{mn!}{(n!)^m}$ <br>
(It means divide by m! if there are m groups having same number of items) <br>

Order of groups is not important, i.e. groups do not have distinct identity, as they are just being divided and not distributed. <br>

##### Q. In how many ways can 12 persons be divided into three groups having 4 persons each?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Using Formula Method <br><br>

Groups do not seem to be distinct. So, this is a case of division and not distribution.

Number of ways to divide mn distinct items into m groups of equal size = $\frac{1}{m!}$ $\frac{mn!}{(n!)^m}$ = $\frac{1}{3!}$ $\frac{12!}{(4!)^3}$ <br> 
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2:   <br><br>

Number of ways of selecting 4 people out of 12 = $C^{12}_4$  <br>
AND Number of ways of selecting 4 people out of the remaining 8 = $C^8_4$  <br>
AND Number of ways of selecting 4 people out of the remaining 4 = $C^4_4$  <br><br>

So, total number of ways = $\frac{C^{12}_4 × C^8_4 × C^4_4}{3!}$  <br>
(we will multiply because we need to do all the three steps; notice the word AND)  <br>
= $\frac{1}{3!}$ × $\frac{12!}{(4!8!)}$ × $\frac{8!}{(4!4!)}$ × 1 = $\frac{12!}{3! (4!)^3}$  <br>

Note: We divided by 3! because the groups are identical and have the same number of items (so we do so to avoid overcounting). If the groups were distinct or if the number of items in them were different, then there was no need to divide by 3!
</div><br>

<hr>

## Distribution

### Distribution of distinct items into groups of unequal size

Number of ways to distribute (m+ n) distinct items into two groups of unequal size = $C^{m+n}_m$ × $C^n_n$ × 2! = $C^{m+n}_m$ × 2! = $\frac{(m + n)!}{(m! n!)}$ × 2! 

(basically selecting m items out of m+n items or selecting n items out of m+n items and then distributing/arranging them)

Number of ways to distribute (m + n + p) distinct items into three groups of unequal size = $C^{m+n+p}_m$ × $C^{n+p}_n$ × $C^p_p$ × 3! = $C^{m+n+p}_m$ × $C^{n+p}_n$ × 3! = $\frac{(m + n + p)!}{(m! n! p!)}$ × 3! 

(Note that m ≠ n ≠ p, i.e. m, n and p are non-equal)

##### Q. In how many ways can 12 persons be distributed into three groups having 3, 4 and 5 persons? 

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Using Formula Method <br><br>

Groups do not seem to be distinct. So, this is a case of division and not distribution.

Number of ways to divide (m + n + p) distinct items into groups of unequal size = $\frac{(m + n + p)!}{(m! n! p!)}$ × 3! = $\frac{12!}{(3! 4! 5!)}$ × 3! = $\frac{12!}{(4! 5!)}$   
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Using the concept of Multiplying Factors  <br><br>

Number of ways of selecting 3 people out of 12 = $C^{12}_3$ <br>
AND Number of ways of selecting 4 people out of the remaining 9 = $C^9_4$  <br>
AND Number of ways of selecting 5 people out of the remaining 5 = $C^5_5$  <br>

So, total number of ways of dividing = $C^{12}_3$ × $C^9_4$ × $C^5_5$     <br>
(we will multiply because we need to do all the three steps; notice the word AND) <br>
= $\frac{12!}{(3! 9!)}$ × $\frac{9!}{(4! 5!)}$ × 1 = $\frac{12!}{(3! 4! 5!)}$  

Total number of ways of distributing these items in 3 groups = $\frac{12!}{(3! 4! 5!)}$ × 3! = $\frac{12!}{(4! 5!)}$
</div><br>

### Distribution of distinct items into groups of equal size

We know that: <br>
Number of ways to divide mn distinct items into m groups of equal size = $\frac{1}{m!}$ $\frac{mn!}{(n!)^m}$

Now to distribute these groups into m categories (e.g. m people etc): <br>
Number of ways to distribute mn distinct items into m groups of equal size = $\frac{1}{m!}$ $\frac{mn!}{(n!)^m}$ × m! = $\frac{mn!}{(n!)^m}$ 

(order of groups is important, i.e. groups have distinct identity, as they are being distributed to different groups/persons)

For example:

Number of ways to distribute 2n distinct items into 2 groups of equal size = $\frac{2n!}{(n!)^2}$ 

Number of ways to distribute 3n distinct items into 3 groups of equal size = $\frac{3n!}{(n!)^3}$ 

##### Q. In how many ways can 18 students be divided into:
(a) 3 groups <br>
(b) blue, green and yellow houses. <br>

Explanation: Using Formula Method<br>
<div class="Exp">
(a) Number of ways to divide mn distinct items into m groups of equal size = $\frac{1}{m!}$ $\frac{mn!}{(n!)^m}$ = $\frac{1}{3!}$ $\frac{18!}{(6!)^3}$  <br><br>

(b) Here the groups are distinct. So, this is a question of distribution and not just division. <br>
Number of ways to distribute mn distinct items into m groups of equal size = $\frac{mn!}{(n!)^m}$ = $\frac{18!}{(6!)^3}$  
</div> <br>

## What if the items are identical?

If all the items are identical then there is only one way to divide or distribute them. 

Say you have 10 identical balls and you want to divide them into three groups of 3, 3 and 4. You can choose any of the 3 balls and make group 1, choose any of the 3 balls from the remaining balls and make group 2; rest of the 4 balls will make group 3. 

Similarly, as the balls are identical, there is no there is no point in distributing them. There’s only 1 possible way. So, number of ways of distribution = number of ways of division 
