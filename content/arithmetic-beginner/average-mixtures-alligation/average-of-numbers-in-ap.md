---
title: Average of Numbers in an Arithmetic Progression (A.P.)
linktitle: Average of Numbers in an AP
toc: true
type: docs
date: "2021-01-29T00:00:00+01:00"
draft: false
menu:
  average-mixtures-alligation:
    parent: 1. Average
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

To find the Average of numbers in an Arithmetic Progression, we have three methods, depending on the kind of numbers provided to us.

## Method 1

In the Arithmetic Progression there are two cases:

* Series having odd number of terms
* Series having even number of terms

### Series having odd number of terms

When the number of terms is odd then the average will be the middle term.  

For example, in the sequence 5, 6, 7, 8, 9, the middle number is 7. <br>
So, mean/average of this series = 7.

##### Q. If the average of 23 consecutive odd numbers is 91, then which must be the largest of these numbers?
<pre>(a) 113   (b) 115    (c) 117   (d) 119</pre>

Explanation:<br>
<div class="Exp">

Here the odd numbers, whose average is given, are consecutive. So, they are in A.P. 

As there are odd number of items in the Arithmetic series (i.e. 23), their average must be the middle number, i.e. the 12th odd number of the given series.

Thus, 91 is the 12th number and we are supposed to find the 23rd number (which is the largest number). 

The difference between any two consecutive odd numbers is 2.

Thus, the 23rd number = 12th number + (11 × 2) = 91 + 22 = 113

Answer: (a)
</div> <br>


##### Q. The average of 15 consecutive numbers is 26. What must be the difference between the second highest and the fourth lowest number in this series? 
<pre>(a) 6         (b) 8          (c) 7         (d) 10</pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: <br><br>

Average of 15 consecutive numbers is 26. <br>
Middle term = (15 + 1)/2 = 8th term <br>
Here, middle term i.e. 8th term must be 26 and difference between each term is 1.

Hence, the numbers will be: <br>
19 20 21 22 23 24 25 26 27 28 29 30 31 32 33

2nd highest of these numbers = 32 <br>
4th lowest of these numbers = 22

Required difference = 32 – 22 = 10

Answer: (d)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Let the first number in the series be x. 

As the numbers are consecutive, the fourth lowest number must be x + 3, and the second highest number must be x + 13.

So, Required difference = (x + 13) – (x + 3) = 10
</div><br>


### Series having even number of terms

When the number of terms is even then the average will be the average of two middle terms.

For example, in the sequence 5, 6, 7, 8, the middle terms are 6 and 7. <br>
So, mean/average of the series = (6 + 7)/2 = 13/2 = 6.5

{{% alert warning %}}
Note: It will be difficult to use this method if the series is too long. Locating the middle term(s) will take some time.  
{{% /alert %}}

## Method 2

In an A. P. with the first term a and the last term l. <br>
Average of the series = (a + l)/2.

For example, in the series 5, 6, 7, 8, 9, average = (5 + 9)/2 = 7. <br>
And in the series 5, 6, 7, 8, average = (5 + 8)/2 = 6.5.

{{% alert note %}}
Note: This method can be used if the series is too long. 
{{% /alert %}}

## Method 3: For Consecutive Numbers

### General Formulae

We can use another method specifically to find average of Consecutive Natural Numbers beginning with 1.

* Average of first n consecutive natural numbers = $\frac{𝑛+1}{2}$

* Average of squares of first n consecutive natural numbers = $\frac{(n+1)(2n+1)}{6}$

* Average of the cubes of first n consecutive natural numbers =  $\frac{n(n+1)^2}{4}$

### Formulae for consecutive even numbers

* Average of first n consecutive even numbers = (n + 1) <br>
E.g. Average of 2, 4, 6, 8, 10 = (5 + 1) = 6

* Average of first n consecutive even numbers starting from 2 to x = $\frac{x + 2}{2}$  
E.g. Average of 2, 4, 6, 8, 10 = (10 + 2)/2 = 12/2 = 6

* The average of square of first n consecutive even numbers = $\frac{2(n+1)(2n+1)}{3}$

* The average of square of first n consecutive even numbers starting from 2 to x = $\frac{(x + 1) (𝑥 + 2)}{3}$

### Formulae for consecutive odd numbers

* Average of first n consecutive odd numbers = n <br>
E.g. Average of 1, 3, 5, 7, 9, 11 = 6

* The average of first n consecutive odd numbers starting from 1 to x = $\frac{x+1}{2}$ <br>
E.g. Average of 1, 3, 5, 7, 9, 11 = (11 + 1)/2 = 12/2 = 6

* The average of square of first n consecutive odd numbers starting from 1 to x = $\frac{𝑥(𝑥 + 2)}{3}$



