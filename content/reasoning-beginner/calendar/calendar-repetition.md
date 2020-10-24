---
title: Calendar Repetition
linktitle: Calendar Repetition
toc: true
type: docs
date: "2020-09-25T00:00:00+01:00"
draft: false
menu:
  calendar:
    parent: Calendar
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

## Basics

Two years have the same calendar when:

* 1st Jan of both the years falls on the same day, i.e. sum of odd days between the years is zero, and
* Both years are of the same type, i.e. both are leap years or both are non-leap years. 

Let's see some examples:

Total number of odd days between 2001 and 2007 = 1 + 1 + 1 + 2 + 1 + 1 = 7 = 0 odd days. <br>
So, 2007 will have the same calendar as that of 2001. <br>
(Years 2001, 2002, 2003, 2005 and 2006 are non-leap years and so have 1 odd day; 2004 is a leap year, so it has 2 odd days)<br>

{{% alert warning %}}
When we say odd days between 2001 and 2007, we mean odd days between 1st January, 2001 and 1st January, 2007. We will count 1st January, 2001 OR 1st January, 2007, not both. <br><br>
In our tutorial we always count the first day and not the last. <br><br>
So, here we have counted all days from 1st January, 2001 to 31st December, 2006, i.e. full years from 2001 to 2006.
{{% /alert %}}

Similarly, total number of odd days between 2002 and 2013 = 1 + 1 + 2 + 1 + 1 + 1 + 2 + 1 + 1 + 1 + 2 = 14 = 0 odd days. <br>
So, 2013 will have the same calendar as 2002. <br>
(Years 2002, 2003, 2005, 2006, 2007, 2009, 2010, 2011 are non-leap years and so have 1 odd day; 2004, 2008 and 2012 are leap years, so they have 2 odd days)<br><br>

## Some Tips

* A leap year calendar repeats in 28 years while the calendar of an ordinary year repeats after 6 or 11 years.

* Calendar of non-leap year just after a leap year (e.g. 2001) will be repeated in 6 years. For the next two non-leap years (e.g. 2002 & 2003) the repetition will be in 11 years. 

{{% alert warning %}}
Exceptions:<br><br>
In case if a century non-leap year (e.g. 1700, 1800, 1900) comes in between, then the calendar of leap year will be repeated after 40 or 12 years. <br><br>
Ex- calendar of  1880 will be repeated in 1920, 1872 in 1912 etc. <br>
Calendar of 1892 and 1896 is repeated in 1904 and 1908 respectively. <br><br>
But in aptitude exams you won't be tested to this extent. 
{{% /alert %}}

##### Q. Which of the given years will have the same calendar as that of year 2003?
<pre>(a) 2013         (b) 2014          (c) 2015          (d) 2016</pre>
Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Odd days Method <br><br>
2003 is a non-leap year. <br><br>

So, Number of odd days till 2008 = 1 + 2 + 1 + 1 + 1 + 2 = 8 = (1) (this 1 will be carried forward) <br>
Number of odd days from 2009 to 2013 = (1) + 1 + 1 + 1 + 2 + 1 = 7 = 0 <br><br>

2014 is a non-leap year. So the calendar of 2003 will repeat in 2014.  <br><br>
Answer: (b)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Short Trick<br><br>

Since, 2003 is a non-leap year. <br>
So, 2003 + 6 = 2009 and 2003 + 11 = 2014 (as we know that, a non-leap year repeats itself after 6 years or 11 years) <br><br>

Given the options, year 2014 will have the same calendar as that of 2003. <br><br>
Answer: (b)
</div> <br>

##### Q. Which year will have the same calendar as that of 2012?
<pre>(a) 2020         (b) 2040          (c) 2025          (d) 2031</pre>
Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Using Odd days Method <br><br>
To have the same calendar as 2012, we must have 0 odd days between 2012 and the required year. Also, that year should be a leap year.<br><br>

2012 is a leap year. <br>

So, Number of odd days from 1st Jan 2012 till 31st Dec 2016 = 2 + 1 + 1 + 1 + 2 = 7 = 0 (but 2017 is not a leap year) <br>
Number of odd days from 1st Jan 2017 till 31st Dec 2022 = 1 + 1 + 1 + 2 + 1 + 1 = 7 = 0 (but 2023 is not a leap year) <br>
Number of odd days from 1st Jan 2023 till 31st Dec 2028 = 1 + 2 + 1 + 1 + 1 + 2 = 8 = 7 + 1 = 1 (one odd day left) <br>
Number of odd days from 1st Jan 2029 till 31st Dec 2033 = 1 + 1 + 1 + 1 + 2 + 1 = 7 = 0 (but 2034 is not a leap year) <br>
Number of odd days from 1st Jan 2034 till 31st Dec 2039 = 1 + 1 + 2 + 1 + 1 + 1 = 7 = 0 <br><br>

Now, 2040 is a leap year too. So the calendar of 2012 will repeat in 2040.  <br><br>
Answer: (b)
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Using Short Trick  <br><br>
Since, 2012 is a leap year. <br><br>
So, 2012 + 28 = 2040 (as we know that, a leap year repeats itself after 28 years)<br><br>
So, year 2040 will have the same calendar as that of 2012.<br><br>
Answer: (b)
</div><br>