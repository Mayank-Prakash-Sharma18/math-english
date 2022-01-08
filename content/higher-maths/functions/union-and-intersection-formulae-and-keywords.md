---
title: Union and Intersection Formulae and Concepts
linktitle: Union and Intersection Formulae and Concepts 
toc: true
type: docs
date: "2021-08-14T00:00:00+01:00"
draft: false
menu:
  functions:
    parent: 1. Set Theory
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

In this article, we will study about the concepts of Union and Intersection of two or more sets in much more detail. 

## Union and Intersection formulae for two and three sets

### Formula 1

If A and B are finite sets then:

n (A ∪ B) = n (A) + n (B) – n (A ∩ B) 
<img src="../../../media/functions/set-theory-8.png" alt="Set Theory" style="width:54%;height:54%;">

{{% alert note %}}
If there is no common element in the two sets, i.e. (A ∩ B) = φ, then n (A ∪ B) = n (A) + n (B)
<img src="../../../media/functions/set-theory-9.png" alt="Set Theory" style="width:72%;height:72%;">
{{% /alert %}}

##### Q. In a college there are 30 teachers. 22 teachers teach English and 6 teachers teach both Maths and English. How many teachers must be teaching Maths?  

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Using Formula <br><br>

Let E be the set of teachers who teach English and M be the set of teachers who teach Maths. <br>
It's given that: n (E ∪ M) = 30, n (E) = 22 and n (E ∩ M) = 6 

We know that, n (E ∪ M) = n (E) + n (M) – n (E ∩ M) <br>
or 30 = 22 + n (M) – 6 <br>
or n (M) = 14 

Hence 14 teachers teach Maths.
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: Using Venn Diagram <br><br>

Let E be the set of teachers who teach English and M be the set of teachers who teach Maths. <br>
<img src="../../../media/functions/set-theory-11.png" alt="Set Theory" style="width:99%;height:99%;">

We can see from the above Venn diagram, that teachers who teach only English = 22 - 6 = 16

So, teachers who teach Maths = Total number of teachers - Teachers who teach only English = 30 - 16 = 14
</div><br>


### Formula 2

If A, B and C are finite sets then:

n (A ∪ B ∪ C) = n (A) + n (B) + n (C) – n (A ∩ B) – n (A ∩ C) – n (B ∩ C) + n (A ∩ B ∩ C)
<img src="../../../media/functions/set-theory-10.png" alt="Set Theory" style="width:99%;height:99%;">

##### Q. In a school 38 students passed in mathematics, 15 students passed in Physics and 20 students passed in Chemistry. If only three students passed in all the three subjects and there are total 58 students in the school then how many students passed in exactly two of the three subjects? 

Explanations :<br>
<button class="mak-tablink tablink-group2 default-tab" onclick="openTab('2Exp-1', this, 'tablink-group2', 'tabcontent-group2')">1</button>
<button class="mak-tablink tablink-group2" onclick="openTab('2Exp-2', this, 'tablink-group2', 'tabcontent-group2')">2</button>

<div id="2Exp-1" class="Exp-1 mak-tabcontent tabcontent-group2">
Explanation 1: Using Formula <br><br>

Let A, B and C be the set of students passed in Mathematics, Physics and Chemistry respectively. 

It's given that: n (A) = 38, n (B) = 15, n (C) = 20, n (A ∪ B ∪ C) = 58 and n (A ∩ B ∩ C) = 3
<img src="../../../media/functions/set-theory-17.jpg" alt="Set Theory" style="width:54%;height:54%;">

We know that, n (A ∪ B ∪ C) = n (A) + n (B) + n (C) – n (A ∩ B) – n (A ∩ C) – n (B ∩ C) + n (A ∩ B ∩ C) <br>
or 58 = 38 + 15 + 20 – {n (A ∩ B) + n (A ∩ C) + n (B ∩ C)} + 3 <br>
or n (A ∩ B) + n (A ∩ C) + n (B ∩ C) = 18 

* Here, ‘a’ denotes the number of students who passed in Mathematics and Physics only, 
* ‘b’ denotes the number of students who passed in Mathematics and Chemistry only, 
* ‘c’ denotes the number of students who passed in Physics and Chemistry only and 
* 3 students passed in all the three subjects.   

Now, n (A ∩ B) + n (A ∩ C) + n (B ∩ C) = 18 <br>
or (a + 3) + (b + 3) + (c + 3) = 18 <br>
or a + b + c = 9 

