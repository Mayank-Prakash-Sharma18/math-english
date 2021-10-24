---
title: Problems based on the concept of Permutation
linktitle: Permutation 
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  permutation-and-combination:
    parent: P & C
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

In this article, we will have a look at the various problems that are formulated on the concept on ***Permutation***. 

Compare this with the previous article on Combination, to further enhance your knowledge regarding the differences between these two closely related concepts. 

## n distinct items

### Arranging all items

Number of ways to arrange all n distinct items = $P^n_n$ = n!

##### Q. In how many ways can 9 persons be arranged in a row?

Explanation:<br>
<div class="Exp">
Obviously all the 9 persons are distinct. <br>
So, Number of possible ways = $P^9_9$ = 9!
</div> <br>

#### Cases of Subgroups

In some cases n distinct items are provided, but there are subgroups within the larger group.

Let's see some examples:

##### Q. In how many ways can we arrange the letters of the word ‘BHUTAN’, in such a way that the vowels always come together?

Explanation:<br>
<div class="Exp">
All the 6 letters in the word ‘BHUTAN’ are distinct. <br>
As vowels are always together, we will consider the two vowels UA as one letter. <br>
So, we basically have to arrange these 5 letters – B, H, T, N, (UA) <br><br>
Number of possible ways to arrange these 5 distinct letters = 5! = 120 ways <br>
Moreover, the number of ways in which the vowels (UA) may be arranged = 2! = 2 <br><br>
So, total possible ways = 120 × 2 = 240 ways
</div> <br>

### Arranging r items out of n (without repetition)

Number of ways to select and arrange r items from n distinct items (Repetition is not allowed) = $P^n_r$

Solutions are of the type: n × (n - 1) × (n - 2) ... × (n - m)

{{% alert note %}}
Here we make use of boxes to visualize the situation.

The first box can be filled up in n ways. <br>
The second box can be filled up again in n-1 ways (because repetition is not allowed) <br>
The third box can be filled in n-2 ways and so on.

So, the $r^{th}$ box can be filled in n-(r-1) or n-r+1 ways. 

So, number of ways of filling all the r boxes (i.e. 1st box AND 2nd box AND …. AND rth box) = n × (n-1) × (n-2) × (n-3) ... (n-r+1) times = $\frac{n!}{(n-r)!}$ = $P^n_r$
{{% /alert %}}

##### Q. How many three digit numbers can be made using the digits 1, 2, 3, 4 and 5, without repeating any digit?
Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using formula Method <br><br>
All the 5 digits are distinct. <br><br>
Number of ways to select and arrange r items from n distinct items (Repetition is not allowed) = $P^n_r$ = $P^5_3$ = 5 × 4 × 3 =  60
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using diagram Method<br><br>
All the 5 digits are distinct. <br><br>
The 1st digit of the number can be any of the given 5 digits. So, number of ways = 5 <br>
The 2nd digit of the number can be any of the remaining 4 digits (as repetition of digits is not allowed). So, number of ways = 4 <br>
Similarly, 3rd digit of the number can be any of the remaining 3 digits (as repetition of digits is not allowed). So, number of ways = 3 <br><br>

<table>
  <tr>
    <th>Digit 1</th>
    <th>Digit 2</th>
    <th>Digit 3</th>
  </tr>
  <tr>
    <td>5 possible ways</td>
    <td>4 possible ways</td>
    <td>3 possible ways</td>
  </tr>
</table>

Hence, number of ways of formulating such a number (i.e. ways to choose 1st digit AND 2nd digit AND 3rd digit) = 5 × 4 × 3 =  60 <br>
(Remember with ‘AND’ we use multiplication)
</div>

### Arranging r items out of n (repetition allowed)

The number of permutations (i.e. ways of arranging) of n things, taking r at a time (wherein each item may be repeated once, twice, .... up to r times) = $n^r$

{{% alert note %}}
Here also we make use of boxes to visualize the situation.

The first box can be filled up in n ways. <br>
The second box can also be filled up again in n ways (because repetition is allowed) <br>
The third box can also be filled in n ways and so on. <br>
So, the $r^{th}$ box can be filled in n ways too. 

So, number of ways of filling all the r boxes (i.e. 1st box AND 2nd box AND …. AND rth box) = n × n × n × n ... r times = $n^r$
{{% /alert %}}

##### Q. In how many ways can 3 different balls be distributed among 4 different boxes, wherein any box can have any number of balls?
Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Using formula Method <br><br>
The number of permutations (i.e. ways of arranging) of n things, taking r at a time (wherein each item may be repeated once, twice, .... up to r times) = $n^r$ = $4^3$ = 64
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Using diagram Method  <br><br>

All the balls and boxes are distinct.

The 1st ball can be placed in any of the given 4 boxes. So, number of ways = 4 <br>
The 2nd ball can also be placed in any of the given 4 boxes (as repetition is allowed). So, number of ways = 4  <br>
Similarly, 3rd ball can also be placed in any of the given 4 boxes. So, number of ways = 4

<table>
  <tr>
    <th>Box 1</th>
    <th>Box 2</th>
    <th>Box 3</th>
    <th>Box 4</th>
  </tr>
</table>

Hence, number of ways of putting all the balls in boxes (i.e. possible placement options for 1st ball AND 2nd ball AND 3rd ball) = 4 × 4 × 4 = $4^3$ = 64 <br>
(Remember with ‘AND’ we use multiplication)
</div><br>

{{% alert warning %}}
A Caveat: <br>
The number of permutations (i.e. ways of arranging) of 3 balls in 4 boxes = $4^3$ and not $3^4$

Correct way of thinking: Each ball can be placed in how many boxes. <br>
Incorrect way of thinking: Each box can have how many balls. 

Let’s see why this is incorrect.

1st box can contain any of the 3 balls. <br>
2nd box can contain any of the 3 balls. <br>
3rd box can contain any of the 3 balls. <br>
4th box can contain any of the 3 balls. <br>
So, number of ways = $3^4$ = 81  (But correct answer is $4^3$ = 64)

Here we have counted some impossible cases too. E.g. if the first box has all the 3 balls, then the other boxes cannot have any ball. 
{{% /alert %}}

<br><hr><br>

## n items - some or all identical

Now, let us study the Permutation of n items, wherein some or all are identical.

### All items identical

Number of ways to arrange all n identical items = 1

(If all the items are identical, then there can be only one way in which all these items can be arranged. That is, no matter how you arrange them, the pattern will look the same.)

### Some items identical

Number of ways to arrange all n items, wherein p are of one kind and q are of other kind (and rest all are distinct) = $\frac{n!}{(p! q!)}$

Here, ‘of one kind’ implies identical items

(same pattern will continue if there are more groups of identical items)

##### Q. In how many ways can we arrange the letters of the word ‘INDIA’?
Explanation:<br>
<div class="Exp">
The word ‘INDIA’ contains 5 letters – 3 distinct (N, D, A) and 2 of the same kind (2 Is). <br><br>
Number of ways to arrange all n items, wherein p are of one kind and q are of other kind (and rest all are distinct)  = $\frac{n!}{(p! q!)}$ = $\frac{5!}{(2!)}$ = $\frac{120}{2}$ = 60 
</div> <br><br>