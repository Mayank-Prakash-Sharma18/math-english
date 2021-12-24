---
title: Types of Combination Questions
linktitle: Combination Question Types
toc: true
type: docs
date: "2021-10-24T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 7

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 7
---

In this article, we will have a look at the various types of questions that we encounter based on the topic of Combination. 

But you must be aware of the basic concepts of Combination before we do so. If you aren't, then have a look at the previous articles. 

## Type 1: Selecting two items

In such questions, you will be asked to find the number of ways in which you can select two people/items out of a group. 

### Type 1a: Making a team

##### Q. From a group of 40 people, in how many ways can a team be formed having one boss and 4 juniors?
(a) 40 × $C^{39}_4$ <br>
(b) 41 × $C^{39}_4$ <br>
(c) 41 × $C^{40}_4$ <br>
(d) None of these.

Explanation:<br>
<div class="Exp">

One boss can be selected in 40 ways. <br>
Remaining 4 juniors can be selected from 39 remaining members in $C^{39}_4$ ways.

Total number of ways in which team can be formed = 40 × $C^{39}_4$

Answer: (a)
</div> <br>


##### Q. A team for mixed doubles tennis match has one male and one female player. You have to make a mixed doubles team from amoung 5 men and 6 women. There is exactly one married couple amongst them. In how many ways can you do so, if the couple cannot play as a team?
(a) $C^{5}_1$ × $C^{6}_1$ - 1 <br>
(b) $C^{11}_2$ + 1 <br>
(c) 29 <br>
(d) 30

Explanation:<br>
<div class="Exp">

The number of ways of choosing 1 male as a team member = 5. <br>
The number of ways of choosing 1 female as a team member = 6.

Total number of ways of choosing 1 team = 5 × 6 = 30. <br>
Number of ways of choosing the couple = 1. <br>
So, the number of ways to form the team = 30 – 1 = 29.

Answer: (c) 
</div> <br>

##### Q. There are 9 types of envelopes and 8 types of stamps available in a post office. If a letter is to be posted, and each letter requires an envelope and a stamp, how many ways are there to post a letter?
<pre>(a) 86   (b) 48    (c) 72   (d) 36</pre>

Explanation:<br>
<div class="Exp">

To post a letter, we need to select one envelop out of 9 and one stamp out of 8.

Thus, Number of ways of posting a letter = $C^{9}_1$ × $C^{8}_1$ = 9 × 8 = 72

Answer: (c)
</div> <br>

### Type 1b: Handshakes

##### Q. Ten people are sitting around a circular table for a meeting. If each person shakes hands with every other person except for the person sitting adjacent to him/her, how many handshakes took place in the meeting?
<pre>(a) 45         (b) 35          (c) 90          (d) 100</pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Method I: <br><br>

It is given that the ten people are sitting around a circular table and everyone shakes hands with every other person except for the two persons sitting beside him/her.

Therefore, it can be imagined that all the handshakes happen along the diagonals of a ten sided polygon. 
Number of diagonals in a polygon = $C^n_2$ – n , where n = number of sides of polygon. 

So, the number of handshakes = $C^{10}_2$ – 10 = (10 × 9)/2 - 10 = 45 – 10 = 35.

Answer: (b) 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Method II: <br><br>

If there were no restrictions, there would have been $C^{10}_2$ handshakes. 

However, it is mentioned that each person shakes hand with every other person except for the two person sitting beside him/her. Hence, there would be 10 fewer handshakes. 

Required number of handshakes = $C^{10}_2$ – 10 = (10 × 9)/2 - 10 = 45 – 10 = 35.

Answer: (b)
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Method III: <br><br>

It is clear from the statement given in the question that each person shakes hands with 7 persons (excluding himself/herself and two of his/her neighbours).  

So, we may erringly infer that total number of handshakes = 10 × 7

But in this process every A shaking hands with B and B shaking hands with A is counted separately (assuming A and B are two persons). So, the total number of handshakes may be obtained by dividing this by two.

Total number of handshakes = (10 × 7)/2 = 35

Answer: (b)
</div><br>


## Type 2: Selecting a Team

In such questions, you will be asked to find the number of ways in which you can select a team out of a group. 

### Type 2a: No Conditions

##### Q. Out of 6 ruling party leaders and 4 opposition party leaders, 3 leaders are to be selected for a delegation. In how many ways can the delegation be selected?
<pre>(a) 120   (b) 100    (c) 110   (d) 80</pre>

Explanation:<br>
<div class="Exp">

Total number of ways in which 3 persons can be selected = $C^{10}_3$ = 120

Answer: (a)
</div> <br>

### Type 2b: With Inclusion or Exclusion Conditions

