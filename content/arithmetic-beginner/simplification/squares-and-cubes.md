---
title: Finding Squares and Cubes
linktitle: Finding Squares and Cubes 
toc: true
type: docs
date: "2021-07-17T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 1. Simplification
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

###  Even and Odd roots

If to get the given expression/number, we have to multiply the root by itself even number of times, then it is called an ***even root***, e.g. square root. <br>
For example, $\sqrt{3} × \sqrt{3}$ = 3 (root has to be multiplied 2 times)<br>
Only positive quantities can have an even root (not negative quantities). An even root may be positive or negative.  

If to get the given expression/number, we have to multiply the root by itself odd number of times, then it is called an ***odd root***, e.g. cube root. <br >
For example, $\sqrt[3]{2} × \sqrt[3]{2} × \sqrt[3]{2}$ = 2 (root has to be multiplied 3 times) <br>
Any quantity can have an odd root (i.e. both positive and negative quantities). An odd root may be positive or negative; it will have the same sign as that of the quantity.  

## Squares and Cubes

To find the square of a number, we just multiply the number with itself 2 times. For example, $5^2 = 5 × 5 = 25$

To find the cube of a number, we just multiply the number with itself 3 times. For example, $5^3 = 5 × 5 × 5 = 125$


## Square Root 

If square root of an expression/number x is r, then we can write it as:
* r = $\sqrt{x}$, or
* x = $r^2$

Every positive real number has two square roots:
* positive square root (or principal square root), e.g. $\sqrt{9}$ = 3
* negative square root, e.g. $\sqrt{9}$ = -3

So, in general, we write the square root of a positive real number with a preceding ± sign. For example, $\sqrt{9}$ = ±3

{{% alert note %}}
Zero has only one square root, 0 itself. 
{{% /alert %}}

Negative real numbers also have two square roots. Fo example, square roots of -9 are 3i and -3i, where i = $\sqrt{-1}$

### How to find Square Root of a number? 

Let's learn how to find square roots of various kinds of numbers. We have divided the numbers in two categories for this purpose:
* Perfect Square Numbers, e.g. 25, 36 etc. 
* Other Numbers

We can utilize multiple methods to find square root of a number. Let's learn a few of them. 

{{% alert note %}}
Learn squares of all numbers from 1 to 30. It will help you a lot in aptitude exams. 
{{% /alert %}}

##### Using Square Root Division Method

We can use this method to find the square roots of any number (perfect squares or not). Let's understand the steps involved in this method using an example. 

Let's find out the square root of 29,320.

***Step 1***: We will divide the dividend (i.e. 29,320) in a group of two digits, starting from the units digit, i.e. from the right hand side. If the number of digits are odd (as is the case with 29,320), then the extreme left block will have only one digit. So, our dividend will look like this:
<img src="../../../media/simplification/simplification-1.png" alt="Simplification" style="width:18%;height:18%;">

{{% alert note %}}
In case we were finding the square root of a decimal number, say 29320.348, then the process of making blocks of two numbers will start from the decimal point, to the left, as well as to the right. 

On the right side, we can always add a 0 to make a pair of digits, without changing the value of the given number. 

So, our dividend will look like this:
<img src="../../../media/simplification/simplification-7.png" alt="Simplification" style="width:36%;height:36%;">
{{% /alert %}}

***Step 2***: So, we know the dividend. But what about divisor? 

In Square Root Division Method we have to drive our divisor in each step. That is, it will keep on changing. 

For the first step of our calculation, we will consider the leftmost block of digits in our dividend, i.e. 2. Our divisor for this step will be the integral part of the square root of 2. We know that 2 falls between 1 and 4. So, it's square root must be 1.something. It's integral part is 1, which will be our first divisor. 

We will write this in place of the divisor, and also on top of the horizontal line as quotient. It has been shown in the figure below:
<img src="../../../media/simplification/simplification-2.png" alt="Simplification" style="width:27%;height:27%;">

{{% alert note %}}
Eventually, at the end of all the steps, the number above the horizontal bar will be our required square root. 
{{% /alert %}}

***Step 3***: Now, multiply this number with itslf, and subtract it from the leftmost block of numbers. 

So, we get 2 - (1 × 1) = 2 - 1 = 1

Thereafter, bring down the next block of two digits to get the new dividend, 193. 
<img src="../../../media/simplification/simplification-3.png" alt="Simplification" style="width:27%;height:27%;">

***Step 4***: So, we know the new dividend. But what about the new divisor?

The new divisor will have two parts:
* The first part can be drived by adding the divisor of the last step to its unit digit. In our case, it will be 1 (last divisor) + 1 (unit digit of last divisor) = 2
* Let the second part of the divisor be x. So, our new divisor will be 2x. Now, find such a value of the digit x, such that (2x) × x is the greatest possible number that is less than or equal to the new dividend. 

