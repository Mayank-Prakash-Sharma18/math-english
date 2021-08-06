---
title: Fast Multiplication
linktitle: Fast Multiplication 
toc: true
type: docs
date: "2021-07-31T00:00:00+01:00"
draft: false
menu:
  simplification:
    parent: 1. Fast Calculation
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

In aptitude examination, we need to save time and be quick in our calculations. Multiplication is something that you will definitely have to do in any Aptitude or Maths exam. 

So, in this article we will explore some of the alternate methods that allow us to know the value of a product in a fast manner. We hope that you already know the basic traditional method of multiplication (where we start multiplying from the rightmost side, i.e. from unit digits and then work our way to the left hand side). 

## Trick Method

Are you one of those people who find it hard to remember all different numbers, e.g. tables. Let me tell you one secret of mine. I never remembered table in my school days. It was just too much to remember. 

What I did instead was that I evolved a new method. Though there's nothing very extraordinary in this method, and many other people use it too. 

In this method, we do not multiply, but rather add or subtract numbers. Afterall multiplication is just a faster way to do addition. 4 × 3 means that we need to add 4 three times (4 + 4 + 4), or add 3 four times (3 + 3 + 3 + 3). 

### Find multiples till 3

If a number is multiplied by 1, 2 or 3, then it is very easy to find the product. No rocket science here.

For example, 13 × 2 = 13 + 13 = 26 (add tens digit first then unit digits, i.e. 10 + 10 = 20, 3 + 3 = 6; So, 20 + 6 = 26)

17 × 3 = 51 (add tens digit first then unit digits, i.e. 10 + 10 + 10 = 30, 7 + 7 + 7 = 21; So, 30 + 21 = 51)

### Find multiples from 4 to 8

If a number is multiplied by 4, 5, 6, 7 or 8, then we will use a trick. 

The given number multiplied by 5 will form our hinge point. You can remember it for various numbers, or you can also calculate it easily. 

For example, 13 × 5 = (13 × 10)/2 = 130/2 = 65 <br>
11 × 5 = (11 × 10)/2 = 110/2 = 55

How can we use it to find other multiples of a number? 

Say, we need to find 13 × 4. It is nothing but (13 × 5) - 13 = 65 - 13 = 52 <br>
Similarly, 13 × 6 = (13 × 5) + 13 = 65 + 13 = 78

17 × 7 = (17 × 5) + (17 × 2) = 85 + 34 = 119 <br>
17 × 8 = (17 × 5) + (17 × 3) = 85 + 51 = 136  (we can also calculate it as 17 × 10 - 17 × 2 = 170 - 34 = 136)

37 × 6 = (37 × 5) + 37 = [(37 × 10)/2] + 37 = 370/2 + 37 = [300/2 + 70/2] + 37 = 150 + 35 + 37 = 150 + 35 + 35 + 2 = 150 + 70 + 2 = 220 + 2 = 222

All the above calculation needs to be done in your mind, not on paper. It is much faster when done mentally, than it seems on paper. 

### Find multiples from 9 to 13

If a number is multiplied by 9, 10, 11, 12 or 13, then we will use a similar trick. 

The given number multiplied by 10 will form our hinge point.  

For example, 13 × 9. It is nothing but (13 × 10) - 13 = 130 - 13 = 117 <br>
Similarly, 13 × 11 = (13 × 10) + 13 = 130 + 13 = 143

17 × 12 = (17 × 10) + (17 × 2) = 170 + 34 = 204 <br>
17 × 13 = (17 × 10) + (17 × 3) = 170 + 51 = 221  

37 × 11 = (37 × 10) + 37 = 370 + 37 = 407

We can find higher multiples of a number in a similar manner. For example, 44 × 31 = (44 × 30) + (44 × 1) = (440 + 440 + 440) + 44 = (400 + 400 + 400) + (40 + 40 + 40) + (40 + 4) = 1200 + 160 + 4 = 1364

{{% alert note %}}
For the sake of fast calculations, you should remember tables till 20. That is, tables of numbers from 2 to 20. You need to remember their 20 multiples (not just 10). It will boost your calculation speed a lot. 

For example, you should know what is 13 × 17, 11 × 13, 19 × 7 etc. 

