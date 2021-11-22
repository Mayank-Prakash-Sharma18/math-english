---
title: Factorial
linktitle: Factorial
toc: true
type: docs
date: "2021-02-21T00:00:00+01:00"
draft: false
menu:
  number-system:
    parent: 1. Number System
    weight: 18

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 18
---

## What is a Factorial? 

It is the product of some natural numbers starting from 1.

We use the symbol '!' (Exclamatory sign) to denote a factorial.

n! = 1 × 2 × 3 ×....× (n−2) × (n−1) × n

E.g. 5! = 1 × 2 × 3 × 4 × 5 = 120

{{% alert note %}}
0! = 1 & 1! = 1
{{% /alert %}}

## Largest power of a prime in N!

There are two methods that we can use to find the largest power of a prime in N!

* Factorization method

* Long division method

### Factorization method

We can expand a factorial and find the highest power of a prime number.

Example: Find the largest power of 2 in 6!? <br>
6! = 1 × 2 × 3 × 4 × 5 × 6 = $2^4$ × $3^2$ × 5 <br>
∴ the largest power of 2 in 6! is 4.

{{% alert note %}}
This method works fine for small factorials. For large factorial values, this method is not easy to apply. So we use an alternate method – long division method.
{{% /alert %}}

### Long division method

Here we perform a long division of the number using the prime factor specified. That is, we will divide the given number with the given prime number and add all the quotients in all steps. 

Let us understand using an example. <br>
Find the largest power of 3 in 24!  <br>
* Step 1: Quotient (24/3) = 8 
* Step 2: Quotient (8/3) = 2 <br>

Largest power of 3 in 24! = sum of all quotient in all steps = 8 + 2 = 10

Let us double check it. The powers of 3 in 24! can be found in these factors of 24!:
3, 6, 9, 12, 15, 18, 21, 24  (9 and 18 account for 2 powers of 3 each)

{{% alert note %}}
We can also write the above method as follows:

Largest power of 3 in 24! = $[\frac{24}{3}] + [\frac{24}{3^2}] = 8 + 2 = 10$
{{% /alert %}}


##### Q. Find the largest power of 7 in $C^{50}_{25}$.

Explanation:<br>
<div class="Exp">

$C^{50}_{25} = \frac{50!}{25! \hspace{1ex} 25!}$

Largest power of 7 in 50! = $[\frac{50}{7}] + [\frac{50}{7^2}] = 7 + 1 = 8$

Largest power of 7 in 25! = $[\frac{25}{7}] = 3$

So, Largest power of 7 in $C^{50}_{25}$ = 8 - (2 × 3) = 8 - 6 = 2
</div> <br>


## Largest power of a composite number in N!

To find the largest power of a composite number in N!, we need to factorize it into prime factors and then find the largest power of that prime factor which is in least supply (generally the largest prime factor is in least supply). 

Let us understand it using an example. 

Find the largest power of 6 in 24! <br>
6 = 3 × 2; <br><br>
Largest power of 2 in 24! = 12 + 6 + 3 + 1 = 22 <br>
Largest power of 3 in 24! = 8 + 2 = 10 <br><br>
As we need both 3 and 2 to form 6, and the power of 3 are in less supply, so the largest power of 6 in 24! will depend on the largest power of 3 in 24!  <br>
So the largest power of 6 in 24! is 10.

{{% alert note %}}
Generally the largest prime factor is in less supply (e.g. 3 in above example), but it’s not always the case.
{{% /alert %}}

<br><hr><br>

## Number of Zeroes at the end of N!

N! is basically the product of first 'n' natural numbers.

A 'zero' at the end will get generated as per the combination of 2 and 5. In any factorial, the number of 5’s will always be less than the number of 2’s and so the number of 5’s will determine the number of zeroes at the end. 

How many zeros at the end of 24! ? <br>
Largest power of 5 in 26! = 5 + 1 = 6 <br>
So, there will be 6 zeros at the end of 26!

{{% alert note %}}
In some complex factorial expressions the number of 2’s may be less than the number of 5’s. In such a case the number of 2’s will determine the number of zeroes at the end. 

So, we should keep the following in mind:

* In a factorial: <br>
In any factorial value, the number of 5’s will always be less than the number of 2’s. Hence, all we need to do is to count the number of 5’s.

* In a product: <br>
Anyone of 2 or 5 can be less, depending on the numbers that are being multiplied. Whichever of them is less, will determine the number of zeroes at the end of the product. 
{{% /alert %}}
