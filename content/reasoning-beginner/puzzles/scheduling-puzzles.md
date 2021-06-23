---
title: Scheduling Puzzles
linktitle: Scheduling Puzzles
toc: true
type: docs
date: "2021-06-22T00:00:00+01:00"
draft: false
menu:
  puzzles:
    parent: 5. Scheduling Puzzles
    weight: 24

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 24
---

In these types of puzzles, we are supposed to schedule things as per a time-table. For example, when various lectures will be taught in a school, who will take what class and at what time etc. 

Let's see a few examples.

##### Q. Read the information given below and answer the item that follows.

Six professors – A, B, C, D, E and F are given a task for taking classes from Monday to Saturday, not necessarily in the same order. Each professor would take exactly one class in a week. It’s also given that:
1.	D would not take a class until A has already taken his.
2.	C must take a class a day before B does.
3.	F can’t take a class on Saturday and should take his class a day after D has taken his.
4.	C takes his class on Monday.

Q. Who is going to take lecture on Saturday? <br>
(a)	A <br>
(b)	D <br>
(c)	E <br>
(d)	F <br>


Explanation:<br>
<div class="Exp">

There are 2 dimensions in this question: Professors, and Days. So, it's a 2-D question. 

Using statements 2, 3 and 4, we get two cases.

Case I:
<img src="../../../media/puzzles/scheduling-3.png" alt="Scheduling Puzzles" style="width:45%;height:45%;">

Case II:
<img src="../../../media/puzzles/scheduling-4.png" alt="Scheduling Puzzles" style="width:45%;height:45%;">

Now, as per statement 1, D would not take a class until A has already taken his. Thus, we may reject Case I. The final scenario may be depicted in the form of a table as follows:
<img src="../../../media/puzzles/scheduling-5.png" alt="Scheduling Puzzles" style="width:45%;height:45%;">

Answer: (c)
</div> <br>


##### Q. Read the information given below and answer the 3 (three) items that follow.

Lectures on 6 subjects viz. Physics, Chemistry, Maths, Biology, Computer Science and Physical Education have to be arranged in a week, starting from Monday to Saturday and have to be taken exactly by one professor each, out of A, B, C, D, E and F. Only one lecture can be arranged on each day. 

1.	Biology is to be scheduled on Wednesday.
2.	Professor B takes classes on the very first day of the week, but doesn’t teach Physics and Chemistry.
3.	Professor E teaches Physical Education, which is scheduled on Saturday.
4.	Class of Maths is to be scheduled immediately after Biology.
5.	On Wednesday, neither Professor C nor Professor A is available for teaching.
6.	F takes class just on the next day of B and do not teach Chemistry.

Q1. Which of the following combination of Day-Professor-Subject is definitely true? <br>
(a)	Tuesday-F-Physics <br>
(b)	Thursday-A-Maths <br>
(c)	Friday-C-Chemistry <br>
(d)	None of the above

Q2. Who is scheduled to take the class on Thursday? <br>
(a)	Professor A <br>
(b)	Professor B <br>
(c)	Professor C <br>
(d)	Data is not sufficient 

Q3. Which of the following statements are definitely correct? <br>
1.	On Tuesday F takes class of Physics <br>
2.	A or C take a class immediately after D <br>
3.	D teaches on Wednesday 

(a)	Only 1 & 2 are correct <br>
(b)	Only 2 is correct <br>
(c)	Only 3 is correct <br>
(d)	All 1, 2 and 3 are correct

Explanation:<br>
<div class="Exp">

There are 3 dimensions in this question: Professors, Subjects and Days. So, it's a 3-D question. 

Answer 1: (a) <br>
Using statements, 1, 2, 3, 4, we get the following picture:
<img src="../../../media/puzzles/scheduling-1.png" alt="Scheduling Puzzles" style="width:99%;height:99%;">

Professor B must be taking Computer Science, as we already know that Biology, Maths and Physical Education are scheduled on Wednesday, Thursday and Saturday respectively and as per statement 2, B doesn’t teach Physics and Chemistry.

Using statement 5 and 6, we get the following table:
<img src="../../../media/puzzles/scheduling-2.png" alt="Scheduling Puzzles" style="width:99%;height:99%;">

As either of A or C may be teaching on Thursday and Friday, option (b) & (c) can be ruled out. However, option (a) is definitely true.

Answer 2: (d) <br>
Either of the two professors, A or C can take the class on Thursday. Hence, the data is not sufficient.

Answer 3: (d) <br>
As its evident from the table drawn based on the information provided in the question, all the three given statements are true.
</div> <br>


