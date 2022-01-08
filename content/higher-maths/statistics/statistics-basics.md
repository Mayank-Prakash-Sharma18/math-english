---
title: Basics of Statistics
linktitle: Basics of Statistics 
toc: true
type: docs
date: "2021-08-16T00:00:00+01:00"
draft: false
menu:
  statistics:
    parent: 1. Statistics
    weight: 3

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 3
---

## What is Statistics?

Statistics is a science which involves 3 broad steps:
* ***Collecting Statistical data*** - Collecting large amount of numerical data from a representative sample of the target population.
* ***Analysing Statistical data*** - Analysing that numerical data, to convert it into usable information.
* Inferring things about the whole target population, from the information we extracted out of the sample. 

<img src="../../../media/statistics/statistics-1.png" alt="Statistics" style="width:99%;height:99%;">

Statistical data are basically the ***facts*** that we collect from a sample of the target population. For example, in exit polls after elections some voters are asked certain questions, e.g. whom they vote, what is the most important national/state issue for them, etc. 

If our data collection is faulty, then any inference we draw on the basis of its analysis will be wrong too. 

{{% alert note %}}
***Population*** - It is the target group about which we want to conduct a statistical study and from which we aim to collect the data. 

For example, a group of people, amount of rainfall in an area, solar radiation patterns etc. 

The size of the population (i.e. the total number of objects or individuals in a population) may be finite or infinite. 

***Sample*** - This is the part of population that represents all the characteristics of the target population, and which has been chosen for the purpose of statistical study via a process of sampling. 

Most of the times the target population is so big that we cannot study each and every element/person. That's why we take a sample out of it, and then after studying it we try to infer things about the whole target population. 
{{% /alert %}}


## Branches of Statistics

There are two branches of Statistics:

* ***Descriptive statistics*** - It is the summary of certain data. It serves the purpose of giving an overview of the data under analysis. For example, if you want to know how a student is in Maths, you may have a look at the average of the marks scored by him in the last 10 maths tests. <br><br>
We use various tables, charts and graphs to showcase the results. 

* ***Inferential statistics*** - It is a statistical method that helps us deduce characteristics of a bigger target population, by just analysing a small but representative sample. For example, an actuary in a life insurance company deduces the life expectancy of a person with heart problems and then decides what premium such people should pay for their life insurance policy. For this purpose, he analyses the data of only a few heart patients, and then make assumptions (i.e. generalizes or draw conclusions) regarding the whole target population. <br><br>
Here, our goal is to predict the future. We get probability scores at the end of the analysis. 


{{% alert note %}}
### Tools of Descriptive Statistics

There are two general types of descriptive statistics tools that are used to analyze and describe data:
* Measures of Central tendency - e.g. mean, median, mode. 
* Measures of Dispersion or Spread - e.g. range, quartile deviation, mean deviation and absolute deviation, variance, standard deviation.

We will study these in much more detail in separate articles. 

### Tools of Inferential Statistics

In Inferential Statistics, we make use of tools such as, hypothesis tests, analysis of variance etc.
{{% /alert %}}


## Types of Statistical data

Now, let's see the various types of data that we may encounter. Data may be categorized based on various parameters. 

### Based on Source

Based on the source from where we got the data, we can divide it into primary and secondary data.

* ***Primary Data*** - It's a data collected first-hand by an investigator for his own purpose. For example, the data collected by various news channel agencies during exit poll. This kind of data is considered more reliable and relevant. 

* ***Secondary Data*** - As the name suggests, when an investigator uses data that were collected by someone else earlier, then it's referred to as secondary data. So, primary data, when used by someone else, is referred to as secondary data. For example, sometimes poll of many exit polls is done, i.e. all the various exit polls are anlaysed and a single exit poll on that basis is derived. 

Collecting primary data is a labour and time intensive excercise. Sometimes, collecting primary data may not even be possible, even if one wants too. For example, if someone is conducting a study on World War - I, then he/she will obviously have to rely on old data. 

Data may also be categorized based on whether it has been grouped or not. 

* ***Raw or Ungrouped Data*** - It is the data that has not been arranged at all. For example, marks of 8 students in a test - 34, 56, 81, 23, 81, 56, 45, 91

* ***Grouped Data*** - When the raw data collected is arranged in groups/categories, then it is called Grouped data. For example, the marks of 8 students in a test - 34, 56, 81, 23, 81, 56, 45, 91, can be bundled together in certain groups and displayed as follows:

<table>
  <tr>
    <th>Marks obtained</th>
    <th>23</th>
    <th>34</th>
    <th>45</th>
    <th>56</th>
    <th>81</th>
    <th>91</th>
  </tr>
  <tr>
    <td>Number of students</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>2</td>
    <td>2</td>
    <td>1</td>
  </tr>
