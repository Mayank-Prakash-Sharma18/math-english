---
title: Successive Discounts 
linktitle: Successive Discounts 
toc: true
type: docs
date: "2021-01-14T00:00:00+01:00"
draft: false
menu:
  profit-and-loss:
    parent: Profit & Loss
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

## Concept 1: Basic Formulae

If there are two discounts: <br>
If the first discount is x% and second discount is y%, then <br>
Total discount = (x + y − $\frac{xy}{100}$)%

SP = MP × (1−$\frac{x}{100}$) (1−$\frac{y}{100}$)

If there are three discounts x%, y% and z%, then: <br>
SP = MP × (1−$\frac{x}{100}$) (1−$\frac{y}{100}$) (1−$\frac{z}{100}$)

##### Q. What is the single discount equivalent to a series of discounts of 10%, 20% and 50%?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Percentage Method <br><br>

Let MP = Rs. 100

So, $SP_1$  = 100 – 10% of 100 = Rs. 90

$SP_2$ = 90 – 20% of 90 = 90 – 18 = Rs. 72

$SP_3$ = 72 – 50% of 72 = 72 – 36 = Rs. 36

So, discount percentage = [(100 – 36)/100] × 100 = 64%
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Formula Method  <br><br>

Let MP = Rs. 100

If there are three discounts x%, y% and z%, then: <br>
SP = MP × (1−$\frac{x}{100}$) (1−$\frac{y}{100}$) (1−$\frac{z}{100}$) = 100 × (90/100) × (80/100) × (50/100) = 100 × (9/10) × (4/5) × (1/2)  = Rs. 36

So, discount percentage = [(100 – 36)/100] × 100 = 64%
</div><br>


##### Q. A shopkeeper gives successive discounts of 20%, 10% and 5% on an item. What will be the selling price of the item if its cost price is Rs. 800?
(a) Rs. 523.6	<br>
(b) Rs. 547.2 <br>
(c) Rs. 576	<br>
(d) Rs. 640.5

Explanation:<br>
<div class="Exp">

Selling price after first discount = 800 - 800 × (20/100) = 800 – 160 = Rs. 640 <br>
Selling price after second discount = 640 × (90/100) = Rs. 576 <br>
Selling price after third discount = 576 × (95/100) = Rs. 547.2

Answer: (b)
</div> <br>


##### Q. A trader allows two successive discounts of 20% and 10%. If he sells the article for Rs. 108, then the marked price of the article is:
(a) Rs. 120	<br>		
(b) Rs. 135 <br>
(c) Rs. 140	<br>			
(d) Rs. 150

Explanation:<br>
<div class="Exp">

Net discount = -20 - 10 + (200/100) = 28%

SP = MP × [(100 - Discount percentage)/100] <br>
or 108 = MP × [(100 - 28)/100] <br>
or 108 = MP × (72/100) <br>
or MP = 150

{{% alert note %}}
We can also use the options and apply the two successive discounts of 20% and 10%, and then see which option gives the final value of Rs. 108. This can be done mentally, and would probably be a faster way to solve this question.  
{{% /alert %}}

Answer: (d)
</div> <br>


## Concept 2 

In case of Successive Discounts, the discount is lower if the two discount values are closer.  

Let's see how. 

We already know that, Net discount percentage = (x + y − $\frac{xy}{100}$)%

When x + y = constant, then the value of xy is the largest when x = y. The closer the values of x and y will be the higher will be the value of xy, and so lower will be the value of net discount percentage.

E.g. if x + y = 20, then maximum value of xy = 10 × 10 = 100 (i.e. when x = y = 10) <br>
So, Net discount percentage = 10 + 10 – 1 = 19% (minimum possible value)

If x = 1, and y = 19, then Net discount percentage = 1 + 19 – 0.19 = 19.81%

##### Q. To maximize his profit on his product, should a shopkeeper provide two discounts of 40% and 30% or 50% and 20%?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Percentage Method <br><br>

Let MP be Rs. 100

Case 1: <br>
After 40% discount, SP = Rs. 60 <br>
And after 30% discount, SP = Rs. 42 <br>

Case 2: <br>
After 50% discount, SP = Rs. 50 <br>
And after 20% discount, SP = Rs. 40 <br>

So, the shopkeeper should opt for discounts of 40% and 30%. This way the net discount offered by him will be less.
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Fraction Method<br><br>

Case 1: <br>
40% discount = 2/5; So, SP1/MP = 3/5 <br>
30% discount = 3/10; So, SP2/SP1 = 7/10 <br>
So, SP2/MP = (3/5) × (7/10) = 21/50 = 42/100 <br>
So, net discount = 58% <br>

Case 2: <br>
50% discount = 1/2; So, SP1/MP = 1/2 <br>
20% discount = 1/5; So, SP2/SP1 = 4/5 <br>
So, SP2/MP = (1/2) × (4/5) = 4/10 = 40/100 <br>
So, net discount = 60% <br>

So, the shopkeeper should opt for discounts of 40% and 30%. This way the net discount offered by him will be less.
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Formula Method<br><br>

Case 1: <br>
Net discount after 40% and 30% discount = (x + y − $\frac{xy}{100}$)% = (40 + 30 − $\frac{(40)(30)}{100}$)% = 70 – 12 = 58%

Case 2: <br>
Net discount after 50% and 20% discount = (x + y − $\frac{xy}{100}$)% = (50 + 20 − $\frac{(50)(20)}{100}$)% = 70 – 10 = 60%

So, the shopkeeper should opt for discounts of 40% and 30%. This way the net discount offered by him will be less.
</div><br>
