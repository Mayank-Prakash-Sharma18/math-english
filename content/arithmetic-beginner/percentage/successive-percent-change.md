---
title: Successive Percent Change  
linktitle: Successive Percent Change  
toc: true
type: docs
date: "2020-10-03T00:00:00+01:00"
draft: false
menu:
  percentage:
    parent: Percentage
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

Suppose a number x undergoes a percentage change of a% and then b%, then:

Net percentage change ≠ (a + b)% 

Can you guess why?

The net percentage change is not the simple addition of the two percentage changes as the base changes after the first change.

New number after a% change = x × (1 + $\frac{a}{100}$)  <br>
This is the new base, i.e. the base changes.

So, New number after b% change = [x × (1 + $\frac{a}{100}$)] × (1 + $\frac{b}{100}$)

So, the new number after successive a% and b% changes = x × ($\frac{a}{100}$) × ($\frac{b}{100}$) = x × [1 + $\frac{𝑎 + 𝑏 + \frac{ab}{100}}{100}$]

So, net percentage change = <strong><span class="mak-text-color">𝑎 + 𝑏 + $\frac{ab}{100}$</span></strong>

Net Change is an increase or decrease according to the positive or negative sign of the final result.

If there are more than 2 successive percentage changes then we can apply net percent change formula successively in pair of two.

{{% alert note %}}
In successive percentage increase/decrease, the order of the percentages do not matter. You can apply anyone first, the answer will be the same. 

As, x × (1 + $\frac{a}{100}$) × (1 + $\frac{b}{100}$) = x × (1 + $\frac{b}{100}$) × (1 + $\frac{a}{100}$)
{{% /alert %}}

##### Q. If Mragank’s salary increases by 20% in the first year and by 10% the next year, then what will be the net percentage increase in his salary after 2 years?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-4', this, 'tablink-group1', 'tabcontent-group1')">4</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-5', this, 'tablink-group1', 'tabcontent-group1')">5</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Traditional Method <br><br>

Let Mragank’s salary be Rs x

Mragank’s salary after first year = x × (120/100) = 1.2x

Mragank’s salary after second year = 1.2x × (110/100) = 1.2x × 1.1 = 1.32x

So, Net percentage increase = [(1.32x - x)/x] × 100 = (0.32x/x) × 100 = 0.32 × 100 = 32%
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using the concept of Multiplying Factors<br><br>

First multiplying factor = 1.2<br>
Second multiplying factor = 1.1<br>
Net Multiplying Factor = 1.2 × 1.1 = 1.32<br>
So, Net percentage increase = 32%
</div><br>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Formula Approach <br><br>

Net percentage change ≠ (a + b)% 

Net percentage increase = (𝑎 + 𝑏 + $\frac{ab}{100}$)% = (20 + 10 + $\frac{20 × 10}{100}$)% = (30 + 2)% = 32%
</div>

<div id="1Exp-4" class="Exp-4 mak-tabcontent tabcontent-group1">
Explanation 4: Percentage Method<br><br>

Let the initial salary of Mragank be Rs 100

Salary after 20% increase = 100 + 20 = Rs 120<br>
Salary after further 10% increase = 120 + 12 = Rs 132<br>
So, Net percentage increase = 32%
</div><br>

<div id="1Exp-5" class="Exp-5 mak-tabcontent tabcontent-group1">
Explanation 5: Using Fractions<br><br>

20% ≡ 1/5 <br>
New salary after first year = 5 + 1 = 6 <br>
Ratio of salary after first year /original salary = 6/5

10% ≡ 1/10 <br>
New salary after second year = 10 + 1 = 11 <br>
Ratio of salary after second year / salary after first year = 11/10

Ratio of salary after second year / original salary = (11/10) × (6/5) = 33/25

So, Net percentage increase = [(33 - 25)/25] × 100 = (8/25) × 100 = 32%
</div><br>

{{% alert note %}}
Tips:

Use <strong><span class="mak-text-color">net percent change formula method</span></strong> if the percentage data given is in integers but kind of ugly, e.g. 17% increase, 19% increase (in such type of data it will be hard to use either the percentage method or fraction method)

Use <strong><span class="mak-text-color">percent method</span></strong> if the percentage data given is in integers that are beautiful, e.g. 20% increase, 15% increase (in such type of data you can also use either the formula method or fraction method, but percentage method will be the fastest)

