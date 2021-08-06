---
title: Finding Squares and Cubes
linktitle: Finding Squares and Cubes 
toc: true
type: docs
date: "2021-07-17T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 1. Fast Calculation
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## What are Involution and Evolution?

When we multiply an expression or a number by itself to find its second, third, fourth ... $n^{th}$ powers, we call it ***Involution***. So, it's a process of finding the powers of an expression/number. 

For example, square, cube etc. 

{{% alert note %}}
Even powers of an expression are always positive. <br>
Odd powers may be positive or negative. 
{{% /alert %}}

***Evolution*** is the process of finding the roots of an expression/number. 

Root is a quantity, which when multiplied by itself one, two, three .... n times, produces the given expression/number.

For example, square root, cube root etc. 


## Squares and Cubes

To find the square of a number, we just multiply the number with itself 2 times. For example, $5^2 = 5 × 5 = 25$

To find the cube of a number, we just multiply the number with itself 3 times. For example, $5^3 = 5 × 5 × 5 = 125$

But there are some other methods that we can use. Let's have a look at a few of them 


## Various Methods to find Squares

### Finding Squares using a Formula

We can use the formula $(x + y)^2 = x^2 + y^2 + 2xy$, to find square of two-digit and three-digit numbers. 

We can use it for bigger numbers too, but the calculation gets tougher. 

##### Q. Find $63^2$

Explanation:<br>
<div class="Exp">

We know that: $(x + y)^2 = x^2 + y^2 + 2xy$

Now, $63^2 = (60 + 3)^2 = 60^2 + 3^2 + 2 × 60 × 3$ = 3600 + 9 + 360 = 3969

{{% alert note %}}
There's an alternate Vedic method to make the above calculation even faster. 

Write the given number as follows: <br>
$63^2 = [6 | 3]^2$ 

Now, apply the formula $(x + y)^2 = x^2 + y^2 + 2xy$ on the digits of the given number.<br>
So, $[6 | 3]^2 = [6^2 | 2 × 6 × 3 | 3^2] = [36 | 36 | 9]$

The middle term is 36. We will keep the 6, and carry over 3 to the left hand side. <br>
So, $[36 | 36 | 9] = [39 | 6 | 9]$ = 3969
{{% /alert %}}
</div> <br>

##### Q. Find $114^2$

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Formula Method <br><br>

We know that: $(x + y)^2 = x^2 + y^2 + 2xy$

Now, $114^2 = (100 + 14)^2 = 100^2 + 14^2 + 2 × 100 × 14$ = 10000 + 196 + 2800 = 12996
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Vedic Method<br><br>

Write the given number as follows: <br>
$114^2 = [11 | 4]^2$ 

Now, apply the formula $(x + y)^2 = x^2 + y^2 + 2xy$ on the digits of the given number.<br>
So, $[11 | 4]^2 = [11^2 | 2 × 11 × 4 | 4^2] = [121 | 88 | 16]$

The last term is 16. We will keep the 6, and carry over 1 to the left hand side. <br>
So, $[121 | 88 | 16] = [121 | 89 | 6]$

The middle term is 89. We will keep the 9, and carry over 8 to the left hand side. <br>
So, $[121 | 89 | 6] = [129 | 9 | 6]$ = 12996
</div><br>


##### Q. Find $253^2$

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Using Formula Method <br><br>

We know that: $(x + y)^2 = x^2 + y^2 + 2xy$

Now, $253^2 = (250 + 3)^2 = 250^2 + 3^2 + 2 × 250 × 3$ = 62500 + 9 + 1500 = 64009
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Using Vedic Method <br><br>

Write the given number as follows: <br>
$253^2 = [25 | 3]^2$ 

Now, apply the formula $(x + y)^2 = x^2 + y^2 + 2xy$ on the digits of the given number.<br>
So, $[25 | 3]^2 = [25^2 | 2 × 25 × 3 | 3^2] = [625 | 150 | 9]$

