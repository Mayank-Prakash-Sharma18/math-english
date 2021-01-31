---
title: Miscellaneous Formulae (Simple Interest)
linktitle: Miscellaneous Formulae (SI)
toc: true
type: docs
date: "2021-01-05T00:00:00+01:00"
draft: false
menu:
  interest:
    parent: Interest
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

## Formula 1

If a person deposits a sum of Rs. $P_1$ at $r_1$% p.a. and sum of Rs. $P_2$ at $r_2$% p.a., then 

the effective rate of interest for whole sum, r = $\frac{P_1 \hspace{1ex} r_1 \hspace{1ex} + \hspace{1ex} P_2 \hspace{1ex} r_2}{P_1 \hspace{1ex} + \hspace{1ex} P_2}$

{{% alert note %}}
Note: This formula is nothing but the weighted average of the two rate of interests. 
{{% /alert %}}

##### Q. If a person deposits a sum of Rs. 5000 at 4% p.a. and sum of Rs. 2000 at 11% p.a., then what must be the effective rate of interest for whole sum?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method / Weighted Average Method <br><br>

If a person deposits a sum of Rs. $P_1$ at $r_1$% p.a. and sum of Rs. $P_2$ at $r_2$% p.a., then 

the effective rate of interest for whole sum, r = $\frac{P_1 \hspace{1ex} r_1 \hspace{1ex} + \hspace{1ex} P_2 \hspace{1ex} r_2}{P_1 \hspace{1ex} + \hspace{1ex} P_2}$ = {(5000 × 4 + 2000 × 11)/ (5000 + 2000)} = 42000/7000 = 6%
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Basic SI Formula Method<br><br>

Let the term for which the amounts were invested be 1 year.

Total simple interest = $\frac{(5000 × 4 × 1)}{100}$ + $\frac{(2000 × 11 × 1)}{100}$   (using the formula SI = $\frac{Prn}{100}$) 

= 200 + 220 = Rs. 420

So, SI = Rs, 420, P = 5000 + 2000 = Rs. 7000, n = 1 year

Hence, r = $\frac{(SI × 100)}{Pn}$ = $\frac{(420 ×100)}{7000 × 1}$ = 6%
</div><br>

## Formula 2

A certain sum P is lent out for n years. If it amounts to $A_1$ at simple interest of $r_1$% per annum and to $A_2$ at simple interest of $r_2$% per annum, then

P = $\frac{(A_2 \hspace{1ex} r_1 - A_1 \hspace{1ex} r_2)}{(r_1 - r_2)}$

n = $\frac{(A_1 - A_2)}{(A_2 \hspace{1ex} r_1 - A_1 \hspace{1ex} r_2)}$ × 100

##### Q. A certain sum of money P, is invested for T years. We know that if it is invested at a rate of 8% per annum, it will amount to Rs. 1200. And if it is invested at a rate of 6% per annum, it will amount to Rs. 1000. Find the values of P and T. 

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Method <br><br>

P = $\frac{(A_2 \hspace{1ex} r_1 - A_1 \hspace{1ex} r_2)}{(r_1 - r_2)}$

= (1000 × 8 – 1200 × 6) / (8 - 6) = (8000 - 7200)/2 = 800/2 = Rs. 400

n = $\frac{(A_1 - A_2)}{(A_2 \hspace{1ex} r_1 - A_1 \hspace{1ex} r_2)}$ × 100

= [(1200 - 1000) / (1000 × 8 – 1200 × 6) ] × 100 = [200 / 800] × 100 = 25 years
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Basic SI Formula Method  <br><br>

Simple interest @ 8% for T years = Amount – Principal = 1200 – P <br>
Simple interest @ 6% for T years = Amount – Principal = 1000 – P

As T and P are constant, so SI ∝ r. <br>
So, (1200 – P) / (1000 – P) = 8/6 <br>
Or 3 (1200 – P) = 4 (1000 – P)  <br>
Or 3600 – 3P = 4000 – 4P <br>
Or P = Rs. 400 <br>

So, T = $\frac{(SI ×100)}{P𝑟}$ = ((1200 − P) × 100)/(400 × 8)) = ((1200 − 400) × 100)/(400 × 8) = 25 years
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3: Short Trick Method  <br><br>

Amount @ 8% = Rs. 1200 <br>
Amount @ 6% = Rs. 1000 

P and T are constant.  <br>
So, SI @ 2% = Amount @ 8% - Amount @ 6% = 1200 – 1000 = Rs. 200 <br>
So, SI @ 8% = 200 × 4 = Rs. 800

