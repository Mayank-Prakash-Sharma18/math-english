---
title: Concept of Base Change 
linktitle: Concept of Base Change 
toc: true
type: docs
date: "2020-09-03T00:00:00+01:00"
draft: false
menu:
  percentage:
    parent: Percentage
    weight: 5

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 5
---

<img src="../../../media/percentage/base-change.png" alt="base-change">

Question types covered:

Percent Change Reversal – If x is increased/decreased to y, then by what percent should y be decreased/increased to take it back to the original value?

If B is p% more/less than A, then A is how much percent less/more than B?

If z = x × y, and x is increased/decreased by p%, then by what percentage y should be decreased/increased to maintain the same value of z?

## Traditional method 

Using the variables.

###### Q. If salary of Mragank is 20% more than the salary of Aanya, then the salary of Aanya is how much percent less than the salary of Mragank?
Explanation:<br>
<div class="Exp">
Explanation 1: Traditional Method <br>
Let Salary of Aanya be x. 
<img src="../../../media/percentage/base-change-traditional-method.png" alt="base change - traditional method" style="width:27%;height:27%;">
Mragank is 20% more than the salary of Aanya.<br>
So, Salary of Mragank = x + (20/100) × x =  1.2 x<br>
Difference is salaries remain the same, i.e. 0.2x. <br>
Required percentage = (0.2x/1.2x) × 100 = (1/6) × 100 = 16.67% <br>
</div>

## Formula Method

<img src="../../../media/percentage/formula-method-increase.png" alt="base change - formula method" style="width:36%;height:36%;">
If a value x is increased by p%, then to get back to the original x, we have to decrease the increased value by $\frac{p}{100+p}$ × 100%. <br>
OR <br>
If y is p% more than x, then x is $\frac{p}{100+p}$ × 100% less than y. <br>

<img src="../../../media/percentage/formula-method-decrease.png" alt="base change - formula method" style="width:36%;height:36%;">
If a value x is decreased by p%, then to get back to the original x, we have to increase the decreased value by $\frac{p}{100-p}$ × 100%. <br>
OR <br>
If y is p% less than x, then x is $\frac{p}{100-p}$ × 100% more than y. <br>

###### Q. If salary of Mragank is 20% more than the salary of Aanya, then the salary of Aanya is how much percent less than the salary of Mragank?
Explanation:<br>
<div class="Exp">
Explanation 2: Formula Method <br>
If y is p% more than x, then x is $\frac{p}{100+p}$ × 100 % less than y. <br>
So, Required percentage = (20/120) × 100 = (1/6) × 100 = 16.67%  <br>
</div>

## Percentage Method

<img src="../../../media/percentage/base-change-percentage-method.png" alt="base change - percentage method" style="width:60%;height:60%;">

###### Q. If salary of Mragank is 20% more than the salary of Aanya, then the salary of Aanya is how much percent less than the salary of Mragank?
Explanation:<br>
<div class="Exp">
Explanation 3: Percentage Method<br>
Salary of Mragank is 20% more than the salary of Aanya. - Base is the salary of Aanya.<br>
If Aanya’s salary = 100, then Mragank’s salary = 120
<img src="../../../media/percentage/base-change-percentage-method1.png" alt="base change - percentage method" style="width:27%;height:27%;">
Salary of Aanya is how much percent less than the salary of Mragank. - Now, Base is the salary of Mragank.<br>
Difference is salaries remain the same, i.e. 20. But now base will be 120.<br>
Required percentage = (20/120) × 100 = (1/6) × 100 = 16.67% <br>
</div>

## Fraction Method

<img src="../../../media/percentage/base-change-fraction-method.png" alt="base change - fraction method" style="width:80%;height:80%;">

* Increase: In terms of fraction, if a value x is first increased by p% (= n/d) then to get back to the original number x, we have to decrease the increased value by $\frac{d}{d+n}$. (where d is denominator and n is numerator)

* Decrease: In terms of fraction, if a value x is first decreased by p% (= n/d) then to get back to the original number x, we have to increase the increased value by $\frac{d}{d-n}$. (where d is denominator and n is numerator)

For example, a number is increased by 25% 
<img src="../../../media/percentage/base-change-fraction-method1.png" alt="base change - fraction method" style="width:27%;height:27%;">
25% = 𝒏/𝒅 = 𝟏/𝟒      - It implies an increase of 1 on 4 <br>
So, the original number ≡ 4 (i.e. d)  <br>
And new number ≡ 4 + 1 = 5 (i.e. d + n)  <br>
Percent change required in bringing down 5 to 4 again = 1/5 ≡ 20% <br>