The middle term is 150. We will keep the 0, and carry over 15 to the left hand side. <br>
So, $[625 | 150 | 9] = [640 | 0 | 9]$ = 64009
</div><br>

### Some specific cases

Now, let us have a look at a few methods that do help us find squares of a number, but they are applicable to very specific type of numbers. 

#### Squares of numbers ending with 5

If we have to find the square of a number ending with the digit 5, then we can do it even faster. It's pretty easy. 

Write down the square of 5 (i.e. 25) at the end and then multiply the rest of the number with its next consecutive number and write it infront of 25.

For example, $25^2 = (2 × 3) | 25 = 6 | 25$ = 625 <br>
$135^2 = (13 × 14) | 25 = 182 | 25$ = 18225

#### Squares of numbers ending with 25

We can find the squares of such numbers by previously mentioned method too. But if the number is bigger, say 4-digit long, then the following method will reduce our calculations and hence will save some of our time in exam hall. 

Write down the square of 25 (i.e. 625) at the end and then multiply the rest of the number with (number5) and write it infront of 25.

For example, $1225^2 = (12 × 125) | 625 = 1500 | 625$ = 1500625 <br>
$1625^2 = (16 × 165) | 625 = 2640 | 625$ = 2640625

#### Squares of numbers having only 1's

To find the square of a number consisting wholly of n 1’s, we write natural numbers in ascending order as many times as the ‘1’ digit appears in the given number and then write the natural numbers in descending order (without repeating the last digit).

For example, in $11111^2$, we have five 1's.<br>
* We will write down five natural numbers in ascending order: 12345
* Then write the natural numbers in descending order (without repeating the last digit): 4321

So, square of 11111 will be 123454321

Have a look at the following pattern for more clarity:
* Square of 1 = 1
* Square of 11 = 121
* Square of 111 = 12321
* Square of 1111 = 1234321
* Square of 11111 = 123454321

{{% alert note %}}
To find the square of a number consisting wholly of n 2’s:
* we take out the power of 2 (i.e. $2^2$), so that only 1's are left
* find out the square of a number consisting wholly of n 1’s
* multiply that with the power of 2 that we took out earlier

For example, in $222^2$, we have three 2's.<br>
* we take out the power of 2, so that only 1's are left: $222^2$ = $2^2 × 111^2$
* find out the square of a number consisting wholly of n 1’s: $111^2$ = 12321
* multiply that with the power of 2 that we took out earlier: $2^2 × 12321$ = 4 × 12321 = 49284

We will follow a similar process to find the square of a number consisting wholly of n 4’s. There the common power taken out will be $4^2$ or $2^4$.
{{% /alert %}}

#### Squares of numbers having only 3's

To find the square of a number consisting wholly of n 3’s, we do the following:
* write down 9 at the end, preceded by (n – 1) 8's and then 
* add one 0 (zero) before the number got in last step, preceded by (n – 1) 1's.

For example, in $33333^2$, we have five 3's.<br>
* We will write down 9 at the end, preceded by (n – 1) 8's: 88889
* add one 0 (zero) before the number got in last step, preceded by (n – 1) 1's: 11110

So, square of 99999 will be 1111088889

#### Squares of numbers having only 9's

To find the square of a number consisting wholly of n 9’s, we do the following:
* write down (n – 1) nines followed by 8 and then 
* add (n – 1) zeroes followed by 1.

For example, in $99999^2$, we have five 9's.<br>
* We will write down (n – 1) nines followed by 8: 99998
* add (n – 1) zeroes followed by 1: 00001

So, square of 99999 will be 9999800001


## Various Methods to find Cubes 

Now, let us see a few methods that may help us find cubes of numbers quickly. 

### Cube of a numbers near 100

Let's see how to find cubes of numbers that are close to 100; a little above it or below it. 

#### Cubes of numbers a little above 100

Divide the number in two parts: For example, we can write 108 as (100 + 8). 