Hence, 9 students passed in exactly two of the three subjects. 
</div>

<div id="2Exp-2" class="Exp-2 mak-tabcontent tabcontent-group2">
Explanation 2: Using Venn Diagram <br><br>

Using the Venn diagram method:
<img src="../../../media/functions/set-theory-18.jpg" alt="Set Theory" style="width:54%;height:54%;">

58 = (35 - a - b) + (12 - a - c) + (17 - b - c) + a + b + c + 3 <br>
or 58 = 35 + 12 + 17 + 3 - a - b - c <br>
or a + b + c = 9 

Hence, 9 students passed in exactly two of the three subjects.
</div><br>

<br><hr><br>


## Keywords related to Set Theory

While solving Set Theory questions, you will often come across some keywords that you must understand, or else you won't be able to understand the problems correctly and make unforced errors. 

We will study about: and, or, only, at least, at most, no/not

Have a look at the following Venn diagram and try to understand what these keywords mean in Set Theory:
<img src="../../../media/functions/set-theory-12.png" alt="Set Theory" style="width:99%;height:99%;">

### Only

A = P + X + Y + T <br>
A only = P

B = Q + X + Z + T <br>
B only = Q

C = R + Y + Z + T <br>
C only = R

### And

***And*** implies Intersection, i.e. ∩.

A AND B = X + T <br>
A AND B only = X

B AND C = Z + T <br>
B AND C only = Z 

A AND C = Y + T <br>
A AND C only = Y

### Or

***Or*** implies Union, i.e. ∪.

A OR B = P + Y + X + T + Q + Z <br>
A OR B only = P + Q + X <br>
A only OR B only = P + Q 

B OR C = X + Q + T + Z + Y + R <br>
B OR C only = Q + R + Z <br>
B only OR C only = Q + R 

A OR C = P + X + Y + T + R + Z <br>
A OR C only = P + R + Y <br>
A only OR C only = P + R

### Not/None

None of Three = (A + B + C)′, i.e. (A ∪ B ∪ C)′

Not A OR B = (A OR B)′ = R + (A + B + C)′ <br>
Not B OR C = (B OR C)′ = P + (A + B + C)′ <br>
Not A OR C = (A OR C)′ = Q + (A + B + C)′

### At least and At most

At least two means 2 or more, i.e. not less than 2. As we have only three sets A, B and C, so here 'at least' means 2 or 3. <br>
At least Two = X + Y + Z + T 

At most two means 2 or less (2, 1, or 0), i.e. not more than 2. <br>
At most Two = Total – T = U - T = P + Q + R + X + Y + Z + (A ∪ B ∪ C)′

This will become much more clear with a few examples. 

##### Q. The following Venn diagram represent the number of people can speak three languages viz. Tamil, Telugu or English.
<img src="../../../media/functions/set-theory-13.png" alt="Set Theory" style="width:36%;height:36%;">
Find number of people, who can speak: <br>
(i)	Tamil AND Telugu <br>
(ii) Tamil AND Telugu only <br>
(iii)	Tamil OR Telugu only <br>
(iv)	Tamil only OR Telugu only <br>
(v)	Not Tamil OR Telugu <br>
(vi)	Either Tamil OR Telugu <br>
(vii)	At least two languages <br>
(viii)	At most two languages


Explanation:<br>
<div class="Exp">

(i)	Number of people who can speak Tamil AND Telugu = 12+9 = 21 <br>
(ii) Number of people who can speak Tamil and Telugu only = 12 <br>
(iii)	Number of people who can speak Tamil OR Telugu only = 35 + 12 + 24 = 71 <br>
(iv) Number of people who can speak Tamil only OR Telugu only = 24 + 35 = 59 <br>
(v)	Number of people who can speak Not Tamil OR Telugu = (Tamil OR Telugu)′ = 27 <br>
(vi) Number of people who can speak either Tamil or Telugu = 35 + 12 + 24 + 9 + 13 + 19 = 112 <br>
(vii) Number of people who can speak at least 2 languages = 12 + 13 + 19 + 9 = 53 <br>
(viii) Number of people who can speak at most 2 languages = Total – 9 or 35 + 24 + 27 + 12 + 19 + 13 = 130
</div> <br>


##### Q. In a class of 150 students, 50 students passed in mathematics, 40 students failed only in Hindi and 20 students failed in both the subjects. Find:
(i) How many students passed in both the subjects? <br>
(ii) How many students passed exactly in one subject? <br>
(iii) How many students failed in atleast one of the subjects?