On the other hand, if a number is decreased by 25% 
<img src="../../../media/percentage/base-change-fraction-method2.png" alt="base change - fraction method" style="width:33%;height:33%;">
25% = 𝒏/𝒅 = 𝟏/𝟒       - It implies an decrease of 1 on 4 <br>
So, the original number ≡ 4 (i.e. d) <br>
And new number ≡ 4 - 1 = 3 (i.e. d - n)   <br>
Percent change required in bringing up 3 to 4 again = 1/3 ≡ 33.33%  <br>

###### Q. If salary of Mragank is 20% more than the salary of Aanya, then the salary of Aanya is how much percent less than the salary of Mragank?
Explanation:<br>
<div class="Exp">
Explanation 4: Fraction Method <br>
20% is equivalent to 1/5  <br>
If Aanya’s salary = 5, then Mragank’s salary = 6
<img src="../../../media/percentage/base-change-fraction-method3.png" alt="base change - fraction method" style="width:27%;height:27%;">
Difference is salaries remain the same, i.e. 1. But now base will be 6.<br>
Required percentage = 1/6 × 100 = 16.67%  <br>
</div>

###### Q. If salary of Mragank is 20% less than the salary of Aanya, then the salary of Aanya is how much percent more than the salary of Mragank?
Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Formula Method<br>
If y is p% less than x, then x is $\frac{p}{100−p}$ × 100% more than y.<br>
So, Required percentage = (20/80) × 100 = (1/4) × 100 = 25% <br>
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Percentage Method<br>
Salary of Mragank is 20% less than the salary of Aanya. - Base is the salary of Aanya.<br>
If Aanya’s salary = 100, then Mragank’s salary = 80
<img src="../../../media/percentage/question2-1.png" alt="base change - fraction method" style="width:27%;height:27%;">
Salary of Aanya is how much percent more than the salary of Mragank. - Now, Base is the salary of Mragank.<br>
Difference is salaries remain the same, i.e. 20. But now base will be 80.<br>
Required percentage = (20/80) × 100 = 1/4 × 100 = 25% <br>
</div>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: Fraction Method<br>
20% is equivalent to 1/5 <br>
If Aanya’s salary = 5, then Mragank’s salary = 4
<img src="../../../media/percentage/question2-2.png" alt="base change - fraction method" style="width:27%;height:27%;">
Difference is salaries remain the same, i.e. 1. But now base will be 4.<br>
Required percentage = (1/4) × 100 = 25% <br>
</div>

## Percentage Method or Fraction Method?

Should we use the Percentage Method or Fraction Method?

Let us try to understand it using a couple of examples.

###### Q. On increasing a number by 37.5%, the new number obtained is 63 more than the original number. What must be the original number?
Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Percentage Method <br>
37.5% is equivalent to 63 <br>
So, 37.5% ≡ 63  <br>
Then, 100% ≡ 63 × 100/37.5 = 63 × 8/3 = 21 × 8 = 168 <br>
Complex calculation involved! <br>
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Fraction Method <br>
37.5% is equivalent to 3/8  <br>
If Original number = 8, then increase = 3 <br>
So, 3 ≡ 63  <br>
Then, 8 ≡ 63 × 8/3 = 21 × 8 = 168 <br>
Easier calculation as compared to percentage method. <br>
</div><br>

###### Q. On increasing a number by 37.5%, the new number obtained is 231. What must be the original number?
Explanations :<br>
<button class="mak-tablink tablink-group3 default-tab" onclick="openTab('3Exp-1', this, 'tablink-group3', 'tabcontent-group3')">1</button>
<button class="mak-tablink tablink-group3" onclick="openTab('3Exp-2', this, 'tablink-group3', 'tabcontent-group3')">2</button>

<div id="3Exp-1" class="Exp-1 mak-tabcontent tabcontent-group3">
Explanation 1: Percentage Method <br>
137.5% (i.e. 100 + 37.5%)  is equivalent to 231 <br>
So, 137.5% ≡ 231  <br>
Then, 100% ≡ 231 × 100/(100+37.5) = 231 × 100/137.5 = 231 × 8/11 = 21 × 8 = 168 <br>
Complex calculation involved! <br>
</div>

<div id="3Exp-2" class="Exp-2 mak-tabcontent tabcontent-group3">
Explanation 2: Fraction Method <br>
37.5% is equivalent to 3/8  <br>
If Original number = 8, then new number = 8 + 3 = 11 <br>
So, 11 ≡ 231  <br>
Then, 8 ≡ 231 × 8/11 = 21 × 8 = 168 <br>
Easier calculation as compared to percentage method. <br>
</div><br>

As you will keep on practicing you will develop a better sense of which method to use based on the kind of data given in the question. 