For the sake of generalization, we can take the number to be 10a, i.e. 100 + a

The cube of this number can be found in three parts: 3rd part | 2nd part | 1st part
* 1st part will have 2 digits: write down $a^3$
* 2nd part will have 2 digits: write down $a^2 × 3$
* 3rd part: 100 + $a × 3$

{{% alert note %}}
In first part, Number of digits = Number of zeroes in the first part of the number after dividing it into two parts

For example, if number is near 100, then there will be 2 digits in the first part. 

If number is near 1000, then there will be 3 digits in the first part. 
{{% /alert %}}

For example, to find $102^3$, we will write it as $(100 + 2)^3$:
* 1st part will have 2 digits: write down $a^3$, i.e. $2^3$ = 8. But as 1st part need to have 2 digits, we will write it as 08.  
* 2nd part will have 2 digits: write down $a^2 × 3$, i.e. $2^2 × 3$ = 12
* 3rd part: 100 + $a × 3$, i.e. 100 + $2 × 3$ = 100 + 6 = 106

So, we get: 106 | 12 | 08 <br>
So, $102^3$ = 1061208

Let's see one more example. 

To find $108^3$, we will write it as $(100 + 8)^3$:
* 1st part will have 2 digits: write down $a^3$, i.e. $8^3$ = 512 
* 2nd part will have 2 digits: write down $a^2 × 3$, i.e. $8^2 × 3$ = 192
* 3rd part: 100 + $a × 3$, i.e. 100 + $8 × 3$ = 100 + 24 = 124

So, we get: 124 | 192 | 512 

But 1st part can only have 2 digits. So, we will keep 12 and carry 5 to the left. <br>
So, we get: 124 | 197 | 12

But 2nd part can only have 2 digits. So, we will keep 97 and carry 1 to the left. <br>
So, we get: 125 | 97 | 12

So, $108^3$ = 1259712

#### Cubes of numbers a little below 100

Divide the number in two parts: For example, we can write 92 as (100 - 8). 

For the sake of generalization, we can take the number to be 10a, i.e. 100 - a

The cube of this number can be found in three parts: 3rd part | 2nd part | 1st part
* 1st part will have 2 digits: write down $(-a)^3$. As (-a) is a negative number, $(-a)^3$ will be negative too. So, we will make it positive. (For this, we will take 100, 200, 300 etc. from 2nd part.)
* 2nd part will have 2 digits: write down $a^2 × 3 - x$ (x = 1 if we gave 100 to 1st part, x = 2 if we gave 200 to 1st part, etc.)
* 3rd part: 100 - $a × 3$

For example, to find $98^3$, we will write it as $(100 - 2)^3$:
* 1st part will have 2 digits: 100 - $2^3$ = 100 - 8 = 92
* 2nd part will have 2 digits: $2^2 × 3 - 1$ = 12 - 1 = 11
* 3rd part: 100 - $2 × 3$ = 100 - 6 = 94

So, we get: 94 | 11 | 92 <br>
So, $98^3$ = 941192

Let's see one more example. 

To find $92^3$, we will write it as $(100 - 8)^3$:
* 1st part will have 2 digits: 600 - $8^3$ = 600 - 512 = 88
* 2nd part will have 2 digits: $8^2 × 3 - 6$ = 192 - 6 = 186
* 3rd part: 100 - $8 × 3$ = 100 - 24 = 76

So, we get: 76 | 186 | 88 

But 2nd part can only have 2 digits. So, we will keep 86 and carry 1 to the left. <br>
So, we get: 77 | 86 | 88

So, $98^3$ = 778688

{{% alert note %}}
Ideally, you should learn squares till 30, and cubes till 12. 

A couple of tables have been given below for your reference:
<img src="../../../media/simplification/simplification-11.png" alt="Simplification" style="width:54%;height:54%;">
<img src="../../../media/simplification/simplification-12.png" alt="Simplification" style="width:54%;height:54%;">
{{% /alert %}}
