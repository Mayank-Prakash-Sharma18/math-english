---
# Course title, summary, and position.
linktitle: Introduction to Permutation & Combination
summary: This is a basic introduction to Permutation & Combination.
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2020-10-12T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  permutation-and-combination:
    name: Overview
    weight: 1
---

## Fundamental Principles Of Counting 

Permutation and Combination are basically methods that enable us to count faster. 

They are based on two counting principles: 
* Fundamental Principle Of Multiplication
* Fundamental Principle Of Addition

### Fundamental Principle Of Multiplication

Fundamental Principle Of Multiplication - If there are two jobs such that one of them can be completed in m ways and when it has been completed (in any of the m ways), second job can be completed in n ways; then the two jobs can be completed in m × n ways.
<img src="../../../media/p-and-c/principal-of-multiplication.png" alt="permutation and combination" style="width:81%;height:81%;">
Notice that the completion of the second job is dependent on the completion of the first job. <br>
The keyword is ***AND*** – We need to finish the first job AND the second job after that.

{{% alert note %}}
Fundamental principle of multiplication is used in Permutation, as well as Combination.
{{% /alert %}}

##### Q. There are 2 roads connecting cities A and B and 3 roads connecting cities B and C. In how many ways can one travel from city A to C?
<pre>(a)  8        (b) 6        (c) 12        (d) 14 </pre>
<img src="../../../media/p-and-c/principal-of-multiplication1.png" alt="permutation and combination" style="width:81%;height:81%;">

Explanation:<br>
<div class="Exp">

The person needs to travel to city B ***AND*** then city C

Number of ways to go from city A to city B = 2 <br>
Number of ways to go from city B to city C = 3

So, total number of ways in which one can go from city A to city C = 2 × 3 = 6 ways <br>
Answer: (b)
</div> <br>


##### Q. A teacher has to select 1 boy and 1 girl out of 5 boys and 6 girls. In how many ways can this be done?
<pre>(a)  30        (b) 36        (c) 28        (d) 29 </pre>

Explanation:<br>
<div class="Exp">

The teacher has to select 1 boy ***AND*** 1 girl.

Number of ways to select 1 boy = 5 <br>
Number of ways to select 1 girl = 6

So, total number of ways in which the required selection can be made = 5 × 6 = 30 ways <br>
Answer: (a)
</div> <br>


### Fundamental Principle Of Addition

Fundamental Principle Of Addition - If there are two jobs such that they can be performed independently in m and n ways respectively, then either of the two jobs can be performed in (m + n) ways.
<img src="../../../media/p-and-c/principal-of-addition.png" alt="permutation and combination" style="width:81%;height:81%;">
Notice that the completion of each of the two jobs is independent of the completion of the other job. <br>

The keyword is ***OR*** – We need to finish the first job OR the second job.

{{% alert note %}}
Fundamental principle of addition is used in Combination.
{{% /alert %}}

##### Q. There are 2 roads connecting cities A and B and 3 roads connecting cities A and C. In how many ways can one travel from city A to city B or C?
<pre>(a)  8        (b) 10        (c) 5        (d) 7 </pre>
<img src="../../../media/p-and-c/principal-of-multiplication2.png" alt="permutation and combination" style="width:81%;height:81%;">

Explanation:<br>
<div class="Exp">

The person can go to city B ***OR*** city C

Number of ways to go from city A to city B = 2 <br>
Number of ways to go from city A to city C = 3

So, total number of ways in which one can go from city A to city B or C = 2 + 3 = 5 ways <br>
Answer: (c)
</div> <br>

##### Q. A teacher has to select 1 boy or 1 girl out of 5 boys and 6 girls. In how many ways can this be done?
<pre>(a)  30        (b) 36        (c) 10        (d) 11 </pre>

Explanation:<br>
<div class="Exp">

The teacher has to select 1 boy ***OR*** 1 girl.

Number of ways to select 1 boy = 5 <br>
Number of ways to select 1 girl = 6

So, total number of ways in which the required selection can be made = 5 + 6 = 11 ways <br>
Answer: (d)

{{% alert note %}}
Basically, the teacher has to select 1 student out of 11 students. So, this can be done in 11 ways. 
{{% /alert %}}
</div> <br>

##### Q. The figure shows the various one-way routes between the four cities A, B, C and D. How many routes are possible to travel from the city A to city C?
<img src="../../../media/p-and-c/principal-of-multiplication3.jpg" alt="permutation and combination" style="width:81%;height:81%;">
<pre>(a)  7       (b) 8        (c) 12        (d) 11 </pre>

Explanation:<br>
<div class="Exp">
Number of ways to go from A to C = Number of ways to go from A to B to C + Number of ways to go from A to D to C = 3 × 1 + 2 × 2 = 3 + 4 = 7 ways

Answer: (a)
</div> <br>

##### Q. There are 6 men and 9 women in an office. Find out:
1. In how many ways can a person be selected?
2. In how many ways can a team of one man and one woman be selected?

Explanation:<br>
<div class="Exp">
The number of ways in which a man can be selected = 6 <br>
The number of ways in which a woman can be selected = 9

So, number of ways in which a Man ***OR*** a Woman can to be selected = 6 + 9  <br>
(remember with OR we will do addition)

And number of ways in which a Man ***AND*** a Woman can be selected = 6 × 9 = 54 <br>
(remember with AND we will do multiplication) <br>
</div> <br>

<hr>

## Concept of Factorial

The notation n! or ∟n represents the product of first n natural numbers (i.e. product of all natural numbers from 1 to n). 

n! = 1 × 2 × 3 × . . . × (n – 1) × n 

n! is called ‘n factorial’.

1 ! = 1 <br>
2 ! = 1 × 2  <br>
3 ! = 1 × 2 × 3 <br>
4 ! = 1 × 2 × 3 × 4 and so on.

{{% alert note %}}
Note that, 0 ! = 1
{{% /alert %}}

### Recursive factorial formula

We can easily calculate a factorial from the previous one, i.e. if we know (n - 1)!, we can easily calculate n!.

n! = n × (n−1)!     (Recursive factorial formula)

We know that, 4 ! = 1 × 2 × 3 × 4 = 24 <br>
So, 5! = 5 × 4! = 5 × 24 = 120 <br>
6! = 6 × 5! = 6 × 120 = 720
