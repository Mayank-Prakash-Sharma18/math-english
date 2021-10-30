---
title: Compound Interest
linktitle: Compound Interest
toc: true
type: docs
date: "2021-01-15T00:00:00+01:00"
draft: false
menu:
  interest:
    parent: Interest
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

## What is Compound Interest (C.I.) ?

* Simple interest (SI) - If interest is accrued on principal.

* Compound interest (CI) - When interest is accrued on principal as well as on interest due for the principal.

***Let's consider an example:***

Mragank borrows Rs. 1,000 @ 10% Interest. <br>
So amount he has to pay back in one year = Principal + SI = 1000 + 10% of 1000 = 1000 + 100 = Rs. 1100 <br>
(interest in the first year is the same both in case of simple interest and compound interest)

In the second year: <br>
If we take the principal amount as Rs. 1000, then this means we are calculating SI. <br>
But if we take the principal amount as Rs. 1100, then this means we are calculating CI (i.e. we are compounding). <br>

With CI we find out the interest for the first period, add it in the total, and then calculate the interest for the next period, and so on (i.e. we pay interest on interest). After a year Mragank owed Rs. 100 interest, which is considered as another loan and interest is charged on it too (i.e. in CI we charge interest on interest earned last year too).  

***Consider another example:***

Rs. 2000 at 10% for 3 years

First year: SI = CI = 20% of 2000 = Rs. 200 <br>
Second year: SI = 200; CI = 200 + 10% of 200 = Rs. 220 <br>
Third year: SI = 200; CI = 200 + 10% of (200 + 220) = 200 + 42 = Rs. 242

So, total SI in 3 years = 200 + 200 + 200 = Rs. 600 <br>
Total CI in 3 years = 200 + 220 + 242 = Rs. 662 <br>

<div class="toc-mak">
<b> Let us generalize this: </b> <br><br>

Let principal P was lent at compound interest of r% p.a.

The interest earned in the first year = r% of P = $\frac{Pr}{100}$   (P is the amount at the start of the first year)

For the second year: <br><br>
Amount outstanding at start of 2nd year = P + $\frac{Pr}{100}$ = P(1 + $\frac{r}{100}$)  <br><br>
Interest earned in the second year = r% of P(1 + $\frac{r}{100}$)  <br><br>
So, Amount after 2 years = P(1 + $\frac{r}{100}$) + r% of P(1 + $\frac{r}{100}$) = P(1 + $\frac{r}{100}$) (1 + $\frac{r}{100}$) = P(1 + $\frac{r}{100})^2$ <br><br>

Similarly, Amount after 3 years = P(1 + $\frac{r}{100})^3$ and so on. 
</div>

{{% alert note %}}
Note: So, under compound interest, the amount at the end of the first year will become principal for the second year; the amount at the end of the second year will become the principal for the third year, and so on.
{{% /alert %}}


## Compound Interest (C.I.) for uniform rate

### Formula 1

So, if principal = P, rate = r% p.a. and time = n year, and interest is compounded annually, then

Amount at the end of n years = P (1 + $\frac{r}{100})^n$

{{% alert note %}}
Note: This formula is nothing but that of a successive increase of r%. So, Compound Interest is nothing but a case of successive percentage increases. 
{{% /alert %}}

Compound interest = Amount – Principal = = P [(1 + $\frac{r}{100})^n$ − 1]

##### Q. A sum of Rs. 6000 was borrowed at a rate of 5% per annum compounded annually. What will be the amount to be paid after 2 years? 

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

Amount at the end of n years = P (1 + $\frac{r}{100})^n$ = 6000(1 + $\frac{5}{100})^2$ = 6000 ($\frac{21}{20})^2$ = Rs. 6615 

</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Percentage Method<br><br>

CI for first year = 5% of 6000 = Rs. 300

CI for second year = 5% of (Principal + Interest earned in the first year) = 5% of (6000 + 300) = Rs. 315

So, total CI earned in two years = 300 + 315 = Rs. 615

Hence, amount to be paid after 2 years = Principal + Total CI = 6000 + 615 = Rs. 6615
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Percentage Method<br><br>

CI = 5%

Effective interest for two years = 5 + 5 + (5×5)/100 = 10 + 0.25 = 10.25%

So, Amount = 6000 + 10.25% of 6000 = 6000 + 615 = Rs. 6615
</div><br>


### Formula 2

If interest is compounded annually but time is given in fraction (suppose time = n $\frac{a}{b}$ years), then

