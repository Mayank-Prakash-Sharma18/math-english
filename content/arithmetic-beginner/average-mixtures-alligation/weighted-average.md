---
title: Weighted Average
linktitle: Weighted Average - Basics
toc: true
type: docs
date: "2021-01-27T00:00:00+01:00"
draft: false
menu:
  average-mixtures-alligation:
    parent: 1. Average
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

## What is Weighted Average?

Weighted Average is basically the average of two or more than two groups.

If the averages of two or more groups are known, then to find the combined average of all the items in all these groups we can use Weighted Average Method.

## How to find Weighted Average?

### Formula Method

If n groups have: <br>
Averages - $A_1$, $A_2$, $A_3$ ... $A_n$ respectively and  <br>
Number of items - $n_1$, $n_2$, $n_3$ ... $n_n$ respectively

Combined/Weighted Average = $\frac{A_1 n_1 + A_2 n_2 + ... + A_n n_n}{n_1 + n_2 + ... + n_n}$

{{% alert note %}}
Note: If there are only 2 groups then: <br>
Combined/Weighted Average = $\frac{A_1 n_1 + A_2 n_2}{n_1 + n_2}$
{{% /alert %}}

***Let’s see some examples:***

In class X - 3 students with 20, 30 and 40 marks respectively. <br>
So, average marks of class X = 30 marks

In class XI – 2 students with 70 and 80 marks respectively. <br>
So, average marks of class XI = 75 marks

Their Combined/Weighted Average = $\frac{A_1 n_1 + A_2 n_2}{n_1 + n_2}$ = $\frac{30 x 3 + 75 x 2}{3 + 2}$ = $\frac{240}{5}$ = 48 marks

Let's see another formula:

If the average of n quantities is A and the average of $n_1$ quantities out of n quantities is $A_1$, then: 

Average of the remaining quantities = $\frac{nA − n_1 A_1}{n − n_1}$

### Method of deviations

Finding weighted average using method of deviations.

To further simplify the calculation of finding weighted average we can use the method of deviations, that we used for calculating averages. 

* Step I: Choose an arbitrary weighted average number. <br>
* Step II: Find out deviations from this arbitrarily chosen number and calculate the weighted average of these deviations.

In our example, three classes have their average marks as 50, 60 and 90 respectively. <br>
Let us assume 65 as the arbitrary weighted average. <br>
The deviations of the three given averages from 65 are: -15, -5 and +25.  <br>
The weighted average of these deviations = [(-15) x 3 + (-5) x 2 + 25 x 4]/(3 + 2 + 4) = 45/9 = 5 <br>
Hence, the weighted average = 65 + 5 = 70

### Short-Cut Method

This method is applicable only in case of two groups. 

We can calculate the weighted average of two groups as follows:

To find the weighted average of $A_1$ and $A_2$ ($A_2$ > $A_1$) with weights $w_1$ and $w_2$:

* Step I: divide the difference ($A_2$ – $A_1$) in the ratio $w_1$ : $w_2$. <br>
Let m = ($A_2$ – $A_1$) × [$\frac{w_2}{w_1 + w_2}$] and <br>
n = ($A_2$ – $A_1$) × [$\frac{w_1}{w_1 + w_2}$] 

* Step II: Weighted average = $A_1$ + m   OR   $A_2$ – n. <br>
So, Weighted Average = $A_1$ + ($A_2$ – $A_1$) × [$\frac{w_2}{w_1 + w_2}$]  OR $A_2$ – ($A_2$ – $A_1$) × [$\frac{w_1}{w_1 + w_2}$] 

E.g. To find weighted average of 40 and 70 with weights in ratio 2:3 <br>
* Step I: ($A_2$ – $A_1$) = 70 – 40 = 30 <br>
m = (3/5) × 30 = 18 <br>
n = (2/5) × 30 = 12 <br>
* Step II: Weighted average = $A_1$ + m = 40 + 18 = 58   OR    $A_2$ – n = 70 – 12 = 58