</table>


## Classes in Statistics 

Sometimes we divide the data into various groups, with each group covering a certain range. These groups are called classes. 

There are a few keywords related to classes in statistics that you will encounter pretty often. So, it would be a good idea to get acquainted with them firsthand. 

### Class Interval

When we divide the given data into groups, then each group covers a certain range of values. This range is called the class interval. 

For example, consider the table given below, which showcases various classes of marks attained by students in a test:
<img src="../../../media/statistics/statistics-2.png" alt="Statistics" style="width:99%;height:99%;">

The various class-intervals in which we have distributed the data are: 10-25, 25-40, 40-55, 55-70, 70-85, 85-100. 

Each class interval has:
* ***Class Limits*** - Every class-interval has two limits - lower and upper. For example, for the class interval 40-55, the lower limit is 40 and the upper limit is 55. 

* ***Class Size*** - This is the difference between the lower and upper limits of a class interval. For example, the class size of 40-55 is 55 - 40 = 15. 

* ***Class Mark*** - This is a point inside a class-interval that can represent the whole class. As in general, we can assume that data within a class would probably be centred around the mid-point, so mid-point of any class may be chosen to represent the data falling within a class. So, the mid-point of a class may be taken as its class mark. <br><br>
That is, Class Mark = $\frac{Lower \hspace{1ex} limit \hspace{1ex} of \hspace{1ex} Class \hspace{1ex} + \hspace{1ex} Upper \hspace{1ex} limit \hspace{1ex} of \hspace{1ex} Class}{2}$<br>
For example, for the class interval 40-55, the class mark will be (40 + 55)/2 = 95/2 = 47.5 

* ***Class Frequency*** - Frequency (or absolute frequency) of a class is the number of times that observation ocurred or the number of data points within that class-interval. For example, for the class interval 40-55, the class frequency is 7. That is, 7 students got marks in that range. 

{{% alert note %}}
A concept related to class frequency is ***Cumulative Frequency***. 

The cumulative frequency of any class is obtained by adding all the frequencies successively prior to that class. That is, it is the sum of all frequencies up to that class. 

For example, if we want to find out the number of students who got 55 or less marks, we can add the frequencies of all classes till the 55 mark. In our table it will be 2 + 4 + 7 = 13. 

We can showcase the table having cumulative frequencies of classes, just as we did with class frequencies. So, the table given above can also be represented as:
<img src="../../../media/statistics/statistics-3.png" alt="Statistics" style="width:99%;height:99%;">
{{% /alert %}}

### Inclusive and Exclusive distributions

#### Exclusive Distribution

In this type of distribution, the upper limit of the preceding class coincides with the lower limit of the subsequent class. For example, have a look at the table given below:
<img src="../../../media/statistics/statistics-2.png" alt="Statistics" style="width:99%;height:99%;">

In exclusive classes, the upper and lower limit of a class are known as its true upper limit and true lower limit respectively.

#### Inclusive Distribution

In this type of distribution, the upper limit of the preceding class does not coincide with the lower limit of the subsequent class. For example, have a look at the table given below:
<img src="../../../media/statistics/statistics-4.png" alt="Statistics" style="width:99%;height:99%;">

In inclusive classes, the true lower and upper limits of a class are obtained by:
* subtracting 0.5 from the lower limit, and
* adding 0.5 to the upper limit.

{{% alert note %}}
##### True Class Limit 

True upper limits and true lower limits of a class are also known as boundaries of the class.
{{% /alert %}}


## Graphical representation of data

While we can almost always use data tables to represent a data, ungrouped or grouped. It does not help us much in visualization. 

But luckily, a given data can always be represented in graphical way(s). 

For ungrouped data or solitary data points, we often use Line charts and Scatter charts. 

As far as grouped data, or frequency distribution is concerned, there are various methods for its graphical representation. 

* Bar Graphs - for frequency distribution of a discrete value. The bars in a bar chart are kept distinct to show that the variate-values are distinct. The height of the bars is proportional to the frequency of each variate-value. 

* Pie charts - Just like bar graph, it is also used for frequency distribution of a discrete value. It uses slices to illustrate numerical proportion. So, here frequencies are showcased in percentage terms. Size of slices is proportional to the frequency of each variate-value. 

* Histograms - It is used to represent a grouped frequency distribution with continuous classes. Unlike a bar graph, here there is no gap between bars. The height of the bars is proportional to their class frequencies (if class intervals are equal). 

* Frequency Polygons - It is also a graph of frequency distribution. We can draw frequency polygons either by using histograms or without them. 

* Cumulative frequency curve or Ogive - It is used to showcase cumulative frequency distribution of grouped data. 