Use <strong><span class="mak-text-color">fraction method</span></strong> if the percentage data given is in decimals (that are percentage equivalents of fractions), e.g. 16.67% increase, 12.5% increase (in such type of data it will be hard to use either the percentage method or formula method)
{{% /alert %}}

##### Q. If the price of a book is decreased by 22.22% and then increased by 50%, then what must be the net percent change in its price?

Explanation: Using Fractions<br>
<div class="Exp">
22.22% ≡ 2/9 <br>
New price = 9 - 2 = 7 <br>
Ratio of new price/original price = 7/9

50% ≡ 1/2 <br>
New price = 2 + 1 = 3 <br>
Ratio of new price/original price = 3/2

Ratio of final price / original price = (7/9) × (3/2) = 7/6 <br>
So, Net percentage increase = [(7 - 6)/6] × 100 = (1/6) × 100 = 16.67%
</div> <br>

## Special case

We sometimes encounter a special case when we use net percent change formula. 

* If a number is first increased by a% and then it is decreased by a%, then net effect is always a decrease which is equal to: <br>
a – a – $\frac{a^2}{100}$ = - $\frac{a^2}{100}$%

* The net percentage change will be the same even if a number is first decreased by a% and then it is increased by a%. <br>
-a + a – $\frac{a^2}{100}$ = - $\frac{a^2}{100}$%

So, in both the cases the answer is the same, i.e. <strong><span class="mak-text-color">- $\frac{a^2}{100}$%</span></strong>

##### Q. If price of a jute bag is increased by 20% and then decreased by 20%, then what will be the net percentage change in its price?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Formula Approach <br><br>

Net percentage increase = - $\frac{a^2}{100}$% = - $\frac{20^2}{100}$% = - $\frac{400}{100}$% = -4%
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Percentage Method  <br><br>

Let the initial price of jute bag be Rs 100 <br>
Price after 20% increase = 100 + 20 = Rs 120<br>
Price after further 20% decrease = 120 - 24 = Rs 96<br>
So, Net percentage decrease = -4%
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3: Fraction Method  <br><br>

20% increase ≡ 1/5 <br>
New price = 5 + 1 = 6 <br>
Ratio of new price/original price = 6/5

20% decrease ≡ 1/5  <br>
New price = 5 - 1 = 4 <br>
Ratio of new price/original price = 4/5

Ratio of final price / original price = (6/5) × (4/5) = 24/25 <br>
So, Net percentage decrease = [(25 - 24)/25] × 100 = (1/25) × 100 = 4%
</div><br>

<br><hr><br>

## z = x × y 

Let there be two quantities x and y that multiply to form a quantity z. We can say: <br>
z = x × y

Say x is changed by a% and y is changed by b%, then:<br>
z = x (1 + $\frac{a}{100}$) × y (1 + $\frac{b}{100}$) = x y × [1 + $\frac{𝑎 + 𝑏 + \frac{ab}{100}}{100}$
] = z × [1 + $\frac{𝑎 + 𝑏 + \frac{ab}{100}}{100}$]

So changing x and y by a% and b% respectively means that z is changed by: <br>
𝑎 + 𝑏 + $\frac{ab}{100}$.

So, the question basically reduces to:<br>
If z is successively changed by a% and then b%, then what is the net percentage change?

{{% alert note %}}
That is, changing x by a% and y by b% ≡ changing z successively by a% and b%
{{% /alert %}}

Let's see a couple of examples:

##### Q. If in a rectangle the length increases by 40% and breath decreases by 20%, then what must be the net change in area? 

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-3', this, 'tablink-group3', 'tabcontent-group3')">3</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-4', this, 'tablink-group3', 'tabcontent-group3')">4</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Formula Method <br><br>

Net percentage change = (𝑎 + 𝑏 + $\frac{ab}{100}$)% = (40 - 20 - $\frac{40 × 20}{100}$)% = (20 − 8)% = 12%

</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Using the concept of Multiplying Factors  <br><br>

First multiplying factor = 1.40 <br>
Second multiplying factor = 0.80 <br>
Net Multiplying Factor = 1.4 × 0.8 = 1.12 <br>

So, Net percentage increase = 12% 

</div>

<div id="3Exp-3" class="Exp-3 mak-tabcontent tabcontent-group3">
Explanation 3: Percentage Method  <br><br>

Let the initial area of the rectangle be 100 <br>
Area after 40% increase in length = 100 + 40 = 140 <br>
Area after further 20% decrease in breath = 140 - 28 = 112 <br>

So, Net percentage increase = 12%

</div>

