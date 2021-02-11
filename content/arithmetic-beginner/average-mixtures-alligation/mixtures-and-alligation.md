---
title: Mixtures and Alligation
linktitle: Mixtures & Alligation
toc: true
type: docs
date: "2021-01-29T00:00:00+01:00"
draft: false
menu:
  average-mixtures-alligation:
    parent: 2. Mixtures & Alligation
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

## What is a mixture?

Mixture - any collection of parts with distinct characteristics. 

For example: <br>
A class is a mixture of boys and girls with different ages, heights, marks scored etc. 

## Types of Mixtures

### Simple mixture

Simple mixture: When two different ingredients are mixed together.

For example: <br>
A solution having milk and water in the ratio 3:7. <br>
It means that, if the solution has 3k litres of milk, there will be 7k litres of water and the total solution will be 10k litres. <br>
Fraction or Concentration of milk = 3/10 or 30%

### Compound mixture

Compound mixture: When two or more simple mixtures are mixed together to form another mixture.

E.g. A 2 : 3 milk and water solution is mixed with a 3 : 1 alcohol and water solution in the ratio 1 : 4. 

The composition of resultant solution depends on:
* the concentration of the solutions being mixed.
* the ratio in which the two solutions are mixed. 

## Methods for Mixture Questions

There are two methods via which we can solve questions based on mixtures:
* Weighted average method
* Alligation method

### Weighted average method

If two ingredients A and B of price x and y respectively are mixed the ratio m : n, then the price of resultant mixture is:

$A_{wt}$ = $\frac{mx + ny}{m + n}$

### Alligation method

In weighted average method we had to use variables and we needed to solve equations. Can we avoid that?

That’s where Alligation method comes in. Alligation is nothing but a rearranged form of weighted average.

We saw that, weighted average $A_{wt}$ = $\frac{mx + ny}{m + n}$ <br>
Or $A_{wt}$ (m + n) = (mx + ny) <br>
Or $A_{wt}$ m + $A_{wt}$ n = mx + ny <br>
Or mx  - $A_{wt}$ m = $A_{wt}$ n - ny <br>
Or m(x - $A_{wt}$) = n($A_{wt}$  - y) <br>
Or $\frac{m}{n}$ = $\frac{A_{wt} - y}{x - A_{wt}}$

This is the alligation formula.

The above formula can be represented as follows:
<img src="../../../media/mixtures/alligation-method.png" alt="alligation method" style="width:81%;height:81%;">
Please note that since we took dearer price on the top left comer, the ratio of the bottom left figure to that of the bottom right figure will give the ratio of dearer quantity to cheaper quantity.

{{% alert note %}}
Alligation does not give the actual volumes to be mixed, but only the ratio in which volumes are to be mixed. 
{{% /alert %}}

## Weighted Average Vs. Alligation Method

Wherever Weighted Average can be used, Alligalion can also be used and wherever Alligation can be used, Weighted average can also be used as basically both are the same. 

But one method can be faster than the other based on the kind of question we encounter. 

Keep these points in mind:

* If the weighted average ($A_{wt}$) is given and the ratio of weights (m : n) is to be found out, we should prefer the Alligation method.

* If weighted average ($A_{wt}$) is unknown and instead the weights are given, then the Weighted Average formula can be faster.

##### Q. If 15 litres of 20% milk solution is mixed with 20 litres of 10% milk solution, then what will be the concentration of milk in the final solution?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Weighted Average Method <br><br>

x = 20%  and  y = 10% <br>
m : n = 15 : 20 = 3 : 4

$A_{wt}$ = $\frac{mx + ny}{m + n}$ = [(3 × 20) + (4 × 10)] / (3 + 4) = (60 + 40) / 7 = 100/7 = 14.28% 
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Alligation Method<br><br>

<img src="../../../media/mixtures/alligation-method1.png" alt="alligation method" style="width:63%;height:63%;">
$\frac{m}{n}$ = $\frac{A_{wt} - y}{x - A_{wt}}$ <br>
or $\frac{15}{20}$ = $\frac{A_{wt} - 10}{20 - A_{wt}}$ <br>
or 3 (20 - $A_{wt}$) = 4 ($A_{wt}$ – 10)  <br>
or $A_{wt}$ = 100/7 = 14.28%

{{% alert note %}}
Note: When the weighted average is not given, we should prefer to use the weighted average method instead of the allegation method. 
{{% /alert %}}
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: <br><br>

x = 20%  and  y = 10%
m : n = 15 : 20 = 3 : 4

Concentration of milk in final solution = 10% + $\frac{3}{(3 + 4)}$ × (20 - 10) = 10 + 30/7 = 14.28%
</div><br>