##### Q. Out of 6 ruling party leaders and 4 opposition party leaders, 3 leaders are to be selected for a delegation. In how many ways can the delegation be selected, if it must have atleast one opposition party leader?
<pre>(a) 120   (b) 100    (c) 110   (d) 80</pre>

Explanation:<br>
<div class="Exp">

Required number of ways = Total number of ways in which 3 persons can be selected – Number of ways of not including any opposition party leader = $C^{10}_3$  – $C^{6}_3$ = 120 – 20 = 100

Answer: (b)
</div> <br>

### Type 2c: At least, At most Conditions

##### Q. A team of 11 is to be selected from 7 batsmen and 6 bowlers available. The team must have at least 5 bowlers. In how many ways can it be done?
<pre>(a) 21   (b) 42    (c) 84   (d) 63</pre>

Explanation:<br>
<div class="Exp">

Here we have to select, i.e. it's a question of combination, as the order of the players do not matter. 
As the team must have at least 5 bowlers, two cases emerge:

**Case I**: Team has 5 bowlers and 6 batsmen. <br>
Number of ways of choosing such a team = Number of ways of choosing 5 bowlers out of 6 and 6 batsmen out of 7 = $C^{6}_5$ × $C^{7}_6$ = 6 × 7 = 42.

**Case II**: Team has 6 bowlers and 5 batsmen. <br>
Number of ways of choosing such a team = Number of ways of choosing 6 bowlers out of 6 and 5 batsmen out of 7 = $C^{6}_6$ × $C^{7}_5$ = 1 × 21 = 21.

Hence, total ways possible = 42 + 21 = 63.

Answer: (d)
</div> <br>


## Type 3: Selecting Points

In such questions, you will be asked to find the number of ways in which you can select two, three or more points out of a number of points. 

### Type 3a: Selecting 2 Points

##### Q. There are 19 points in a plane, out of which 5 are collinear. What are the number of straight lines that can be formed using these points?
<pre>(a) 196   (b) 162    (c) 175   (d) 191</pre>

Explanation:<br>
<div class="Exp">

To draw a line we need two points which may be joined. 

If the 19 points were non-collinear, then the number of straight lines that can be drawn = $C^{19}_2$

Number of straight lines that can be formed using 5 points = $C^{5}_2$

However, these five points are collinear. So, now $C^{5}_2$ has to be considered to be 1, as only one line can be drawn using these points.

∴ The number of straight lines that can be formed = $C^{19}_2$ – $C^{5}_2$ + 1 = 171 – 10 + 1 = 162

Answer: (b)
</div> <br>

### Type 3b: Selecting 4 Points

##### Q. Nine points are there on a given plane, out of which four are collinear. How many quadrilaterals can be formed using these nine points?
<pre>(a) 40   (b) 100    (c) 105   (d) 60</pre>

Explanation:<br>
<div class="Exp">

Number of ways to select r items from n distinct items (wherein r ≤ n) = $C^n_r$ = n!/[r! × (n−r)!]

A quadrilateral can be formed in following cases:

Case I: All four points are non-collinear. <br>
Number of ways in which this can be done = $C^{9 - 4}_4 = C^5_4 = 5$

Case II: One point is from the set of collinear points, and three points are from the set of non-collinear points. <br>
Number of ways in which this can be done = $C^4_1 × C^{9 - 4}_3 = C^4_1 × C^5_3 = 4 × 10 = 40$

Case III: Two points are from the set of collinear points, and two points are from the set of non-collinear points. <br>
Number of ways in which this can be done = $C^4_2 × C^{9 - 4}_2 = C^4_2 × C^5_2 = 6 × 10 = 60$

So, Total number of quadrilaterals that can be formed = 5 + 60 + 40 = 105.

{{% alert note %}}
If three points are from the set of collinear points, then a triangle will be formed, and not a quadrilateral.

If all four points are from the set of collinear points, then a line will be formed, and not a quadrilateral.
{{% /alert %}}

Answer: (c)
</div> <br>


## Miscellaneous Questions

##### Q. How many terms will be there having only a single x in them, if we simplify the following product?
$(x_1 + y_1) (x_2 + y_2) ... (x_{10} + y_{10})$

<pre>(a) 1   (b) 10    (c) 100   (d) 50</pre>

Explanation:<br>
<div class="Exp">

We need to select x out of 10 terms.
Selecting 1 out of 10 terms = $C^{10}_1$ = 10!/(1! × 9!) = 10

∴ Required terms are 10 in number.

{{% alert note %}}
We can also solve this question by observing the pattern we get on simplifying the given expression. 

For example, $(x_1 + y_1) (x_2 + y_2)$ gives 2 terms that have only one x in them. <br>
$(x_1 + y_1) (x_2 + y_2) (x_3 + y_3)$ gives 3 terms that have only one x in them. <br>
And so on. 
{{% /alert %}}

Answer: (b)
</div> <br>

