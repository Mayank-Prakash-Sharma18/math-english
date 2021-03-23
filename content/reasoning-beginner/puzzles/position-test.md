---
title: Position Puzzles
linktitle: Position Puzzles
toc: true
type: docs
date: "2021-03-19T00:00:00+01:00"
draft: false
menu:
  puzzles:
    parent: 2. Counting Puzzles
    weight: 9

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 9
---

In this type of questions, the rank/position of a person(s) from either of the two ends of a row/queue is given and we have to determine:

* Either the total number of persons in the group 
* Or the number of persons to the left/right of a particular person.
* Or the number of persons between two given persons. 

Sometimes, such questions are given in the form of a puzzle involving interchanging of seats by two or more persons.

<div class="toc-mak"> <br>

Rank of a Person/Object from Left or Right:

Position (or rank) from the left end = (Total number of persons + 1) — Rank from the right end

Position (or rank) from the right end = (Total number of persons + 1) — Rank from the left end
</div>


## Types of Position Puzzles

### Finding position from other end

##### Q. In class of 45 students rank of Mragank is 15th from the top, then rank of Mragank from the bottom is 
<pre>(a) 30         (b) 31          (c) 32          (d) 33</pre>

Explanation:<br>
<div class="Exp">

<img src="../../../media/puzzles/sequence-and-ordering-4.png" alt="Sequence and Ordering" style="width:36%;height:36%;">

Mragank's rank from the bottom = (Total number of students + 1) — Rank of Mragank from top <br>
= (45 + 1) - 15 = 46 – 15 = 31

Answer: (b)
</div> <br>


### Finding the number of persons between two given persons

Let's see a couple of questions wherein the number of people between two given individuals is to be found out. Do read and compare the following two questions. 

##### Q. In class of 45 students rank of Mragank is 15th from the top, and that of Aanya is 22nd from the top. How many students must be there between the two?  
<pre>(a) 5         (b) 6          (c) 8          (d) Cannot be determined</pre>

Explanation:<br>
<div class="Exp">

We have been given the position of Mragank and Aanya from the same side (i.e. from the top). So, our task is easy. 

(If their positions had been given from different sides, then we would first have found out their positions from one side.)

{{% alert note %}}
Note that the data, that there were 45 students in the class, is not required/used. It's because we already know the positions of both the individuals from the same side. If we would have been given their positions from separate ends, then we would have used this data. 
{{% /alert %}}

<img src="../../../media/puzzles/sequence-and-ordering-7.png" alt="Sequence and Ordering" style="width:54%;height:54%;">

Number of students between Mragank and Aanya = (22 - 15) - 1 = 7 - 1 = 6

{{% alert note %}}
Alternate Method: 

Number of students between Mragank and Aanya = 21 - 15 = 6

If we do 22 - 15 = 7, then this will also include Aanya. It will be wrong, as we have to find the number of students ***between*** Mragank and Aanya, excluding both Mragank and Aanya.
{{% /alert %}}

Answer: (b)
</div> <br>

##### Q. In class of 45 students rank of Mragank is 15th from the top, and that of Aanya is 22nd from the bottom. How many students must be there between the two?  
<pre>(a) 5         (b) 6          (c) 8          (d) Cannot be determined</pre>

Explanation:<br>
<div class="Exp">

Their positions had been given from different sides. So, we would first find out their positions from one side (either their ranks from the top, or their ranks from the bottom).

{{% alert note %}}
Note that the data, that there were 45 students in the class, will be required/used here. It's because we have been given their positions from separate ends. If we would have already known their positions from the same side, then we would not have used this data. 
{{% /alert %}}

Rank of Mragank = 15th from the top.

Rank of Aanya = 22nd from the bottom 

So, Rank of Aanya from the top = (Total number of students + 1) — Rank from the bottom = (45 + 1) - 22 = 24

