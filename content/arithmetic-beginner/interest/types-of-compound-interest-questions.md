---
title: Types of Compound Interest Questions
linktitle: Compound Interest Question Types
toc: true
type: docs
date: "2021-10-05T00:00:00+01:00"
draft: false
menu:
  interest:
    parent: Interest
    weight: 19

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 19
---

In this article, we are going to have a look at the various kinds of questions formed on Compound Interest. 

## Type 1: Difference between CI and SI

##### Q. What is the difference between simple interest and compound interest on Rs. 2,000 for one year at an annual interest rate of 20%, if compounded half-yearly?
<pre>(a) Rs. 20   (b) Rs. 0    (c) Rs. 10   (d) Rs. 200</pre>

Explanation:<br>
<div class="Exp">

Simple Interest = (P × r × t)/100  = (2000 × 20 × 1)/100 = Rs. 400

Compound Interest (compounded half yearly) = Amount – Principle <br>
= P (1 + $\frac{r}{100 × m})^{mt}$ - P <br>
= 2000 (1 + $\frac{20}{100 × 2})^2$ - 2000 <br>
= 2000 (1 + $\frac{10}{100})^2$ - 2000 <br>
= 2000 $(1.1)^2$ – 2000 = 2000 × 1.21 – 2000 = 0.21 × 2000 = Rs. 420

Required difference = CI - SI = 420 - 400 = Rs. 20 

Answer: (a)
</div> <br>

##### Q. What will be the difference between the compound interest and simple interest at the rate of 5 percent per annum on a sum of Rs. 4,000 at the end of two years?
<pre>(a) Rs. 25         (b) Rs. 10         (c) Rs. 20         (d) Rs. 30</pre>

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method <br><br>

Principal = Rs. 4,000, Rate = 5% p.a. and Time = 2 years

C.I. = [P $(1 + r/100)^t$] - P = [4000 $(1 + 5/100)^2$] - 4000 <br>
= 4410 - 4000 = Rs. 410

S.I. = (P × r × t)/100 = (4000 × 5 × 2)/100 = Rs. 400 

∴	S.I. - C.I. = 410 - 400 = Rs. 10

Answer: (b)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: <br><br>

Simple interest gained in the first year = (P × r × t)/100 = (4000 × 5 × 1)/100 = Rs. 200 

Difference between the compound interest and simple interest at the end of two years = Interest made in the 2nd year on the simple interest gained in the first year <br>
= Interest made in 2nd year on Rs. 200 <br>
= (P × r × t)/100 = (200 × 5 × 1)/100 = Rs. 10

Answer: (b)
</div><br>

## Type 2: Data Sufficiency

##### Q. Which of the following statement(s) is/are not required to find the total interest earned at the end of 4 years, if compounded annually?

1.	Rate of compound interest is 5% per annum.
2.	Compound interest for 4 years is more than the simple interest for the same period of 4 years and at the same rate, by Rs. 155.
3.	Simple interest earned on that amount at the same rate and the same time is Rs. 2,000.

(a)	Both 1 and 2 are not required <br>
(b)	Both 1 and 3 are not required <br>
(c)	Only 3 is not required <br>
(d)	Any one out of the three is not required at a time

Explanation:<br>
<div class="Exp">

Let us assume the principal amount to be Rs. x. 

After reading the given statements it becomes obvious that the compound interest cannot be calculated using only one of the given statements at a time. 

Hence, let us try to calculate the required compound interest using two statements at a time.

**Using statements 1 and 2**:

C.I. - S.I. = 155 <br>
or x[$(1 + R/100)^t$ - 1] - (x × R × t)/100 = 155 <br>
or x[$(1 + 5/100)^4$ – 1 – (5 × 4)/100] = 155 <br>
or x[$(1.05)^4$ – 1 - 0.2] = 155 <br>
or 0.0155x = 155 <br>
or x = 155/0.0155 <br>
or x = Rs. 10,000 

Now, C.I. = 155 + S.I. <br>
or C.I. = 155 + (10000 × 5 × 4)/100 = Rs. 2,155

**Using statements 2 and 3**:

C.I. – S.I. = 155 <br>
or C.I. = 155 + 2000 = Rs. 2,155

**Using statements 1 and 3**:

S.I. = 2,000 <br>
or (x × 5 × 4)/100 = 2000 <br>
or x = Rs. 10,000

C.I. = 10000 $(1 + 5/100)^4$ – 10000
= Rs. 2,155

Hence (d) is the right option, as the question can be answered with the use of any two of the given statements. So, any one out of the three statements is not required at a time.

{{% alert note %}}
We have to remember that question is not asking the values. So there is no need to solve the question in detail in exam. 

We know that Compound interest = P [(1 + $\frac{r}{100})^t$ - 1]

Here value of t is given as 4 years. Thus, to find out the Compound interest we need to know the values of P (Principle) and r (rate of interest). 

Now we need two equations to find these two variables. Thus, any two given statements are enough to form two equations and find the values of P and r and thereby calculating the required Compound interest.
{{% /alert %}}

Answer: (d)
</div> <br>