##### Q. If two types of grains which cost Rs. 18 per kg and Rs. 27 per kg are mixed in a ratio of 2:1, then find the cost of one kg of the mixture?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

Combined/Weighted Average = $\frac{A_1 n_1 + A_2 n_2}{n_1 + n_2}$ = [(18 × 2) + (27 × 1)] / (2 + 1) = 63/3 = Rs. 21
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Shortcut Method<br><br>

Combined/Weighted Average = $A_1$ + ($A_2$ – $A_1$) × [$\frac{w_2}{w_1 + w_2}$] = 18 + (27 - 18) × (1/3) = 18 + 3 = Rs. 21
</div><br>

<br><hr>

## Concepts related to weighted averages

Now, let us understand some concepts related to weighted averages. 

### Concept 1: Weighted Average Vs. Average of Averages

If we want to find the average of two or more groups, is taking average of averages the right approach?

In class X - 3 students with 20, 30 and 40 marks respectively. <br>
In class XI – 2 students with 70 and 80 marks respectively.

The average of marks of students of both the classes = [20 + 30 + 40 + 70 + 80]/5 = 48 (correct)

We will get the same answer if we use the weighted average method: <br>
The average of marks of students of both the classes = [(30 × 3) + (75 × 2)]/(3 + 2) = 240/5 = 48 (correct)

Noe let us try to find the average the marks of all the students of two classes by taking the average of averages: <br>
The average of marks of students of both the classes ≠ [30 + 75]/2 = 52.5 marks (incorrect) <br>
So, average of the averages need not be the correct answer.

{{% alert note %}}
We will get the correct answer using average of averages method only if the number of items in each group is the same. For example, if there were equal number of students in both the classes. 
{{% /alert %}}

### Concept 2: Influence on Weighted Average

The group having more items influence the weighted average more.

Let's understand it using the same example of two classes. 

The average of marks of students of both the classes OR Weighted average of the two classes = 48 marks

Middle point between the two group averages OR The average of averages = [30 + 75]/2 = 52.5 marks 

We can see that the combined average of the students of the two classes is tilted more towards the average of the group having more students, i.e. Class X average. 

<img src="../../../media/mixtures/weighted-average1.png" alt="weighted average" style="width:99%;height:99%;">

Thus, the larger class size pulled the average of both the classes taken together, closer to itself, i.e. the class with larger strength had more of an influence (or weight) on the average of both the classes considered together. 

### Concept 3: Ratio of items given

Finding weighted average if ratio of the number of items in the groups is given.

If we know only the average of the two groups individually, we cannot find out the weighted average of the combined group of items. We also need to know:

The number of items in the two groups, e.g. 3 students in Class X and 2 students in Class XI. 

OR

The ratio of the number of items in the two groups, e.g. 3:2. Knowing the ratio is as good as knowing the exact number of items in the two groups, because we are just interested in how much relative importance does each average exert on the weighted average. 

{{% alert note %}}
In fact it will be easier to calculate if we use the ratio rather than the absolute values in the formula. So, even if absolute values are given we can find out their ratio and use that in the weighted average formula. 
{{% /alert %}}

For example: <br>
Three classes have their average marks as 50, 60 and 90 respectively and their respective strengths are 30, 20 and 40. <br>
So, ratio of the number of students = 30 : 20 : 40 = 3 : 2 : 4 <br>
The average marks of all the students = [50 x 3 + 60 x 2 + 90 x 4]/(3 + 2 + 4) = 630/9 = 70

### Concept 4: Identifying weights

When we are trying to find the weighted average, it is important to identify and differentiate between the averages and weights.

For example: <br>
5 kg of wheat costing Rs 40/kg is mixed with 9 kg of wheat costing Rs 50/kg. 

Here, weights are 5 and 9 and not 40 and 60. We are supposed to find the average cost using the weighted average formula. Thus the costs 40 and 50 are the defining character of the two groups and the other values 5 and 9 are the weights, which try to pull the weighted average towards them. 

