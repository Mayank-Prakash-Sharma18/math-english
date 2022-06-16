---
title: Letter Series
linktitle: Letter Series
toc: true
type: docs
date: "2021-03-09T00:00:00+01:00"
draft: false
menu:
  number-and-alphabet-series:
    parent: 2. Letter Series
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

In this sub-module, we will study letter / alphabet series. But before we do so, let us first get ourselves acquainted with English alphabet. 

## Introduction to Alphabet 

Let's know our ABCD ... 

English alphabet has:

* 26 letters
* 5 vowels (A, E, I, O and U) and 21 consonants
* 13 letters in first half i.e., A to M
* 13 letters in second half i.e., N to Z

<img src="../../../media/english-introduction/letters.png" alt="Letters" style="width:36%;height:36%;">

### Position of Letters

The first thing you should do, is to memorize all the positions of the letters in the alphabet. 

Our ultimate aim should be to remember the position number of each alphabet separately. You should be able to tell the position number of any alphabet instantaneously. 

Positions of English alphabets (in forward order) have been represented in the following figure:
<img src="../../../media/series/letters-numbered.png" alt="Letters numbered" style="width:99%;height:99%;">

{{% alert note %}}
<strong>Forward order</strong> means left to right. For example, if we move from left to right, then position of A is 1 and position of Z is 26. 

<strong>Reverse order</strong> means right to left. For example, if we move from right to left, then position of Z is 1 and position of A is 26.
{{% /alert %}}

But we need to remember only the positions of alphabets in forward order because  ... 

Position of a letter in reverse order = 27 - Position of a letter in forward order 

For example, Position of B in Forward order = $2^{nd}$ <br>
So, Position of B in reverse order = 27 - Position of B in forward order = 27 - 2 = 25 

Position of A in Forward order = $1^{st}$ <br>
So, Position of A in Reverse order = 27 – 1 = $26^{th}$ 

Position of L in Forward order = $12^{th}$ <br>
So, Position of L in Reverse order = 27 – 12 = $15^{th}$ 

### Concept of Opposite Letters

Position of a letter in reverse order = 27 - Position of a letter in forward order OR <br>
Position of a letter in forward order + Position of a letter in reverse order = 27

Thus, a letter is said to opposite of other when sum of their positional values is equal to 27.

For example, A is opposite to Z, as A (1) + Z (26) = 27. <br>
Similarly, B is opposite to Y, as B (2) + Y (25) = 27  and so on...

<br><hr><br>

## What is Letter Series?

Letter series is a sequence of English alphabets that follows a certain underlying rule or some logical pattern. 

You will have to decipher the underlying rule and then find out:
* either the missing letter(s) or 
* wrong letter(s) in the series. 

Let us consider a few cases ...  


## Types of Letter Series

### Type 1: Same Addition/Subtraction Series

In such series, every next term is obtained by adding/subtracting the same number to the corresponding position of previous letter.

That is, a few letters are jumped over or skipped in alphabetical order or reverse alphabetical order.

##### Q. Find the missing letter in the following series: <br>
A, D, G, J, M, P, ?
<pre>(a) Q        (b) S          (c) V          (d) T</pre>

Explanation:<br>
<div class="Exp">

Rule: Next letter = Previous letter + 3 <br>
Or we can say that two letters are skipped between any two elements in the given series. 

Pattern: <br>
A + 3 = D <br>
D + 3 = G <br>
G + 3 = J <br>
J + 3 = M <br>
M + 3 = P <br>
P + 3 = ***S*** <br>

Answer: (b)
</div> <br>

##### Q. Find the missing letter in the following series: <br>
P, M, J, G, D, ?
<pre>(a) A        (b) B          (c) C          (d) Z</pre>

Explanation:<br>
<div class="Exp">

Rule: Next letter = Previous letter - 3 <br>
Or we can say that two letters are skipped between any two elements in the given series. 

Pattern: <br>
P - 3 = M <br>
M - 3 = J <br>
J - 3 = G <br>
G - 3 = D <br>
D - 3 = ***A*** <br>

Answer: (a)
</div> <br>

Sometimes, couple of numbers may be added/subtracted in alternate fashion.

##### Q. Find the missing letter in the following series: <br>
B, E, I, L, P, ?
<pre>(a) U        (b) R          (c) T          (d) S</pre>
<pre>(SSC Question)</pre>

Explanation:<br>
<div class="Exp">

Pattern: <br>
B + 3 = E <br>
E + 4 = I <br>
I + 3 = L <br>
L + 4 = P <br>
P + 3 = ***S*** <br>

Answer: (d)
</div> <br>


### Type 2: Increasing/Decreasing order Addition/Subtraction Series

In such series, every next term is obtained by adding/subtracting a different number to the corresponding position of previous letter.

The gap between alphabets may be in increasing or decreasing order. 

##### Q. Find the missing letter in the following series: <br>
B, C, E, H, L, ?
<pre>(a) S        (b) R          (c) Q          (d) P</pre>

Explanation:<br>
<div class="Exp">

Pattern: <br>
B + 1 = C <br>
C + 2 = E <br>
E + 3 = H <br>
H + 4 = L <br>
L + 5 = ***Q*** <br>

Answer: (c)
</div> <br>

##### Q. Find the missing letter in the following series: <br>
P, O, M, J, F, ?
<pre>(a) X   (b) A    (c) Y    (d) Cannot be determined</pre>

Explanation:<br>
<div class="Exp">