Amount = P (1 + $\frac{r}{100})^n$ × (1 + $ \frac{ (\frac{a}{b}) r}{100}$)

##### Q. A loan of Rs. 10000 was give at a rate of 10% compounded annually. What will be the amount after 2 $\frac{2}{5}$ years?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Method <br><br>

Amount = P (1 + $\frac{r}{100})^n$ × (1 + $ \frac{ (\frac{a}{b}) r}{100}$)

= Amount = 10000 (1 + $\frac{10}{100})^2$ × (1 + $ \frac{ (\frac{2}{5}) 10}{100}$)

= 10000 ($\frac{11}{10})^2$ × (1 + $\frac{4}{100}$) = 100 × $11^2$ × ($\frac{26}{25}$) = Rs. 12,584
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Percentage Method  <br><br>

CI for first year = 10% of 10000 = Rs. 1000

CI for second year = 10% of (Principal + Interest earned in the first year) = 10% of (10000 + 1000) = Rs. 1100

CI for next 2/5 years = 10% of (Principal + Interest earned in the first two years) × 2/5 = 10% of (10000 + 2100) × (2/5) = Rs. 1210 × (2/5) = Rs. 484

So, total CI earned in 2$\frac{2}{5}$ years = 1000 + 1100 + 484 = Rs. 2584

Hence, amount to be paid after 2 years = Principal + Total CI = 10000 + 2584 = Rs. 12584
</div><br>

<br><hr>

## Compounding Periods (at uniform rate)

Apart from being calculated per year, Compound Interest could also be calculated per month, per day, etc. If it is so, then the question will state that explicitly. 

<div class="toc-mak">
<b>Non-Annual Compounding : </b> <br><br>

If interest is compounded n times per year, then Rate = $\frac{r}{n}$ and Time = nt

Amount = P (1 + $\frac{r}{𝑛×100})^{n𝑡}$
</div>

Let us try to understand this formula using various approaches.

### Approach Number 1

If interest is compounded half-yearly, then Rate = $\frac{r}{2}$ and Time = 2n
 
Amount = P (1 + $\frac{r}{2×100})^{2n}$  

If interest is compounded quarterly, then Rate = $\frac{r}{4}$  and Time = 4n	

Amount = P (1 + $\frac{r}{4×100})^{4n}$  

### Approach Number 2

We can also write the above formula as:

Amount at the end of n years = P (1 + $\frac{r}{100})^{n𝑡}$, where

* r - rate of interest per period <br>
The period will be a year if there is annual compounding, 6 months if semi-annual compounding or 1 month if monthly compounding and so on.

* n - the number of time periods.

For example: <br>
If compounding happens every quarter and money is invested at 8% p.a. for 3 years, then <br>
* r = 8/4 = 2% per quarter and  <br>
* n = 3 × 4 = 12 quarters.  <br>
(these are the values of r and n that we will use in the CI formula) <br>

Compare the following two cases of money compounded monthly:

* Case 1: If a loan is taken for 12 months at a rate of 2% per month, then r = 2% and n = 12 (12 time-periods of one month each)

* Case 2: If a loan is taken for 12 months at a rate of 24% interest with monthly compounding, then r = 24/12 = 2% and n = 12 (12 time-periods of one month each)

{{% alert note %}}
Note: higher the frequency of compounding, the faster the money grows. 
{{% /alert %}}

### Approach Number 3

If we do not want to use the formula, then we can find the effective rate of interest and then find out the final amount or interest made.

For example:

If rate is 20% per annum, compounded half-yearly, then half-yearly rate, r = 20/2 = 10%

Now, we can either use this in the CI formula  or find the effective rate of annual interest.

Effective rate of annual interest, R = r + r + $\frac{r^2}{100}$ = 10 + 10 + $\frac{10^2}{100}$ = 21%

Amount = Principal + R% of Principal

Choose the method that involves easier calculation.  

##### Q. How much will Rs. 15,000 amount to in 2 years at 8% per annum, if the interest is compounded every 6 months? 

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

If interest is compounded half-yearly, then Rate = $\frac{r}{2}$ and Time = 2n
 
Amount = P (1 + $\frac{r}{2×100})^{2𝑛}$ = 15000(1 + $\frac{8}{2×100})^{2×2}$

= 15000(1 + $\frac{1}{25})^4$ = 15000($\frac{26}{25})^4$

= Rs. 17,548 (approx)

</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Percentage  Method  <br><br>