In our case, if we put x = 7, then 27 × 7 = 189 (which is less than 193); while 28 × 8 = 224 (which is more than 193). So, our new divisor is 27. We will place this new value of x (i.e. 7) at the top of the horizontal bar too. 

Now, substract this product from the dividend, i.e. 193 - 189 = 4

Thereafter, bring down the next block of two digits to get the new dividend, 420. 
<img src="../../../media/simplification/simplification-4.png" alt="Simplification" style="width:27%;height:27%;">

***Step 5***: So, we know the new dividend. But what about the new divisor?

The process that we followed in the above step should be followed again. 

The new divisor will have two parts:
* The first part can be drived by adding the divisor of the last step to its unit digit. In our case, it will be 27 (last divisor) + 7 (unit digit of last divisor) = 34
* Let the second part of the divisor be x. So, our new divisor will be 34x. Now, find such a value of the digit x, such that (34x) × x is the greatest possible number that is less than or equal to the new dividend. 

In our case, if we put x = 1, then 341 × 1 = 341 (which is less than 420); while 342 × 2 = 684 (which is more than 420). So, our new divisor is 341. We will place this new value of x (i.e. 1) at the top of the horizontal bar too. 

Now, substract this product from the dividend, i.e. 420 - 341 = 79

{{% alert note %}}
If our number 29,320 would have been a perfect square, then we would have got 0 as remainder in this step. That is, in case of perfect squares, when there will be no more digits left to be brought down, we will get a remainder of 0.

However, as we got a remainder here, it means that our required square root must have a decimal component. 
{{% /alert %}}

Thereafter, bring down the next block of two digits to get the new dividend. As, no numbers are left, we will put a decimal point in the quotient, and add two zeroes to 79 to get the new dividend, 7900. 
<img src="../../../media/simplification/simplification-5.png" alt="Simplification" style="width:27%;height:27%;">

{{% alert note %}}
In case we were finding the square root of a decimal number, say 29320.348, then we would have brought down the next block of two digits (written after the decimal point). 
{{% /alert %}}

***Step 6***: So, we know the new dividend. But what about the new divisor?

The process that we followed in the above step should be followed again. 

The new divisor will have two parts:
* The first part can be drived by adding the divisor of the last step to its unit digit. In our case, it will be 341 (last divisor) + 1 (unit digit of last divisor) = 342
* Let the second part of the divisor be x. So, our new divisor will be 342x. Now, find such a value of the digit x, such that (342x) × x is the greatest possible number that is less than or equal to the new dividend. 

In our case, if we put x = 2, then 3422 × 2 = 6844 (which is less than 7900); while 3423 × 3 = 10269 (which is more than 7900). So, our new divisor is 3422. We will place this new value of x (i.e. 2) at the top of the horizontal bar too. 

Now, substract this product from the dividend, i.e. 7900 - 6844 = 1056

Thereafter, add two zeroes to 1056 to get the new dividend, 105600. 
<img src="../../../media/simplification/simplification-6.png" alt="Simplification" style="width:27%;height:27%;">

{{% alert note %}}
We can continue this process to get more and more precise values of the required square root (written on the top of the topmost horizontal bar).
{{% /alert %}}


##### Hit and Try Method

Make a rough estimate of the square root of a number, and check if your estimate is true by multiplying that number by itself. Make adequate corrections if the resulting number is less/more than the given number. 

This method works fine for smaller numbers. Let's see a few examples. 

Say, we have to find the square root of 529. Now, we already know that $20^2$ = 400, and $25^2$ = 625. So, the required number must be more than 20, but less than 25. 529 seems closer to 625 than 400. So, our required root must be closer to 25 than 20. Let's check $23^2$ - it's value is 529. Bingo!

{{% alert note %}}
As the last digit of 529 is 9, we could easily have guessed that it must be a square of a number whose last digit is 3 (because 3 × 3 = 9).
{{% /alert %}}

We can also use the above method to find approximate square root values of numbers that are not perfect squares. 


## Cube Root 

If cube root of an expression/number x is r, then we can write it as:
* r = $\sqrt[3]{x}$, or
* x = $r^3$

Every real number (positive or negative) has three cube roots:
* one real cube root, e.g. $\sqrt[3]{27}$ = 3 (because $3^3$ = 27), and $\sqrt[3]{-27}$ = -3 (because $-3^3$ = -27)
* two complex cube roots, e.g. apart from the real cube root 1, the number 1 has two complex cube roots too → $(-\frac{1}{2} + i\frac{\sqrt{3}}{2})$ and $(-\frac{1}{2} - i\frac{\sqrt{3}}{2})$

{{% alert note %}}
Zero has only one cube root, 0 itself. 
{{% /alert %}}
