---
title: Finding day on a particular date
linktitle: Finding day on a particular date
toc: true
type: docs
date: "2020-09-27T00:00:00+01:00"
draft: false
menu:
  calendar:
    parent: Calendar
    weight: 12

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 12
---

Generally a reference day is given and we are supposed to find out the day on some other date. 

Step I: Find the net number of odd days between the reference date and the date for which the day is to be determined. <br>
(Include the reference day but exclude the final day for counting the number of net odd days. Vice-versa is also correct.)

Step II: Finding the day of the week on the final date <br><br>
If final date is after the reference date: <br>
The day of the week on the final date = Day on the reference date + the number of net odd days. (So, here we will add the odd days) <br>

If final date is before the reference date: <br>
The day of the week on the final date = Day on the reference date - the number of net odd days. (So, here we will subtract the odd days)

##### Q. If 15th August, 2011 was Monday, what day of the week was on 17th September, 2011?
<pre>(a) Saturday   (b) Sunday   (c) Friday   (d) Thursday </pre>
Explanation:<br>
<div class="Exp">
Step I: Counting the odd days in between the two dates (15th August, 2011 and 17th September, 2011)<br><br>

Here, total days in August, 2011 = 31 – 14 = 17 (include the reference day, i.e. 15th August) <br>
Total days in September, 2011 (1st to 16th) = 16 (exclude the final day, i.e. 17th September) <br>
Total days = 17 + 16 = 33

Number of odd days = Remainder {33/7} = 5 

Step II: Finding the day of the week on the final date 

Here final date (17th September, 2011) is after the reference date (15th August, 2011). So, we will add the odd days. <br><br>
The day of the week on the final date = Day on the reference date + the number of net odd days. <br>
So, Required day = Monday + 5 = Saturday

Answer: (a)
</div> <br><br>



##### Q. If 5th January, 1991 was Saturday, then what day of the week was it on 4th March 1992? 
<pre>(a) Monday   (b) Wednesday   (c) Friday   (d) Sunday</pre>
Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-3', this, 'tablink-group1', 'tabcontent-group1')">3</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: <br><br>
Step I: Counting the odd days in between the two dates (5th January, 1991 and 4th March 1992)<br><br>

Number of days in 1991 = 365–4 = 361 (include the reference day, i.e. 5th January)<br>
Number of days in January 1992 = 31<br>
Number of days in February 1992 = 29 (1992 is a Leap year)<br>
Number of days from 1st to 4th March 1992 = 3 (exclude the final day, i.e. 4th March 1992)<br><br>
Total days = 361 + 31 + 29 + 3 = 424 <br>
Number of odd days = Remainder {424/7} = 4

Step II: Finding the day of the week on the final date <br>

Here final date (4th March 1992) is after the reference date (5th January, 1991).<br>
The day of the week on the final date = Day on the reference date + the number of net odd days. <br>
So, Required day = Saturday + 4 = Wednesday<br>

Answer: (b)
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Finding odd days for every segment<br><br>
Number of odd days in 1991 = 365 – 4 = 361 = 51 × 7 + 4 = 4<br>
Number of odd days in January 1992 = 31 = 28 + 3 = 3<br>
Number of odd days in February 1992 = 29 = 28 + 1 = 1 (Leap year)<br>
Number of odd days from 1st to 3rd March, 1992 = 3<br>
Total odd days = 4 + 3 + 1 + 3 = 11 = 7 + 4 = 4 odd days<br><br>

So, Required day = Saturday + 4 = Wednesday

Note: We can also mix the two methods (methods 1 and 2) as per our convenience. 

Answer: (b)
</div><br>

<div id="1Exp-3" class="Exp-3 mak-tabcontent tabcontent-group1">
Explanation 3: <br><br>
5th January, 1991 was Saturday.<br>
Hence, 5th January, 1992 will be Sunday. 

Number of odd days between 5th January, 1992 and 4th March 1992 = (31 – 4) + 29 + 3 = 59 = 3

Hence, 4th March 1992 = Sunday + 3 = Wednesday

Answer: (b)
</div><br>