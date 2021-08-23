---
title: Measures of Central tendency in Statistics
linktitle: Measures of Central tendency 
toc: true
type: docs
date: "2021-08-19T00:00:00+01:00"
draft: false
menu:
  statistics:
    parent: 1. Statistics
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

## What is Measures of Central tendency in Statistics?

Measures of Central tendency refer to a value in the given data, that is somehow the centre point of that data set. 

We can use various tools to find out the central point in a data set:
* Mean - Arithmetic mean, Geometric mean, Harmonic mean
* Median
* Mode

{{% alert note %}}
If only 'Mean' is written, then it means 'Arithmetic Mean'. 
{{% /alert %}}

Now, let us study these tools in more detail. 


## Arithmetic Mean

Arithmetic Mean is also know as the Mean or the Average.

It is obtained by dividing the sum of observations by the number of observations. 

Arithmetic Mean = $\frac{Sum \hspace{1ex} of \hspace{1ex} observations}{Number \hspace{1ex} of \hspace{1ex} observations}$ 

{{% alert note %}}
To learn more about Arithmetic Mean, you may refer to our module on Averages. 
{{% /alert %}}

### Formulae for calculating the Mean / Average

#### In case of Ungrouped data

To find the mean of n numbers, $x_1, x_2, x_3, ..... , x_n$, we can use the following formula:

Arithmetic Mean = $\frac{x_1 + x_2 + x_3 + ..... + x_n}{n}$

##### Q. What is the Arithmetic mean of 3, 4, 5, 6, 7, and 8?

Explanation:<br>
<div class="Exp">

Arithmetic Mean = $\frac{3 + 4 + 5 + 6 + 7 + 8}{6}$ = $\frac{33}{6}$ = 5.5
</div> <br>

#### In case of Grouped data

If $x_1, x_2, x_3, ..... , x_n$ are numbers with respective frequencies of $f_1, f_2, f_3, ..... , f_n$, then it means number $x_1$ occurs $f_1$ times, $x_2$ occurs $f_2$ times, and so on. 

So, the sum of the values of all the numbers/observations = $f_1 x_1 + f_2 x_2 + ..... + f_n x_n$ 

Number of observations (i.e. Sum of all frequencies) = $f_1 + f_2 + ..... + f_n$.

Arithmetic Mean = $\frac{f_1 x_1 + f_2 x_2 + ..... + f_n x_n}{f_1 + f_2 + ..... + f_n}$


## Geometric Mean

Geometric mean is a tool that uses product of the data values to showcase their central tendency. Geometric mean is the $n^{th}$ root of their product. 

To find the geometric mean of n numbers, $x_1, x_2, x_3, ..... , x_n$, we can use the following formula:

Geometric Mean = $\sqrt[n]{x_1 × x_2 × x_3 × ..... × x_n}$

##### Q. What is the Geometric mean of 3, 4, and 18?

Explanation:<br>
<div class="Exp">

Geometric Mean = $\sqrt[3]{3 × 4 × 18}$ = $\sqrt[3]{3^3 × 2^3}$ = 3 × 2 = 6
</div> <br>


## Harmonic Mean

Harmonic mean is the reciprocal of the Arithmetic mean of the reciprocals of given numbers. 

To find the geometric mean of n numbers, $x_1, x_2, x_3, ..... , x_n$, we can use the following formula:

Harmonic Mean = $\frac{n}{\frac{1}{x_1} + \frac{1}{x_2} + \frac{1}{x_3} + ... + \frac{1}{x_n}}$

##### Q. What is the Harmonic mean of 1, 1/2, and 1/3?

Explanation:<br>
<div class="Exp">

Harmonic Mean = $\frac{n}{\frac{1}{x_1} + \frac{1}{x_2} + \frac{1}{x_3} + ... + \frac{1}{x_n}}$ = $\frac{3}{1 + 2 + 3}$ = $\frac{3}{6}$ = $\frac{1}{2}$
</div> <br>

### Relation between Arithmetic, Geometric and Harmonic means

If arithmetic, geometric and harmonic means of any two numbers are A, G and H respectively, then:
* A ≥ G ≥ H
* A, G, H are in GP, i.e. $A.H = G^2$


## Median 

Median is the middle value of a data set, when the numbers/observations are arranged in ascending or descending order.

{{% alert note %}}
To find out the median, we must arrange the given data in some order, whether ascending or descending. 
{{% /alert %}}

### Formulae for calculating Median

#### In case of Ungrouped data

##### Number of data is odd

If we are given n numbers, where n is odd, then the number at the middle will be the median.

That is, Median will be the $\frac{n + 1}{2}^{th}$ observation

##### Q. Find the median of {2, 7, 1, 0, and 9}.

Explanation:<br>
<div class="Exp">

Arranging the elements of the given set in ascending order, we get {0, 1, 2, 7, 9}

Median will be the $\frac{n + 1}{2}^{th}$ observation, i.e. $\frac{5 + 1}{2}^{th}$ = $3^{rd}$ observation (i.e. the middle term)

So, 2 is the median of the given set.
</div> <br>

##### Number of data is even

If we are given n numbers, where n is even, then there will be two numbers at the middle.

Then, Median will be the mean of $\frac{n}{2}^{th}$ and $(\frac{n}{2} + 1)^{th}$ observations

##### Q. Find the median of {2, 7, 1, 0, 6, and 9}.

Explanation:<br>
<div class="Exp">

Arranging the elements of the given set in ascending order, we get {0, 1, 2, 6, 7, 9}

