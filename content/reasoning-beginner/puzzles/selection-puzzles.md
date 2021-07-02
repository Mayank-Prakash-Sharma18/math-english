---
title: Selection Puzzles
linktitle: Selection Puzzles
toc: true
type: docs
date: "2021-06-26T00:00:00+01:00"
draft: false
menu:
  puzzles:
    parent: 6. Selection Puzzles
    weight: 27

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 27
---

In these types of puzzles, we are supposed to select teams and groups, or candidates, or fill-up a post based on some given conditions.  

Generally, in puzzle questions when you crack a set, it does not take much time to answer the questions based on that puzzle. However, in selection puzzles you will have to invest some time in each of the question, go through all the conditions again and again. So, it might be a little more time-consuming. Though it depends on the number and complexity of the given conditions too. 

Let's see a few examples.

## Type 1: No Condition given

##### Q. Out of a cricket squad of 13 players, a team of 11 players is to be formed. How many such compositions are possible?
<pre>(a) 70   (b) 90    (c) 88   (d) 78</pre>

Explanation:<br>
<div class="Exp">

We have to select 11 players out of 13. <br>
Therefore, Possible combinations = $C^{13}_{11}$ = $C^{13}_2$ = $\frac{13 × 12}{2 × 1}$ = 78

Answer: (d)
</div> <br>

## Type 2: Type of team members given

### Type 2a

##### Q. A cricket squad of 14 players has 7 batsmen, 2 wicketkeepers and 5 bowlers. From this, a team of 11 players is to be formed, including 6 batsmen, 1 wicketkeeper and 4 bowlers. How many such compositions are possible?
<pre>(a) 70   (b) 140    (c) 210   (d) 420</pre>

Explanation:<br>
<div class="Exp">

We have to select 6 batsmen out of 7, 1 wicketkeeper out of 2 and 4 bowlers out of 5. <br>
Therefore, Possible combinations = $C^7_6$ × $C^2_1$ × $C^5_4$ = $C^7_1$ × $C^2_1$ × $C^5_1$ = 7 × 2 × 5 = 70

Answer: (a)
</div> <br>

##### Q. A local restaurant provides a breakfast combo in which a customer has to choose one item from each of the following three categories:
<img src="../../../media/puzzles/selection-puzzles-1.png" alt="Selection Puzzle Questions" style="width:99%;height:99%;">
Each of the items given above has been marked as vegetarian (veg) or non-vegetarian (non - veg). For a vegetarian person, how many combinations of breakfast combos are possible?
<pre>(a) 60   (b) 20    (c) 12   (d) 15</pre>

Explanation:<br>
<div class="Exp">

There is only one vegetarian sandwich (Potato and cheese) <br>
However, all 4 Sides and 5 Juices are vegetarian items.

Thus, total possible vegetarian combinations in a breakfast combo = 1 × 4 × 5 = 20

Answer: (b)
</div> <br>


### Type 2b: Use of atleast or atmost

##### Q. A 5-member committee is to be formed, out of 4 lawyers and 3 health practitioners. For it to be representative, the committee must have at least 2 members each having legal and health backgrounds respectively. What is the total number of possible ways in which the aforementioned committee can be formed?
<pre>(a) 16   (b) 18    (c) 25   (d) 27</pre>

Explanation:<br>
<div class="Exp">

The committee may consist of:
* either 2 lawyers and 3 health practitioners  
* or 3 lawyers and 2 health practitioners

Hence, the number of possible combinations = ($C^4_2$ × $C^3_3$) + ($C^4_3$ × $C^3_2$) = ($C^4_2$ × $C^3_0$) + ($C^4_1$ × $C^3_1$) = (6 × 1) + (4 × 3) = 6 + 12 = 18

Answer: (b)
</div> <br>


## Selection Puzzle Sets

##### Q. Read the information given below and answer the 3 (three) items that follow.

A team of 4 players is to be made out of 6 players available, i.e. A, B, C, D, E, and F.  However, there are some conditions attached to the team selection:
1.	Either both B and C are selected, or neither of the two.
2.	A and D can’t be together
3.	F must be selected

Q1. What are the number of ways, a team can be formed? <br>
(a)	3 ways <br>
(b)	4 ways <br>
(c)	5 ways <br>
(d)	6 ways

Q2. If A is not selected in the team, then which of the following teams is possible? 
1.	BCDE
2.	BCDF
3.	BCEF

Select from the codes below: <br>
(a)	1 & 2 only <br>
(b)	3 only <br>
(c)	2 & 3 only <br>
(d)	1, 2 and 3

Q3. Which of the following pair of players are always selected in the team? <br>
(a)	A & B <br>
(b)	B & C <br>
(c)	B & E <br>
(d)	A & F

Explanation:<br>
<div class="Exp">

Answer 1: (a)

As per statement 3, F must be selected. Hence, basically we have to select 3 players out of the remaining 5.

If A is selected, the possible team combinations may be: ABCF, i.e. 1. <br>
If B is selected, the possible new team combinations may be: BCDF and BCEF, i.e. 2. (ABCF has already been accounted for) <br>
If C is selected, the possible team combinations will be the same as when B is selected. So, no new team combinations are there. <br>
If D is selected, the possible team combination may be DBCF, but it has already been accounted for. <br>
If E is selected, the only team combination possible is EBCF, but it has already been accounted for. <br>

Thus, the only possible combinations are ABCF, BCDF and BCEF. In rest of the combinations, the above 3 conditions do not hold valid.

Answer 2: (c)

As we already know, the only possible combinations are ABCF, BCDF and BCEF. If A is not selected in the team, then only two combinations BCDF and BCEF are possible, i.e. 2 and 3.

Answer 3: (b)

Out of the three possible team combinations, ABCF, BCDF and BCEF, B and C are always present in the team. Hence, option (b) is the correct.
</div> <br>