If interest is compounded half-yearly, then half-yearly rate = 8/2 = 4% <br>
Effective rate of annual interest for 1 year = x + y + $\frac{xy}{100}$ = 4 + 4 + 16/100 = 8.16% <br>
Effective rate of annual interest for 2 years = x + y + $\frac{xy}{100}$ = 8.16 + 8.16 + (8.16)(8.16)/100 = 16.99% (i.e. around 17%) <br>

So, Amount = P + 17% of P = 15000 + 17% of 15000 = 15000 + 2550 = Rs. 17,550 (approx)
</div><br>

##### Q. An amount is lent at 50% compound interest per annum, compounded half yearly. After how many years (approximately) would the amount payable be twice the principal?
<pre>(a) 3   (b) 4    (c) 2.5   (d) 1.5</pre>

Explanations :<br>
<button class="mak-tablink tablink-group6 default-tab" onclick="openTab('6Exp-1', this, 'tablink-group6', 'tabcontent-group6')">1</button>
<button class="mak-tablink tablink-group6" onclick="openTab('6Exp-2', this, 'tablink-group6', 'tabcontent-group6')">2</button>

<div id="6Exp-1" class="Exp-1 mak-tabcontent tabcontent-group6">
Explanation 1: Formula Method <br><br>

Let the number of years be n.

Amount payable, 2P = P $[1 + (50/200)]^{2n}$ <br>
or $[1 + 0.25]^{2n}$ = 2 <br>
or $(1.25)^{2n}$ = 2

The approximate value of 2n that satisfies the above equation is 3. <br>
Hence, n = 3/2 = 1.5 years

{{% alert note %}}
50% compound interest per annum, compounded half yearly ≡ 25% compound interest per 6 months
{{% /alert %}}
</div>

<div id="6Exp-2" class="Exp-2 mak-tabcontent tabcontent-group6">
Explanation 2: Using the Options  <br><br>

Let us assume that simple interest is payable. Even under S.I. at the rate of 50%, the amount will double in 2 years. 

Hence, it is obvious that if compound interest is applied, the amount will double sooner. Only 1.5 years fits the bill among the given options.
</div><br>

<br><hr>

## Compound Interest (C.I.) for varying rates 

If rates of interest are $r_1$%, $r_2$% and $r_3$% for $1^{st}$, $2^{nd}$ and $3^{rd}$ year respectively, then

Amount = P (1 + $\frac{r_1}{100}$) (1 + $\frac{r_2}{100}$) (1 + $\frac{r_3}{100}$)

##### Q. A sum of Rs. 5000 was given on loan for 3 years. If the rate charged foe first, second and third years were 4%, 10% and 5% respectively, then what must be the final amount?

Explanation: Formula Method<br>
<div class="Exp">
Amount = P (1 + $\frac{r_1}{100}$) (1 + $\frac{r_2}{100}$) (1 + $\frac{r_3}{100}$) <br><br>
= 5000 (1 + $\frac{4}{100}$) (1 + $\frac{10}{100}$) (1 + $\frac{5}{100}$) <br><br>
= 5000 ($\frac{26}{25}$) ($\frac{11}{10}$) ($\frac{21}{20}$) = Rs. 6006
</div> <br>

<br><hr>

## Money becomes n times (in case of CI)

### Formula 1

<div class="toc-mak"> <br>
A certain sum of money becomes ‘k’ times in n years. <br> <br>

The rate of compound interest, r = 100 [($\frac{A}{P})^{\frac{1}{n}}$ – 1] = 100($k^\frac{1}{n}$ – 1)
</div>

We can also reframe this formula as follows:

If certain sum of money amounts to  ‘$A_1$’ in $n_1$ years and to ‘$A_2$’ in $n_2$ years. 

Then, k = $A_2$ / $A_1$  and time, n = ($n_2$ - $n_1$) years

The rate of compound interest, r = 100 [($\frac{A_2}{A_1})^{\frac{1}{(n_2 - n_1)}}$ – 1]

#### Shortcut Method:

The number of years taken for an amount to double at CI @ r% p.a. is

* 72/r years. (we will  get approximate answer)

* (69/r) + 0.35 (this will give even more accurate answer)

{{% alert note %}}
Note: The exact answer will be greater than these approximations. The error in the answer increases drastically if r < 5%
{{% /alert %}}

##### Q. A sum of money becomes 8 times of itself in 3 years, compounded annually. Find the rate of interest.  

Explanations :<br>
<button class="mak-tablink tablink-group4 default-tab" onclick="openTab('4Exp-1', this, 'tablink-group4', 'tabcontent-group4')">1</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-2', this, 'tablink-group4', 'tabcontent-group4')">2</button>