Pattern: <br>
P - 1 = O <br>
O - 2 = M <br>
M - 3 = J <br>
J - 4 = F <br>
F - 5 = ***A*** <br>

Answer: (b)
</div> <br>

### Type 3: Mixed Addition-Subtraction Series

In such series, addition – subtraction (or subtraction – addition) takes place alternatively to obtain the terms of the series.

##### Q. Find the missing letter in the following series: <br>
A, E, C, G, E, I, ?
<pre>(a) G        (b) J          (c) H          (d) L</pre>

Explanation:<br>
<div class="Exp">

Pattern: <br>
A + 4 = E <br>
E - 2 = C <br>
C + 4 = G <br>
G - 2 = E <br>
E + 4 = I <br>
I - 2 = ***G*** <br>

Answer: (a)
</div> <br>

### Type 4: Combination of 2 or more Series

Such series have two or more interwoven series. 

Let’s see some examples… 

##### Q. Find the missing letter in the following series: <br>
C, V, D, W, E, X, F, Y, G, Z, ?
<pre>(a) K        (b) D          (c) H          (d) G</pre>

Explanation:<br>
<div class="Exp">

There are two separate number series in the given series:

* Series made by odd-position elements: C, D, E, F, G, ? (difference of +1 between elements)
* Series made by even-position elements: V, W, X, Y, Z (difference of +1 between elements)

Hence, the missing number belongs to the series made by odd-position elements.

<img src="../../../media/series/combined-letter-series.png" alt="combined letter series" style="width:99%;height:99%;">

So, missing letter = G + 1 = H

Answer: (c)
</div> <br>

##### Q. Find the missing letters in the following series: <br>
KKMLLNMMONNPOOQP??
<pre>(a) RR        (b) RS          (c) PR          (d) ST</pre>
<pre>(SSC Question)</pre>

Explanation:<br>
<div class="Exp">

There are two separate number series in the given series:

<img src="../../../media/series/combined-letter-series1.png" alt="combined letter series" style="width:99%;height:99%;">

So, missing letters are P and R. 

Answer: (c)
</div> <br>

### Type 5: Reverse Order or Swap Series

In such series, the first part may be written in reverse order in the second part of the series or such reversals may be present in other slightly varied forms.

##### Q. Find the missing letter in the following series: <br>
M, A, Y, A, N, K, N, A, Y, A, ?
<pre>(a) M        (b) K          (c) Y          (d) Z</pre>

Explanation:<br>
<div class="Exp">

This series is a reverse order series. The second half of the series is the mirror image of the first half (with the middle element 'K' shared by both parts). 

<img src="../../../media/series/letter-series.png" alt="reverse order letter series" style="width:99%;height:99%;">

So, missing letter must be 'M'.

Answer: (a)
</div> <br>

### Type 6: Cyclic Series

In such series the letters of the words move in a cyclic manner. 

##### Q. Find the missing letters in the following series: <br>
LDP, DPL, PLD, ?
<pre>(a) PDL        (b) LPD          (c) DLP          (d) LDP</pre>

Explanation:<br>
<div class="Exp">

This is a cyclic series as shown below: 

<img src="../../../media/series/letter-series1.png" alt="reverse order letter series" style="width:72%;height:72%;">

Every letter shifts one position to the left with each step. And the leftmost letter goes to the extreme right. 

So, missing letters must be 'LDP'.

Answer: (d)
</div> <br>

### Type 7: Frequency Series

In such series, frequency of occurrence of a letter increases/decreases in every next element.

##### Q. Find the missing letter in the following series: <br>
L, LL, LLLL, LLLLLLL, ?
<pre>(a) LLLLLLLLL  (b) LLLLLLLL  (c) LLLLLLLLLLL  (d) LLLLLLLLLL</pre>

Explanation:<br>
<div class="Exp">

Pattern: <br>
L → 1 letter <br>
LL → 2 letters (i.e. increment of 1 letter) <br>
LLLL → 4 letters (i.e. increment of 2 letters) <br>
LLLLLLL → 7 letters (i.e. increment of 3 letters) <br>
***LLLLLLLLLLL*** → 11 letters (i.e. increment of 4 letters) <br>

Answer: (c)
</div> <br>

<!-- Commented out for ebook sake -->
<!-- ### Type 8: Small and Capital Letter Series

Such series consists of small and capital letters in various patterns.

##### Q. Find the missing letter in the following series: <br>
mm, OO, qq, SS, ?
<pre>(a) vv  (b) uu  (c) tt  (d) rr</pre>

Explanation:<br>
<div class="Exp">

The pattern of the series has been represented in the diagram given below:
<img src="../../../media/series/letter-series2.png" alt="reverse order letter series" style="width:72%;height:72%;">

Answer: (b)
</div> <br> -->

<br><hr><br>

## Rule Detection

In this type of questions of alphabets, four options are given as the group of letters. Out of these four groups, candidates have to choose that one which follows a certain pattern in a particular manner. 

##### Q. Number of letters skipped in between adjacent letters in the series is two. Which of the following series observes this rule? <br>
<pre>(a) MPSVYBE  (b) SVZCGJN  (c) ZCGKMPR  (d) QSVYZCF</pre>

Explanation:<br>
<div class="Exp">

The pattern of the series has been represented in the diagram given below:
<img src="../../../media/series/letter-series3.png" alt="reverse order letter series" style="width:90%;height:90%;">

Answer: (a)
</div> <br>