<img src="../../../media/puzzles/sequence-and-ordering-8.png" alt="Sequence and Ordering" style="width:54%;height:54%;">

Number of students between Mragank and Aanya = (24 - 15) - 1 = 9 - 1 = 8

{{% alert note %}}
Alternate Method: 

Number of students between Mragank and Aanya = 23 - 15 = 8

If we do 24 - 15 = 9, then this will also include Aanya. It will be wrong, as we have to find the number of students ***between*** Mragank and Aanya, excluding both Mragank and Aanya.
{{% /alert %}}

Answer: (c)
</div> <br>


#### Finding the total number of persons in the row

Now, let's see a question wherein total number of people in the row are to be found out. 

In such questions, our goal should be to find the position of a certain individual from both ends. 

##### Q. In a class of students, Mragank is 25th from top and 32nd from bottom in a class, then total number of students in the class is 
<pre>(a) 55         (b) 57          (c) 56          (d) 58</pre>

Explanation:<br>
<div class="Exp">

Here, the position of Mragank from both ends is already given. So, our task is easy. 

<img src="../../../media/puzzles/sequence-and-ordering-6.png" alt="Sequence and Ordering" style="width:27%;height:27%;">

Total students in a class = (Rank of Mragank from top + Rank of Mragank from bottom) — 1 <br>
= (25 + 32) — 1 <br>
= 57 — 1 = 56

{{% alert note %}}
Alternate Method: 

Mragank is 25th from top and 32nd from bottom.

Total students in a class = (Total number of students before Mragank + Total number of students after Mragank) + 1 <br>
= 24 + 31 + 1 <br>
= 55 + 1 = 56
{{% /alert %}}

Answer: (c)
</div> <br>


### Questions where people change their positions 

Now, once we have understood the basics, let's see some questions wherein people change their positions. 

##### Q. In a row of 40 girls, when Alka was shifted to her left by 4 places, her place from the left end of the row became 10. What is the position of Aanya from the right end of the row, if Aanya was three places to the right of Alka's original position?
<pre>(a) 24         (b) 23          (c) 22          (d) 25</pre>

Explanation:<br>
<div class="Exp">

On shifting 4 places to the left, Alka’s position = 10th from the left end. 

Thus, Alka's original position = 10 + 4 = 14th from the left end.

Aanya is 3 places to the right of Alka's original position = 17th from the left end.

<img src="../../../media/puzzles/sequence-and-ordering-5.png" alt="Sequence and Ordering" style="width:81%;height:81%;">

Now, Aanya's position from right = (Total number of girls + 1) — Aanya's position from left = (40 + 1) — 17 = 41 - 17 = $24^{th}$ 

Answer: (a)
</div> <br>


### Questions with multiple cases

In such questions, multiple cases may arise (generally two cases). We have to keep both cases in mind while answering the questions. 

##### Q. If in a row, Rohan is 10th from left and Mukesh is 13th from right and there are four persons in between Rohan and Mukesh, then find the maximum and minimum number of persons in the row.
<pre>(a) 27, 18         (b) 30, 15          (c) 27, 17          (d) 30, 19</pre>

Explanation:<br>
<div class="Exp">

Two cases may arise in this question, depending on the relative position of Rohan and Mukesh.

***Case I: For maximum number of persons***

<img src="../../../media/puzzles/sequence-and-ordering-9.png" alt="Sequence and Ordering" style="width:81%;height:81%;">

Total number of persons = Sum of positions of both persons + Number of persons in middle <br>
= 10 + 13 + 4 = 27

***Case II: For minimum number of persons***

<img src="../../../media/puzzles/sequence-and-ordering-10.png" alt="Sequence and Ordering" style="width:81%;height:81%;">

Total number of persons = Sum of positions of both places — Number of persons in middle including Mukesh and Rohan who have been counted twice <br>
= (10 + 13) — (4 + 2) = 23 – 6 = 17

Answer: (c)
</div> <br>