So, Principal (P) = Amount – SI = 1200 – 800 = Rs. 400 <br>
And so, T = $\frac{(SI ×100)}{P𝑟}$ = (800 × 100)/(400 × 8) = 25 years
</div><br>


## Formula 3

A sum of money P, is lent out in n parts in such a way that the interest on first part at $r_1$% for $n_1$ years, the interest on second part at $r_2$% for $n_2$ years and the interest on third part at $r_3$% for $n_3$ years and so on, are equal, then the ratio in which the sum was divided in k parts is given by

$\frac{1}{r_1 n_1}$ : $\frac{1}{r_2 n_2}$ : $\frac{1}{r_3 n_3}$ : .......... : $\frac{1}{r_n n_n}$


{{% alert note %}}
Calculation Tip: If ratio is in fraction, then to simplify it we can:

Take LCM: 
(1/a) : (1/b) : (1/c) – multiply all fractions with LCM of a, b and c

E.g. (1/3) : (1/4) <br>
LCM of 3 and 4 = 12 <br>
Now, multiply it with both the fractions. <br>
So, new ratio will be: (12/3) : (12/4) = 4 : 3

But if the numbers involved are large then we can preferably do this: <br>
(1/a) : (1/b) : (1/c) = (bc/abc) : (ac/abc) : (ab/abc) = bc : ac : ab
{{% /alert %}}

##### Q. A moneylender distributes Rs. 2300 among three farmers, Anand, Botham and Chaman at 4%, 5% and 10% respectively for 5, 5 and 4 years respectively. If he earns the same interest from them, then what must have been the amount he lent to Anand?  

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

Let the principal amount lent to Anand, Botham and Chaman be a, b and c respectively. 

Simple interest on a at 4% for 5 years = Simple interest on b at 5% for 5 years = Simple interest on c at 10% for 4 years <br>
Or $\frac{a(4)(5)}{100}$ = $\frac{b(5)(5)}{100}$ = $\frac{c(10)(4)}{100}$   (we know that Simple Interest = $\frac{Prn}{100}$) <br>
Or a/5 = b/4 = 2c/5 <br>
Or b = 4a/5 and c = a/2

We know that, a + b + c = 2300 <br>
Or a + 4a/5 + a/2 = 2300 <br>
Or 10a + 8a + 5a = 23000 <br>
Or a = Rs. 23000/23 = Rs. 1000
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Formula Method  <br><br>

The ratio in which the sum was divided in 3 parts = $\frac{1}{r_1 n_1}$ : $\frac{1}{r_2 n_2}$ : $\frac{1}{r_3 n_3}$ = $\frac{1}{(4)(5)}$ : $\frac{1}{(5)(5)}$ : $\frac{1}{(10)(4)}$ = $\frac{1}{4}$ : $\frac{1}{5}$ : $\frac{1}{8}$ = 10 : 8 : 5 

We know that, total amount lent is Rs. 2300 <br>
Or 10x + 8x + 5x = 2300 <br>
Or x = 2300/23 = 100

So, amount he lent to Anand = 10x = 10 × 100 = Rs. 1000
</div><br>

## Formula 4

A sum of money P, is lent out in n parts in such a way that the final amount received on first part at $r_1$% for $n_1$ years, the amount on second part at $r_2$% for $n_2$ years and the amount on third part at $r_3$% for $n_3$ years and so on, are equal, then the ratio in which the sum was divided in k parts is given by

$\frac{1}{100 + r_1 n_1}$ : $\frac{1}{100 + r_2 n_2}$ : $\frac{1}{100 + r_3 n_3}$ : .......... : $\frac{1}{100 + r_n n_n}$

##### Q. A moneylender distributes Rs. 25300 among three students, Andrew, Binny and Cheemu at 4%, 5% and 10% respectively for 5, 6 and 4 years respectively. If the amount he receives from all the investments are equal, then what must have been the amount he lent to Anand? 

Explanation: Formula Method<br>
<div class="Exp">
The ratio in which the sum was divided in 3 parts = $\frac{1}{100 + r_1 n_1}$ : $\frac{1}{100 + r_2 n_2}$ : $\frac{1}{100 + r_3 n_3}$ = $\frac{1}{100 + (4)(5)}$ : $\frac{1}{100 + (5)(6)}$ : $\frac{1}{100 + (10)(4)}$ 

= $\frac{1}{120}$ : $\frac{1}{130}$ : $\frac{1}{140}$ = 13 × 14 : 12 × 14 : 12 × 13 = 91 : 84 : 78

Now, 91 + 84 + 78 = 253

So, amount he lent to Anand = (91/253) × 25300 = Rs. 9100
</div> <br>