Explanation:<br>
<div class="Exp">

Total number of students = 150 <br>
Number of students passed in Mathmatics = 50 <br>
Number of students failed in Mathmatics = 150 – 50 = 100 <br>
Number of students passed in Hindi = Total number of students – number of students failed in Hindi = 150 – 60 = 90

(i) The Venn diagram based on the given information is shown below:
<img src="../../../media/functions/set-theory-14.jpg" alt="Set Theory" style="width:45%;height:45%;">

Number of students who passed in both the subjects = Number of students who did not fail = 150 – (80 + 20 + 40) = 10

(ii) The Venn diagram based on the given information is shown below:
<img src="../../../media/functions/set-theory-15.jpg" alt="Set Theory" style="width:45%;height:45%;">

Required answer = Number of students who passed in Mathematics only (but did fail in Hindi) + number of students who passed in Hindi only (but did fail in Mathematics)
= 40 + 80 = 120

(iii) The number of people who failed in at least one of the subjects = number of students who failed in Maths (but passed in Hindi) + the number of students who failed in Hindi (but passed in Maths) + the number of students who failed in both subjects = 80 + 40 + 20 = 140.

Or this can be obtained by subtracting the students who passed in both the subjects from the total number of students = 150 – 10 = 140
</div> <br>


##### Q. The diagram gives the number of candidates who failed in Chemistry, Electronics and English tests in college. The total number of candidates that appeared in these 3 tests was 600.
<img src="../../../media/functions/set-theory-16.png" alt="Set Theory" style="width:63%;height:63%;">

(i) What is the percentage of candidates who failed in at least two subjects? <br>
(ii) What is the total number of passed candidates? <br>
(iii)	What is the number of candidates who passed in at least one subject? <br>
(iv) What is the number of candidates passed in only Chemistry? <br>
(v) What is the number of candidates passed in only English? <br>
(vi) What is the number of candidates passed in only Electronics? <br>
(vii)	What is the number of candidates passed in both Chemistry and Electronics? <br>
(viii) What is the number of candidates passed in both Electronics and English? <br>
(ix) What is the number of candidates passed in both Chemistry and English? <br>
(x) What is the number of candidates passed in at least two subjects? <br>
(xi) What is the number of candidates passed in at most two subjects? <br>
(xii) What is the number of candidates passed in at most one subject? 

Explanation:<br>
<div class="Exp">

(i) Candidates failed in at least two subjects = 15 + 10 + 22 + 28 = 75 <br>
Required percentage = $\frac{75}{600}$ × 100 = 12.5%

(ii) Total failed candidates = 27 + 65 + 90 + 15 + 10 + 22 + 28 = 257 <br>
Total passed candidates passed in all the three subjects = 600 - 257 = 343  

(iii)	Number of candidates who passed in at least one subject = Total number of candidates appeared in test – Total number of candidates who failed in all the three subjects = 600 – 10 = 590

(iv) Number of candidates passed in only Chemistry = candidates failed in rest two subjects (i.e. Electronics and English) = 22

(v) Number of candidates passed in only English = candidates failed in rest two subjects (i.e. Electronics and Chemistry) = 15

(vi) Number of candidates passed in only Electronics = candidates failed in rest two subjects (i.e. English and Chemistry) = 28

(vii)	Number of candidates failed in both Chemistry and Electronics = 15 + 10 + 27 + 65 + 22 + 28 = 167 <br>
Number of candidates passed in both Chemistry and Electronics = 600 - 167 = 437 

(viii) Number of candidates failed in both Electronics and English = 15 + 10 + 90 + 65 +22 + 28 = 240 <br>
Number of candidates passed in both Electronics and English = 600 - 240 = 360

(ix) Number of candidates failed in both Chemistry and English = 27 + 28 + 90 + 10 + 22 + 15 = 192 <br>
Number of candidates passed in both Chemistry and English = 600 - 192 = 408

(x) Number of candidates passed in at least two subjects = candidates passed in at least two subjects + candidates passed in at least three subjects = 27 + 65 + 90 + 343 = 525

(xi) Number of candidates passed in at most two subjects = candidates passed in two subjects + candidates passed in one subject + candidates passed in zero subject = 27 + 65 + 90 + 15 + 28 + 22 + 10 = 257

(xii) Number of candidates passed in at most one subject = candidates passed in one subject + candidates passed in zero subject = 15 + 28 + 22 + 10 = 75
</div> <br>

