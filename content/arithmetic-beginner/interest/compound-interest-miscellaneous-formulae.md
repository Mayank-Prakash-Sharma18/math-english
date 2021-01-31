---
title: Miscellaneous Formulae (Compound Interest)
linktitle: Miscellaneous Formulae (CI)
toc: true
type: docs
date: "2021-01-29T00:00:00+01:00"
draft: false
menu:
  interest:
    parent: Interest
    weight: 15

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 15
---

## Formula 1

If a sum of money P amounts to $A_1$ after n years at CI and the same sum of money amounts to $A_2$ after (n + 1) years at CI, then

r = $\frac{(A_2 – A_1)}{A_1}$ x 100

##### Q. If a sum of money amounts to Rs. 2420 in 2 years and to Rs. 2662 in 3 years, then what was the original sum lent (assume compound interest)?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

If a sum of money P amounts to $A_1$ after n years at CI and the same sum of money amounts to $A_2$ after (n + 1) years at CI, then

r = $\frac{(A_2 – A_1)}{A_1}$ x 100 = $\frac{(2662 – 2420)}{2420}$ x 100 = $\frac{242}{2420}$ x 100 = 10%

So, P amounts to Rs. 2420 in 2 years at 10%. <br><br>
Amount = P (1 + $\frac{r}{100})^n$ <br><br>
Or 2420 = P (1 + $\frac{10}{100})^2$ <br><br>
Or P = 2420 x ($\frac{10}{11})^2$ = Rs. 2000
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Amount after 3 years - Amount after 2 years = 2662  - 2420 = Rs. 242 <br>
This difference is the interest earned on the amount of the previous year, i.e. on Rs. 2420.

So, P = Rs. 2420, SI = Rs. 242 and n = 1 year

Now, SI = Prn/100    (we can apply the SI formula, as n = 1 and for one year CI = SI) <br>
Or r = (SI x 100) / Pn = (242 x 100) / (2420 x 1) = 10%

So, P amounts to Rs. 2420 in 2 years at 10%.

Amount = P (1 + $\frac{r}{100})^n$ <br><br>
Or 2420 = P (1 + $\frac{10}{100})^2$ <br><br>
Or P = 2420 x ($\frac{10}{11})^2$ = Rs. 2000
</div><br>