<div id="4Exp-1" class="Exp-1 mak-tabcontent tabcontent-group4">
Explanation 1: Formula Method <br><br>

Amount = P (1 + $\frac{r}{100})^n$ <br><br>
Or 8P = P (1 + $\frac{r}{100})^3$ <br><br>
Or (1 + $\frac{r}{100})^3$ = 8 <br><br>
Or (1 + $\frac{r}{100}$) = 2 <br><br>
Or $\frac{r}{100}$ = 1 <br><br>
Or r = 100%
</div>

<div id="4Exp-2" class="Exp-2 mak-tabcontent tabcontent-group4">
Explanation 2: Formula Method  <br><br>

A certain sum of money becomes ‘k’ times in n years. 

The rate of compound interest, r =  100 ($k^\frac{1}{n}$ – 1) = 100 ($8^\frac{1}{3}$ – 1) = 100 (2 - 1) = 100%
</div><br>

##### Q. What are the least number of years in which a sum of money will become 1.21 times itself at a compound rate of 10%? 

Explanation: Formula Method<br>
<div class="Exp">
Amount = P (1 + $\frac{r}{100})^n$ <br><br>
Or 1.21 P = P (1 + $\frac{10}{100})^n$ <br><br>
Or ($\frac{11}{10})^n$ = 1.21 <br><br>
Or $(1.1)^n$ = 1.21 <br><br>
So, n = 2 years
</div> <br>

##### Q. What are the least number of years in which a sum of money will become 2 times itself at a compound rate of 10%? 

Explanation: Short Trick Method<br>
<div class="Exp">
The number of years taken for an amount to double at CI @ r% p.a. = 72/r = 72/10 = 7.2 years

OR

The number of years taken for an amount to double at CI @ r% p.a. = (69/r) + 0.35 = (69/10) + 0.35 = 6.9 + 0.35 = 7.25 years
</div> <br>

### Formula 2

If a certain sum at compound interest becomes $k_1$ times in $n_1$ years and $k_2$ times in $n_2$ years, then

$k_1^{\frac{1}{n_1}}$ = $k_2^{\frac{1}{n_2}}$

Or $k_1^{n_2}$ = $k_2^{n_1}$

If a certain sum becomes k times in n years at compound interest, then the same sum becomes $k^m$ times in mn years.

For example, if a sum becomes 2 times in 3 years, then the same sum will become $2^4$ (=16) times in 4×3 = 12 years

##### Q. A certain sum triples in 3 years under compound interest. In how many years will the sum become 9 times at the same rate of interest?  

Explanations :<br>
<button class="mak-tablink tablink-group5 default-tab" onclick="openTab('5Exp-1', this, 'tablink-group5', 'tabcontent-group5')">1</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-2', this, 'tablink-group5', 'tabcontent-group5')">2</button>
<button class="mak-tablink tablink-group5" onclick="openTab('5Exp-3', this, 'tablink-group5', 'tabcontent-group5')">3</button>

<div id="5Exp-1" class="Exp-1 mak-tabcontent tabcontent-group5">
Explanation 1: Traditional Method <br><br>

Amount = P (1 + $\frac{r}{100})^n$ <br><br>
Or 3 P = P (1 + $\frac{r}{100})^3$ <br><br>
Or (1 + $\frac{r}{100})^3$ = 3  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   ... (equation i)<br><br>

Now, 9 P = P (1 + $\frac{r}{100})^n$ <br><br>
Or (1 + $\frac{r}{100})^n$ = 9 <br><br>
Or (1 + $\frac{r}{100})^n$ = $3^2$ <br><br>
Or (1 + $\frac{r}{100})^n$ = (1 + $\frac{r}{100})^6$   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;    ... (from equation i)<br><br>
So, n = 6 years
</div>

<div id="5Exp-2" class="Exp-2 mak-tabcontent tabcontent-group5">
Explanation 2: Formula Method  <br><br>

$k_1^{n_2}$ = $k_2^{n_1}$ <br>
or $3^{n}$ = $9^{3}$ <br>
or $3^{n}$ = $3^{6}$ <br>
Or n = 6 years <br>
</div>

<div id="5Exp-3" class="Exp-3 mak-tabcontent tabcontent-group5">
Explanation 3: Common Sense Method  <br><br>

An amount triples in 3 years.

So, in another 3 years it will triple again, i.e. it will become 3 × 3 = 9 times

So, time taken for the amount to become 9 times = 3 + 3 = 6 years
</div><br>