<div id="3Exp-4" class="Exp-4 mak-tabcontent tabcontent-group3">
Explanation 4: Fraction Method  <br><br>

40% increase ≡ 2/5 <br>
New length = 5 + 2 = 7 <br>
Ratio of new length/original length = 7/5

20% decrease ≡ 1/5  <br>
New breath = 5 - 1 = 4 <br>
Ratio of new breath /original breath = 4/5

Ratio of final area / original area = (7/5) × (4/5) = 28/25 <br>

So, Net percentage increase = [(28 - 25)/25] × 100 = (3/25) × 100 = 12%
</div><br>

##### Q. The length and breadth of a cuboid is increased by 10% and 20% respectively, while its height is reduced by 30%. What must be the total percent increase/decrease in the volume of the cuboid?

Explanations :<br>
<button class="mak-tablink tablink-group4 default-tab" onclick="openTab('4Exp-1', this, 'tablink-group4', 'tabcontent-group4')">1</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-2', this, 'tablink-group4', 'tabcontent-group4')">2</button>
<button class="mak-tablink tablink-group4" onclick="openTab('4Exp-3', this, 'tablink-group4', 'tabcontent-group4')">3</button>

<div id="4Exp-1" class="Exp-1 mak-tabcontent tabcontent-group4">
Explanation 1: Formula Method <br><br>

Volume of cuboid = l × b × h 

As here 3 variables are involved, we will have to use the formula twice.

Net percentage increase of l & b = (𝑎 + 𝑏 + $\frac{ab}{100}$)% = (10 + 20 + $\frac{10 × 20}{100}$)% = (30+2)% = 32%

Net percentage increase of (l & b) & h = (𝑎 + 𝑏 + $\frac{ab}{100}$)% = (32 - 30 - $\frac{32 × 30}{100}$)% = (2 − 9.6)% = -7.6%

So, percent decrease in the volume of the cuboid = 7.6%
</div>

<div id="4Exp-2" class="Exp-2 mak-tabcontent tabcontent-group4">
Explanation 2: Percentage Method  <br><br>

Let initial volume be 100. <br>
After 10% increase, volume = 100 + 10% of 100 = 100 + 10 = 110 <br>
After further 20% increase, volume = 110 + 20% of 110 = 110 + 22 = 132 <br>
After further 30% decrease, volume = 132 - 30% of 132 = 132 – (3 × 13.2) = 132 – 39.6 = 92.4

So, percent decrease in the volume of the cuboid = 100 – 92.4 = 7.6%
</div>

<div id="4Exp-3" class="Exp-3 mak-tabcontent tabcontent-group4">
Explanation 3: Fraction Method  <br><br>

10% increase ≡ 1/10 <br>
20% increase ≡ 1/5  <br>
30% decrease ≡ 3/10 

Ratio of final volume / original volume = (11/10) × (6/5) × (7/10) = 462/500

So, Net percentage decrease = [(500 - 462)/500] × 100 = (38/500) × 100 = 7.6%
</div><br>

<br><hr><br>

## Successive Percent Change for three or more years

### Constant Growth Rate

If the population of a town is P and it is increased at the rate of r% per annum (i.e. growth rate is constant over the years), then

(a) Population after n years, $P_n = P (1 + \frac{r}{100})^n$

(b) Population n years ago, P = $\frac{P_n}{(1 + \frac{r}{100})^n}$   

### Variable Growth Rate

If the population of a town is P and increases at the rate of $r_1%$ in first year, $r_2%$ in second year and $r_3%$ in third year (i.e. growth rate varies over the years), then

(a) Population after 3 years, $P_3 = P (1 + \frac{r_1}{100}) (1 + \frac{r_2}{100}) (1 + \frac{r_3}{100})$

(b) Population 3 years ago, P = $\frac{P_3}{(1 + \frac{r_1}{100}) (1 + \frac{r_2}{100}) (1 + \frac{r_3}{100})}$   

<br>

If present value of a machine is P and it’s depreciation rates are $r_1%$, $r_2%$ and $r_3%$ yearly (i.e. growth rate varies over the years), then

(a) Value of machine after 3 years, $P_3 = P (1 - \frac{r_1}{100}) (1 - \frac{r_2}{100}) (1 - \frac{r_3}{100})$

(b) Value of machine 3 year ago, P = $\frac{P_3}{(1 - \frac{r_1}{100}) (1 - \frac{r_2}{100}) (1 - \frac{r_3}{100})}$   

