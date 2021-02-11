---
title: Combined Work
linktitle: Combined Work 
toc: true
type: docs
date: "2021-02-10T00:00:00+01:00"
draft: false
menu:
  time-and-work:
    parent: Work
    weight: 6

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 6
---

Sometimes, we are given questions wherein there are more than one people doing some work. Let's look at various such cases. 

## Case 1: Individual Efficiency or Time-taken given separately

### Case 1a: Two people working together

If A can do a piece of work in x days and B can do the same work in y days, then 

A's one day work (i.e. A’s efficiency) = 1/x and <br>
B's one day work (i.e. B’s efficiency) = 1/y

(A + B)'s one day work, i.e. combined efficiency of A & B = 1/x + 1/y = (x + y)/xy  

{{% alert note %}}
Note: We can add efficiencies but not time taken.
{{% /alert %}}

Now, Time taken α 1/Efficiency

So, the number of days required to complete the work if A and B work together = xy/(x + y) days

##### Q. If Mragank and Aanya can do a job in 8 and 12 days independently, then in how many days will they complete the job working together?

Explanations :<br>
<button class="mak-tablink tablink-group1 default-tab" onclick="openTab('1Exp-1', this, 'tablink-group1', 'tabcontent-group1')">1</button>
<button class="mak-tablink tablink-group1" onclick="openTab('1Exp-2', this, 'tablink-group1', 'tabcontent-group1')">2</button>

<div id="1Exp-1" class="Exp-1 mak-tabcontent tabcontent-group1">
Explanation 1: Traditional or Formula Method <br><br>

Let the total work be 1 unit. <br>
Efficiency of Mragank = 1/8 and Efficiency of Aanya = 1/12 <br>
So, their combined efficiency = 1/8 + 1/12 = (3 + 2) / 24 = 5/24

So, the  time taken by them working together = 24/5 = 4.8 days

Note: We can also have used the formula directly. <br>
The number of days required to complete the work if A and B work together = xy/(x + y) days = (8 × 12) / (8 + 12) = (8 × 12) / 20 = 24/5 = 4.8 days
</div>

<div id="1Exp-2" class="Exp-2 mak-tabcontent tabcontent-group1">
Explanation 2: LCM Method <br><br>

Let the total work be LCM of the days taken individually, i.e. LCM of 8 and 12, which is 24 units. 

So, work done by Mragank per day, i.e. Efficiency of Mragank = 24/8 = 3 units per day <br>
And, work done by Aanya per day, i.e. Efficiency of Aanya = 24/12 = 2 units per day

Their combined efficiency when working together = 3 + 2 = 5 units per day <br>
(efficiencies can be added)

So, the  time taken by them working together = Total work / Combined efficiency = 24/5 = 4.8 days

{{% alert note %}}
Note: Using LCM method helps us avoid fractions in our calculation. 
{{% /alert %}}
</div><br>

### Case 1b: Three people working together

If (A + B) can do a piece of work in x days and C can do the same work in y days, then 

(A + B)'s one day work (i.e. A+B’s efficiency) = 1/x and <br>
C's one day work (i.e. C’s efficiency) = 1/y

So, (A + B + C)'s one day work, i.e. combined efficiency of A, B & C = 1/x + 1/y = (x + y)/xy

Now, Time taken α 1/Efficiency

The number of days required to complete the work if (A + B + C) work together = xy/(x + y) days

### Case 1c: Three people working together

If 'A', 'B' & 'C' can complete the work in x, y & z days respectively, then

(A + B+ C)'s 1 day work, i.e. their combined efficiency = 1/x + 1/y + 1/z = (xy + yz + xz)/xyz

Now, Time taken α 1/Efficiency

So, the number of days required to complete the work if A, B and C work together = xyz/ (xy + yz + xz) days 


## Case 2: If Combined Efficiency or Combined Time-taken given

### Case 2a: Two people working together

If A can do a piece of work in x days and A + B can do the same work in y days, then 

A's one day work, i.e. A’s efficiency = 1/x

(A+B)'s one day work, i.e. (A+B)’s efficiency = 1/y

So, B's one day work, i.e. B’s efficiency = 1/y – 1/x = (x - y)/xy

The number of days required to complete the work if B works alone = xy/(x - y) days

### Case 2b: Three people working together

If A & B together perform some part of work in 'x' days, B & C together perform it in 'y' days and C & A together perform it in 'z' days, then

(A + B)'s one day work, or efficiency = 1/x <br>
(B + C)'s one day work, or efficiency = 1/y <br>
(C + A)'s one day work, or efficiency = 1/z

Combining the above three: <br>
2(A+B+C)'s 1 one day work = 1/x + 1/y + 1/z = (xy + yz + xz)/xyz <br>
Or (A+B+C)'s 1 one day work, i.e. their combined efficiency = (xy + yz + xz)/2xyz

Now, Time taken α 1/Efficiency

So, the number of days required to complete the work if A, B and C work together = 2xyz/ (xy + yz + xz) days 

### Case 2c: Three people working together

A & B together perform some part of work in 'x' days, B & C together perform it in 'y' days and C & A together perform it in 'z' days.

Then, we know that (A + B + C)'s 1 one day work, i.e. their combined efficiency = (xy + yz + xz)/2xyz

And (B + C)'s one day work = 1/y

So, A’s one day work = (A + B + C) – (B + C) = (xy + yz + xz)/2xyz – 1/y = (xy + yz + xz – 2xz)/2xyz = (xy + yz - xz)/2xyz

So, the number of days required to complete the work by A alone = 2xyz/(xy + yz - xz)

Similarly, if B works alone, then time required = 2xyz/(-xy + yz + xz)

Similarly, if C works alone, then time required = 2xyz/(xy - yz + xz)


## Case 3

If A working alone takes x days more than A and B together and B working alone takes y days more than A and B together, then 

the number of days taken by A and B together to complete the task = √(xy)


## Case 4: B is m times as good a workman as A

### Case 4a

If A can complete a work in ‘t’ days and B is ‘m’ times efficient than A, then

Ratio of work done by A & B in equal time = 1 : m and <br>
Ratio of time taken by A & B to complete the work = m : 1. This means that ‘B' takes (1/mth) time as that of ‘A' to finish same amount of work.

So, combined efficiency of A & B = 1/t + m/t = (1 + m)/t <br>
And the time taken by both A and B, working together to complete the work = t/(1 + m)

### Case 4b

If A and B working together can complete a task in ‘t’ days and B is ‘m’ times more efficient than A, then

The time taken by A alone to complete the task = (m+1) × t days

The time taken by B alone to complete the task = [(m + 1)/m] × t days

