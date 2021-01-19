---
title: Successive Profit & Loss 
linktitle: Successive Profit & Loss 
toc: true
type: docs
date: "2020-11-21T00:00:00+01:00"
draft: false
menu:
  profit-and-loss:
    parent: Profit & Loss
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## Two successive  transactions

If there are two successive  transactions: 

If the first profit/loss is x% and second profit/loss is y% (use + sign for profit and – sign for loss), then <br>

Total profit/loss = x + y + $\frac{xy}{100}$%

##### Q. Mragank bought a truck and paid 30% less than the original price. Thereafter he sold it with 10% profit on the price he had paid. The selling price is how much percent less than the original price?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Traditional Method <br><br>

Let original price = Rs. 100 <br>
So, the price paid by Mragank = 100 – 30% of 100 = 100 – 30 = Rs. 70

His selling price = 70 + 10% of 70 = 70 + 7 = Rs. 77

Now, our base here is the original price, i.e. Rs. 100

Required percent = 23% decrease 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Formula Method<br><br>

First there is a decrease of 30% and then an increase of 10%. 

Required percent = −30 + 10 − $\frac{(10)(30)}{100}$ = -20 – 3 = -23%, i.e. a decrease of 23% as compared to the original price.
</div><br>

## More than two successive  transactions

If ‘A’ sold an article to B at a profit/loss of $x_1%$, B sold this article to C at a profit/loss of $x_2%$ and C sold this article to D at a profit/loss of $x_3%$, then cost price of the article for D is given by

CP (D) = CP(A) × $\frac{100±𝑥_1}{100}$ × $\frac{100±𝑥_2}{100}$ × $\frac{100±𝑥_3}{100}$

(+ve) for profit and (– ve) for loss.

##### Q. Anand sells a pencil to Bhaskar at a gain of 20%, who in turn sells it to Chetan at a loss of 10%. If Chetan pays Rs. 216 to Bhaskar, what must be the cost price of the pencil for Anand?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Traditional Method <br><br>

Let cost price for Anand = Rs. 100 <br>
So, selling price for Anand = cost price for Bhaskar = 100 + 20% of 100 = 100 + 20 = Rs. 120 <br>
Now, selling price for Bhaskar = cost price for Chetan = 120 - 10% of 120 = 120 - 12 = Rs. 108

But as per the question, cost price for Chetan = Rs. 216

So, the cost price for Anand must have been Rs. 200
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Formula Method  <br><br>

CP (C) = CP(A) × $\frac{100±𝑥_1}{100}$ × $\frac{100±𝑥_2}{100}$

or 216 = CP(A) × $\frac{100 + 20}{100}$ × $\frac{100 - 10}{100}$ = CP(A) × (6/5) × (9/10) 

Or CP(A) = 216 × (50/54) = Rs. 200
</div><br>

##### Q. Anand sells a pencil to Bhaskar at a gain of 10%, who in turn sells it to Chetan at a gain of 9.09%. If Chetan pays Rs. 60 to Bhaskar, what must be the cost price of the pencil for Anand? 

Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Traditional Method <br><br>

Let cost price for Anand = Rs. 100 <br>
So, selling price for Anand = cost price for Bhaskar = 100 + 10% of 100 = 100 + 10 = Rs. 110 <br>
Now, selling price for Bhaskar = cost price for Chetan = 110 + 9.09% of 110 = 110 + (110/11) = 110 + 10 = Rs. 120

But as per the question, cost price for Chetan = Rs. 60

So, the cost price for Anand must have been Rs. 50
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Formula Method  <br><br>

CP (C) = CP(A) × $\frac{100±𝑥_1}{100}$ × $\frac{100±𝑥_2}{100}$

Using the formula will lead to complex calculations, because of the second percentage 9.09%. 
</div><br>

