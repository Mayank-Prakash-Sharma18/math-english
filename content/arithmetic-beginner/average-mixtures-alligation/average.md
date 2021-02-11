---
title: Average
linktitle: Average - Basics
toc: true
type: docs
date: "2021-01-25T00:00:00+01:00"
draft: false
menu:
  average-mixtures-alligation:
    parent: 1. Average
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## What is Average?

The average of n quantities of the same kind is equal to the sum of all the quantities divided by the number of quantities.

## How to find Average?

### Formula Method

Average = $\frac{Sum \hspace{1ex} of \hspace{1ex} Quantities}{Number \hspace{1ex} of \hspace{1ex} Quantities \hspace{1ex} (n)}$

For example: <br>
An average or an arithmetic mean of given data is sum of the given observations divided by number of observations. <br>
Average = $\frac{Sum \hspace{1ex} of \hspace{1ex} Observations}{Number \hspace{1ex} of \hspace{1ex} Observations}$

### Method of deviations

Instead of using the formula, we can use method of deviations to ease out our calculation.

For example, we need to find average of n quantities – $x_1$, $x_2$, ..... $x_n$

In this method:
* We assume some arbitrary number (A) as the average. 
* After that we algebraically add the deviations (differences) of all the quantities from A, i.e. ($x_1$ – A) ± ($x_2$ - A) ± ..... ± ($x_n$ - A). 
* Thereafter we take average of these differences. That is, we find $\frac{1}{n} \sum_{i=1}^{n} (x_i − 𝐴)$
* Then we algebraically add this average to A to get our answer. 

So, the average of these n items, Average = A ± $\frac{1}{n} \sum_{i=1}^{n} (x_i − 𝐴)$

{{% alert warning %}}
Adding algebraically means that we take into account the signs too. So, always keep in mind the signs. 
{{% /alert %}}

***Let's consider an example:***

A student scored the following marks in five subjects: 38, 58, 44, 54 and 61. 

Now, assume some arbitrary number (A) as the average, say 50.
* The deviations of the marks from 50 are: -12, +8, -6, +4 and +11
* The algebraic sum of these deviations is +5.
* Hence the average of the student’s marks = 50 + 5/5 = 51

If we take A = 55. 
* The deviations of the scores from 55 are: -17, +3, -11, -1 and +6
* The algebraic sum of these deviations is -20.
* Hence the average of the student’s marks = 55 - 20/5 = 55 - 4 = 51.

{{% alert note %}}
Note: The extent to which this method will simplify the calculation will depend on the selection of the arbitrary average A. It should be selected in such a way that the positive and negative deviations cancel out each other as much as possible. Then the final figure left for division will be relatively small making the division easier.
{{% /alert %}}

##### Q. If a cricketer scored 98, 82, 66, 76, 80 and 90 runs in his six innings, then what is his average score?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

Average = $\frac{Sum \hspace{1ex} of \hspace{1ex} Quantities}{Number \hspace{1ex} of \hspace{1ex} Quantities \hspace{1ex} (n)}$ = (98 + 82 + 66 + 76 + 80 + 90)/6 = 492/6 = 82 runs
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Method of Deviations<br><br>

Let us assume 80 as the mean.

Algebraic sum of deviations = 18 + 2 – 14 – 4 + 0 + 10 = 12

So, average score of cricketer = 80 + 12/6 = 82 runs
</div><br>

## Properties of Averages

### Addition 

If all the numbers get increased by a, then their average must be increased by a. <br>
E.g. If the average age of group of people is x years, then their average age after n years will be (x + n). This is because with each passing year, each person’s age increases by 1 and vice versa.

### Subtraction  

If all the numbers get decreased by a, then their average must be decreased by a. <br>
E.g. If the average age of group of people is x years, then their average age n years ago would have been (x – n).

### Multiplication/Division 

If all the numbers are multiplied by a, then their average must be multiplied by a. <br>
If all the numbers are divided by a, then their average must be divided by a. (a ≠ 0)

### Multiples of a number

Average of n multiples of any number = $\frac{Number × (n+1)}{2}$

<br><hr>

## Impact of Group change on Average 

Average may increase/decrease on an entity leaving or joining the group. That's what we are going to focus on, in this section. 

There are three probable scenarios. 

### Addition of a new item

Average of n quantities is equal to X and on adding a new entity/quantity to the group the average becomes Y (i.e. number of entities in the group increases by 1), then: 

Value of new entity = Y + (Y - X)n     OR       X + (Y - X)(n + 1) 

### Removal of an existing item

Average of n quantities is equal to X and on removing an entity/quantity from the group the average becomes Y (i.e. number of entities in the group decreases by 1), then: 

Value of removed entity = Y + (X - Y)n    OR     X + (X - Y)(n - 1)

### Replacement of an existing item with a new one

The average of n quantities is equal to X. When one quantity of value P is replaced with a new quantity having value Q, the average of quantities becomes Y (i.e. number of entities in the group remain the same), then

Value of new entity, Q = P + (Y - X)n

##### Q. The average age of a group of 8 boys is 12 years. Thereafter a new boy joins the group and their average age increases to 13 years. What is the age of the new boy?

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-3', this, 'tablink-group2', 'tabcontent-group2')">3</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Traditional Method <br><br>

Average = Sum of ages / Number of boys

Or Sum of ages = Average × Number of boys = 12 × 8 = 96 years

New sum of ages = New Average × New Number of boys = 13 × 9 = 117

So, the age of the new boy = 117 – 96 = 21 years
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Formula Method  <br><br>

Average of n quantities is equal to X and on adding a new entity/quantity to the group the average becomes Y (i.e. number of entities in the group increases by 1), then: 

Value of new entity = Y + (Y - X)n     OR       X + (Y - X)(n + 1) 

So, age of the new boy = Y + (Y - X)n = 13 + (13 - 12)8 = 13 + 8 = 21 years 
</div>

<div id="2Exp-3" class="Exp-3 mak-tabcontent tabcontent-group2">
Explanation 3: Short Trick Method  <br><br>

The average of group increased from 12 to 13.

So, the age of the new boy must be atleast 13 plus the amount needed to raise the average of the rest of the boys. 

That is, age of new boy = New average + Amount needed to raise the average of rest of the boys <br>
= New average + Difference in averages × Original number of boys <br>
= 13 + (13 - 12) × 8 = 13 + 8 = 21 years
</div><br>