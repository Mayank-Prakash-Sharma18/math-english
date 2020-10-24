---
title: Concept of Odd days
linktitle: Concept of Odd days
toc: true
type: docs
date: "2020-10-05T00:00:00+01:00"
draft: false
menu:
  calendar:
    parent: Calendar
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

Concept of odd days emerges from the concept of a week.<br>
Concept of a week - The day gets repeated after every seventh day. 

Ex - If today is Monday, then 28th day from now will also be a Monday as it a multiple of 7 (28/7 = 4, so four weeks). 

Ex - If today is Monday, then 30th day = 28 + 2 (4 weeks and 2 days), i.e. 30/7 will give a remainder of 2.<br>
These two days are odd days. With starting day as Monday and two odd days, the 30th day will be Wednesday.

{{% alert note %}}
So, Number of odd days in a given period = Remainder {Period/7} <br>
That is, Remainder left will be the number of odd days.
{{% /alert %}}

Extra days, apart from complete weeks in a given period are called odd days, e.g.:	<br>
A period of 7 days = 7 + 0 extra day = 0 odd day <br>
A period of 8 days = 7 + 1 extra day = 1 odd day <br>
A period of 9 days = 7 + 2 extra days = 2 odd days <br>
A period of 10 days = 7 + 3 extra days = 3 odd days <br>
A period of 11 days = 7 + 4 extra days = 4 odd days <br>
A period of 12 days = 7 + 5 extra days = 5 odd days <br>
A period of 13 days = 7 + 6 extra days = 6 odd days <br>
But a period of 14 days = 7 + 7 = 2 complete weeks = 0 odd days <br>

## Odd days in a Month

##### Number of odd days in different months:

<img src="../../../media/calendar/months-odd-days.png" alt="calendar" style="width:81%;height:81%;">

##### Number of odd days in different quarters:
Jan + Feb + Mar = 6 OR 7 (i.e. 0) <br>
Apr + May + June = 7 (i.e. 0) <br>
July + Aug + Sep = 8 (i.e. 1) <br>
Oct + Nov + Dec = 8 (i.e. 1) <br>

##### Q. Today is Tuesday. What day will it be a day after 72 days?
<pre>(a) Sunday     (b) Friday    (c) Thursday    (d) Saturday </pre>

Explanation:<br>
<div class="Exp">
Tuesday will be repeated after each 7 days, so after 70 days it will again be Tuesday. <br>
The day after 72th day, i.e. 73rd day = 70 + 3, i.e. 3 odd days <br>
The required day is Tuesday + 3 = Friday. <br>
Answer: (b)
</div> <br>

## Odd days in a Year

#### Number of odd days in an ordinary year
Number of days in an ordinary year = 365 = 364 + 1 <br>
Number of odd days in an ordinary year = Remainder {365/7} = 1 odd day

#### Number of odd days in a leap year
Number of days in a leap year = 366 = 364 + 2 <br>
Number of odd days in a leap year = Remainder {366/7} = 2 odd days

#### Number of odd days in a 100 years
Number of odd days in 100 years = 76 ordinary years + 24 leap years <br>
= 76 odd days of 76 ordinary years + (24 × 2) odd days of 24 leap years <br>
= 76 odd days + 48 odd days = 124 odd days <br>
= (7 × 17 + 5) odd days = 5 odd days

{{% alert warning %}}
Note: This will be the case if the century year divisible by 400 (e.g. 1600, 2000) is not there in the 100 years counted, or else 1 more odd day has to be added.
{{% /alert %}}

##### Q. If 1st Jan 1901 is a Tuesday, what is the day on 1st Jan 2001?
<pre>(a) Sunday     (b) Tuesday    (c) Monday    (d) Saturday </pre>

Explanation:<br>
<div class="Exp">
Number of odd days in 100 years = 5 odd days <br>
However, it’s true only when the century year divisible by 400 is not there, or else 1 more odd day has to be added. <br><br>
Here, we are counting from 1st January, 1901 to 31st December, 2000. So, 2000 is also getting counted. 

Hence, number of odd days between 1st January, 1901 and 1st January, 2001 = 5 + 1 = 6

So, 1st January, 2001 = Tuesday + 6 = Monday <br><br>
Answer: (c)
</div> <br>

#### Number of odd days in a 200 years
Odd days in 200 yrs = (Odd days in 100 yrs) × 2 = 5 × 2 = 10 days = 1 week + 3 days = 3 odd days

{{% alert warning %}}
Note: This will be the case if the century year divisible by 400 (e.g. 1600, 2000) is not there in the 200 years counted, or else 1 more odd day has to be added.
{{% /alert %}}

#### Number of odd days in a 300 years
Odd days in 300 yrs = (Odd days in 100 yrs) × 3 = 5 × 3 = 15 days = 2 weeks + 1 day = 1 odd day

{{% alert warning %}}
Note: This will be the case if the century year divisible by 400 (e.g. 1600, 2000) is not there in the 300 years counted, or else 1 more odd day has to be added.
{{% /alert %}}

#### Number of odd days in a 400 years
Odd days for 400 yrs = (Odd days in 100 yrs) × 4 + 1 day = (5 × 4 + 1) days = 21 days = 3 weeks = 0 odd day

{{% alert note %}}
Note: If we count any consecutive 400 years, the century year divisible by 400 (e.g. 1600, 2000) will always get counted. 
{{% /alert %}}

<br><hr>

## Finding day on the same date

If today is Monday, then can you tell what day will it be on the same date next year or previous year?

Well, it is easy. Just remember this:
* If 29th February falls in between the two given dates of consecutive years, then there will be 2 odd days between the two dates.
* If there's no 29th February between the two given dates of consecutive years, then there will only be 1 odd day between them. 

Let's see some examples:

##### Q. March 6, 1992 was Thursday. What day of the week will it be on March 6, 1993?
<pre>(a) Friday     (b) Thursday    (c) Monday    (d) Saturday </pre>

Explanation:<br>
<div class="Exp">
1992 – leap year <br>
1993 – non-leap year<br><br>

But our period is March 6, 1992 to March 6, 1993. 29th February, 1992 does not fall in this period.<br><br>
So, there will only be 1 odd day between the two given dates. Hence, March 6, 1993 will be 1 day ahead of March 6, 1992. 

So, March 6, 1993 will be Thursday + 1 = Friday <br><br>
Answer: (a)
</div> <br>

##### Q. January 6, 1992 was Thursday. What day of the week will it be on January 6, 1993?
<pre>(a) Friday     (b) Thursday    (c) Monday    (d) Saturday </pre>

Explanation:<br>
<div class="Exp">
1992 – leap year<br>
1993 – non-leap year <br><br>

Our period is January 6, 1992 to January 6, 1993. 29th February, 1992 does fall in this period.<br><br>
So, there will be 2 odd days between the two given dates. Hence, January 6, 1993 will be 2 days ahead of January 6, 1992. 

So, January 6, 1993 will be Thursday + 2 = Saturday<br><br>
Answer: (d)
</div> <br>