However, if you cannot, or you are not very confident regarding your memory, then use the method mentioned above. I still use that method in many cases. A beauty of that method is that we can use it even for higher numbers, e.g. 23 × 31, 123 × 102 etc. 
{{% /alert %}}


## Specific Cases

### Multiplication of numbers near hundred

If the numbers being multiplied are near 100, then there's another fast method to find their product. 

Let our two numbers be 100 + a and 100 + b. Then our product can be found in two parts: 2nd part | 1st part
* 1st part will have 2 digits: a × b (if there are more than 2 digits, then we will carry it to the left)
* 2nd part: (100 + a) + b

For example, 102 × 106 = (100 + 2) × (100 + 6) 
* 1st part will have 2 digits: 2 × 6 = 12
* 2nd part: (100 + a) + b = 102 + 6 = 108 

So, our product will be 10812

113 × 109 = (100 + 13) × (100 + 9) 
* 1st part will have 2 digits: 13 × 9 = 117 (we will keep 17, and carry over 1 to the left)
* 2nd part: (100 + a) + b = 113 + 9 = 122 

So, our product will be 122 | 117 = 123 | 17 = 12317

What if the numbers are below 100? 

96 × 92 = (100 - 4) × (100 - 8) 
* 1st part will have 2 digits: (-4) × (-8) = 32
* 2nd part: (100 + a) + b = 96 + (-8) = 88 

So, our product will be 8832

87 × 91 = (100 - 13) × (100 - 9) 
* 1st part will have 2 digits: (-13) × (-9) = 117 (we will keep 17, and carry over 1 to the left)
* 2nd part: (100 + a) + b = 87 + (-9) = 78 

So, our product will be 78 | 117 = 79 | 17 = 7917

What if one of the number is above 100, and the other is below 100? 

104 × 92 = (100 + 4) × (100 - 8) 
* 1st part will have 2 digits: 4 × (-8) = -32 (we will make it positive by taking 100 from the left hand side)
* 2nd part: (100 + a) + b = 104 + (-8) = 96 

So, our product will be 96 | (-32) = 95 | (100 - 32) = 95 | 68 = 9568

What if the numbers are near 200 or 300? 

For example, 202 × 206 = (200 + 2) × (200 + 6) 
* 1st part will have 2 digits: 2 × 6 = 12
* 2nd part: n [(200 + a) + b] = 2 [202 + 6] = 2 × 208 = 416 (value of n will be 2, if numbers are close to 200, 3 if they are close to 300 and so on.) 

So, our product will be 41612


### Unit digits add upto 10 and Ten's digits are same 

If two 2-digit numbers being multiplied are such that:
* There ten's digit is the same, say t.
* The sum of their unit digits is 10, say a + b = 10. 

Then, their product will have two parts: 2nd part | 1st part

1st part (it will have 2 digits) = a × b <br>
2nd part = t (t + 1)

For example, 44 × 46 = 4 (4 + 1) | 4 × 6 = 4 × 5 | 4 × 6 = 20 | 24 = 2024 <br>
31 × 39 = 3 (3 + 1) | 1 × 9 = 3 × 4 | 1 × 9 = 12 | 09 = 1209


### Difference of the numbers is 10 and Unit digits are 5 

If two numbers being multiplied are such that:
* There unit's digit of both is 5. So, let the numbers be a5 and b5 
* The difference between the numbers is 10. 

Then, their product will have two parts: 2nd part | 1st part

1st part = 75 (it will always be 75) <br>
2nd part = a (a + 2), such that a ⩽ b

For example, 35 × 45 = 3 (3 + 2) | 75 = 3 × 5 | 75 = 15 | 75 = 1575


### Multiplication by a number close to 10, 100, 1000 

To multiply with such numbers, convert them into the form of (10 ± a), (100 ± a), (1000 ± a). 

For example, 43 × 98 = 43 × (100 – 2) = 43 × 100 – 43 × 2 = 4300 – 86 = 4214

### Multiplication by 5 or powers of 5

To multiply with 5 or powers of 5, convert them into 10 or powers of 10, and then divide by 2 or its powers. 

For example, 67 × 25 = 67 × $5^2$ = 67 × $(\frac{10}{2})^2$ = 67 × $\frac{100}{4}$ = $\frac{6700}{4}$ = 1675