Median will be the mean of $\frac{n}{2}^{th}$ and $(\frac{n}{2} + 1)^{th}$ observations, i.e. $\frac{6}{2}^{th}$ and $(\frac{6}{2} + 1)^{th}$ observations, i.e $3^{rd}$ and $4^{th}$ observations (i.e. the mean of the two middle terms)

So, the median of the given set = $\frac{2 + 6}{2}$ = 4.
</div> <br>

#### In case of Grouped data

If the data is given in form of classes, then:

Median = L + $(\frac{\frac{n}{2} - C.F.}{f})$ × h 

L - lower limit of the median class <br>
h - Size of the median class (i.e. upper limit - lower limit) <br>
f - frequency of the median class <br>
C.F. - Cumulative Frequency of class preceding the median class <br>
n - total frequency


## Mode 

In case of ungrouped data, its mode is the number/observation which occurs the maximum number of times. 

In case of grouped data, its mode is the number/observation which has the highest frequency.

### Formulae for calculating Mode

#### In case of Ungrouped data

It's pretty easy to find the mode in case of ungrouped data. Just look out for the number that occurs the maximum number of times. 

For example, mode of the data set {1, 4, 3, 6, 7, 3, 4, 6, 3, 5, 8, 3} will be 3, as it has occurred four times, more than any other number. 

#### In case of Grouped data

Mode = L + $(\frac{f - f_p}{2f - f_p - f_s})$ × h 

L = lower limit of modal class <br>
h = size of class interval (assuming all class sizes to be equal) <br>
$f$ = frequency of the modal class <br>
$f_p$ = frequency of the class preceding the modal class <br>
$f_s$ = frequency of the class succeeding the modal class


{{% alert note %}}
A set of data may have:
* one mode - e.g. 1, 3, 5, 6, 4, 6. It has one mode, i.e. 6. 
* more than one mode - e.g. 1, 3, 5, 6, 4, 6, 1. It has two modes, i.e. 1 and 6.
* no mode at all - e.g. 2, 2, 2, 2, 2, 2. It has no mode 
{{% /alert %}}


## Relation between Mean, Median and Mode

* Arithmetic mean is the ***average*** of the numbers in a data set.

* Mode is the ***most common number*** in a data set.

* Median is the ***middle*** of the set of numbers in a data set (when they are arranged in ascending or descending order)

### Empirical relationship

Mode = 3 Median – 2 Mean

### Relation between Arithmetic Mean and Median 

When data in a set is evenly distributed, i.e. the difference between any two consecutive elements of the set is equal (e.g. in case of arithmetic progressions), then Median = Arithmetic Mean

For example, consider the numbers 3, 5, 7, 9, 11 <br>
Difference between any two elements in the above set is 2. So, their median and mean must be equal. Let's check.<br>
Mean = (3 + 5 + 7 + 9 + 11)/5 = 35/7 = 7 <br>
Median = the middle value, which is 7. 


## Skewness

Before we understand skewness in data distribution, we need to understand normal or non-skewed data distribution. 

### What is a Symmetric distribution?

Symmetric distribution is also called Normal distribution or Zero-skewed distribution.

In a Symmetric distribution, the left side of the distribution mirrors the right side, i.e. the distribution of data shows zero skewness. Have a look at the figure given below:
<img src="../../../media/statistics/statistics-5.png" alt="Statistics" style="width:36%;height:36%;">

As you can see, in a symmetric distribution, the mean, median, and mode coincide with each other. That is, Mean = Median = Mode

### What is an Asymmetric distribution?

Skewness is an asymmetry in a statistical distribution, in which the curve appears distorted or skewed either:
* to the left, or 
* to the right.

So, we have two types of Asymmetric distributions. 
* Left skewed distribution or Negative skewed distribution
* Right skewed distribution or Positive skewed distribution

#### Left skewed distribution

Left skewed distribution is also known as Negative skewed distribution. 

A left-skewed distribution has a long left tail, i.e. a long tail in the negative direction on the number line. The right tail is shorter. 

This skewed distribution occurs because most of the data values fall on the right side of the negatively skewed distribution curve.

Have a look at the figure given below:
<img src="../../../media/statistics/statistics-6.png" alt="Statistics" style="width:90%;height:90%;">

As you can see, here both the mean and median are less than the mode, and in general, the mean is also  less than the median. That is, Mean < Median < Mode

#### Right skewed distribution

Right skewed distribution is also known as Positive skewed distribution. 

A right-skewed distribution has a long right tail, i.e. a long tail in the positive direction on the number line. The left tail is shorter. 

This skewed distribution occurs because most of the data values fall on the left side of the positively skewed distribution curve.

Have a look at the figure given below:
<img src="../../../media/statistics/statistics-7.png" alt="Statistics" style="width:90%;height:90%;">

As you can see, here both the mean and median are more than the mode, and in general, the mean is also  more than the median. That is, Mean > Median > Mode

{{% alert note %}}
You are more likely to encounter positively skewed distributions, as they are more common than negatively skewed ones.
{{% /alert %}}

### Pearson's Coefficient of Skewness 

Pearson's Coefficient of Skewness is used to determine whether a distribution is positively skewed or negatively skewed. 

Pearson's Coefficient of Skewness = $\frac{Mean \hspace{1ex} - \hspace{1ex} Mode}{Standard \hspace{1ex} deviation}$

If the value of Pearson's Coefficient of Skewness is:

* Zero - it means no skewness at all, i.e. Normal distribution or Zero-skewed distribution.

* Negative value - it means the distribution is negatively skewed - one of the reasons why such a distribution is called Negative skewed distribution. That's because, in Negative skewed distribution Mean < Mode. 

* Positive value - it means the distribution is positively skewed - one of the reasons why such a distribution is called Positive skewed distribution. That's because, in Positive skewed distribution Mean > Mode.

